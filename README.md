# BUTTONS

private void Button_Click(object sender, RoutedEventArgs e)
    {

        for (int i = 2; i < 26; i++)
        {
            Main_Frame.Source = new BitmapImage(new Uri("/Assets/Eye_thing/im" + i + ".jpg", UriKind.Relative));
        }


    }

    private void Button_Click_1(object sender, RoutedEventArgs e)
    {
        for (int i=25; i > 2; i--)
        {
            Main_Frame.Source = new BitmapImage(new Uri("/Assets/Eye_thing/im" + i + ".jpg", UriKind.Relative));

        }

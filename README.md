

    static string diffCurrencies(int x)
    {
        string[] currencies = { "baht", "dollar", "euro", "koruna", "lira", "rand", "rupee", "yen" };
        if (x >= 0 && x < currencies.Length)
        {
            return currencies[x];
        }
        else
        {
            return "Invalid index";
        }

    }
}

# hw-02
 static void Main(string[] args)
        {
            int Value;
            Console.WriteLine("Please enter the Maximum or Minimum Value");
            try
            {

                Value = sbyte.Parse(Console.ReadLine());
                Console.WriteLine(checked((sbyte)(Value)));
            }

            catch (Exception)
            {
                Console.WriteLine("Error! Exceeding the maximum or minimum volume");
            }

            // Я старался как мог, не cудите строго я еще нуб)))

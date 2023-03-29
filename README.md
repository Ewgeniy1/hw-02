# hw-02
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

            
 
        

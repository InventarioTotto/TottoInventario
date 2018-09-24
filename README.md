alonso mamerto hijo de perra dice la aguelita
 class RangosApp
    {
        static void Main()
        {
            int[] array = new int[2];
            int[,] array2 = new int[2, 2];
            int[,,] array3 = new int[2, 2, 2];
            int[,,,] array4 = new int[2, 2, 2, 2];
            Console.WriteLine("Rando de array: {0}", array.Rank);
            Console.WriteLine("Rando de array2: {0}", array2.Rank);
            Console.WriteLine("Rando de array3: {0}", array3.Rank);
            Console.WriteLine("Rando de array4: {0}", array4.Rank);

            Console.ReadKey();
        }
    }
}

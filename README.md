# LOGITpe20-IDCodeReader

## Substring
´´´ 
 class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Good Morning!");
            string somestring = "interpolation";
            Console.WriteLine($"{somestring.Length}");
            string newstring = somestring.Substring(0, 5);
            Console.WriteLine(newstring);
            string polationstring = somestring.Substring(5, 8);
            Console.WriteLine(polationstring);
        }
    }
    
    ´´´
    
    ## LOGITpe20
    
    ´´´ 
     class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Good Morning!");
            DisplayLOGIT();
            Displaype();
            Display20();
        }
        public static void DisplayLOGIT()
        {
            string Word = "LOGITpe20";
            string LOGIT = Word.Substring(0, 5);
            Console.WriteLine(LOGIT);
        }
        public static void Displaype()
        {
            string Word = "LOGITpe20";
            string pe = Word.Substring(5, 2);
            Console.WriteLine(pe);
        }
        public static void Display20()
        {
            string Word = "LOGITpe20";
            string Twenty = Word.Substring(7, 2);
            Console.WriteLine(Twenty);
        }
    }
    ´´´

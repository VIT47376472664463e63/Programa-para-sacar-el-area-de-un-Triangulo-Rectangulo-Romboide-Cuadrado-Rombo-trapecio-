# Programa-para-sacar-el-area-de-un-Triangulo-Rectangulo-Romboide-Cuadrado-Rombo-trapecio-
En este programa vas a poder sacar el area de Triangulo ,Rectangulo , Romboide ,Cuadrado ,Rombo ,trapecio , Circulo y Poligeno Circulo

using System.Net.Http.Headers;




    class Program
    {
    
        static void Main(string[] args)
        {
        
           

            int b, h;
            string a;
            
            Console.Write($"en esta parte vamos a sacar el area del Triangulo , Rectangulo y Romboide :");
            Console.WriteLine("_______________________________________________________");
            Console.Write($"Ingrese la base :");
            b = Convert.ToInt32(Console.ReadLine());
            Console.Write($"Ingresese la altura : ");
            h = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del Triangulo");
            Console.WriteLine($"{b * h / 2}");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del Rectangulo");
            Console.WriteLine($"{b * h}");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del Romboide");
            Console.WriteLine($"{b * h}");

            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del cuadrado");
            int L, l;
            Console.WriteLine("ingrese el primer lado del cuadrado: ");
            l = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("ingrese el segundo lado del cuadrado: ");
            L = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("El area del cuadrado es: ");
            Console.WriteLine($"{L * l} ");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del rombo");
            int D, d;
            Console.WriteLine("Ingresa el valor del diagonal mayor ");
            d = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Ingresa el valor del diagonal menor");
            D = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("El area del rombo es:");
            Console.WriteLine($"{d * D / 2} ");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del Trapecio");
            int A , K ,k;
            Console.WriteLine("Ingresa el valor de la altura ");
            A = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Ingresa el valor de la base mayor");
             K= Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Ingresa el valor de la base menor");
            k= Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("el area del trapecio es: ");
            Console.WriteLine($"{((K + k) / 2) *A} ");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del Circulo");
            int r;
                Console.WriteLine("Ingresa el valor del radio  ");
            r = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("el area del circulo es : ");
            Console.WriteLine($"{r*r * 3.1416} ");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Area del Poligono");
            int M, ap;
            Console.WriteLine("Ingresa el valor del apotema:  ");
            ap= Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Ingresa el valor del perimetro:  ");
            M = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("El area del poligono es :  ");
            Console.WriteLine($"{((M*ap)/2)} ");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("_______________________________________________________");
            Console.WriteLine("Gracias :D ");

        }
    }


    

# Hello-world

					
public class Program
{
	public static void Main()
	{
		Console.WriteLine("Ingrese una nota");
		string nota= Console.ReadLine();
		switch (nota)
		{
		case "A": Console.WriteLine("Aprobó"); break;
	    case "B": Console.WriteLine("Necesita reforzamiento"); break;
		case "C": Console.WriteLine("Desaprobo"); break;
		default: Console.WriteLine("Error"); break;
	}
	}
}

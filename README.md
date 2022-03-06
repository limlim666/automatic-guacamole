// See https://aka.ms/new-console-template for more information
string a = Console.ReadLine();
string b = Console.ReadLine();
int r = Convert.ToInt32 (a);
int f = Convert.ToInt32 (b);
Console.WriteLine($"Результат деления={r/f}");
Console.WriteLine($"Остаток от деления={r%f}");

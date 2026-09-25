using System;

class Program
{
static void Main()
{
Rectangle rect = new Rectangle();
rect.Height = 2;
rect.Width = 3;

rect.Show();
double p = rect.Perimetr();
Console.WriteLine($&quot;Периметр прямоугольника = {p}&quot;);

Console.ReadLine();
}
}

class Rectangle
{
public double Height;
public double Width;

public void Show()
{
Console.WriteLine($&quot;Прямоугольник: высота = {Height}, ширина = {Width}&quot;);
}

public double Perimetr()
{

return 2 * Height + 2 * Width;
}
}

using System;
class Program
{
    static void Main()
    {
        Console.WriteLine("Минимальные и максимальные значения типов данных CTS:");
        Console.WriteLine("=====================================================");
        Console.WriteLine($"sbyte:  {sbyte.MinValue} до {sbyte.MaxValue}");
        Console.WriteLine($"byte:   {byte.MinValue} до {byte.MaxValue}");
        Console.WriteLine($"short:  {short.MinValue} до {short.MaxValue}");
        Console.WriteLine($"ushort: {ushort.MinValue} до {ushort.MaxValue}");
        Console.WriteLine($"int:    {int.MinValue} до {int.MaxValue}");
        Console.WriteLine($"uint:   {uint.MinValue} до {uint.MaxValue}");
        Console.WriteLine($"long:   {long.MinValue} до {long.MaxValue}");
        Console.WriteLine($"ulong:  {ulong.MinValue} до {ulong.MaxValue}");
        Console.WriteLine("-----------------------------------------------------");
        Console.WriteLine($"float:  {float.MinValue} до {float.MaxValue}");
        Console.WriteLine($"double: {double.MinValue} до {double.MaxValue}");
        Console.WriteLine($"decimal: {decimal.MinValue} до {decimal.MaxValue}");
        Console.WriteLine("-----------------------------------------------------");
        Console.WriteLine($"char:   {(int)char.MinValue} до {(int)char.MaxValue} (Unicode)");
        Console.WriteLine("-----------------------------------------------------");
        Console.WriteLine($"bool:   {bool.FalseString} до {bool.TrueString}");
        Console.WriteLine("=====================================================");
    }
}

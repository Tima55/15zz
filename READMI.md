//  Напишите программу, которая выводит третью цифру заданного числа или сообщает, что третьей цифры нет.

int number = int.Parse(Console.ReadLine());
Console.WriteLine(number);

if (number > 99)
{
    int digitIndex = 2;
    int digit      = number.ToString()[digitIndex] - '0';
    Console.Write(digit);
}
else
{
    Console.Write("Нет третей цифры");
}
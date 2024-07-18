# FizzBuzz
Lektion1Övning1

Beskrivning
Skriv ett konsollprogram i C# som skriver ut alla tal från 1 till 100 på varsin rad. 
Om talet är delbart på 3, skriv ut ”Fizz” istället för talet.
3 och 6 ska exempelvis ersättas med Fizz.
Om talet är delbart med 5, skriv ut ”Buzz” istället för talet. 
5 och 10 ska exempelvis ersättas med Buzz
Om talet är delbart på både 3 och 5, skriv ut FizzBuzz istället.
15 och 30 ska exempelvis ersättas med FizzBuzz




for (int i = 0; i < 101; i++)
{
    if (i % 3 == 0 && i % 5 == 0) Console.WriteLine("FizzBuzz");

    else if (i % 3 == 0) Console.WriteLine("Buzz");

    else if (i % 5 == 0) Console.WriteLine("Buzz");

    else Console.WriteLine(i);
}

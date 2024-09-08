# Fizzbuzz
Fizzbuzz app


for (int myval = 0; myval <= 100; myval++)
{
    var resultString = "";
    if (myval % 3 == 0) resultString += "fizz";
    if (myval % 5 == 0) resultString += "buzz";
    if (myval % 5 != 0 && myval % 3 != 0) resultString += myval;
    Console.WriteLine(resultString);
}

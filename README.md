# PROGIDY_SD_01
Create a program that converts temperatures between CelsiusFahrenheit, and Kelvin scales. Theprogram should prompt the user toinput a temperature value and theoriginal unit of measurement. Itshould then converttemperatureto the other two units and displaythe converted values to the user. Forexample, if the user enters atemperature of 25 degrees Celsius,the program should convert it toFahrenheit and Kelvin, andpresentthe converted values as outputs.
EXPLAINATION:
This C++ program converts a temperature from Celsius to Fahrenheit. Here's a concise explanation:

1. **Include Directive**: It includes the input-output stream library to enable console input and output operations.

2. **Function Definition**: 
   - A function `celsius_to_fahrenheit` is defined, which takes a temperature in Celsius as an argument and returns the equivalent temperature in Fahrenheit using the formula: \((\text{Celsius} \times \frac{9.0}{5.0}) + 32\).

3. **Main Function**:
   - The main function declares a variable to store the Celsius temperature.
   - It prompts the user to enter a temperature in Celsius.
   - It reads the user's input.
   - It calls the `celsius_to_fahrenheit` function to convert the input temperature to Fahrenheit.
   - It outputs the converted temperature in Fahrenheit.
   - It ends the program successfully.

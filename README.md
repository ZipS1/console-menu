# Menu for C++ console projects

### Using
1. Include header file in project.
2. Initialize a std::vector<std::string>> of menu items.
   </br>*They will be shown as a menu lines*
3. Initialize a std::vector<> of function pointers.
   </br>*- It contains function pointers that will be running
   when you select menu item with same index as func pointer*
   </br>*- Don't forget to specify input parameters
   for function pointers when initializiing vector*
   </br>**Vector sizes should be equal!**
5. Instantiate a ConsoleMenu example and pass both vectors here.
   </br>*ConsoleMenu template parameters is function input parameters
   you specified for function pointers*
7. Call method .run() with parameters you specified.

# Functions With Parameters (Lesson 4)

With your introduction to functions completed, you should learn about extending functions further with parameters. Functions alone are powerful for reducing code duplication, but they excel when updated to include parameters. Parameters are inputs for functions which are used during function execution. This allows for programs to have re-usable code with differing outputs/operations based on the provided parameters.

1. Start by creating a new Python file.
2. Open the file in your editor/IDE of choice.
3. Create a function.
4. Next, update the function to accept parameters!
   ```python
   def add(x, y):
      return x + y
   ```
5. Lastly, you should learn how to provide parameters when calling a function, they are included within the parenthesis in the order of the parameter(s) within the functuon definition.
   ```python
   add(1, 2)
   ```
6. Finish up the assignment by doing the following:
  1. Create a function which takes two parameters, the `sale_price` and `tax_rate` for a sale, and returns the sales tax.
  2. Call the function with a sale price of 100 and a tax rate of 6%, then print the output.
  3. Call the function with a sale price of 29.99 and a tax rate of 10%, then print the output.
7. Run your program!
1. At Line 9 values added: 20 is printed since the var variables do not have a block scope ensuring the code to execute successfully.
2. In Line 13 final result: 20 is printed since the var keyword ignores the if block scope allowing the result variable to be accessed anywhere inside the function
3. var should be avoided since it can lead to naming conflicts and scoping issues since it has no block scope
4. At Line 9, value added = 20 is printed
5. Reference Error is returned at Line 13 since the let keyword gives the result variable block scope since it is not defined outside of the if block.
6. TypeError is returned before reachin line 9 since line 7 attempts to reassign result. This is forbidden since the variable is declared with the const keyword.
7. ReferenceError would be returned from the code for the same reason as 5, the block scope. But we will never reach line 13 because of the TypeError on line 7
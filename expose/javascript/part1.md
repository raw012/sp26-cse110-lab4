1. values added: 20
2. final result: 20
3. var can be accessed whereever inside the function regardless the if and else statement. This can lead to accidental variable access outside the intended block,
causing hard-to-find bugs.
4. values added: 20
5. Error occurs because the variable "result" is not defined inside the else statmenet. As the result variable is defined by "let", which is limited inside the if block, so there will be an error in accessing the "result" in the else scope.
6. Error occurs becasue "result" is defined as "const", so it can not be revised. As line 7 tries to reassign the value of "result", an error occurs. Line 9 is not reached.
7. Error occurs because error from Question6 stops the execution before line 13.
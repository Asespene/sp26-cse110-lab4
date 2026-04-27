1. **What was the bug?**
    A data type issue caused by reading values directly from HTML input fields. This resulted in returning a string because of the .value property so we had 2 strings; "2" and "3" being concatanated with "+" instead of it being a mathematical addition.
2. **How would you fix it?**
    I would fix this bug my explicitly type casting the string input into numerical values before we add them together. We can do this by wrapping them around Number() function. The changed code was let result = Number(num1) + Number(num2);
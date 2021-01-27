# Part 1 questions

1. The length of the array `prices` will be printed. Because `var` is scoped in the entire function, `i` is still defined.
2. The last value in the array `prices` multiplied by `1-discount` will be printed. Because `var` is scoped in the function, `discountedPrice` exists in the entire function.
3. The last value in the array `prices` with the applied `discount` value will be printed, rounded to the nearest hundredths. Since `var` is scoped in the function, `finalPrice` is still defined.
4. The array `[50, 100, 150]` will be returned. The function will iterate through the array, and multiply each value by `1-0.5`. Each value is then added to a new array `discounted`, which is returned when the function finishes.
5. An error will occur because `i` is not defined. Since `let i = 0` is scoped in the for loop, it does not exist outside of the loop.
6. An error will occur because `discountedPrice` is not defined. Since `let discountedPrice` is scoped in the for loop, it does not exist outside of the loop.
7. The last value of `finalPrice` will be printed. Since `let finalPrice = 0` is scoped in the entire function, it is defined at the time of `console.log(finalPrice)`.
8. The array `[50, 100, 150]` will be returned. Since no variables are being used out of scope, the function will return the same result as before.
9. An error will occur because `i` is not defined. Since `const` has the same scope as `let`, `i` is only defined in the for loop.
10. An error will occur because `discountedPrice` is not defined. Since `const discountedPrice` is scoped in the for loop, it does not exist outside of the loop.
11. The last value of `finalPrice` will be printed. Since `const finalPrice = 0` is scoped in the entire function, it is defined at the time of `console.log(finalPrice)`.
12. An error will occur. On lines 5 and 7, a value is being assigned to a constant, which is illegal.
13. A. `student.name`\
    B. `student['Grad Year']`\
    C. `student.greeting()`\
    D. `student['Favorite Teacher'].name`\
    E. `student.courseLoad[0]`\
14. A. `32`. Because `'3'` is a string, `2` is converted to a string, and string concatentation is performed.\
    B. `1`. The `-` sign between two variables automatically converts both values to numbers.\
    C. `3`. Since `3` is a number, null is converted to `0`. The operation `3 + 0` returns `3`.\
    D. `3null`. Since `'3'` is a string, null is converted to the string `'null'`. A string concatention operation is performed.\
    E. `4`. `True` is converted to the number `1`, and `1 + 3` is performed.\
    F. `0`. `False` is coverted to the number `0`, and `null` is converted to the number `0`. The result is `0 + 0`.\
    G. `3undefined`. Since `"3"` is a string, `undefined` is converted to the strnig `"undefined"`, and a string cnocatentation is performed.\
    H. `NaN`. Since `-` is present, an automatic numeric conversion is performed. However, `undefined` cannot be converted to a number, so `NaN` is returned.\
15. A. `true`, since the string `'2'` becomes a number `2`.\
    B. `false`. A lexigraphical comparison is made. Since `'2' > '1'`, false is returned.\
    C. `true`. The string `'2'` becomes the number `2`.\
    D. `false`. The operator `===` does not convert types. Since the types are different, `false` is returned.\
    E. `false`. `true` is converted to the number `1`, which is not equal to `2`.\
    F. `true`. The `Boolean()` conversion converts `2` to `true`.\
16. `===` checks strict equality, and performs no conversion. `==` checks loose equality, and performs type coercion.
17. `How are you?` is printed. In the first condition, `true` is converted to the number `1`. In the second condition, `2` is converted to the boolean `true`.
18.
19. `[6, 8, 10]`. For each value in the array, a callback to `doSomething(array[i], function (x) {return x*2})` is made. This increments `array[i]` by 2, and then makes another callback to the function `function (x) {return x*2}`. In the end, the value of each element in the array is first incremented by 2, then multiplied by 2.
20.
21. `1432`

# Javascript Operator Precedence

| Precedence    | Operator type                 | Associativity     | Individual operators |
| ------------- | -------------                 | ----------------- | -------------------- |
| 19            | [Grouping]                    | n/a               | (...)                |
| 18            | [Member Access]               | left‐to‐right     | ... **.** ...        |
|               | Computed [Member Access]      | left‐to‐right     | ... [ ... ]          |
|               | [new] (with argument list)    | n/a               | new ... ( ... )      |
| 17            | [Function Call]               | left‐to‐right     | ...(...)             |
|               | [new] (without argument list) | right‐to‐left     | new ...              |
| 16            | [Postfix Increment]           | n/a               | ... ++               | 
|               | [Postfix Decrement]           | n/a               | ... ‐‐               | 

[Operator Precedence] ‐ Javascript by Mozilla Contributors is licensed under CC‐BY‐SA 2.5.

[Grouping]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping
[Member Access]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors#Dot_notation
[new]:https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Operators/Special/new
[Function Call]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions
[Operator Precedence]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_Precedence
[Postfix Increment]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment
[Postfix Decrement]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Decrement
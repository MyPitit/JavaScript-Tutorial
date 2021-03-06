# JavaScript Arithmetic

#### JavaScript Operator Precedence Values

Operator Precedence determines the order in which operators are evaluated. Operators with higher precedence are evaluated first.

|Precedence	|Operator type             |Associativity        |Individual operators |
|-----------|--------------------------|---------------------|---------------------|
|19	        |[Grouping](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping)	               |n/a	                 |( … )                |
|18	        |[Member Access](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors#Dot_notation)             |left-to-right        |… . …                |
|           |[Computed Member Access](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_Accessors#Bracket_notation)    |left-to-right	     |… [ … ]              |
|           |[new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new) (with argument list)  |n/a	                 |new … ( … )          |
|17	        |[Function Call](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)	           |left-to-right	     |… ( … )              |
|           |[new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new) (without argument list)|right-to-left	     |new …                |
|16	        |[Postfix Increment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment)	        |n/a	             |… ++                 |
|           |[Postfix Decrement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Decrement)	        |n/a	             |… --                 |
|15	        |[Logical NOT](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators#Logical_NOT)	           |right-to-left	     |! …                  |
|           |[Bitwise NOT](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators#Bitwise_NOT)	           |right-to-left	     |~ …                  |
|           |[Unary Plus](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Unary_plus)	               |right-to-left	     |+ …                  |
|           |[Unary Negation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Unary_negation)	           |right-to-left	     |- …                  |
|           |[Prefix Increment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Increment)	       |right-to-left	     |++ …                 |
|           |[Prefix Decrement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Decrement)	       |right-to-left	     |-- …                 |
|           |[typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof)	                   |right-to-left	     |typeof …             |
|           |[void](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/void)	                   |right-to-left	     |void …               |
|           |[delete](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/delete)	                   |right-to-left	     |delete …             |
|14	        |[Exponentiation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Exponentiation)	           |right-to-left	     |… ** …               |
|           |[Multiplication](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Multiplication)	           |left-to-right	     |… * …                |
|           |[Division](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Division)	               |left-to-right	     |… / …                |
|           |[Remainder](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Remainder)               |left-to-right	     |… % …                |
|13	        |[Addition](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Addition)               |left-to-right	     |… + …                |
|           |[Subtraction](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Subtraction)	           |left-to-right	     |… - …                |
|12	        |[Bitwise Left Shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)	       |left-to-right	     |… << …               |
|           |[Bitwise Right Shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)	   |left-to-right	     |… >> …               |
|           |[Bitwise Unsigned Right Shift](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)	|left-to-right	 |… >>> …              |
|11	        |[Less Than](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Less_than_operator)                |left-to-right	 |… < …                |
|           |[Less Than Or Equal](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Less_than__or_equal_operator)	            |left-to-right	 |… <= …               |
|           |[Greater Than](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Greater_than_operator)	                |left-to-right	 |… > …                |
|           |[Greater Than Or Equal](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Greater_than_or_equal_operator)	        |left-to-right	 |… >= …               |
|           |[in](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/in)	                            |left-to-right	 |… in …               |
|           |[instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof)	                    |left-to-right	 |… instanceof …       |
|10	        |[Equality](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Equality)	                    |left-to-right	 |… == …               |
|           |[Inequality](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Inequality)	                    |left-to-right	 |… != …               |
|           |[Strict Equality](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Identity)	            |left-to-right	 |… === …              |
|           |[Strict Inequality	](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Nonidentity)            |left-to-right	 |… !== …              |
|9	        |[Bitwise AND](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators#Bitwise_AND)	                |left-to-right	 |… & …                |
|8	        |[Bitwise XOR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators#Bitwise_XOR)	                |left-to-right	 |… ^ …                |
|7	        |[Bitwise OR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators#Bitwise_OR)	                    |left-to-right	 |… | …                |
|6	        |[Logical AND](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators#Logical_AND)	                |left-to-right	 |… && …               |
|5	        |[Logical OR](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators#Logical_OR)	                    |left-to-right	 |… || …               |
|4	        |[Conditional](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator)	                |right-to-left	 |… ? … : …            |
|3	        |[Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Assignment_Operators)	                    |right-to-left	 |… = …                |
|           |                               |                |… += …               |
|           |                               |                |… -= …               |
|           |                               |                |… **= …              |
|           |                               |                |… *= …               |
|           |                               |                |… /= …               |
|           |                               |                |… %= …               |
|           |                               |                |… <<= …              |
|           |                               |                |… >>= …              |
|           |                               |                |… >>>= …             |
|           |                               |                |… &= …               |
|           |                               |                |… ^= …               |
|           |                               |                |… |= …               |
|2	        |[yield](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield)	                        |right-to-left	 |yield …              |
|           |[yield*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*)	                        |right-to-left	 |yield* …             |
|1	        |[Spread](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_operator)	                        |n/a	         |... …                |
|0	        |[Comma / Sequence](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comma_Operator)	            |left-to-right	 |… , …                |

### Next...
Go [back](https://github.com/MyPitit/JavaScript-Tutorial) or to the [next]() lesson.

Programming is the act of constructing a program—a set of precise instructions telling a computer what to do.

# 1. Values, Types, and Operators

## 1.1 Arithmetic

When operators appear together without parentheses, the order in which they are applied is determined by the precedence of the operators.

The ``/`` operator has the same precedence as ``*``. Likewise for ``+`` and ``-``. When multiple operators with the same precedence appear next to each other, as in **1 - 2 + 1**, they are applied left to right: **(1 - 2)+ 1**.

The ``%`` symbol is used to represent the remainder operation. ``X % Y`` is the remainder of dividing X by Y. For example, 

    314 % 100   // →  14
    144 % 12    // →  0

The remainder operator’s precedence is the same as that of multiplication and division. You’ll also often see this operator referred to as modulo.

## 1.2 Special numbers

There are three special values in JavaScript that are considered numbers but don’t behave like normal numbers.

The first two are ``Infinity`` and ``-Infinity``,  which represent the positive and negative infinities.

It isn’t mathematically sound, and it will quickly lead to the next special number: ``NaN``. **NaN** stands for **“not a number”**.


## 1.3 Strings

They are written by enclosing their content in quotes.

You can use single quotes, double quotes, or backticks to mark strings, as long as the quotes at the start and the end of the string match.

#### 1.3.1 Backslash

Whenever a backslash ``\`` is found inside quoted text, it indicates that the character after it has a special meaning. This is called escaping the character

    "This is the first line\nAnd this is the second"

        The actual text contained is this:
    
    This is the first line And this is the second

If two backslashes follow each other, they will collapse together, and only one will be left in the resulting string value.

    "A newline character is written like \"\\n\"."

Strings, too, have to be modeled as a series of bits to be able to exist inside the computer. The way JavaScript does this is based on the Unicode standard.

#### 1.3.2 Concatenation

Strings cannot be divided, multiplied, or subtracted, but the ``+`` operator can be used on them. It does not add, but it concatenates—it glues two strings together. The following line will produce the string **"concatenate"**:

    "con" + "cat" + "e" + "nate"

#### 1.3.3 Backtick-quoted strings

Usually called template literals, can do a few more tricks. Apart from being able to span lines, they can also embed other values.

    `half of 100 is ${100 / 2}`

When you write something inside ``${}`` in a template literal, its result will be computed, converted to a string, and included at that position

    `half of 100 is ${100 / 2}`     // →  half of 100 is 50

## 1.4 Unary operators

#### 1.4.1 typeof

One example is the ``typeof`` operator, which produces a string value naming the type of the value you give it.

    console.log(typeof 4.5)     // → number
    console.log(typeof "x")     // → string

#### 1.4.2 minus (-)

Operators that use two values are called binary operators, while those that take one are called unary operators. The minus operator can be used both as a binary operator and as a unary operator.

    console.log(- (10 - 2))     // → -8
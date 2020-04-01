# **Lexical Structure**

### Whitespace and Comments
Whitespace has two uses: to separate tokens in the source file and to help determine whether an operator is a prefix or postfix (see Operators), but is otherwise ignored. The following characters are considered whitespace: 
> space `(U+0020)`
> line feed `(U+000A)`
> carriage return `(U+000D)`
> horizontal tab `(U+0009)`
> vertical tab `(U+000B)`
> form feed `(U+000C)`
> null `(U+0000)`.

Comments are treated as whitespace by the compiler. Single line comments begin with `//` and continue until a line feed `(U+000A)` or carriage return `(U+000D)`. Multiline comments begin with `/*` and end with `*/`. Nesting multiline comments is allowed, but the comment markers must be balanced.

### Identifiers


### Keywords and Punctuation

### Literals

### Operators
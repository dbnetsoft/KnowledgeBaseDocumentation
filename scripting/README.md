# Scripting

Some software products come with a powerful scripting engine called [Scriban](https://github.com/scriban/scriban).

At the developer's website, you'll find an extensive documentation about the [language ](https://github.com/scriban/scriban/blob/master/doc/language.md)and [built-in functions](https://github.com/scriban/scriban/blob/master/doc/builtins.md).&#x20;

## Primer

* Scripts are enclodes in double curly braces `{{` `}}`.
* Every line of code that is not an assignment to a variable and produces a string is output
* &#x20;Functions can be called with parameters in two ways:
  * Either in a traditional way: `FunctionName "Param1" Param2 Parame 3`...
  * or in a piping-way: `"Param1" | FunctionName Param2 Param3`


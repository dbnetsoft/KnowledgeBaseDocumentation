# How to begin

The following script will output "Hello World":

```
{{ "Hello World" }}
```

The following script will modify the field from RR12 and pads it to 12 characters and center aligns it if need be. This is possible by using the `|` pipe character: The expression to the left is forwasrded to a function that is given by the name after the pipe. The forwarded argument will be the first in the function arguments list:

```
{{ "[LastName]" | TrimPad 12 "Center" }}
```

Without using piping, you can also use a traditional way of calling methods:

```
{{ TrimPad "[LastName]" 12 "Center" }}
```

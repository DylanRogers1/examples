# Python Examples - Hello World

Hello World  program  
[View / download code](code/helloworld.py)

``` python
print("Hello World")
```

Output to the console:

``` text
Hello World
```

Let's go through the code in detail.

The code is only one line long, so we don't need to break it up into lines this time!

---

Line 1 (the only line):

``` python
print("Hello)
```

Let's first look at the `print` function:

``` python
print
```

`print` is what we call a function. Functions are basically just bits of code that we can run.

For example, we could create a function called `say_hello`, which would say hello to the user and ask them some questions. We could then call this function, and instead of typing out, say, 10 lines of code to greet the user, we can just call the `say_hello` function using `say_hello()` and we have only written one short line.

Just like our imaginary function `say_hello`, the `print` function runs lots of different lines of code when we call it. All of these lines of code are packaged into one nice function that we can call in one line.

We can call a function using this syntax:

``` python
function_name()
```

replacing `function_name` with the name of the function.

In our code, the name of the function is `print`, so we would replace `function_name` with `print`:

``` python
print()
```

You may notice, however, that this code just prints a blank line:

``` text

```

This is because we haven't given any data - called ***arguments***. Arguments are just bits of information that we can give to functions to change the way they run. To give arguments to a function, we use this syntax:

``` python
function_name(arguments)
```

In our case, the function name is `print` and the argument is `"Hello World"`. Therefore, we can just substitute the values into our syntax example:

``` python
print("Hello World")
```

Now let's look at `"Hello World"`:

``` python
"Hello World"
```

`"Hello World"` is what we call a string. Programmers may tell you that "a string is a sequence of characters", but what they really mean is that a string is just text. It could be anything - numbers letters, symbols, etc. - as long as it's just text.

The speech marks `""` indicate that `"Hello World"` is a string ***literal***. Literals are pretty much the same as a constant, if you're familiar with those. Basically, it just means that the text `"Hello World"` never changes. Whenever we run our program, it will always print "Hello World" to the screen.

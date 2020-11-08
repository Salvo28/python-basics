# Output and Input

## `print`

We've already seen this: `print()` allows us to display information in the terminal to show to the program's user. This is called **output**.  

```python
print('Hello world!')
```

If you have more than one piece of data to be printed, you can also use commas in your `print` statement:

```python
name = 'Jill'
print('Good', 'Morning', name)
#--> Good Morning Jill
```

When you use commas in `print`, notice how it automatically inserts a space between each item to be printed!

(You can also make a longer string with **string interpolation** as we saw already, of course. It's up to the programmer!)

## `input`

The opposite of `print()` ("output") is `input()`.

`input()` allows us to receive information from the program's user.

```python
print("What's your name?")
user_name = input()
print(f'Hello, {user_name}')
```

**Protip:** When a user gives you data via `input()`, it's always in the form of a **string**, even if they might have typed in some numbers!

---

# Additional Resources

* [A Repl.it Summarizing Print Statements](https://repl.it/@brandiw/Python-01-Variables-4?lite=true)

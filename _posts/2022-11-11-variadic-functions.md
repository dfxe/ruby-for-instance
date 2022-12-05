```rb
# Define a variadic function that takes a variable number of arguments
# and returns their sum
def sum(*numbers)
  numbers.inject(0, :+)
end

# Define a variadic function that takes a variable number of arguments
# and returns the maximum value
def max(*numbers)
  numbers.max
end

# Define a variadic function that takes a variable number of arguments
# and returns an array of all the arguments
def to_array(*elements)
  elements
end
```

[Try on playground](https://onecompiler.com/ruby/3yh7dhbz9)

Next: [strings and runes](/2022/11/12/strings-and-runes.html)

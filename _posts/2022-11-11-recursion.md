```rb
# Define a recursive function that computes the factorial of a number
def factorial(n)
  n == 1 ? 1 : n * factorial(n - 1)
end

# Define a recursive function that computes the sum of the elements in an array
def sum(array)
  return 0 if array.empty?
  array[0] + sum(array[1..-1])
end

# Define a recursive function that finds the maximum value in an array
def max(array)
  return array[0] if array.size == 1
  [array[0], max(array[1..-1])].max
end

```

[Try on playground](https://onecompiler.com/ruby/3yh7dhbz9)

Next: [values](/2022/11/01/variadic-functions.html)

```rb
# Define a simple function that takes no arguments
def say_hello
  puts "Hello"
end

# Define a function that takes one argument
def add(x, y)
  x + y
end

# Define a function that takes a variable number of arguments
def sum(*numbers)
  numbers.inject(0, :+)
end

# Define a function that takes a block
def each_element(array)
  array.each do |element|
    yield element
  end
end

# Define a function that returns multiple values
def min_and_max(array)
  [array.min, array.max]
end

# Define a function with default argument values
def power(base, exponent = 2)
  base ** exponent
end

# Define a recursive function
def factorial(n)
  n == 1 ? 1 : n * factorial(n - 1)
end

# Define a lambda function
add_two = ->(x) { x + 2 }

# Define a function that raises an exception
def divide(x, y)
  raise ZeroDivisionError, "Cannot divide by zero" if y == 0
  x / y
end

# Define a method on a class
class MyClass
  def initialize(name)
    @name = name
  end

  def say_hello
    puts "Hello, #{@name}"
  end
end
```

[Try on playground](https://onecompiler.com/ruby/3yh7dhbz9)

Next: [values](/2022/11/10/multiple-return-values.html)

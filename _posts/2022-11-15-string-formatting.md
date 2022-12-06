```rb
# Define a string with placeholder symbols
template = "Hello, %s! Today is %s."

# Use the % method to insert values into the string
formatted_string = template % ["world", "Monday"]
# => "Hello, world! Today is Monday."

# Define a string with placeholder symbols and indexed placeholders
template = "Hello, %s! Today is %s. You are the %{index}th person to visit today."

# Use the format method to insert values into the string
formatted_string = template.format("world", "Monday", index: 1)
# => "Hello, world! Today is Monday. You are the 1th person to visit today."

# Define a string
string = "Hello, hello! Is anyone there?"

# Use the gsub method to replace all occurrences of "hello" with "world"
formatted_string = string.gsub("hello", "world")
# => "World, world! Is anyone there?"
```

[Try on playground](https://onecompiler.com/ruby/3yh7dhbz9)

Next: [command line](/2022/11/15/command-line.html)
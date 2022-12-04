```rb
# Define a string and get its length
my_string = "Hello, world!"
puts my_string.length

# Define a string and get its runes
my_string = "😀🤔😐😑😶"
my_string.each_char do |c|
  puts c.ord
end

# Define a string and convert its runes to code points
my_string = "😀🤔😐😑😶"
my_string.each_codepoint do |c|
  puts c
end
```
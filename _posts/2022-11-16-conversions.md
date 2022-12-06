```rb
# integer to string
number = 42
string = number.to_s
# => "42"

# string to integer
string = "42"
number = string.to_i
# => 42

# string to float
string = "3.1415"
number = string.to_f
# => 3.1415

# array to hash
array = [["key", "value"], ["another_key", "another_value"]]
hash = Hash[array]
# => {"key"=>"value", "another_key"=>"another_value"}

# hash to array
hash = {"key"=>"value", "another_key"=>"another_value"}
array = hash.to_a
# => [["key", "value"], ["another_key", "another_value"]]

# string to array
string = "hello world"
array = string.split(" ")
# => ["hello", "world"]
```

[Try on playground](https://onecompiler.com/ruby/3yh7dhbz9)

Next: [string formatting](/2022/11/15/string-formatting.html)
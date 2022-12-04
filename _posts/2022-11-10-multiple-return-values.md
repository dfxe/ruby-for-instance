```rb
# Define a function that returns an array
def min_and_max(array)
  [array.min, array.max]
end

# Define a method that returns a struct
def user_info(name, age)
  Struct.new(:name, :age).new(name, age)
end

# Define a method that returns an array of structs
def users_info(names, ages)
  names.zip(ages).map { |name, age| Struct.new(:name, :age).new(name, age) }
end
```
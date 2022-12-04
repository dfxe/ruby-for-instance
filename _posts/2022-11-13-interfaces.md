```rb
# Define an interface and a class that implements it
module MyInterface
  def my_method
    raise NotImplementedError
  end
end

class MyClass
  include MyInterface

  def my_method
    # Implement the my_method method
  end
end

# Define an interface and a class that extends it
module MyInterface
  def my_method
    raise NotImplementedError
  end
end

class MyClass < MyInterface
  def my_method
    # Implement the my_method method
  end
end

# Define an interface and a mixin that implements it
module MyInterface
  def my_method
    raise NotImplementedError
  end
end

module MyMixin
  include MyInterface

  def my_method
    # Implement the my_method method
  end
end

class MyClass
  include MyMixin
end
```
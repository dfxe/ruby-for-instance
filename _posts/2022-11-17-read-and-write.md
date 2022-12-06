---
layout: post
author: dfxe
---

```rb
# Open the file in read-only mode and store the file object in a variable
file = File.open('my-file.txt', 'r')

# Read the contents of the file and store them in a variable
file_contents = file.read

# Print the contents of the file to the terminal
puts file_contents

# Close the file
file.close

# Open the file in write mode and store the file object in a variable
file = File.open('my-file.txt', 'w')

# Write some text to the file
file.write('Hello, world!')

# Close the file
file.close
```

```rb
# Install the json and nokogiri gems (if necessary)
# $ gem install json
# $ gem install nokogiri

# Require the json and nokogiri gems
require "json"
require "nokogiri"

# Define some JSON data
json_data = '{"hello": "world"}'

# Parse the JSON data
json = JSON.parse(json_data)

# Print the parsed JSON data
puts json["hello"]
# => "world"

# Define some XML data
xml_data = '<hello>world</hello>'

# Parse the XML data
xml = Nokogiri::XML(xml_data)

# Print the parsed XML data
puts xml.at("hello").text
# => "world"
```
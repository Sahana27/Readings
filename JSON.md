# JSON : JavaScript Object Notation

Json is a textual data interchange format and language independent. 
DO NOT USE THIS TAG FOR NATIVE JAVASCRIPT OBJECTS OR JAVASCRIPT OBJECT LITERALS

### Validations of JSON
To validate JSON using validation tool such as [JSONLint](https://jsonlint.com)

JSON is a serializable data interchange format intended to be machine and human readable. JSON is completely language independently but it uses conventions familiar to C Language, including c++, C#, Java, javascript, perl, python.JSON can be used with Restful API or AJAX. Instead of XML we can use with JSON because its lighweight and compact structure. 

Programming language method for parsing JSOn text-formatted text string. There are few methods used JSON.parse() and JSON.stringify()

### JSON Format
There are two different format
Name/value pair
```javascript
{"name":"value1","name2":"value2"}
```

An ordered list of values 
```javascript
["values1", "values2"]
```

### JSON types
There are 6 types
- null
- numbers
- strings
- booleans
- arrays
- objects

JSON is not the same thing as Javascript object literals. JSON is common format to serialize form and deserialize to objects.

### Advantages
* JSON lightweight data-interchange format
* JSON is language independent
* JSON is self-describing and easy to understand
* JSON can be native understood by JavaScript parser, including node.js
* JSON can have a substantially lower character count reducing the overhead in data transfers.

# Disadvantage of JSON
It's limited in terms of the number of data types defined by default.

### JSON Library for Ruby
Link : https://github.com/flori/json

* Install json gem 
```
gem install json
```

* Install Pure ruby json only variant of the gem
```
gem install json_pure
```

* Usage
Use Json
```
require 'json'

require 'json/ext'
require 'json/pure'
```

* Parse JSON document into a ruby data structure
```
JSON.parse(document)
```

* Generate a JSON document from a ruby data structure 
```
JSON.generate(data)
```

### Stroing JSON Data
```javascript
var jason = {
   "age": "24",
   "hometown": "Missoula, MT",
   "gender" : "Male"
 };
```
We can access JSON object using the variable jason.  Data is enclosed using curly braces. Inside the object we declare value in form of "name":"value" separated by commas.

To access the property from jason we use
```javascript
jason.age
jason.gender
```

### Storing JSON Data in Arrays
Enclose multiple ibjects in square brackets
```javascript
var family = [{
   "name": "Json",
   "age": "24",
   "gender":"male"
   },
   {
   "name":"Kyle",
   "age":"21",
   "gender":"male"
   }
]
```
To access the data values from JSON
```
family[0].name
family[1].age
```

### Nested JSON Data
```
var family = {
    "jason" : {
        "name" : "Jason Lengstorf",
        "age" : "24",
        "gender" : "male"
    },
    "kyle" : {
        "name" : "Kyle Lengstorf",
        "age" : "21",
        "gender" : "male"
    }
}
```
Accessing information from nested object
```
family.jason.name
family.kyle.age
```


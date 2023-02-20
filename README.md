# Json
Introduction to JSON
> JSON stands for Javascript Object Notation. It is a ligtweight data **interchange** format that is easy for humans to read and write and easy for machines to parse and generate.
JSON is often used for transmitting data between a server and a web application


JSON is a collection of **key-value** pairs, similar to a dictionary.

A key is always a `"string"` wrap with **double quotes** 

A value can be (below data types)
1. string - `"Zakeer" or "zakeer579`
1. number - `10 or 78.9999`
1. boolean - `true or false`
1. null - `null - Absence of value`
1. array - `[]`
1. object - `{}`

Here is an example of simple JSON Object:
```json
{
    "name": "Shoyab",
    "age": 25,
    "city": "Guntur",
    "isMarried": false
}
```

JSON can also represents arrays (multiple) of Objects.
```json
[
    {
        "name": "Zahid",
        "age": 28,
        "city": "kerala",
        "isMarried": true
    },
    {
        "name": "Chandu",
        "age": 29,
        "city": "Vijayawada",
        "isMarried": false
    }
]
```
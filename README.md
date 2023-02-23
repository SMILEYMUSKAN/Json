# *Json*
Introduction to JSON
> JSON stands for Javascript Object Notation. It is a ligtweight data **interchange** format that is easy for humans to read and write and easy for machines to parse and generate.
JSON is often used for transmitting data between a server and a web application


JSON is a collection of **key-value** pairs, similar to a dictionary.

A key is always a `"string"` wrap with **double quotes** 

A value can be (below data types)
1. string - `"Muskan" or "Muskan579`
1. number - `10 or 78.9999`
1. boolean - `true or false`
1. null - `null - Absence of value`
1. array - `[]`
1. object - `{}`

**Here is an example of simple JSON Object:**
```json
{
    "name": "Momin",
    "age": 14,
    "city": "Guntur",
    "isMarried": false
}
```

**JSON can also represents arrays (multiple) of Objects**.
```json
[
    {
        "name": "Muskan",
        "age": 16,
        "city": "Ongole",
        "isMarried": false
    },
    {
        "name": "Afifa",
        "age": 17,
        "city": "Vijayawada",
        "isMarried": false
    }
]
```
### *Nested Object and Arrays*
```json
{
 "name" "Sony",
 "age": 20,
 "married": "no",
 "skills": [
    "Python",
    "Django",
    "HTML",
    "SQL"
 ],
 "compentencies": [
    {
        "name": "Python",
        "rating": 8
    },
    {
        "name": "Django",
        "rating": 6
    },
    {
        "name": "HTML",
        "rating": 9
    },
    {
        "name": "SQL",
        "rating": 7
    },
 ],
 "education": [
    {
        "institute": "Anjuman High School",
        "type": "SSC",
        "city": "Guntur",
        "year": 2010
    },
    {
        "institute": "NRI Academy",
        "type": "Intermediate",
        "city": "Ongole",
        "year": 2012
    },
    {
        "institute": "KHIT",
        "type": "B.Tech",
        "city": "Guntur",
        "year": 2016
    }
 ] 
}
```

# Business Model Analysis
This project aims to explore known or lesser-known companies for their underlying business model patterns. To do this, the [BMI Lab's Business Model Innovation Patterns](http://bit.ly/bmi-lab-patterns) are used to establish a common reference for the patterns. This allows different companies to be compared.

The data format used is JSON (JSON schema validation exists) so that the results can be further processed by machine (thinking of some nice graphic visualisations or some data science projects).

For visual editing you can use this great tool [json editor](https://github.com/jdorn/json-editor)

I am looking forward to community support. Forks and pull requests are very welcome.

**Notes:**
In the file *schema.json* you will find the JSON-Schema in which the JSON data should be in.
You can validate you input by using this [Link](https://www.npoint.io/docs/fc2d4ea410827c9f9f59). Feel free to suggest some changes. Try to stick to the Wikipedia Industries for the sector field. For example: [Industries](https://en.wikipedia.org/wiki/Category:Industries) -> [Service\_industries](https://en.wikipedia.org/wiki/Category:Service_industries) -> [E-commerce](https://en.wikipedia.org/wiki/Category:E-commerce)

**One imaginary example:**
```json
[
  {
    "companyName": "Example Company",
    "stockSymbol": "NASDAQ:EXAMPLE",
    "url": "https://example.org/",
    "sector": [
      "E-commerce"
    ],
    "patterns": [
      {
        "name": "E-COMMERCE",
        "description": "The main company pattern."
      }
    ],
    "products": [
      {
        "name": "SomeProduct",
        "sector": "E-COMMERCE",
        "patterns": [
          {
            "name": "OBJECT-AS-POINT-OF-SALE",
            "description": "Maybe something like a Buy-Button :D"
          }
        ]
      }
    ]
  }
]
```

This example looks like a big E-Commerce company.

So, please help to support this project and add some companies under *companyAnalysis.json*.

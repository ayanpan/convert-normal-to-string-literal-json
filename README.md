# Convert Normal JSON to String Literal JSON in Boomi

## Problem Statement: 
How to convert a Normal JSON format to a String Literal JSON format in Boomi?

Normal JSON Format:
```
{
  "id": "101",
  "name": "Ayan Kumar Pan",
  "department": "IT"
}
```

String Literal JSON Format:

```
{\"id\":\"101\",\"name\":\"Ayan Kumar Pan",\"department\":\"IT\"}
```

## Business Use-Case: 
There can be a business requirement to consume a Normal JSON from a boundary application and send it to a JSON field for the target boundary application.

## Solution:
**Step-1:** Add a Data Process Shape.

**Step-2:** Select first Search/Replace

Text To Find: "

Replace With: \\"

<img width="721" alt="image" src="https://github.com/user-attachments/assets/a0de7677-f314-4246-a48a-6fe200203abf" />

**Step-3:** Select first Search/Replace

Text To Find: "

Replace With: \\"

<img width="721" alt="image" src="https://github.com/user-attachments/assets/7674f9bd-c5be-4eb7-b961-81b28367fe8c" /># Convert Normal JSON to String Literal JSON in Boomi

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
**Step-1:** Add a Data Process Shape and add 3 Search/Replace Processing Steps.

**Step-2:** Select the first Search/Replace Processing Step with below options.

<img width="721" alt="image" src="https://github.com/user-attachments/assets/a0de7677-f314-4246-a48a-6fe200203abf" />

**Step-3:** Select the second Search/Replace Processing Step with below options.

<img width="721" alt="image" src="https://github.com/user-attachments/assets/965422e4-f594-4998-bf82-d221341eb9a7" />

**Step-4:** Select the third Search/Replace Processing Step with below options.

<img width="721" alt="image" src="https://github.com/user-attachments/assets/6e59e963-8ac7-4aa4-8f95-cbc75d49f334" />


# ChatGptFunction class

Represents the description of a function available for ChatGPT.

```csharp
public class ChatGptFunction
```

## Public Members

| name | description |
| --- | --- |
| [ChatGptFunction](ChatGptFunction/ChatGptFunction.md)() | The default constructor. |
| [Description](ChatGptFunction/Description.md) { get; set; } | Gets or sets The description of what the function does. |
| [Name](ChatGptFunction/Name.md) { get; set; } | Gets or sets the name of the function to be called. Must be a-z, A-Z, 0-9, or contain underscores and dashes, with a maximum length of 64. |
| [Parameters](ChatGptFunction/Parameters.md) { get; set; } | Gets or sets a JsonDocument containing the parameters the function accepts. |

## See Also

* namespace [ChatGptNet.Models](../ChatGptNet.md)
* [ChatGptFunction.cs](https://github.com/marcominerva/ChatGptNet/tree/master/src/ChatGptNet/Models/ChatGptFunction.cs)

<!-- DO NOT EDIT: generated by xmldocmd for ChatGptNet.dll -->

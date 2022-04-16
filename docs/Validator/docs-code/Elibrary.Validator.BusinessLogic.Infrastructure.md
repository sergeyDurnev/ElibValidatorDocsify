# `EValidationMessageType`

```csharp
public enum Elibrary.Validator.BusinessLogic.Infrastructure.EValidationMessageType
    : Enum, IComparable, IFormattable, IConvertible

```

## Enum

| Value | Name | Description | 
| --- | --- | --- | 
| `0` | Warning |  | 
| `1` | Error |  | 
| `2` | Duplicate |  | 
| `3` | ScienceIndexScopusDuplicate |  | 
| `4` | OnlineFirstDuplicate |  | 



# `TypedValidationMessage`

```csharp
public class Elibrary.Validator.BusinessLogic.Infrastructure.TypedValidationMessage
    : ValidationError

```

## Constructors

- `TypedValidationMessage(String message)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `String` | message |  | 



- `TypedValidationMessage(EValidationMessageType type, String message)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `EValidationMessageType` | type |  | 
   | `String` | message |  | 



- `TypedValidationMessage(String key, String message)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `String` | key |  | 
   | `String` | message |  | 



- `TypedValidationMessage(EValidationMessageType type, String key, String message)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `EValidationMessageType` | type |  | 
   | `String` | key |  | 
   | `String` | message |  | 




## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EValidationMessageType` | Type |  | 




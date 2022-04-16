# `ICommand`

```csharp
public interface Elibrary.Validator.BusinessLogic.Commands.ICommand
    : IAdaptable

```

# `IssueCaptionValidateCommand`

```csharp
public class Elibrary.Validator.BusinessLogic.Commands.IssueCaptionValidateCommand
    : ICommand, IAdaptable

```

## Constructors

- `IssueCaptionValidateCommand()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `String` | AltNumber |  | 
| `String` | Number |  | 
| `String` | Part |  | 
| `Boolean` | Special |  | 
| `Int32` | TitleId |  | 
| `String` | Volume |  | 
| `Int32` | Year |  | 



# `SchemaTypeCommand`

```csharp
public class Elibrary.Validator.BusinessLogic.Commands.SchemaTypeCommand
    : ICommand, IAdaptable

```

## Constructors

- `SchemaTypeCommand()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlType` | Type |  | 



# `XmlValidateCommand`

```csharp
public class Elibrary.Validator.BusinessLogic.Commands.XmlValidateCommand
    : ICommand, IAdaptable

```

## Constructors

- `XmlValidateCommand()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Boolean` | ValidateByXsdScheme |  | 
| `Boolean` | ValidateData |  | 
| `Boolean` | ValidateDuplicates |  | 
| `String` | Xml |  | 




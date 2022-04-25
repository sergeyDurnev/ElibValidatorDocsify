# `IBookValidationService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.IBookValidationService
    : IService, IXmlValidationService

```

# `IDepositedManuscriptValidationService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.IDepositedManuscriptValidationService
    : IService, IXmlValidationService

```

# `IIssueValidationService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.IIssueValidationService
    : IService, IXmlValidationService

```

## Methods

- `Validate(IssueCaptionValidateCommand command)`

   **Return type:** `TypedValidationMessage`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IssueCaptionValidateCommand` | command |  | 




# `IJatsValidationService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.IJatsValidationService
    : IService, IXmlValidationService

```

# `IPatentValidationService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.IPatentValidationService
    : IService, IXmlValidationService

```

# `ISchemaService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.ISchemaService
    : IService

```

## Methods

- `GetSchema(EXmlType type)`

   **Return type:** `XDocument`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `EXmlType` | type |  | 



- `GetSchemaTypesObject(EXmlType type)`

   **Return type:** `IEnumerable<XmlSchemaTypeDto>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `EXmlType` | type |  | 



- `GetSchemaObject(EXmlType type)`

   **Return type:** `XmlSchemaElementDto`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `EXmlType` | type |  | 




# `IXmlValidationService`

```csharp
public interface Elibrary.Validator.BusinessLogic.Services.IXmlValidationService

```

## Methods

- `Validate(XmlValidateCommand command)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `XmlValidateCommand` | command |  | 





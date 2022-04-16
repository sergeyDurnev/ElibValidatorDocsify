# `IDto`

```csharp
public interface Elibrary.Validator.BusinessLogic.Dto.IDto
    : IMappable

```

# `XmlSchemaAttributeDto`

```csharp
public class Elibrary.Validator.BusinessLogic.Dto.XmlSchemaAttributeDto
    : IDto, IMappable

```

## Constructors

- `XmlSchemaAttributeDto()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `String` | DescriptionEng |  | 
| `String` | DescriptionRus |  | 
| `String` | Name |  | 
| `String` | Type |  | 



# `XmlSchemaElementDto`

```csharp
public class Elibrary.Validator.BusinessLogic.Dto.XmlSchemaElementDto
    : IDto, IMappable

```

## Constructors

- `XmlSchemaElementDto()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `IEnumerable<XmlSchemaAttributeDto>` | Attributes |  | 
| `IEnumerable<XmlSchemaElementDto>` | Children |  | 
| `String` | DescriptionEng |  | 
| `String` | DescriptionRus |  | 
| `String` | Name |  | 
| `String` | Type |  | 



# `XmlSchemaTypeDto`

```csharp
public class Elibrary.Validator.BusinessLogic.Dto.XmlSchemaTypeDto
    : IDto, IMappable

```

## Constructors

- `XmlSchemaTypeDto()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `String` | DescriptionEn |  | 
| `String` | DescriptionRu |  | 
| `String` | Name |  | 
| `String` | Pattern |  | 
| `IEnumerable<XmlSchemaTypeValueDto>` | Values |  | 



# `XmlSchemaTypeValueDto`

```csharp
public class Elibrary.Validator.BusinessLogic.Dto.XmlSchemaTypeValueDto
    : IDto, IMappable

```

## Constructors

- `XmlSchemaTypeValueDto()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `String` | DescriptionEn |  | 
| `String` | DescriptionRu |  | 
| `String` | Value |  | 



# `XmlValidationMessageDto`

```csharp
public class Elibrary.Validator.BusinessLogic.Dto.XmlValidationMessageDto
    : IDto, IMappable

```

## Constructors

- `XmlValidationMessageDto()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `String` | Key |  | 
| `String` | Text |  | 
| `EValidationMessageType` | Type |  | 



# `XmlValidationOptionsDto`

```csharp
public class Elibrary.Validator.BusinessLogic.Dto.XmlValidationOptionsDto
    : IMappable

```

## Constructors

- `XmlValidationOptionsDto()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Boolean` | ValidateByXsdScheme |  | 
| `Boolean` | ValidateData |  | 
| `Boolean` | ValidateDuplicates |  | 
| `String` | Xml |  | 
| `EXmlType` | XmlType |  | 




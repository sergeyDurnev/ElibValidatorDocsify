# `BookValidationService`

```csharp
public class Elibrary.Validator.BusinessLogic.Services.Impl.BookValidationService
    : XmlValidationService<Book>, IXmlValidationService, IBookValidationService, IService

```

## Constructors

- `BookValidationService(ILoggerFactory loggerFactory, IValidationProvider validationProvider, IDuplicateRepository duplicateRepository, IConfigurationManager<ApplicationConfiguration> configurationManager)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IValidationProvider` | validationProvider |  | 
   | `IDuplicateRepository` | duplicateRepository |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 




## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlSpecification` | XmlSpecification |  | 
| `Func<XsdSchemesSettings, String>` | XsdSchemePath |  | 



## Methods

- `ValidateDuplicates(Book book)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Book` | book |  | 




# `DepositedManuscriptValidationService`

```csharp
public class Elibrary.Validator.BusinessLogic.Services.Impl.DepositedManuscriptValidationService
    : XmlValidationService<DepositedManuscript>, IXmlValidationService, IDepositedManuscriptValidationService, IService

```

## Constructors

- `DepositedManuscriptValidationService(ILoggerFactory loggerFactory, IValidationProvider validationProvider, IDuplicateRepository duplicateRepository, IConfigurationManager<ApplicationConfiguration> configurationManager)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IValidationProvider` | validationProvider |  | 
   | `IDuplicateRepository` | duplicateRepository |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 




## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlSpecification` | XmlSpecification |  | 
| `Func<XsdSchemesSettings, String>` | XsdSchemePath |  | 



## Methods

- `ValidateDuplicates(DepositedManuscript depositedManuscript)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `DepositedManuscript` | depositedManuscript |  | 




# `IssueValidationService`

```csharp
public class Elibrary.Validator.BusinessLogic.Services.Impl.IssueValidationService
    : XmlValidationService<Journal>, IXmlValidationService, IIssueValidationService, IService

```

## Constructors

- `IssueValidationService(ILoggerFactory loggerFactory, IValidationProvider validationProvider, IDuplicateRepository duplicateRepository, IConfigurationManager<ApplicationConfiguration> configurationManager, ITitleRepository titleRepository)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IValidationProvider` | validationProvider |  | 
   | `IDuplicateRepository` | duplicateRepository |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 
   | `ITitleRepository` | titleRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `ITitleRepository` | TitleRepository |  | 



## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlSpecification` | XmlSpecification |  | 
| `Func<XsdSchemesSettings, String>` | XsdSchemePath |  | 



## Methods

- `Validate(IssueCaptionValidateCommand command)`

   **Return type:** `TypedValidationMessage`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IssueCaptionValidateCommand` | command |  | 



- `ValidateDuplicates(Journal journal)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Journal` | journal |  | 




# `JatsValidationService`

```csharp
public class Elibrary.Validator.BusinessLogic.Services.Impl.JatsValidationService
    : XmlValidationService<Journal>, IXmlValidationService, IJatsValidationService, IService

```

## Constructors

- `JatsValidationService(ILoggerFactory loggerFactory, IValidationProvider validationProvider, IDuplicateRepository duplicateRepository, IConfigurationManager<ApplicationConfiguration> configurationManager, ITitleRepository titleRepository)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IValidationProvider` | validationProvider |  | 
   | `IDuplicateRepository` | duplicateRepository |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 
   | `ITitleRepository` | titleRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `ITitleRepository` | TitleRepository |  | 



## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlSpecification` | XmlSpecification |  | 
| `Func<XsdSchemesSettings, String>` | XsdSchemePath |  | 



## Methods

- `ValidateDuplicates(Journal journal)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Journal` | journal |  | 




# `PatentValidationService`

```csharp
public class Elibrary.Validator.BusinessLogic.Services.Impl.PatentValidationService
    : XmlValidationService<Patent>, IXmlValidationService, IPatentValidationService, IService

```

## Constructors

- `PatentValidationService(ILoggerFactory loggerFactory, IValidationProvider validationProvider, IDuplicateRepository duplicateRepository, IConfigurationManager<ApplicationConfiguration> configurationManager)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IValidationProvider` | validationProvider |  | 
   | `IDuplicateRepository` | duplicateRepository |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 




## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlSpecification` | XmlSpecification |  | 
| `Func<XsdSchemesSettings, String>` | XsdSchemePath |  | 



## Methods

- `ValidateDuplicates(Patent patent)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Patent` | patent |  | 




# `SchemaService`

```csharp
public class Elibrary.Validator.BusinessLogic.Services.Impl.SchemaService
    : ServiceBase, ISchemaService, IService

```

## Constructors

- `SchemaService(ILoggerFactory loggerFactory, IConfigurationManager<ApplicationConfiguration> configurationManager)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 




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




# `XmlValidationService<TRootObject>`

```csharp
public abstract class Elibrary.Validator.BusinessLogic.Services.Impl.XmlValidationService<TRootObject>
    : ServiceBase, IXmlValidationService

```

## Constructors

- `XmlValidationService1(ILoggerFactory loggerFactory, IValidationProvider validationProvider, IDuplicateRepository duplicateRepository, IConfigurationManager<ApplicationConfiguration> configurationManager)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ILoggerFactory` | loggerFactory |  | 
   | `IValidationProvider` | validationProvider |  | 
   | `IDuplicateRepository` | duplicateRepository |  | 
   | `IConfigurationManager<ApplicationConfiguration>` | configurationManager |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `ApplicationConfiguration` | ApplicationConfiguration |  | 
| `IDuplicateRepository` | DuplicateRepository |  | 
| `IValidationProvider` | ValidationProvider |  | 



## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `EXmlSpecification` | XmlSpecification |  | 
| `Func<XsdSchemesSettings, String>` | XsdSchemePath |  | 



## Methods

- `Validate(XmlValidateCommand command)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `XmlValidateCommand` | command |  | 



- `ValidateDuplicates(TRootObject object)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `TRootObject` | object |  | 



- `ValidateData(IEntity node)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IEntity` | node |  | 



- `ValidateBookData(Book book)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Book` | book |  | 



- `ValidateIssueData(Journal journal)`

   **Return type:** `IEnumerable<TypedValidationMessage>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Journal` | journal |  | 



- `BuildArticlesHash(IEnumerable<Article> articles)`

   **Return type:** `IEnumerable<String>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IEnumerable<Article>` | articles |  | 



- `BuildBookHash(Book book)`

   **Return type:** `IEnumerable<PublicationHashModel>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Book` | book |  | 





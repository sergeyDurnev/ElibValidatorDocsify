# `AbstractWrapperValidator`

Валидатор, в котором проверяется сущность AbstractWrapper
```csharp
public class Elibrary.Validator.BusinessLogic.Validators.AbstractWrapperValidator
    : Validator<AbstractWrapper>, IValidator<AbstractWrapper>, IValidator

```

## Constructors

- `AbstractWrapperValidator(IValidationProvider validationProvider)`

   Инициализация объекта AbstractWrapperValidator

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider | Свойство Elibrary.Engine.Validation при помощи которого собираются все обнаруженные ошибки | 



## Methods

- `Validate(AbstractWrapper abstractWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   Проверка объекта AbstractWrapper на наличие ошибок

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `AbstractWrapper` | abstractWrapper | Обёртка класса Abstract. Эта обёртка нужна для указания типа публикации и номера статьи (если есть) в сообщении об ошибке | 




# `ArticleNameWrapperValidator`

Валидатор, в котором проверяется обёртка ArticleNameWrapper
```csharp
public class Elibrary.Validator.BusinessLogic.Validators.ArticleNameWrapperValidator
    : Validator<ArticleNameWrapper>, IValidator<ArticleNameWrapper>, IValidator

```

## Constructors

- `ArticleNameWrapperValidator(IValidationProvider validationProvider)`

   Инициализация класса ArticleValidator

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider | Свойство Elibrary.Engine.Validation при помощи которого собираются все обнаруженные ошибки | 



## Methods

- `Validate(ArticleNameWrapper articleNameWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   Проверка сущности ArticleName (название статьи) на наличие ошибок

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ArticleNameWrapper` | articleNameWrapper | Проверяемое название статьи | 




# `ArticleValidator`

Валидатор, в котором проверяется сущность Article
```csharp
public class Elibrary.Validator.BusinessLogic.Validators.ArticleValidator
    : Validator<Article>, IValidator<Article>, IValidator

```

## Constructors

- `ArticleValidator(IValidationProvider validationProvider, IItemRepository itemRepository)`

   Инициализация класса ArticleValidator

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 
   | `IItemRepository` | itemRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider | Свойство Elibrary.Engine.Validation при помощи которого собираются все обнаруженные ошибки | 



## Methods

- `Validate(Article article)`

   **Return type:** `IEnumerable<ValidationError>`

   Проверка сущности Article (статья) на наличие ошибок

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Article` | article | Сущность article. Это может быть статья в журнале в сбонике | 




# `AuthorInfoWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.AuthorInfoWrapperValidator
    : Validator<AuthorInfoWrapper>, IValidator<AuthorInfoWrapper>, IValidator

```

## Constructors

- `AuthorInfoWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(AuthorInfoWrapper authorInfoWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `AuthorInfoWrapper` | authorInfoWrapper |  | 




# `AuthorWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.AuthorWrapperValidator
    : Validator<AuthorWrapper>, IValidator<AuthorWrapper>, IValidator

```

## Constructors

- `AuthorWrapperValidator(IValidationProvider validationProvider, IAuthorRepository authorRepository)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 
   | `IAuthorRepository` | authorRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(AuthorWrapper authorWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `AuthorWrapper` | authorWrapper |  | 




# `BookInfoWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.BookInfoWrapperValidator
    : Validator<BookInfoWrapper>, IValidator<BookInfoWrapper>, IValidator

```

## Constructors

- `BookInfoWrapperValidator()`


## Methods

- `Validate(BookInfoWrapper bookInfoWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `BookInfoWrapper` | bookInfoWrapper |  | 




# `BookValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.BookValidator
    : Validator<Book>, IValidator<Book>, IValidator

```

## Constructors

- `BookValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(Book book)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Book` | book |  | 




# `CharacteristicWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.CharacteristicWrapperValidator
    : Validator<CharacteristicWrapper>, IValidator<CharacteristicWrapper>, IValidator

```

## Constructors

- `CharacteristicWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(CharacteristicWrapper characteristicWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `CharacteristicWrapper` | characteristicWrapper |  | 




# `CodeWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.CodeWrapperValidator
    : Validator<CodeWrapper>, IValidator<CodeWrapper>, IValidator

```

## Constructors

- `CodeWrapperValidator(IValidationProvider validationProvider, IEdnRepository ednRepository)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 
   | `IEdnRepository` | ednRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(CodeWrapper codeWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `CodeWrapper` | codeWrapper |  | 




# `DepositedManuscriptValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.DepositedManuscriptValidator
    : Validator<DepositedManuscript>, IValidator<DepositedManuscript>, IValidator

```

## Constructors

- `DepositedManuscriptValidator(IValidationProvider validationProvider, IAuthorRepository authorRepository)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 
   | `IAuthorRepository` | authorRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(DepositedManuscript depositedManuscript)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `DepositedManuscript` | depositedManuscript |  | 




# `FileWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.FileWrapperValidator
    : Validator<FileWrapper>, IValidator<FileWrapper>, IValidator

```

## Constructors

- `FileWrapperValidator()`


## Methods

- `Validate(FileWrapper fileWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `FileWrapper` | fileWrapper |  | 




# `FullTextWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.FullTextWrapperValidator
    : Validator<FullTextWrapper>, IValidator<FullTextWrapper>, IValidator

```

## Constructors

- `FullTextWrapperValidator()`


## Methods

- `Validate(FullTextWrapper fullTextWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `FullTextWrapper` | fullTextWrapper |  | 




# `FundingWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.FundingWrapperValidator
    : Validator<FundingWrapper>, IValidator<FundingWrapper>, IValidator

```

## Constructors

- `FundingWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(FundingWrapper fundingWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `FundingWrapper` | fundingWrapper |  | 




# `IssueNameValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.IssueNameValidator
    : Validator<IssueName>, IValidator<IssueName>, IValidator

```

## Constructors

- `IssueNameValidator()`


## Methods

- `Validate(IssueName issueName)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IssueName` | issueName |  | 




# `IssueValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.IssueValidator
    : Validator<Issue>, IValidator<Issue>, IValidator

```

## Constructors

- `IssueValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(Issue issue)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Issue` | issue |  | 




# `JournalNameValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.JournalNameValidator
    : Validator<JournalName>, IValidator<JournalName>, IValidator

```

## Constructors

- `JournalNameValidator()`


## Methods

- `Validate(JournalName journalName)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `JournalName` | journalName |  | 




# `JournalValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.JournalValidator
    : Validator<Journal>, IValidator<Journal>, IValidator

```

## Constructors

- `JournalValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(Journal journal)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Journal` | journal |  | 




# `KeywordWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.KeywordWrapperValidator
    : Validator<KeywordWrapper>, IValidator<KeywordWrapper>, IValidator

```

## Constructors

- `KeywordWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(KeywordWrapper keywordWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `KeywordWrapper` | keywordWrapper |  | 




# `NestedElementsWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.NestedElementsWrapperValidator
    : Validator<NestedElementsWrapper>, IValidator<NestedElementsWrapper>, IValidator

```

## Constructors

- `NestedElementsWrapperValidator()`


## Methods

- `Validate(NestedElementsWrapper nestedElementsWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `NestedElementsWrapper` | nestedElementsWrapper |  | 




# `OrganizationInfoWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.OrganizationInfoWrapperValidator
    : Validator<OrganizationInfoWrapper>, IValidator<OrganizationInfoWrapper>, IValidator

```

## Constructors

- `OrganizationInfoWrapperValidator()`


## Methods

- `Validate(OrganizationInfoWrapper organizationInfoWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `OrganizationInfoWrapper` | organizationInfoWrapper |  | 




# `PatentNameWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.PatentNameWrapperValidator
    : Validator<PatentNameWrapper>, IValidator<PatentNameWrapper>, IValidator

```

## Constructors

- `PatentNameWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(PatentNameWrapper object)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `PatentNameWrapper` | object |  | 




# `PatentValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.PatentValidator
    : Validator<Patent>, IValidator<Patent>, IValidator

```

## Constructors

- `PatentValidator(IValidationProvider validationProvider, IAuthorRepository authorRepository)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 
   | `IAuthorRepository` | authorRepository |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(Patent patent)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `Patent` | patent |  | 




# `ReferenceInfoWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.ReferenceInfoWrapperValidator
    : Validator<ReferenceInfoWrapper>, IValidator<ReferenceInfoWrapper>, IValidator

```

## Constructors

- `ReferenceInfoWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(ReferenceInfoWrapper referenceInfoWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ReferenceInfoWrapper` | referenceInfoWrapper |  | 




# `ReferenceWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.ReferenceWrapperValidator
    : Validator<ReferenceWrapper>, IValidator<ReferenceWrapper>, IValidator

```

## Constructors

- `ReferenceWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(ReferenceWrapper referenceWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `ReferenceWrapper` | referenceWrapper |  | 




# `RubricWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.RubricWrapperValidator
    : Validator<RubricWrapper>, IValidator<RubricWrapper>, IValidator

```

## Constructors

- `RubricWrapperValidator()`


## Methods

- `Validate(RubricWrapper rubricWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `RubricWrapper` | rubricWrapper |  | 




# `SectionNameWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.SectionNameWrapperValidator
    : Validator<SectionNameWrapper>, IValidator<SectionNameWrapper>, IValidator

```

## Constructors

- `SectionNameWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(SectionNameWrapper sectionNameWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `SectionNameWrapper` | sectionNameWrapper |  | 




# `SectionWrapperValidator`

```csharp
public class Elibrary.Validator.BusinessLogic.Validators.SectionWrapperValidator
    : Validator<SectionWrapper>, IValidator<SectionWrapper>, IValidator

```

## Constructors

- `SectionWrapperValidator(IValidationProvider validationProvider)`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `IValidationProvider` | validationProvider |  | 




## Fields

| Type | Name | Description | 
| --- | --- | --- | 
| `IValidationProvider` | ValidationProvider |  | 



## Methods

- `Validate(SectionWrapper sectionWrapper)`

   **Return type:** `IEnumerable<ValidationError>`

   | Type | Name | Description | 
   | --- | --- | --- | 
   | `SectionWrapper` | sectionWrapper |  | 





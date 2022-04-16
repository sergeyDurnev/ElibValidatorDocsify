# `AbstractWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.AbstractWrapper

```

## Constructors

- `AbstractWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Abstract` | Abstract |  | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `IEnumerable<File>` | Files |  | 
| `PublicationType` | PublicationType |  | 



# `ArticleNameWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.ArticleNameWrapper

```

## Constructors

- `ArticleNameWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `ArticleName` | ArticleName |  | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `PublicationType` | PublicationType |  | 



# `AuthorInfoWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.AuthorInfoWrapper

```

## Constructors

- `AuthorInfoWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `AuthorInfo` | AuthorInfo |  | 
| `Int32` | AuthorNumber |  | 
| `PublicationType` | PublicationType |  | 



# `AuthorWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.AuthorWrapper

```

## Constructors

- `AuthorWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `Author` | Author |  | 
| `Int32` | AuthorNumber |  | 
| `PublicationType` | PublicationType |  | 



# `BookInfoWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.BookInfoWrapper

```

## Constructors

- `BookInfoWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `BookInfo` | BookInfo |  | 
| `String` | Type |  | 



# `CharacteristicWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.CharacteristicWrapper

```

## Constructors

- `CharacteristicWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Characteristic` | Characteristic |  | 
| `PublicationType` | PublicationType |  | 



# `CodeWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.CodeWrapper

```

## Constructors

- `CodeWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `Code` | Code |  | 
| `Boolean` | IsReplaced |  | 
| `PublicationType` | PublicationType |  | 



# `EObjectName`

```csharp
public enum Elibrary.Validator.BusinessLogic.Wrappers.EObjectName
    : Enum, IComparable, IFormattable, IConvertible

```

## Enum

| Value | Name | Description | 
| --- | --- | --- | 
| `0` | Abstract |  | 
| `1` | Author |  | 
| `2` | Funding |  | 
| `3` | Keyword |  | 
| `4` | Name |  | 
| `5` | Reference |  | 
| `6` | Section |  | 



# `FileWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.FileWrapper

```

## Constructors

- `FileWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `File` | File |  | 
| `PublicationType` | PublicationType |  | 



# `FullTextWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.FullTextWrapper

```

## Constructors

- `FullTextWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `FullText` | FullText |  | 
| `PublicationType` | PublicationType |  | 



# `FundingWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.FundingWrapper

```

## Constructors

- `FundingWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `Funding` | Funding |  | 
| `PublicationType` | PublicationType |  | 



# `KeywordWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.KeywordWrapper

```

## Constructors

- `KeywordWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `Keyword` | Keyword |  | 
| `Int32` | KeywordNumber |  | 
| `PublicationType` | PublicationType |  | 



# `NestedElementsWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.NestedElementsWrapper

```

## Constructors

- `NestedElementsWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `Nullable<Int32>` | AuthorNumber |  | 
| `Nullable<Int32>` | KeywordNumber |  | 
| `EObjectName` | ObjectName |  | 
| `PublicationType` | PublicationType |  | 
| `Nullable<Int32>` | ReferenceNumber |  | 
| `String` | Value |  | 



# `OrganizationInfoWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.OrganizationInfoWrapper

```

## Constructors

- `OrganizationInfoWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `OrganizationInfo` | OrganizationInfo |  | 
| `PublicationType` | PublicationType |  | 



# `PatentNameWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.PatentNameWrapper

```

## Constructors

- `PatentNameWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `PatentName` | PatentName |  | 
| `PublicationType` | PublicationType |  | 



# `ReferenceInfoWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.ReferenceInfoWrapper

```

## Constructors

- `ReferenceInfoWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `PublicationType` | PublicationType |  | 
| `ReferenceInfo` | ReferenceInfo |  | 
| `Int32` | ReferenceNumber |  | 
| `String` | ReferenceType |  | 



# `ReferenceWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.ReferenceWrapper

```

## Constructors

- `ReferenceWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `PublicationType` | PublicationType |  | 
| `Reference` | Reference |  | 
| `Int32` | ReferenceNumber |  | 
| `String` | ReferenceType |  | 



# `RubricWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.RubricWrapper

```

## Constructors

- `RubricWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `PublicationType` | PublicationType |  | 
| `Rubric` | Rubric |  | 
| `Int32` | RubricNumber |  | 



# `SectionNameWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.SectionNameWrapper

```

## Constructors

- `SectionNameWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `PublicationType` | PublicationType |  | 
| `SectionName` | SectionName |  | 



# `SectionWrapper`

```csharp
public class Elibrary.Validator.BusinessLogic.Wrappers.SectionWrapper

```

## Constructors

- `SectionWrapper()`


## Properties

| Type | Name | Description | 
| --- | --- | --- | 
| `Nullable<Int32>` | ArticleNumber |  | 
| `PublicationType` | PublicationType |  | 
| `Section` | Section |  | 




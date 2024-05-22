---
title: CurrencyMapper
description: API reference for CurrencyMapper in Umbraco Commerce
---
## CurrencyMapper

```csharp
public static class CurrencyMapper
```

**Namespace**
* [Umbraco.Commerce.Cms.Web.Models.Mappers](README.md)

### Methods

#### CurrencyEntitiesToBasicDtos

```csharp
public static IEnumerable<CurrencyBasicDto> CurrencyEntitiesToBasicDtos(
    IEnumerable<CurrencyReadOnly> entities)
```


---

#### CurrencyEntityToBasicDto

```csharp
public static CurrencyBasicDto CurrencyEntityToBasicDto(CurrencyReadOnly entity, 
    CurrencyBasicDto dto = null)
```


---

#### CurrencyEntityToEditDto

```csharp
public static CurrencyEditDto CurrencyEntityToEditDto(CurrencyReadOnly entity, 
    CurrencyEditDto dto = null)
```


---

#### CurrencySaveDtoToEntity

```csharp
public static Currency CurrencySaveDtoToEntity(CurrencySaveDto dto, Currency entity)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->
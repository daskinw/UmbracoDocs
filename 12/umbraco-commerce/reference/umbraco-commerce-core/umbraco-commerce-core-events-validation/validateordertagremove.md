---
title: ValidateOrderTagRemove
description: API reference for ValidateOrderTagRemove in Umbraco Commerce
---
## ValidateOrderTagRemove

```csharp
public class ValidateOrderTagRemove : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateOrderTagRemove

```csharp
public ValidateOrderTagRemove(OrderReadOnly order, string tag)
```


### Properties

#### Order

```csharp
public OrderReadOnly Order { get; }
```


---

#### Tag

```csharp
public string Tag { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

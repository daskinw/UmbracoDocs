---
title: DiscountCode
description: API reference for DiscountCode in Umbraco Commerce
---
## DiscountCode

```csharp
public class DiscountCode : EntityBase
```

**Inheritance**

* class [EntityBase](entitybase.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Constructors

#### DiscountCode (1 of 2)

```csharp
public DiscountCode(string code, int? usageLimit = null, bool isUnlimited = false)
```

---

#### DiscountCode (2 of 2)

```csharp
public DiscountCode(Guid id, string code, int? usageLimit = null, bool isUnlimited = false)
```


### Properties

#### Code

```csharp
public string Code { get; }
```


---

#### Id

```csharp
public override Guid Id { get; }
```


---

#### IsUnlimited

```csharp
public bool IsUnlimited { get; }
```


---

#### UsageLimit

```csharp
public int? UsageLimit { get; }
```


### Methods

#### DeepClone

```csharp
public override object DeepClone()
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

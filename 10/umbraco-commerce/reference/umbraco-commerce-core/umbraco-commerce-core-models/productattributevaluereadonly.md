---
title: ProductAttributeValueReadOnly
description: API reference for ProductAttributeValueReadOnly in Umbraco Commerce
---
## ProductAttributeValueReadOnly

```csharp
public class ProductAttributeValueReadOnly : EntityBase<ProductAttributeValueState>
```

**Inheritance**

* class [EntityBase&lt;TState&gt;](entitybase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Properties

#### Alias

Gets the Alias of the Product Attribute

```csharp
public string Alias { get; }
```


---

#### Name

Gets the Name of the Product Attribute

```csharp
public ReadOnlyTranslatedValue<string> Name { get; }
```


---

#### ProductAttributeId

Gets the ID of the [`ProductAttribute`](productattribute.md) this entity belongs to

```csharp
public Guid ProductAttributeId { get; }
```


---

#### StoreId

Gets the ID of the [`Store`](store.md) this entity belongs to

```csharp
public Guid StoreId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

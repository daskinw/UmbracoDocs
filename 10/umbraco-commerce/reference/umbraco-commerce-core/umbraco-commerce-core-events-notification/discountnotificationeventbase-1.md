---
title: DiscountNotificationEventBase<TEntity>
description: API reference for DiscountNotificationEventBase<TEntity> in Umbraco Commerce
---
## DiscountNotificationEventBase&lt;TEntity&gt;

```csharp
public abstract class DiscountNotificationEventBase<TEntity> : NotificationEventBase
    where TEntity : DiscountReadOnly
```

**Inheritance**

* class [NotificationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/notificationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### DiscountNotificationEventBase&lt;TEntity&gt;

```csharp
public DiscountNotificationEventBase(TEntity discount)
```


### Properties

#### Discount

```csharp
public TEntity Discount { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

---
title: BundledOrderLineReadOnly
description: API reference for BundledOrderLineReadOnly in Umbraco Commerce
---
## BundledOrderLineReadOnly

```csharp
public class BundledOrderLineReadOnly : OrderLineReadOnly
```

**Inheritance**

* class [OrderLineReadOnly](orderlinereadonly.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Properties

#### ParentBundleId

Gets the bundle ID of the parent order line to this order line

```csharp
public string ParentBundleId { get; }
```


---

#### ParentOrderLineId

Gets the ID of the parent [`OrderLineReadOnly`](orderlinereadonly.md) this entity belongs to

```csharp
public Guid ParentOrderLineId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
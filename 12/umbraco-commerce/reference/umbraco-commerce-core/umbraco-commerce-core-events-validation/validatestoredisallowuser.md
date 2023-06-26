---
title: ValidateStoreDisallowUser
description: API reference for ValidateStoreDisallowUser in Umbraco Commerce
---
## ValidateStoreDisallowUser

```csharp
public class ValidateStoreDisallowUser : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateStoreDisallowUser

```csharp
public ValidateStoreDisallowUser(StoreReadOnly store, string userId)
```


### Properties

#### Store

```csharp
public StoreReadOnly Store { get; }
```


---

#### UserId

```csharp
public string UserId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
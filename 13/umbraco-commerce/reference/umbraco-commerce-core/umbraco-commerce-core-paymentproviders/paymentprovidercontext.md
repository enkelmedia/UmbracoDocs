---
title: PaymentProviderContext
description: API reference for PaymentProviderContext in Umbraco Commerce
---
## PaymentProviderContext

```csharp
public class PaymentProviderContext
```

**Namespace**
* [Umbraco.Commerce.Core.PaymentProviders](README.md)

### Properties

#### AdditionalData

```csharp
public IDictionary<string, object> AdditionalData { get; }
```


---

#### Order

```csharp
public OrderReadOnly Order { get; }
```


---

#### Request

```csharp
public HttpRequestMessage Request { get; }
```


---

#### Settings

```csharp
public IReadOnlyDictionary<string, string> Settings { get; }
```


---

#### Urls

```csharp
public PaymentProviderUrlsContext Urls { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

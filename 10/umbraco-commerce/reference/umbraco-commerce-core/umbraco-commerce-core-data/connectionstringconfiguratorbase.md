---
title: ConnectionStringConfiguratorBase
description: API reference for ConnectionStringConfiguratorBase in Umbraco Commerce
---
## ConnectionStringConfiguratorBase

```csharp
public abstract class ConnectionStringConfiguratorBase : 
    IConfigureNamedOptions<ConnectionStringConfig>, IConfigureOptions<ConnectionStringConfig>
```

**Namespace**
* [Umbraco.Commerce.Core.Data](README.md)

### Methods

#### Configure

```csharp
public virtual void Configure(ConnectionStringConfig options)
```


---

#### Configure

```csharp
public abstract void Configure(string name, ConnectionStringConfig options)
```


---

#### DoConfigure

```csharp
public virtual void DoConfigure(string name, ConnectionStringConfig options)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

---
title: IHasReadableServicePrices
description: API reference for IHasReadableServicePrices in Umbraco Commerce
---
## IHasReadableServicePrices

```csharp
public interface IHasReadableServicePrices
```

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Methods

#### GetCountryPriceForCurrency (1 of 2)

```csharp
public decimal GetCountryPriceForCurrency(CountryReadOnly country, CurrencyReadOnly currency)
```

---

#### GetCountryPriceForCurrency (2 of 2)

```csharp
public decimal GetCountryPriceForCurrency(Guid countryId, Guid currencyId)
```


---

#### GetDefaultPriceForCurrency (1 of 2)

```csharp
public decimal GetDefaultPriceForCurrency(CurrencyReadOnly currency)
```

---

#### GetDefaultPriceForCurrency (2 of 2)

```csharp
public decimal GetDefaultPriceForCurrency(Guid currencyId)
```


---

#### GetRegionPriceForCurrency (1 of 2)

```csharp
public decimal GetRegionPriceForCurrency(RegionReadOnly region, CurrencyReadOnly currency)
```

---

#### GetRegionPriceForCurrency (2 of 2)

```csharp
public decimal GetRegionPriceForCurrency(Guid countryId, Guid regionId, Guid currencyId)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->

# Address Finder

## Description
> C# application where addresses can be found using the Google Places &amp; Geocoding API.

## Preview
![](https://github.com/nicholas-dietz/address-finder/blob/master/img/preview.gif) 

## Google API Key
[Get API Key](https://developers.google.com/maps/documentation/javascript/get-api-key?hl=en)
> **Note:** API-Key must be activated for Google-Places API & Google-Geocoding API

### Set API-Key
Navigate to ./AddressFinder/**AddressForm.cs**
>```csharp
>private static protected string apiKey = "<your-api-key>";
>```
  
## Dependencies
- [Serilog](https://github.com/serilog/serilog)
- [Newtonsoft](https://github.com/JamesNK/Newtonsoft.Json)

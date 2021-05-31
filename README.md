# Paytrim.Validationhelper  [![buildstatus](https://github.com/Paytrim/Paytrim.Validationhelper/actions/workflows/dotnet.yml/badge.svg)](https://github.com/Paytrim/Paytrim.Validationhelper/actions/workflows/dotnet.yml) 

Validate Bankaccount
* Get name of bank

Validate SwedishPersonalId(Personnummer)
* Get IsSammorningsnummer
* Get DateOfBirth

Validate SwedishCompanyId(Organisationsnummer) 

## Getting Started
Check if valid
 ```csharp
    var isValid = Organisationsnummer.TryParse("XXXXXX-XXXX");
   ```
Get bankname etc
 ```csharp
   var swedishBank = new SwedishBankAccount("xxxx-xxxxxxx");
   swedishBank.SwedishBank.Name;
   ```

## License

Distributed under the MIT License. See `LICENSE` for more information.

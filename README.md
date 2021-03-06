# CSV Join LINQ
A command-line tool for performing left outer joins on CSV files in C# .NET Core using LINQ:
```
CsvJoin.exe Data sales.csv new_sales.csv > joined_sales.csv
```

## Features:
- Execute LINQ against CSV files
- Save results to CSV
- Generate C# models and LINQ by using T4 Text Templates

## To implement:
- Protect against code injection

## Prerequisites:
- .NET Core 3.1
- Visual Studio 2019

## Build and run:
### VS:
- src\CsvJoin.sln > Build > Transform All T4 Templates
- F5

## Acknowledgements:
- Microsoft.Extensions.DependencyInjection by https://www.nuget.org/packages/Microsoft.Extensions.DependencyInjection (MIT license)
- System.Linq by .NET Core (MIT License)
- ServiceStack.Text by https://www.nuget.org/packages/ServiceStack.Text ([license](https://github.com/ServiceStack/ServiceStack.Text/blob/master/license.txt))

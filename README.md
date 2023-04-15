# StocksVisualizer

## How to Use
1. Download Solution and go to the root of the project
2. Run the following command lines in PowerShell changing `<Token>` with your token obtained from https://finnhub.io/, for example  `"cdf843903459340-2"`
```
dotnet user-secrets init --project StocksVisualizer
dotnet user-secrets set "FinnhubToken" "<Token>" --project StocksVisualizer
dotnet user-secrets list --project StocksVisualizer
```
3. Run the solution either from Visual Studio 2022 or from the same command line with `dotnet run`

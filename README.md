# Install .NET Tool - Sonar Scanner

Install the latest version of [Sonar Scanner for .NET](https://www.nuget.org/packages/dotnet-sonarscanner) using `dotnet tool`.

## Usage

To use this action in your GitHub repository, you can follow these steps:

```yaml
uses: maurosoft1973/gha-dotnet-tool-install-sonarscanner@v1
```

### Inputs

```yaml
with:
  # The version of Sonar Scanner to install.
  version: 9.0.2
```

### Outputs

This action has no outputs.

## Examples

### Install Sonartscanner using `dotnet tool`

```yaml
steps:
  - name: Install Sonar Scanner
    uses: maurosoft1973/gha-dotnet-tool-install-sonarscanner@v1
```

## Contributing to Install .NET Tool - Sonar Scanner

Contributions are welcome! 
Feel free to submit issues, feature requests, or pull requests to help improve this action.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

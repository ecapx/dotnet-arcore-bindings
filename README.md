# .NET Bindings for Google ARCore

This repository contains updated .NET bindings for the [Google ARCore](https://developers.google.com/ar?hl=de) library for use with e.g. .NET MAUI.

They are meant as a successor to the old [ARCore bindings](https://www.nuget.org/packages/Xamarin.Google.ARCore) which are no longer maintained.

The published bindings are only tested to the extent that they compile and can run the HelloAR sample app.

## Installation

The bindings are available on [NuGet]().

```bash
dotnet add package
```

## Usage

```csharp
using Google.AR.Core;
// ...
var session = new Session(Platform.AppContext);
// ...
```

Please check the official [ARCore documentation](https://developers.google.com/ar/develop?hl=en) for more information.

## Contributing

Pull requests are welcome. Unfortunately, I don't have the time to properly maintain this repository. If you want to take over,
please let me know.

## License

[MIT](https://choosealicense.com/licenses/mit/)
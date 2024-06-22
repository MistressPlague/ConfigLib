# ConfigLib
A Lazy-Use Config With Automatic Loading And Saving. Use Is Close To How It Would Be Without A Config.

# Install with NuGet
https://www.nuget.org/packages/Kannya.ConfigLib/

# Example Usage
```csharp
public ConfigLib<YourClass> Config = new ConfigLib<YourClass>("PathToWhereYouWantItSaved.json");

public class YourClass
{
  public bool thing { get; set; } = false;
}

public void Read()
{
  if (Config.InternalConfig.thing)
  {
    Config.InternalConfig.thing = false; // auto saves after small delay if changes are detected
  }
}
```

# ConfigLib
A Lazy-Use Config With Automatic Loading And Saving. Use Is Close To How It Would Be Without A Config.
# Example Usage
```csharp
public ConfigLib<YourClass> Config = new ConfigLib<YourClass>("PathToWhereYouWantItSaved.json");

public class YourClass
{
  public bool thing { get; set; } = false;
}
```

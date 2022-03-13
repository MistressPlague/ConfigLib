# ConfigLib
A Lazy-Use Config With Automatic Loading &amp; Saving. Use Is Close To How It'd Be Without A Config.
# Example Usage
```csharp
public ConfigLib<YourClass> Config = new ConfigLib<YourClass>("PathToWhereYouWantItSaved.json");

public class YourClass
{
  public bool thing { get; set; } = false;
}
```

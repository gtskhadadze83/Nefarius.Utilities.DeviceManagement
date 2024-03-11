# DeviceEventArgs

Namespace: Nefarius.Utilities.DeviceManagement.PnP

Device change event arguments.

```csharp
public class DeviceEventArgs
```

Inheritance [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object) → [DeviceEventArgs](./nefarius.utilities.devicemanagement.pnp.deviceeventargs.md)

## Properties

### <a id="properties-interfaceguid"/>**InterfaceGuid**

The [Guid](https://docs.microsoft.com/en-us/dotnet/api/system.guid) of the device interface.

```csharp
public Guid InterfaceGuid { get; set; }
```

#### Property Value

[Guid](https://docs.microsoft.com/en-us/dotnet/api/system.guid)<br>

### <a id="properties-symlink"/>**SymLink**

The symbolic link path.

```csharp
public string SymLink { get; set; }
```

#### Property Value

[String](https://docs.microsoft.com/en-us/dotnet/api/system.string)<br>

## Constructors

### <a id="constructors-.ctor"/>**DeviceEventArgs()**

```csharp
public DeviceEventArgs()
```

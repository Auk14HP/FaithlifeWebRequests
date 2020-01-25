# WebServiceRequestSettings.StartTrace property

A Func that, if set, is called to start a trace when a web request begins; its return value will be disposed when the web request ends.

```csharp
public Func<HttpRequestMessage, IDisposable> StartTrace { get; set; }
```

## See Also

* class [WebServiceRequestSettings](../WebServiceRequestSettings.md)
* namespace [Faithlife.WebRequests](../../Faithlife.WebRequests.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.WebRequests.dll -->
<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# MaximumContentLength property

Declaring type: [Sisk.Core.Http.HttpServerConfiguration](/spec/Sisk.Core.Http.HttpServerConfiguration.md) (from Sisk.Core)


Definition:

```cs
public long MaximumContentLength { get; set; }
```

Gets or sets the maximum size of a request body before it is closed by the socket.

> **Remarks:**
>
> Leave it as "0" to set the maximum content length to unlimited.
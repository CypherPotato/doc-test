<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->

# RequestHandlerAttribute class
Assembly: Sisk.Core

Namespace: Sisk.Core.Routing

Definition:

```cs
[AttributeUsage(AttributeTargets.Method, AllowMultiple = true)]
public class RequestHandlerAttribute : Attribute
```

Specifies that the method, when used on this attribute, will instantiate the type and call the <a href="/spec/Sisk.Core.Routing.IRequestHandler.md">IRequestHandler</a> with given parameters.

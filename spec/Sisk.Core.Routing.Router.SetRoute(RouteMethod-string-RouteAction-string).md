<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# SetRoute(RouteMethod, string, RouteAction, string) method

Declaring type: [Sisk.Core.Routing.Router](/spec/Sisk.Core.Routing.Router.md) (from Sisk.Core)


Definition:

```cs
public void SetRoute(RouteMethod method, string path, RouterCallback action, string? name)
```

Defines an route with their method, path, action function and name.


# Parameters

<table>
    <tbody>
<tr>
    <td width="33%">method</td>
    <td>The route method to be matched. "Any" means any method that matches their path.</td>
</tr>
<tr>
    <td width="33%">path</td>
    <td>The route path.</td>
</tr>
<tr>
    <td width="33%">action</td>
    <td>The route function to be called after matched.</td>
</tr>
<tr>
    <td width="33%">name</td>
    <td>The route name.</td>
</tr>
    </tbody>
</table>
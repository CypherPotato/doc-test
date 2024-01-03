<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# ListeningPort(int, bool) constructor

Declaring type: [Sisk.Core.Http.ListeningPort](/spec/Sisk.Core.Http.ListeningPort.md) (from Sisk.Core)


Definition:

```cs
public ListeningPort(int port, bool secure)
```

Creates an new <a href="/spec/Sisk.Core.Http.ListeningPort.md">ListeningPort</a> instance with the specified port and secure context at the loopback host.


# Parameters

<table>
    <tbody>
<tr>
    <td width="33%">port</td>
    <td>The port the server will listen on.</td>
</tr>
<tr>
    <td width="33%">secure</td>
    <td>Indicates whether the server should listen to this port securely (SSL).</td>
</tr>
    </tbody>
</table>
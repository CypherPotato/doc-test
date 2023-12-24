<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# Configure(long, TimeSpan) method

Declaring type: [Sisk.Core.Http.RotatingLogPolicy](/read?q=/contents/spec/Sisk.Core.Http.RotatingLogPolicy.md) (from Sisk.Core)


Definition:

```cs
public void Configure(long maximumSize, TimeSpan due)
```

Defines the time interval and size threshold for starting the task, and then starts the task.

> **Remarks:**
>
> The first run is performed immediately after calling this method.

# Parameters

<table>
    <tbody>
<tr>
    <td width="33%">maximumSize</td>
    <td>The non-negative size threshold of the log file size in byte count.</td>
</tr>
<tr>
    <td width="33%">due</td>
    <td>The time interval between checks.</td>
</tr>
    </tbody>
</table>
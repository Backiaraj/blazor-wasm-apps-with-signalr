# Blazor WASM App with SignalR

This example explain how to use the [Blazor WASM App](https://blazor.syncfusion.com/documentation/getting-started/blazor-webassembly-app) with SignalR.

## Overview

`SignalR` is an open-source .NET library that simplifies adding real-time web functionality to applications. It automatically handles the best transport method (WebSockets, Server-Sent Events, or Long Polling) and provides a high-level API for server-to-client and client-to-server communication. SignalR enables persistent two-way connections between clients and servers, allowing instant data synchronization without polling.

## Key Benefits of SignalR

* **Real-Time Communication**: Establish persistent connections for instant data updates across all connected clients.
* **Bidirectional**: Support both server-to-client (broadcasting) and client-to-server (commands) communication.
* **Automatic Transport Selection**: Intelligently choose the best transport protocol (WebSockets, SSE, Long Polling) based on browser and server capabilities.
* **Scalable Broadcasting**: Efficiently broadcast updates to multiple clients simultaneously using SignalR groups.
* **Built-in Reconnection**: Automatically handles client reconnection with exponential back off retry logic.
* **No Page Refresh Required**: Update UI dynamically without reloading the page.
* **Cross-Platform**: Works across browsers, mobile devices, and desktop applications.

## Prerequisites

* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## How to run the project

1. Clone or download this repository to a location in your system.
2. Open the solution file using the Visual Studio or Visual Studio code.
3. Restore the NuGet packages by rebuilding the solution or run `dotnet restore`.
4. Build the project to ensure there are no compilation errors.
5. Run the project.

Optional CLI Commands:

```powershell
dotnet restore
dotnet build
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/connecting-to-backends/signalr
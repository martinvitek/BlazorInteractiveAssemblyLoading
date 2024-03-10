# BlazorInteractiveAssemblyLoading
Blazor InteractiveWeb Assembly .NET 8 application with loading progress when blazor web assembly is loading on client side.

In .NET 7 the Web Assembly apllication has loading bar but it is not present in default .NET 8 tamplate mode.

This application is standard .NET 8 template Blazar Web App with Global WebAssembly interactive render mode. The loading progess is done by wrapping the router component in a Loading copoment.

```
<LoadingProgress>
<Routes />
</LoadingProgress>
```

The Loading compoment is based on the cod from chapter **Blazor WebAssembly app loading progress** that can be found on https://learn.microsoft.com/en-us/aspnet/core/blazor/fundamentals/startup?view=aspnetcore-8.0 


# NetPro.TypeFinder
![.NET Core](https://github.com/LeonKou/NetPro/workflows/.NET%20Core/badge.svg)
 [![NuGet](https://img.shields.io/nuget/v/NetPro.TypeFinder.svg)](https://nuget.org/packages/NetPro.TypeFinder)
 
程序集dll 类型查找辅助服务

 ### 使用
 #### 启用服务
```csharp
public void ConfigureServices(IServiceCollection services,IConfiguration configuration)
{
     services.AddFileProcessService();
}

```

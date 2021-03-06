[**Nancy**](https://github.com/NancyFx/Nancy) is a lightweight, low-ceremony, framework for building HTTP based services on .NET Framework/Core and [Mono](http://mono-project.com). The goal of the framework is to stay out of the way as much as possible and provide a super-duper-happy-path to all interactions.

Nancy is designed to handle `DELETE`, `GET`, `HEAD`, `OPTIONS`, `POST`, `PUT` and `PATCH` requests and provides a simple, elegant, [Domain Specific Language (DSL)](http://en.wikipedia.org/wiki/Domain-specific_language) for returning a response with just a couple of keystrokes, leaving you with more time to focus on the important bits..
**your** code and **your** application.

Write your application
```csharp
public class Module : NancyModule
{
    public Module()
    {
        Get("/greet/{name}", x => {
            return string.Concat("Hello ", x.name);
        });
    }
}
```

---
The [**corefx**](https://github.com/dotnet/corefx) repo contains the library implementation for .NET Core. It includes System.Collections, System.IO, System.Xml, and many other components. You can see more information in Documentation. The corresponding .NET Core Runtime repo contains the runtime implementation (called "CoreCLR") for .NET Core. It includes RyuJIT, the .NET GC, and many other components. Runtime-specific library code - namely mscorlib - lives in the CoreCLR repo. It needs to be built and versioned in tandem with the runtime. The rest of CoreFX is agnostic of runtime-implementation and can be run on any compatible .NET runtime.

---
[**Roslyn**](https://github.com/dotnet/roslyn) provides open-source C# and Visual Basic compilers with rich code analysis APIs. It enables building code analysis tools with the same APIs that are used by Visual Studio.

---
[**DotNetty**](https://github.com/Azure/DotNetty) is a port of Netty, asynchronous event-driven network application framework for rapid development of maintainable high performance protocol servers & clients.

---
[**Cake**](https://github.com/cake-build/cake) (C# Make) is a build automation system with a C# DSL to do things like compiling code, copy files/folders, running unit tests, compress files and build NuGet packages.

---
[**OpenTK**](https://github.com/opentk/opentk) is a fast, low-level C# binding for OpenGL, OpenGL ES and OpenAL. It runs on all major platforms and powers hundreds of apps, games and scientific research.

Use OpenTK to add cross-platform 3d graphics, audio, compute and haptics to your C# application. Integrate it into your existing user interface or use it standalone without any external dependencies.

---
[**NUnit**](https://github.com/nunit/nunit) is a unit-testing framework for all .NET languages. Initially ported from JUnit, the current production release, version 3, has been completely rewritten with many new features and support for a wide range of .NET platforms.

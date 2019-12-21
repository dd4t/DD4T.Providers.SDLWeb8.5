[![AppVeyor](https://ci.appveyor.com/api/projects/status/github/dd4t/DD4T.Providers.SDLWeb8.5?branch=master&svg=true&passingText=master)](https://ci.appveyor.com/project/DD4T/dd4t-providers-sdlweb8-5)

[![AppVeyor](https://ci.appveyor.com/api/projects/status/github/dd4t/DD4T.Providers.SDLWeb8.5?branch=develop&svg=true&passingText=develop)](https://ci.appveyor.com/project/DD4T/dd4t-providers-sdlweb8-5)

# DD4T.Provider.SDLWeb8.5
DD4T in-process provider for SDL Web 8.5

## Release 2.5

- Added missing DependencyMappings so the providers can now be loaded automatically by the DD4T.DI.* packages
- Fixed issue with getting the component presentation with the highest priority (4)
- Upgraded references to DD4T.Core 2.5


## How to use it

This provider requires the SDL Web 8.5 API (in-process) Server Role. This means that you need to copy some DLLs, configuration files and even jar files into the bin folder of your application. Since the in-process CIL is commercial software, we are not allowed to package this with DD4T. For instructions on how to install this server role, see [docs.sdl.com](https://docs.sdl.com/LiveContent/content/en-US/SDL%20Web-v5/GUID-0D330E1A-A753-45D2-B462-3121F756EE14).

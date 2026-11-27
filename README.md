# RBXDecomp for VC2005

## Before reading, please check out the original repo at https://github.com/OpenRBX-org/RBXDecomp.

This is a port of RBXDecomp from its CMake-based build chain to Visual C++ 2005, as the original source would have likely been.

## Building
Open Roblox.sln in VS2005, select Release for the configuration and Win32 for the platform (select the WebService platform if you're building RBXGS).

If you get a file-not-found error about `rgmain.lib` during the linking stage, rebuild the rgmain projects and then build all the other rg* DLLs from then. Retry building Roblox and it should build successfully.

## Status
Currently **only the client** builds properly without modification to the graphics library projects. However WebService will build if the Mesa libraries have been properly compiled and linked.


## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before you open a pull request.

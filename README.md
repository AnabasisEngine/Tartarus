# Tartarus
[![Build](https://github.com/AnabasisEngine/Tartarus/actions/workflows/dotnet.yml/badge.svg)](https://github.com/AnabasisEngine/Tartarus/actions/workflows/dotnet.yml)

Experiments in the manipulation of SPIR-V shader intermediate code directly from C#/.NET with the eventual goal of 
managed SPIR-V reflection and generation of SPIR-V from managed C# shader pseudo-code/DSL.

This project will use the `spirv.h` bindings provided by [Silk.NET](https://github.com/dotnet/Silk.NET) once 
[this pull request](https://github.com/dotnet/Silk.NET/pull/1403) is complete and merged; development of this project
is largely on hold until that time.
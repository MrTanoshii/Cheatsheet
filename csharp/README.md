<div align="center">
  <a href="https://docs.microsoft.com/en-us/dotnet/csharp/"><img src="https://github.com/devicons/devicon/blob/master/icons/csharp/csharp-original.svg" title="C#" alt="C#" width="64" height="64"></a>
</div>

## Table of Contents

- [Style Guide](#book-style-guide)

## :book: Style Guide

Further reading: https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions

## [Access Modifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)

| Access Modifier     | Description                                                                                                                                                                                                                        |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| public:             | The type or member can be accessed by any other code in the same assembly or another assembly that references it. The accessibility level of public members of a type is controlled by the accessibility level of the type itself. |
| private:            | The type or member can be accessed only by code in the same `class` or `struct`.                                                                                                                                                   |
| protected:          | The type or member can be accessed only by code in the same `class`, or in a `class` that is derived from that `class`.                                                                                                            |
| internal:           | The type or member can be accessed by any code in the same assembly, but not from another assembly. In other words, `internal` types or members can be accessed from code that is part of the same compilation.                    |
| protected internal: | The type or member can be accessed by any code in the assembly in which it's declared, or from within a derived `class` in another assembly.                                                                                       |
| private protected:  | The type or member can be accessed by types derived from the `class` that are declared within its containing assembly.                                                                                                             |

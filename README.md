`System.Memory` does not work with `Windows Application Packaging Project`s.

Set `WapProj` as startup project and hit F5. Then the following exception is thrown:

```
System.BadImageFormatException
  HResult=0x80131058
  Message=Could not load file or assembly "System.Memory, Version=4.0.1.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51" or one of its dependencies. Reference assemblies should not be loaded for execution. They can only be loaded in the Reflection-only loader context. (Exception of HRESULT: 0x80131058)
  Source=<Cannot evaluate the exception source>
  StackTrace:
<Cannot evaluate the exception stack trace>
```
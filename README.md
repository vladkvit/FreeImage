FreeImage
=========

This is the FreeImage code, but updated to Visual Studio 2013 and a saner directory structure. No source code changes.

Please note that Enhanced Instruction Set is enabled - turn it off if the target CPU isn't recent.

The build output is in the "Source/$(ProjectName)/$(Platform)/$(Build Type)/" folder for every project other than dynamically-linked FreeImage. FreeImage DLLs are in the "$(Platform)/$(Build Type)/DLL" folder.

This code is version 3.15.4 (one release out of date at the time of writing).

# VCTargets\Platform\Win32\Platform.Common.props missing ItemDefinitionGroup for Lib TargetMachine

Example showcasing the following issue:
https://developercommunity.visualstudio.com/content/problem/395185/vctargetsplatformwin32platformcommonprops-missing.html

## Steps to reproduce
1) create Windows C++ static lib
2) add Resource file (with string resource)
3) Compile for x86

Expected:
    No Warnings

Actual Results:
    1>LINK : warning LNK4068: /MACHINE not specified; defaulting to X86


# NetworkDirect SPI

The NetworkDirect architecture provides application developers with a networking interface that enables zero-copy data transfers between applications, kernel-bypass I/O generation and completion processing, and one-sided data transfer operations. The NetworkDirect service provider interface (SPI) defines the interface that NetworkDirect providers implement to expose their hardware capabilities to applications.

Please find additional documentation in [docs/](./docs) folder.

# Building

## Prerequisites

 - Visial Studio

   Please make sure to select the following workloads during installation:
    - .NET desktop development (required for CBT/Nuget packages)
    - Desktop development with C++ 

 - [Windows SDK](https://developer.microsoft.com/windows/downloads/windows-10-sdk)
 - [Windows WDK](https://docs.microsoft.com/windows-hardware/drivers/download-the-wdk)
 
 Based on the installed VS/SDK/WDK versions, update _VCToolsVersion_ and _WindowsTargetPlatformVersion_ Directory.Build.props
 
 ## Build
 To build, just run ``msbuild`` from root folder.

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

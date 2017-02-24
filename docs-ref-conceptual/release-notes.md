---
title: Azure CLI 2.0 release notes
description: Learn about the latest updates to Azure CLI 2.0
keywords: Azure CLI 2.0, release notes
author: allclark
manager: douge
ms.date: 02/27/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.assetid: ce0428f7-0a59-4e72-9237-d907b171af51
---

# Azure CLI 2.0 release notes

## February 27, 2017

Version 0.1.2

This release of Azure CLI 2.0 is the first "Generally Available" release.
General availability applies to these command modules:
- Container Service (acs)
- Compute (including Resource Manager, VM, VM Scale Sets, Managed Disks)
- Networking
- Storage

These command modules can be used in production and are supported by standard Microsoft SLA.
You can open issues directly with Microsoft support or on our [github issues list](https://github.com/azure/azure-cli/issues).
You can ask questions on [StackOverflow using the azure-cli tag](http://stackoverflow.com/questions/tagged/azure-cli),
or contact the product team at [azfeedback@microsoft.com](mailto:azfeedback@microsoft.com).
You can provide feedback from the command line, use `az feedback`.

The commands in these modules are stable and the syntax will not change in upcoming releases of this version of Azure CLI.

To verify the version of the CLI, use `az --version`.
The output lists the version of the CLI itself (0.1.2 in this release), the individual command modules,
and the versions of Python and GCC that you're using.

```
azure-cli (0.1.2)
 
acs (0.1.2)
appservice (0.1.1b3)
batch (0.1.1b3)
cloud (0.1.2)
component (0.1.1)
configure (0.1.2)
container (0.1.1b2)
core (0.1.2)
documentdb (0.1.1b1)
feedback (0.1.2)
iot (0.1.1b2)
keyvault (0.1.1b4)
network (0.1.2)
nspkg (0.1.2)
profile (0.1.2)
redis (0.1.1b2)
resource (0.1.2)
role (0.1.2)
sql (0.1.1b3)
storage (0.1.2)
vm (0.1.2)
 
Python (Darwin) 2.7.10 (default, Jul 30 2016, 19:40:32) 
[GCC 4.2.1 Compatible Apple LLVM 8.0.0 (clang-800.0.34)]
```

> [!Note]
> Some of the command modules have a "b*n*" or "rc*n*" postfix.
> These command modules are still in preview and will become generally available in the future.

We also have nightly preview builds of the CLI.
For information, see these instructions on [getting the nightly builds](https://github.com/Azure/azure-cli#nightly-builds),
and these instructions on [developer setup and contributing code](https://github.com/Azure/azure-cli#developer-setup).

You can report issues with nightly preview builds in the following ways:
- Report issues in our [github issues list](https://github.com/azure/azure-cli/issues)
- Contact the product team at [azfeedback@microsoft.com](mailto:azfeedback@microsoft.com).
- Provide feedback from the command line, use `az feedback`.

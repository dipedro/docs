﻿<a name="install-aspnet-core" />

## Install the ASP.NET Core Runtime 2.2

[!include[Proceed as root](../su.md)]

Register the Microsoft key and package repository (this only needs to be done once per machine), then install the ASP.NET Core runtime package:

[!include[Install ASP.NET Core Runtime](../../../../../includes/linux/rhel/install-aspnetcore-22.md)]

> [!NOTE]
> If the command above fails due to broken dependencies, for instance on *libicu*, make sure your system is [registered and attached to a Red Hat subscription](https://access.redhat.com/solutions/253273)

[!include[Test dotnet](../test-dotnet-22.md)]

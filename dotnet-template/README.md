# Overview
Microsoft provides a good base template for dotnet docker projects. These instructions were tested on Windows 10.

https://github.com/microsoft/dotnet-framework-docker/tree/main/samples/aspnetmvcapp

# Troubleshooting
You may need to switch to "Windows" containers, as the default for Docker Desktop is "Linux" containers. That option is found in the docker settings.

https://docs.docker.com/desktop/windows/#settings

https://docs.docker.com/desktop/windows/#switch-between-windows-and-linux-containers

When switching, you may need to run an Admin Powershell command to enable Hyper-V, then restart.
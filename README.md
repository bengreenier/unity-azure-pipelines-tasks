# Unity Tools for Azure DevOps

This extension adds tools for use in Azure Pipelines with Unity 3D. Use these tools to build a Unity project and configure
CI / CD for your projects.

![Build Status](https://dev.azure.com/dinomite/Unity%20Tools%20for%20Azure%20DevOps/_apis/build/status/Unity%20Tools%20for%20Azure%20DevOps%20-%20CI?branchName=master)

The `master` branch is automatically built and deployed to the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=DinomiteStudios.64e90d50-a9c0-11e8-a356-d3eab7857116).

## Included Build / Release Tasks

- Unity Get Project Version
- Unity Build

## Supported Unity Target Platforms

- PC & Mac Standalone
- iOS
- tvOS
- Android
- Universal Windows Platform
- WebGL

## How to use

Visit the [Wiki](https://github.com/Dinomite-Studios/unity-azure-pipelines-tasks) for detailed instructions on how to setup your Unity pipelines and configure your agents.

### Custom installation

You'll need these tools to build and deploy the tasks yourself:

- [Node.js®](https://nodejs.org/en/)
- [Node CLI for Azure DevOps](https://www.npmjs.com/package/tfx-cli)
- [TypeScript](https://www.npmjs.com/package/typescript)

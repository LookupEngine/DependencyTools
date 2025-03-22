# Dependency Tools for Revit

A collection of tools for analyzing and managing dependencies in Revit plugins.

## Overview

This repository contains two main tools designed to help developers manage and analyze dependencies in Revit plugins:

1. DependenciesReport — for static analysis of dependency conflicts.
2. AssembliesReport — for runtime analysis of loaded assemblies.

## DependenciesReport

A tool for static analysis of dependency conflicts between plugins. This tool can:
- Analyze dependency conflicts without starting Revit.
- Generate detailed conflict reports.
- Optionally update dependencies to their latest versions.
- Help identify potential compatibility issues.

Conflicts Summary:
![изображение](https://github.com/user-attachments/assets/a5f94bd8-7eca-4998-91c7-99d7b079fa47)

Upgrading:
![изображение](https://github.com/user-attachments/assets/649b6f75-3f55-42b5-8c77-6df4dc04b72d)

> [!WARNING]  
> When using the upgrade feature, please be cautious as dependencies that are not backwards compatible may break older plugins.

## AssembliesReport

A Revit-integrated tool that creates detailed reports on loaded assemblies and their dependencies. This tool is particularly useful for:
- Tracing dependency loading paths
- Debugging assembly loading issues
- Understanding the dependency tree of your Revit plugins

Revit add-in location:
![изображение](https://github.com/user-attachments/assets/85982c9b-6080-4a12-a2aa-18193d0f29ee)

Report Output:
![изображение](https://github.com/user-attachments/assets/a8a3a8fb-71a3-4f03-967a-3ee71a6c7aeb)
# CItron 🍋

CItron [si.tʁon] is a C#-based CI/CD tool.

It's totally **unrelated** to the Yuzu-fork (Switch emulator).

## 𝍕 About

Creating and maintaining a CI/CD system is an arduous task in itself:
testing locally is sometimes impossible or involves a lot of jumping through hoops,
dependencies such as required programs, environment variables and secrets must be managed
-- often in separate procedures, and often mistakes can only be discovered, debugged and resolved
after stopping the production.

To make things worse, migrating from one system to another is a larger project,
that often surpasses what an individual dev or a small team can achieve within
a strict temporal constraint.

Building on [my previous attempt to make GHA CI easier to handle](https://github.com/KageKirin/gha-py-toolbox),
CItron's approach is to implement a CI/CD system entirely in C#,
in a way that allows easier local testing,
easier porting from one CI/CD backend to another,
as well as (hopefully) easier environment management.


As I start working on this project, the goal is to become independent
of GitHub Actions, CircleCI or whatever else CI/CD system there is,
in a way of being able to painlessly migrate my personal repos to other Git hosts
if needed.

## 🖇️ Components

`Citron.CLI` is the frontend executable.

`Citron.Core` is the library implementing the core functionality.

`Citron.RRR` is the library implementing **R**untime **R**oslyn **R**ecompilation,
a feature used to allow local feature extension.

## ⚡ Getting Started

TBD

## 🔧 Building and Running

### 🔨 Build the Project

Until we are self-hosted, the build command is using dotnet.

```shell
dotnet build
```

### ▶ Running and Settings

## 🤝 Collaborate

Please refer to the [collaboration guide](./COLLABORATION.md).

### NO AI SLOB

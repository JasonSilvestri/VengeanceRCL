# GiveSendGo.com/DDE Discovery

`GiveSendGo.com/DDE` (_Deaf, Disabled & Elderly_)™ Discovery acts as a basic blueprint for consistent, scalable, and maintainable creation of content and assets.

---

## **Discovery Variant:**

> [!TIP]
> You are currently viewing the **"_Discovery_" _Variant_** of the **VengeanceRCL Project**. This is not typically created, and is only here to reference the original discovery we performed on this specific information, before evolving content in the way we use it today.
> 
> For the latest details, see [Get Latest](#getting-started) _below_.

---

```bash
# For The Cool Kids: Clone VengeanceRCL Git Repository
$ git clone https://github.com/JasonSilvestri/VengeanceRCL.git
```

---

[`Home`](../../README.md) » [`Introduction`](../ReadMe.md) » [`Get Latest »`](./JSopxNovaFileandDirectoryDesignPatterns.md)

---


## Table of Contents  

 - [Overview](#overview)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
      - [Step 1: Clone the Repository](#step-1-clone-the-repository)
      - [Step 2: Open the Solution](#step-2-open-the-solution)
      - [Step 3: Configure the Project](#step-3-configure-the-project)
      - [Step 4: Build and Run](#step-4-be-sure-to-build-and-run)
      - [Step 5: Project File Structure](#step-5-project-file-structure)
      - [Step 6: Project References & Dependencies](#step-6-jsopx-project-references--dependencies)
      - [Step 7: Usage](#step-7-usage)
      - [Step 8: Extended Usage](#step-8-extended-usage)
  - [Next Steps](#next-steps)

---

## Current Phase

> [!NOTE]
>
>**Phases 1**: This document is currently aligned with [Phase 1: Minimum Viable Product (MVP)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Phases/Phase-1.md) Business Requirements. 
> 

---

## Overview

**DDE™ (_Deaf, Disabled & Elderly_)** Discovery acts as a basic (_original_) blueprint for consistent, scalable, and maintainable creation of content and assets, including markdown documents that support most current initiatives with the `DDE`, such as the content, fundraiser and developed promotional video, as outlined in the [Table of Contents](#table-of-contents) section.

---

## **Prerequisites**

Be sure each technology is installed, with proper versioning, if your goal is to continue exploring and/or installing just the `VengeanceRCL` Project.

- [Visual Studio (v 17.13.5)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)
- [.NET Framework (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#net-framework)
- [ASP.NET Core (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#aspnet-core)
- [Node.js (v 20.14.0)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#node)
- [npm (v 10.8.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#npm)
- [Vue (v 3.4.21)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#vue)
- [Vite (v 5.2.8)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#vite)


---

## Corequisites

These resources served as the primary references during the development of the applications and related content. I followed them closely throughout, but I recommend revisiting them periodically—especially if you need clarity on any implementation decisions. 

- [Development Standards](../../../../Introduction/JSopxDevelopmentStandards.md)
- [Business Requirements](../../../../Introduction/JSopxEnterpriseBusinessRequirements.md)

---

## Business Concerns Addressed

The **DDE™ GiveSendGo Project** addresses **several** high-level **business concerns**, not only shown through design patterns and best practices within its own DDE™ Project ecosystem, but ultimately as it evolves into a valuable project component of the Jason Silvestri Open Project EXperiences (DDE™) Enterprise Application too. 

[`Back to Top`](#table-of-contents) · · [`Next »`](#1-simulating-an-existing-project)

---

## **`VengeanceRCL` Project: Brought to you by Music Revolutuion**:

We initially create the **DDE™ GiveSendGo Project** to help fight the good fight, but it is quickly turning into a place to Snash. 

![Music Revolutuion](https://github.com/JasonSilvestri/VengeanceRCL/blob/master/VengeanceRCL/wwwroot/images/music-revolution-splash.png)

[`Back to Top`](#table-of-contents) · · [`« Previous`](#business-concerns-addressed) [`Next »`](#getting-started)

---

## **Getting Started**

Follow these steps to get started with the `VengeanceRCL` Project. This guide assumes you have a basic understanding of Git, Visual Studio, or Node.js if you plan to use their approach.

## **Step 1: Clone the Repository**

_Clone_ the `VengeanceRCL` GitHub Repository if you plan to explore it independently from the rest of the projects.

Choose the approach below that fits your environment:  

- **[Bash](#step-11-using-bash)** → Ideal for **Linux, macOS, and Windows (WSL/Git Bash)** users.  
- **[PowerShell](#step-12-using-powershell)** → Best for **Windows** users.  
- **[Node.js](#step-13-using-nodejs-or-npm-degit)** → A lightweight option for developers using **JavaScript-based workflows**.  

---

### **Option 1: Using `Bash`:**
 
```bash

 # Using Bash: Clone VengeanceRCL Git Repository

 # 1. Navigate to the desired local directory where you plan to clone the repository
 cd path\to\local\repo\JasonSilvestri\VengeanceRCL

 # 2. Clone VengeanceRCL Git Repository       
 git clone https://github.com/JasonSilvestri/VengeanceRCL.git
    
```

[`Back to Top`](#table-of-contents)

---

### **Option 2: Using `Powershell`:**

```powershell

 # Using PowerShell: Clone VengeanceRCL Git Repository

 # 1. Navigate to the desired local directory where you plan to clone the repository
 cd path\to\local\repo\JasonSilvestri\VengeanceRCL

 # 2. Clone VengeanceRCL Git Repository       
 git clone https://github.com/JasonSilvestri/VengeanceRCL.git
    
```

[`Back to Top`](#table-of-contents)

---

### **Option 3: Using `Node.js` or `npm` (degit):**
 
```shell

 # Using Node.js / npm : Clone VengeanceRCL Git Repository
 # 1. Navigate to the desired local directory where you plan to clone the repository
 cd path\to\local\repo\JasonSilvestri\VengeanceRCL
    
 # 2. Using npx degit to clone without .git history
 npx degit https://github.com/JasonSilvestri/VengeanceRCL

```

[`Back to Top`](#table-of-contents)

---

## **Step 2: Open the Solution**

Working with the `VengeanceRCL` Project in Visual Studio is simple enough.

1. Launch **[Visual Studio (v 17.13.5)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)**.
2. Open the solution file: `VengeanceRCL.sln`.

[`Back to Top`](#table-of-contents)

---

## **Step 3: Configure the Project**

> [!TIP]
>
> Latest versions of [Visual Studio](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio) performs this step regularly, dropping and restoring project dependencies, nuget packages and other resources between builds automatically (*by design*). Still, it is good practice to at least be aware of the commands outlined in this step.
> 

---

### **Step: 3.1: Ensure Dependencies Are Restored:**

Ensure `VengeanceRCL` Project dependencies are restored:

   ```bash
   npm install
   ```


[`Back to Top`](#table-of-contents)

---

### **Option: 3.2: Verify Nuget Packages:**

Verify that all NuGet packages are up to date:

   ```bash
   dotnet restore
   ```
   
[`Back to Top`](#table-of-contents)

---

## **Step 4: Be Sure to Build and Run**

Building and Running the `VengeanceRCL` Project in Visual Studio is also another simple task.

### **Step: 4.1: Build and Run**:

1. Build the solution in [Visual Studio](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/VengeanceRCL/p1/v1/Technologies/#visual-studio).
2. Run the project:
   - Use the **IIS Express** profile for local development.

---

### **Step: 4.2: And Now Your Done**:

Assuming the `VengeanceRCL` Project is running as expected, **you are now done** with the **installation** and **execution** of the project!

1. **Skip Remaining Steps**: 
   - Technically, you could skip to the [Next Steps](#next-steps) section if you are on a project-by-project installation mission.
2. **Conclude Remaining Steps**:
   - **Me personally?** I would continue on to the remaining steps _below_, starting at **[Step 5: Project Structure](#step-5-project-file-structure)**. There is just very useful information related to the project that I would find helpful.

[`Back to Top`](#table-of-contents)

---

## **Step 6: DDE™ Project References & Dependencies**

> [!TIP]
>
> The `VengeanceRCL` Project should already have the DDE™ Project References & Dependencies described below included!
> 

---

## **Step 7: Usage**

Although the `VengeanceRCL` project is primarily designed as a self-contained demonstration project, it is fully capable of integration with other DDE™ projects. Here's how to add it to your project:

---

### **Step 7.1: Adding the DDE™ Vue Core to Other Projects**

1. **Add Project Reference**:
   - Open your solution in Visual Studio.
   - Right-click the project that will use `VengeanceRCL` and select `Add > Project Reference`.
   - Check the box for `VengeanceRCL` and click `OK`.

[`Back to Top`](#table-of-contents)

---

## **Step 8: Extended Usage**

> [!TIP]
> These particular `Extended Usage` examples **are not** required to implement. They are just example extended usages for those of whom are new to projects like the `VengeanceRCL` Project.
>

---



[`Home`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/VengeanceRCL/README.md) » [`Introduction`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Introduction/) » [`Projects`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/) · · **`Use Latest`** · [`By-Phase`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/VengeanceRCL/p1/v1/README.md) · [`From Scratch`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/VengeanceRCL/p1/v1/RECREATEME.md) · · [`Back to Top`](#table-of-contents) · [`« Previous`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.ReactCore/) [`Next »`](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/OpenProjects/jsopx.BlazorServerCore/)

---

##### [JSopX.com](https://www.jsopx.com/) | [Jason's Official Website](https://www.jsilvestri.com/) | [X](https://www.x.com/JasonSilvestri) | [LinkedIn](http://www.linkedin.com/in/JasonSilvestri) | [GitHub](https://github.com/JasonSilvestri) | [Gmail](mailto:therealjasonsilvestri@gmail.com) | [Phone : 508-851-9445](phoneto:508-851-9445)

###### Copyright © 2025 - All Rights Reserved by Jason Silvestri

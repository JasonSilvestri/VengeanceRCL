# GiveSendGo.com/DDE VengeanceRCL

`GiveSendGo.com/DDE` (_Deaf, Disabled & Elderly_)™ VengeanceRCL (_Razor Class Library_) acts as a basic blueprint for consistent, scalable, and maintainable creation of content and assets.

---

```bash
# For The Cool Kids: Clone VengeanceRCL Git Repository
$ git clone https://github.com/JasonSilvestri/VengeanceRCL.git
```

---

[`Home`](./README.md) · · [`Next »`](./../docs/Official/StoryboardMarkers.md)

---

### `VengeanceRCL`: Brought to You by Musician Revolutuion

The `VengeanceRCL` Razor Class Library is brought you by **Musician Revolutuion**.

![Musician Revolutuion](https://github.com/JasonSilvestri/VengeanceRCL/blob/master/VengeanceRCL/wwwroot/images/musician-revolution-splash.png)


## Table of Contents  

 - [Overview](#overview)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
      - [Step 1: Clone the Repository](#step-1-clone-the-repository)
      - [Step 2: Open the Solution](#step-2-open-the-solution)
      - [Step 3: Configure the Project](#step-3-configure-the-project)
      - [Step 4: Build and Run](#step-4-be-sure-to-build-and-run)
      - [Step 5: Project File Structure](#step-5-project-file-structure)
      - [Step 6: Usage](#step-6-usage)
  - [Next Steps](#next-steps)

---

## Overview

**DDE™ (_Deaf, Disabled & Elderly_)** Discovery acts as a basic (_original_) blueprint for consistent, scalable, and maintainable creation of content and assets, including markdown documents that support most current initiatives with the `DDE`, such as the content, fundraiser and developed promotional video, as outlined in the [Table of Contents](#table-of-contents) section.

---

## **Prerequisites**

Before you can get started with the `VengeanceRCL` Project, you need to ensure you have the following prerequisites installed and configured on your system:

---

### **Core Technologies**:

These technologies are essential for the development and execution of the `VengeanceRCL` Project. They provide the necessary frameworks, libraries, and tools to build and run the project effectively.

- [Visual Studio (v 17.14.7)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)
- [.NET Framework (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#net-framework)
- [ASP.NET Core (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#aspnet-core)
- [Node.js (v 20.14.0)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#node)
- [npm (v 10.8.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#npm)

---

### **Extended Use of AI**:

We use `ElevenLabs` Ultra realistic, supports SSML-like input for tone/pauses in the creation of our AI Narrator Scripts.
 
- [ElevenLabs (v 3)](https://www.elevenlabs.io)

---

### **Video Editing**:

Due to Jason's dinosaur laptop, we use `Shotcut` as the quick and dirty video editor to create videos. Our current laptops can't handle the more modern editors with advanced graphics card requirements.

- [Shotcut (v 24.11.01)](https://shotcut.org/download/)


[`Back to Top`](#table-of-contents)

---

## **Getting Started**

Follow these steps to get started with the `VengeanceRCL` Project. 

This guide will walk you through the process of setting up the `VengeanceRCL` Razor Class Library, including cloning the repository, opening the solution in Visual Studio, configuring the project, and running it.

---

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

1. Launch **[Visual Studio (v 17.14.7)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)**.
2. Open the solution file: `VengeanceRCL.sln`.

[`Back to Top`](#table-of-contents)

---

## **Step 3: Configure the Project**

> [!TIP]
>
> Latest versions of [Visual Studio](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio) performs this step regularly, dropping and restoring project dependencies, nuget packages and other resources between builds automatically (*by design*). Still, it is good practice to at least be aware of the commands outlined in this step.
> 

---

### **Option: 3.1: Verify Nuget Packages:**

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

## **Step 5: Project File Structure**

Here’s the `Project File Structure` for the `VengeanceRCL` Razor Class Library in both the _plaintext-tree_ and _styled-table_ formats.

---

### **Step: 5.1: Structured File Tree**:

See the structured file tree below for a quick overview of the `VengeanceRCL` Project, using the _plaintext-tree_ format:

```plaintext

# VengeanceRCL Solution
VengeanceRCL/
├── VengeanceRCL.sln                            # Solution file linking projects
└── VengeanceRCL/                               # Razor Class Library project directory
    ├── VengeanceRCL.csproj                     # Project file for the Razor Class Library
    └── wwwroot/                                # Static web assets and documentation
        ├── docs/                               # Documentation directory
        │   ├── Discovery/                      # Discovery-related markdown and resources
        │   └── Official/                       # Official legal and reference documents
        ├── artwork/                            # Design assets such as logos and artwork
        ├── Audio Assets/                       # Audio files for narration and music
        └── images/                             # Image assets for documentation and splash screens
            └── musician-revolution-splash.png  # Project splash image used in the README

```

---

### **Step: 5.2: Structured Table**:

See the structured file tree below for a quick overview of the `VengeanceRCL` Project, using the _styled-table_ format:

| **File/Directory**                                                                          | **Description**                                                         |
|:--------------------------------------------------------------------------------------------|:------------------------------------------------------------------------|
| &nbsp;📁&nbsp;**VengeanceRCL/**                                                              | Root folder containing the solution                                     |
| &nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`VengeanceRCL.sln`                                           | Solution file linking projects                                          |
| &nbsp;&nbsp;&nbsp;└📁&nbsp;**VengeanceRCL/**                                                 | Subfolder for the Razor Class Library project                           |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`VengeanceRCL.csproj`                      | Project file for the Razor Class Library                                |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└📁&nbsp;**wwwroot/**                                    | Static web assets and documentation                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📂&nbsp;**docs/**               | Documentation directory                                                 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📂&nbsp;**Discovery/** | Discovery-related markdown and resources                                 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└&nbsp;📂&nbsp;**Official/**  | Official legal and reference documents                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📂&nbsp;**artwork/**            | Design assets such as logos and artwork                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📂&nbsp;**Audio Assets/**       | Audio files for narration and music                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└&nbsp;📂&nbsp;**images/**             | Image assets for documentation and splash screens                        |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└&nbsp;🖼️‎&nbsp;`musician-revolution-splash.png` | Project splash image used in the README                                  |


[`Back to Top`](#table-of-contents)

---

### **Step: 5.3: Expect Growth**:

> [!IMPORTANT]
>
> Expect the file structures **_shown_ above** to grow as we add more content.
> 

The `VengeanceRCL` structures **_shown_ above** is one of the most basic iterations of the file structure. There are many videos, images, and documents that will be committed in chunks, due to the size of the collection of media.

Expect the file structures to grow as we add more content.

[`Back to Top`](#table-of-contents)

---

## **Step 6: Usage**

The `VengeanceRCL` project is designed as a self-contained media project that we will be using as the official temporary project until we create an official Musician Revolution repository. 

---

### **Step 6.1: Adding the `VengeanceRCL` Razor Class Library to Other Projects**

1. **Add Project Reference**:
   - Open your solution in Visual Studio.
   - Right-click the project that will use `VengeanceRCL` and select `Add > Project Reference`.
   - Check the box for `VengeanceRCL` and click `OK`.

[`Back to Top`](#table-of-contents)

---

## Next Steps:

if **you did everything right**, you should now have a fully functional `VengeanceRCL` Project set up and running. 

With that said, the `VengeanceRCL` Razor Class Library is a _Razor Class Library_, and not typically run standalone. Still, this part of the application is the documentation part of the application, and it is perfectly normal to review this content on the fly, via the repository and/or within Visual Studio.

There are several sections of the project that you can explore further. In fact, the `VengeanceRCL` Project is designed to be modular and extensible, allowing you to dive deeper into specific areas of interest.

- [1. Storyboard Markers](./../docs/Official/StoryboardMarkers.md)
- [2. Rules of Engagement](./../docs/Official/RulesofEngagement.md)
- [3. Deep Discovery](./../docs/Official/DeepDiscovery.md)
- [4. Viral Exposé Video Script](./../docs/Official/ViralExposeVideoScript.md)
- [5. Editing Videos with Shotcut](./../docs/Official/EditingVideoswithShotcut.md)
- [6. DDE AI Narrator Voice Script](./../docs/Official/DdeGiveSendGoAiNarratorVoiceScript.md)
- [7. DDE Campaign](./../docs/Official/DdeGiveSendGoCampaignSync.md)
- [8. DDE Legal](./../docs/Official/DdeGiveSendGoLegal.md)

---

[`Home`](./README.md) · · [`Back to Top`](#table-of-contents) · [`Next »`](./../docs/Official/StoryboardMarkers.md)

---

##### Follow Campaign: [www.givesendgo.com/dde](https://www.givesendgo.com/dde)

###### Copyright © 2025 - All Rights Reserved by Jason Silvestri & Scott Hall
# DDE GiveSendGo VengeanceRCL

`GiveSendGo.com/DDE` (_Deaf, Disabled & Elderly_)™ VengeanceRCL (_Razor Class Library_) acts as a basic blueprint for consistent, scalable, and maintainable creation of content and assets.

---

```bash
# For The Cool Kids: Clone VengeanceRCL Git Repository
$ git clone https://github.com/JasonSilvestri/VengeanceRCL.git
```

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

### **1. Core Technologies**:

These technologies are essential for the development and execution of the `VengeanceRCL` Project. They provide the necessary frameworks, libraries, and tools to build and run the project effectively.

- [Visual Studio (v 17.14.7)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)
- [.NET Framework (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#net-framework)
- [ASP.NET Core (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#aspnet-core)
- [Node.js (v 20.14.0)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#node)
- [npm (v 10.8.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#npm)

---

### **2. Extended Use of AI**:

We use `ElevenLabs` Ultra realistic, supports SSML-like input for tone/pauses in the creation of our AI Narrator Scripts.
 
- [ElevenLabs (v 3)](https://www.elevenlabs.io)

---

### **3. Video Editing**:

Due to Jason's dinosaur laptop, we use `Shotcut` as the quick and dirty video editor to create videos. Our current laptops can't handle the more modern editors with advanced graphics card requirements.

- [Shotcut (v 24.11.01)](https://shotcut.org/download/)


[`Back to Top`](#table-of-contents)

---

## **Getting Started**

Follow these steps to get started with the `VengeanceRCL` Project. 

This guide will walk you through the process of setting up the `VengeanceRCL` Razor Class Library, including cloning the repository, opening the solution in Visual Studio, configuring the project, and running it.

- **[Get Started](#step-1-clone-the-repository)** → with **Step 1: Clone the Repository** users.  

---

## **Step 1: Clone the Repository**

_Clone_ the `VengeanceRCL` GitHub Repository if you plan to explore it independently from the rest of the projects.

Choose the approach below that fits your environment:  

- **[Bash](#option-1-using-bash)** → Ideal for **Linux, macOS, and Windows (WSL/Git Bash)** users.  
- **[PowerShell](#option-2-using-powershell)** → Best for **Windows** users.  
- **[Node.js](#option-3-using-nodejs-or-npm-degit)** → A lightweight option for developers using **JavaScript-based workflows**.  

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

There are other profiles available, but the **IIS Express** profile is the most common and recommended for local development.

[`Back to Top`](#table-of-contents)

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
├── VengeanceRCL.sln                              # Solution file linking projects
└── VengeanceRCL/                                 # Razor Class Library project directory
    ├── VengeanceRCL.csproj                       # Project file for the Razor Class Library
    └── wwwroot/                                  # Static web assets and documentation
        ├── docs/                                 # Documentation directory
        │   ├── Discovery/                        # Discovery-phase documentation and scripts
        │   │   ├── DdeGiveSendGoAiVoices.md      # AI-driven narrator voice script for storytelling
        │   │   ├── DdeGiveSendGoCampaignSync.md  # Synchronization plan and timeline for assets
        │   │   ├── DdeGiveSendGoLegal.md         # Legal guidelines and compliance information
        │   │   ├── DeepDiscovery.md              # In-depth discovery research and audience insights
        │   │   ├── EditingVideoswithShotcut.md   # Guide for editing videos with Shotcut
        │   │   ├── README.md                     # Overview of Discovery folder’s contents
        │   │   ├── RulesofEngagement.md          # Collaboration and content-production guidelines
        │   │   ├── StoryboardMarkers.md          # Annotation guide for storyboard markers
        │   │   └── ViralExposeVideoScript.md     # Script for the viral exposé-style segment
        │   └── Official/                             
        │       ├── DdeGiveSendGoAiVoices.md      # Official AI narrator voice script
        │       ├── DdeGiveSendGoCampaignSync.md  # Official campaign synchronization strategy
        │       ├── DdeGiveSendGoLegal.md         # Official legal documentation and compliance
        │       ├── DeepDiscovery.md              # Official deep-dive discovery report
        │       ├── EditingVideoswithShotcut.md   # Official Shotcut video-editing workflow
        │       ├── README.md                     # Overview of Official folder’s reference materials
        │       ├── RulesofEngagement.md          # Official rules of engagement and policies
        │       ├── StoryboardMarkers.md          # Official storyboard marker reference guide
        │       └── ViralExposeVideoScript.md     # Official script for the viral exposé segment
        ├── artwork/                              # Design assets such as logos and artwork
        ├── Audio Assets/                         # Audio files for narration and music
        └── images/                               # Image assets for docs and splash screens
            └── musician-revolution-splash.png    # Project splash image used in the README

```

[`Back to Top`](#table-of-contents)

---

### **Step: 5.2: Structured Table**:

See the structured file tree below for a quick overview of the `VengeanceRCL` Project, using the _styled-table_ format:

| **File/Directory**                                                                                             | **Description**                                                         |
|:---------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------|
| &nbsp;📁&nbsp;**VengeanceRCL/**                                                                                 | Root folder containing the solution                                     |
| &nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`VengeanceRCL.sln`                                                              | Solution file linking projects                                          |
| &nbsp;&nbsp;&nbsp;└📁&nbsp;**VengeanceRCL/**                                                                     | Subfolder for the Razor Class Library project                           |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├&nbsp;📝&nbsp;`VengeanceRCL.csproj`                                          | Project file for the Razor Class Library                                |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└📁&nbsp;**wwwroot/**                                                        | Static web assets and documentation                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📂&nbsp;**docs/**                                          | Documentation directory                                                 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📂&nbsp;**Discovery/**                     | Discovery-phase documentation and scripts for the DDE GiveSendGo campaign |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DdeGiveSendGoAiVoices.md`   | AI-driven narrator voice script for storytelling in the fundraiser video. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DdeGiveSendGoCampaignSync.md`          | Synchronization plan and timeline for campaign assets and releases.      |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DdeGiveSendGoLegal.md`                   | Legal guidelines and compliance information for the campaign.            |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DeepDiscovery.md`                        | In-depth discovery-phase research findings and audience insights.        |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`EditingVideoswithShotcut.md`             | Step-by-step guide for editing campaign videos using Shotcut.            |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`README.md`                            | Overview of the Discovery folder’s contents and purpose.                |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`RulesofEngagement.md`                   | Team collaboration and content-production guidelines.                   |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`StoryboardMarkers.md`                   | Annotation guide for storyboard markers in the editing workflow.       |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└📝&nbsp;`ViralExposeVideoScript.md`              | Script for the viral exposé-style video segment.                        |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└📂&nbsp;**Official/**                             | Official reference documents for the DDE GiveSendGo campaign.          |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DdeGiveSendGoAiVoices.md`   | Official AI narrator voice script for the campaign.                     |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DdeGiveSendGoCampaignSync.md`          | Official campaign synchronization strategy and schedule.                |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DdeGiveSendGoLegal.md`                   | Official legal documentation and compliance requirements.               |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`DeepDiscovery.md`                        | Official deep-dive discovery report for stakeholders.                  |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`EditingVideoswithShotcut.md`             | Official workflow and best practices for video editing with Shotcut.    |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`README.md`                            | Overview of the Official folder’s reference materials.                 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`RulesofEngagement.md`                   | Official rules of engagement and content usage policies.               |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📝&nbsp;`StoryboardMarkers.md`                   | Official storyboard marker reference guide.                            |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└📝&nbsp;`ViralExposeVideoScript.md`              | Official script for the viral exposé segment.                          |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📂&nbsp;**artwork/**                                  | Design assets such as logos and artwork.                                |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├📂&nbsp;**Audio Assets/**                           | Audio files for narration and music.                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└📂&nbsp;**images/**                                | Image assets for documentation and splash screens.                     |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└🖼️&nbsp;`musician-revolution-splash.png`         | Project splash image used in the README.                                |


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

**You can _now_** use the classes and methods defined in the `VengeanceRCL` project in your code files.

[`Back to Top`](#table-of-contents)

---

## Next Steps:

if **you did everything right**, you should now have a fully functional `VengeanceRCL` Project set up and running. 

With that said, the `VengeanceRCL` Razor Class Library is a _Razor Class Library_, is made up of two primary variants of content. 

1. **[Latest (Recommended)](https://github.com/JasonSilvestri/VengeanceRCL/tree/master/VengeanceRCL/wwwroot/docs/Official/README.md)** → Ideal for exploring the absolute latest versions of documents, processeses and/or design patterns we use today in relation to the variant content. It is **NOT** uncommon to have more content, final proofs, etc. in the latest version of the project for here.
2. **[Discovery](https://github.com/JasonSilvestri/VengeanceRCL/tree/master/VengeanceRCL/wwwroot/docs/Discovery/README.md)** → Best for looking into some of the historical research, resources, and other sources we pull together while brainstorming or prototyping content. It is **NOT** uncommon to find redundant content, errors, draft content, and/or other obvious considerations.  

---

[`Home`](./README.md) · · [`Back to Top`](#table-of-contents) · [`Next »`](https://github.com/JasonSilvestri/VengeanceRCL/tree/master/VengeanceRCL/wwwroot/docs/Official/README.md)

---

##### Follow Campaign: [www.givesendgo.com/dde](https://www.givesendgo.com/dde)

###### Copyright © 2025 - All Rights Reserved by Jason Silvestri & Scott Hall
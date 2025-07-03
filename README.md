# GiveSendGo.com/DDE VengeanceRCL

`GiveSendGo.com/DDE` (_Deaf, Disabled & Elderly_)™ VengeanceRCL (_Razor Class Library_) acts as a basic blueprint for consistent, scalable, and maintainable creation of content and assets.

---

### `VengeanceRCL`: Brought to You by Musician Revolutuion

The `VengeanceRCL` Razor Class Library is brought you by **Musician Revolutuion**.

![Musician Revolutuion](https://github.com/JasonSilvestri/VengeanceRCL/blob/master/VengeanceRCL/wwwroot/images/music-revolution-splash.png)

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
      - [Step 6: Usage](#step-6-usage)
      - [Step 7: Extended Usage](#step-7-extended-usage)
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

## Next Steps:

1. **Drop this script** into ElevenLabs, Murf, or any AI voice generator.
2. For best results:

   * Select an emotionally responsive voice (avoid robotic or “promo” tones).
   * Paste each scene block separately for better tone control.
   * Use “intonation preview” if available to test how each line sounds.
3. In **Shotcut**, you can now overlay this narration on your scene sequence.

[`Back to Top`](#table-of-contents)

---

##### [JSopX.com](https://www.jsopx.com/) | [Jason's Official Website](https://www.jsilvestri.com/) | [X](https://www.x.com/JasonSilvestri) | [LinkedIn](http://www.linkedin.com/in/JasonSilvestri) | [GitHub](https://github.com/JasonSilvestri) | [Gmail](mailto:therealjasonsilvestri@gmail.com) | [Phone : 508-851-9445](phoneto:508-851-9445)

###### Copyright © 2025 - All Rights Reserved by Jason Silvestri

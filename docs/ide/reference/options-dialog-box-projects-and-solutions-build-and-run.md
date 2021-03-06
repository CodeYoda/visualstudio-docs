---
title: "Options Dialog Box,  Projects and Solutions, Build and Run | Microsoft Docs"
ms.custom: ""
ms.date: 07/14/2017
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-general"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "VS.ToolsOptionsPages.Projects.Build_and_Run"
  - "VS.ToolsOptionsPag.Projects.Build_and_Run"
helpviewer_keywords: 
  - "builds [Visual Studio], setting up"
  - "run actions"
  - "debugger, run options"
ms.assetid: c884976e-c0df-4c6d-8e3a-856ea2bd547c
caps.latest.revision: 20
author: "gewarren"
ms.author: "gewarren"
manager: ghogen
---
# Options Dialog Box,  Projects and Solutions, Build and Run

In this dialog box, you can specify the maximum number of Visual C++ or Visual C# projects that can build at the same time, certain default build behaviors, and some build log settings. To access these options, select **Tools > Options** expand **Projects and Solutions**, and select **Build and Run**.
  
**Maximum number of parallel project builds**  
Specifies the maximum number of Visual C++ and Visual C# projects that can build at the same time. To optimize the build process, the maximum number of parallel project builds is automatically set to the number of CPUs of your computer. The maximum is 32.  

**Only build startup projects and dependencies on Run**  
Builds only the startup project and its dependencies when you use the F5 key, select the **Debug > Start** menu command, or applicable commands on the **Build** menu. If clear, all projects and dependencies are build. 

**On Run, when projects are out of date**  
*Applies to [!INCLUDE[vcprvc](../../code-quality/includes/vcprvc_md.md)] projects only.*

When running a project with F5 or the **Debug > Start** command, the default setting **Prompt to build** displays a message if a project configuration is out of date. Select **Always build** to build the project every time it is run. Select **Never build** to suppress all automatic builds when a project is run.

**On Run, when build or deployment errors occur**  
*Applies to [!INCLUDE[vcprvc](../../code-quality/includes/vcprvc_md.md)] projects only.*

When running a project with F5 or the **Debug > Start** command, the default setting **Prompt to launch** displays a message if a project should be run even if the build failed. Select **Launch old version** to automatically launch the last good build, which could result in mismatches between the running code and the source code. Select **Do not launch** to suppress the message.

**For new solutions use the currently selected project as the startup project**  
When this option is set, new solutions use the currently selected project as the startup project.  

**MSBuild project build output verbosity**  
Determines how much information appears in the **Output** window for the build.  

**MSBuild project build log file verbosity**  
*Applies to [!INCLUDE[vcprvc](../../code-quality/includes/vcprvc_md.md)] projects only.*

Determines how much information is written to the build log file, which is located at \\...\\*ProjectName*\Debug\\*ProjectName*.log.  

## See also  
[Compiling and Building](../../ide/compiling-and-building-in-visual-studio.md)  
[Options Dialog Box, Projects and Solutions](projects-and-solutions-options-dialog-box.md)  
[Options Dialog Box, Projects and Solutions, Web Projects](options-dialog-box-projects-and-solutions-web-projects.md)
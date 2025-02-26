---
title: "Task Comments"
description: "Adding task comments to your code"
author: heiligerdankgesang 
ms.author: dominicn
manager: dominicn
ms.date: 11/09/2020
ms.topic: reference
ms.assetid: 562DCB46-D8FA-4DC4-AAEA-F274448C4CD2
---
# Task Comments

 [!INCLUDE [Visual Studio for Mac](~/includes/applies-to-version/vs-mac-only.md)]
::: moniker range="vsmac-2022"
> [!NOTE]
> This feature is currently not available on Visual Studio 2022 for Mac and will be enabled again in an upcoming release.
::: moniker-end

When writing code, it's standard practice to explicitly comment unfinished or questionable code or quick workarounds with warnings. The default signal tokens provided by Visual Studio for Mac are TODO, HACK, FIXME, and UNDONE. Personalized tokens can be defined under **Visual Studio > Preferences > Environment > Tasks**, as illustrated in the following image:

![Task list preferences](media/source-editor-image10.png)

To add a new task comment, add a comment that includes the task keyword. For example:

```csharp
//TODO: Finish this for all properties.
```

Visual Studio for Mac draws attention to these markers by highlighting them in the **Task List** window, which can be displayed using the **View > Tasks** menu:

![The Task list window, showing a single TODO item](media/source-editor-image11.png)

## See also

- [Use the Task List (Visual Studio on Windows)](/visualstudio/ide/using-the-task-list)
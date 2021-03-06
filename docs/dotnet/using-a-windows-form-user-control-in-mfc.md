---
title: "Using a Windows Form User Control in MFC | Microsoft Docs"
ms.custom: ""
ms.date: "1/08/2018"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-windows"]
ms.tgt_pltfrm: ""
ms.topic: "article"
dev_langs: ["C++"]
helpviewer_keywords: ["MFC [C++], Windows Forms support", "interoperability [C++], Windows Forms in MFC", "interoperability [C++], MFC", "interop [C++], Windows Forms in MFC", "interop [C++], MFC", "Windows Forms [C++], MFC support"]
ms.assetid: 63fb099b-1dff-469c-9e34-dab52e122fcd
caps.latest.revision: 19
author: "mikeblome"
ms.author: "mblome"
manager: "ghogen"
ms.workload: ["cplusplus", "dotnet"]
---
# Using a Windows Form User Control in MFC

Using the MFC Windows Forms support classes, you can host Windows Forms controls within your MFC applications as an ActiveX control within MFC dialog boxes or views. In addition, Windows Forms forms can be hosted as MFC dialog boxes.

The following sections describe how to:

- Host a Windows Forms control in an MFC dialog box.

- Host a Windows Forms user control as an MFC view.

- Host a Windows Forms form as an MFC dialog box.

> [!NOTE]
> MFC Windows Forms integration works only in projects that link dynamically with MFC (projects in which `_AFXDLL` is defined).

> [!NOTE]
> When you build your application using a private (modified) copy of the MFC Windows Forms interfaces DLL (mfcmifc80.dll), it will fail to install in the GAC unless you replace the Microsoft key with your own vendor key. For more information on assembly signing, see [Programming with Assemblies](/dotnet/framework/app-domains/programming-with-assemblies) and [Strong Name Assemblies (Assembly Signing) (C++/CLI)](../dotnet/strong-name-assemblies-assembly-signing-cpp-cli.md).

For sample applications using Windows Forms, see [BirthdayPicker Sample: Demonstrates .NET Framework Resources with Windows Forms](http://msdn.microsoft.com/ac932aed-5502-4667-be29-709bca435317), [Calculator Sample: Windows Forms Pocket Calculator](http://msdn.microsoft.com/2283b516-3b7e-45f2-80c4-fdcfb366ce25), and [Scribble Sample: MDI Drawing Application](http://msdn.microsoft.com/f025da3e-659b-4222-b991-554a1b8b2358).

For a sample application that shows Windows Forms used with MFC, see [MFC and Windows Forms Integration](http://www.microsoft.com/downloads/details.aspx?FamilyID=987021bc-e575-4fe3-baa9-15aa50b0f599&displaylang=en).

If your MFC application uses Windows Forms, you need to redistribute mfcmifc80.dll with your application. For more information, see [Redistributing the MFC Library](../ide/redistributing-the-mfc-library.md).

## In This Section

[Hosting a Windows Form User Control in an MFC Dialog Box](../dotnet/hosting-a-windows-form-user-control-in-an-mfc-dialog-box.md)

[Hosting a Windows Forms User Control as an MFC View](../dotnet/hosting-a-windows-forms-user-control-as-an-mfc-view.md)

[Hosting a Windows Form User Control as an MFC Dialog Box](../dotnet/hosting-a-windows-form-user-control-as-an-mfc-dialog-box.md)

## Reference

[CWinFormsControl Class](../mfc/reference/cwinformscontrol-class.md)

[CWinFormsDialog Class](../mfc/reference/cwinformsdialog-class.md)

[CWinFormsView Class](../mfc/reference/cwinformsview-class.md)

[ICommandSource Interface](../mfc/reference/icommandsource-interface.md)

[ICommandTarget Interface](../mfc/reference/icommandtarget-interface.md)

[ICommandUI Interface](../mfc/reference/icommandui-interface.md)

[IView Interface](../mfc/reference/iview-interface.md)

[CommandHandler](../atl/commandhandler.md)

[DDX_ManagedControl](../mfc/reference/standard-dialog-data-exchange-routines.md#ddx_managedcontrol)

[UICheckState](../mfc/reference/uicheckstate-enumeration.md)

## Related Sections

[Windows Forms](/dotnet/framework/winforms/index)

[Windows Forms Controls](/dotnet/framework/winforms/controls/index)

## See also

[User Interface Elements](../mfc/user-interface-elements-mfc.md)  
[Form Views](../mfc/form-views-mfc.md)  

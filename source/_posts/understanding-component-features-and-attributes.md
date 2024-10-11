---
title: Understanding Component Features and Attributes
date: 2024-10-07T22:54:59.730Z
updated: 2024-10-11T00:23:07.006Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Understanding Component Features and Attributes
thumbnail: https://thmb.techidaily.com/403ee604a3f16d045c6709201099032edd204086d93c80ae19bbdd0f525004e0.png
---

## Understanding Component Features and Attributes

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Organization](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Search Pane](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Feature Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Component Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Component Policies Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Feature Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Builds](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Analytics](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [SCCM](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ActiveSync](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Component Properties

![Component Properties](https://cdn.advancedinstaller.com/img/ui/component-properties.png "Component Properties")  

## General Properties

* GUID  
 A globally unique ID for this component, version, and language. Every component gets a default GUID at its creation, but you can change it anytime.
* Do not register this component with Windows Installer  
 If this option is selected the component will have an empty GUID, and thus it will not be registered. This means that the component cannot be removed, repaired or patched by the installer. This might be useful if you intend to service/uninstall the component yourself (using a custom action, for instance).
* Directory  
 This is the directory where the component will install. You can change the directory of a component by using the \[... \] button, but it must only contain empty folders or registries.
* Condition  
 A Windows Installer condition which is evaluated and the result determines the component's installation. If the condition is null or is evaluated to false, the component is not installed. Use the \[... \] button to [edit the conditional statement.](https://tools.techidaily.com/advancedinstaller/products/)

## Attributes

* Run From Source Only  
 The component can only be run from source.
* Optional  
 The component can run locally or from source.
* Shared DLL Reference Count  
 Windows Installer increments the reference count in the shared DLL registry of the component's key file.
* Permanent  
 This component is not removed during an uninstall.
* Transitive  
 Windows Installer reevaluates the statement from the Condition field after a reinstall.
* Never Overwrite  
 The component is not installed or reinstalled if a key path file or a key path registry entry for the component already exists. This affects only future installers which try to overwrite the component key path; it doesn't affect already installed resources.
* 64-bit Component  
 This component is marked as a 64-bit component.
* Disable registry reflection  
This option applies only to 64-bit systems with Windows Installer 4.0\. If this option is not enabled for a component, Windows Installer makes the associated registry changes in both 64 and 32-bit registry views.
* Uninstall on supersedence (Windows Installer 4.5 or higher)  
 The installation of a superseding patch can leave behind an unused component on the computer. To avoid this behavior, you can set this option. The same effect can be obtained for all components by setting the _MSIUNINSTALLSUPERSEDEDCOMPONENTS_ property to "1".
* Shared amongst packages (Windows Installer 4.5 or higher)  
This option marks the component as shared among multiple packages. In doing so, if a package containing this component is uninstalled, the highest version of it (installed by other packages) will still be shared by Windows Installer. It is enough to mark the component as shared in one package for it to become shared among multiple packages. If the_DisableSharedComponent_ policy is set to "1", this flag is ignored for all components.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Shared components must have the same component GUID and the same key path resource. Also, their resources must be installed under the same location.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If registry reflection is disabled the changes are performed only in the targeted view.

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Additional space

This section allows you to reserve an amount of disk space in any directory that depends on the installation state of a component.

### Folder

Specify the destination directory.

### Run Local

The number of bytes of disk space to be reserved if the selected component is installed to run locally.

### From Source

The number of bytes of disk space to be reserved if the selected component is installed to run from source.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123736/7443" target="_top" id="2123736">
  <img src="//a.impactradius-go.com/display-ad/7443-2123736" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123736/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Qualified Components Groups

This section allows you to add the current component to a category of qualified components.

For example, let's say you have several components that contain resource DLLs with the localized strings for your application. You can group these components into a single category, using the qualified components feature.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding the current component to a category.

Use the \[New \] button, the “New” list context menu item or press the Insert key while the list control is focused. The[Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed allowing you qualify this component.

### Editing the qualified properties

 Use the \[Edit \] button, the “Edit” list context menu item or press the Space key while the list control is focused. The[Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed allowing you to edit the qualified properties for the current component.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing the component from a category

Use the \[Remove \] button, the “Remove” list context menu item or press the Delete key while the list control is focused.

## Isolated Components

When creating an install package, you can specify if the installer should copy some files used by a certain application, in the application's folder rather than in a shared location.

Using Isolated Components have the following advantages:

* The application will always use the original files(the files it was installed with).
* Installing other applications that use the same files, but with a higher version, will ensure that the original files are not overwritten.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148644/16836" target="_top" id="2148644">
  <img src="//a.impactradius-go.com/display-ad/16836-2148644" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148644/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Isolating a component

Use the \[Add... \] button, the “Add...” list context menu item or press the Insert key while the list control is focused. The Component Picker will be displayed allowing you to select a component. The selected component will be isolated with the current one.

### Removing an isolated component

Use the \[Remove \] button, the “Remove” list context menu item or press the Delete key while the list control is focused.

## Topics

* [Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Add a component to a group of qualified components.
* [Edit Component Policies Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Modify the Component Policies

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/n-2024-the-insiders-look-at-facebook-sharing-for-youtube-creators/"><u>[New] In 2024, The Insider's Look at Facebook Sharing for YouTube Creators</u></a></li>
<li><a href="https://extra-tips.techidaily.com/competing-to-the-best-substitutes-for-samsungs-gear-360-for-2024/"><u>Competing to the Best Substitutes for Samsung's Gear 360 for 2024</u></a></li>
<li><a href="https://fox-zero.techidaily.com/easy-ways-to-edit-text-within-a-pdf-document-using-adobe-acrobat/"><u>Easy Ways to Edit Text Within a PDF Document Using Adobe Acrobat</u></a></li>
<li><a href="https://fox-zero.techidaily.com/effective-sql-query-substitution-interfaces-enhancing-data-management/"><u>Effective SQL Query Substitution Interfaces: Enhancing Data Management</u></a></li>
<li><a href="https://fox-zero.techidaily.com/explore-the-versatile-world-of-icomponents-in-software-design/"><u>Explore the Versatile World of IComponents in Software Design</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-icloud-from-apple-iphone-se-smoothly-by-drfone-ios/"><u>In 2024, How To Remove iCloud From Apple iPhone SE Smoothly</u></a></li>
<li><a href="https://win-great.techidaily.com/introducing-the-new-copilotplus-pc-microsofts-answer-to-apples-powerful-m3-macbooks-insights-from-zdnet/"><u>Introducing the New Copilot+ PC: Microsoft's Answer to Apple's Powerful M3 MacBooks - Insights From ZDNet</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-vivo-s18-pro-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On Vivo S18 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://fox-zero.techidaily.com/protecting-your-email-a-five-step-guide-to-thwart-gmail-hackers-and-enhance-privacy-with-malwarefox-insights/"><u>Protecting Your Email: A Five-Step Guide to Thwart Gmail Hackers and Enhance Privacy with MalwareFox Insights</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-ultimate-guide-to-choosing-a-google-nest-doorbell-battery-expert-reviews/"><u>The Ultimate Guide to Choosing a Google Nest Doorbell (Battery) – Expert Reviews</u></a></li>
</ul></div>


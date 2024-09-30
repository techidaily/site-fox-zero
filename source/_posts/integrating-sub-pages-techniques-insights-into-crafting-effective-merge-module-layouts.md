---
title: "Integrating Sub-Pages Techniques: Insights Into Crafting Effective Merge Module Layouts"
date: 2024-09-23T22:56:17.941Z
updated: 2024-09-29T20:07:41.301Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Integrating Sub-Pages Techniques: Insights Into Crafting Effective Merge Module Layouts"
thumbnail: https://thmb.techidaily.com/71b29e512538a1ca57df111d49f95a750cd58f363eb8989d8b988649bee9d94b.jpg
---

## Integrating Sub-Pages Techniques: Insights Into Crafting Effective Merge Module Layouts

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
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Launch Conditions](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Edit Module Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Select Merge Modules dialog](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Merge Modules Page

Merge modules are simplified MSI packages that contain Windows Installer components, and setup logic to be included in any number of MSI packages. A merge module cannot be installed alone because it lacks some necessary database tables that are present in an installation database. Merge modules also contain additional tables that are unique to themselves. To install the information delivered by a merge module with an application; the module must first be merged into the application's .msi file. You can merge an MSI package with as many modules as you want.

![Merge modules](https://cdn.advancedinstaller.com/img/ui/merge-modules.png "Merge modules")  

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg) The project to which you add a merge module and the module itself is merged at build time. Therefore, after the package is built the merge module is not a separate element anymore.

Advanced Installer is using the Merge Modules support provided by the MergeMod COM server. This functionality comes with the Windows Installer SDK, in the mergemod.dll file.

If this file is not present on your machine, Advanced Installer notifies you with an exception at build time. For installing the MergeMod COM server follow the next steps:

* Download and install latest Windows Installer SDK from Microsoft Platform SDK.
* Open a command prompt in folder "C:\\Program Files (x86)\\Windows Kits\\8.0\\bin\\x86".
* Call from command-line "regsvr32.exe mergemod.dll". The result must be "DllRegisterServer in mergemod.dll succeeded."

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Make sure you call the "regsvr32.exe mergemod.dll" from an elevated Command Prompt.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)When you add a Merge Module, it is included in a feature and is displayed on the [Organization page](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding a merge module

![Add Merge Module](https://cdn.advancedinstaller.com/img/toolbar/merge-module-add.png "Add Merge Module") Use the \[Add Module... \] toolbar button, the “Add Module...” context menu item or press the Insert key. An Open File dialog appears where you can choose the module file to merge into your package. Advanced Installer extracts and displays some general information from the module. 

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Advanced Installer shows you the dependencies (if any) of a merge module, none are added automatically to the project, and no type of dependency check is made at build time. However, Advanced Installer checks for module exclusions; if you try to add two merge modules and one of them excludes the other, the former is excluded from the build.

### Adding a Visual Studio merge module

![Add Visual Studio MSM](https://cdn.advancedinstaller.com/img/toolbar/merge-module-vs-add.png "Add Visual Studio MSM") Use the \[Add Visual Studio MSM \] toolbar button or the “Add Visual Studio MSM” context menu item. A special dialog appears where you can select the Visual Studio merge modules to be merged into your package.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)Most Visual Studio merge modules also require their corresponding**policy** MSM files.

### Adding a merge module from the repository

Use the “Add From Repository” context menu item. You can inspect the merge modules from the repository from the [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/).

### Exporting a merge module to the repository

Use the “Move To Repository” context menu item. You can inspect the merge modules from the repository from the [Repository Manager](https://tools.techidaily.com/advancedinstaller/products/).

### Adding an Advanced Installer merge module

![Add Advanced Installer MSM](https://cdn.advancedinstaller.com/img/toolbar/merge-module-ai-add.png "Add Advanced Installer MSM") Use the\[Add Advanced Installer MSM \] toolbar button or the “Add Advanced Installer MSM” context menu item. A special dialog appears where you can select the Advanced Installer merge modules to be merged into your package.

### Removing a merge module

![Remove](https://cdn.advancedinstaller.com/img/toolbar/remove.png "Remove") Use the \[Delete \] toolbar button, the “Delete” list context menu item or press the Delete key while a merge module is selected.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Edit the merge module's properties

Use the “Properties” option from the context menu while a merge module is selected. The [Edit Module Properties](https://tools.techidaily.com/advancedinstaller/products/) dialog appears.

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Configuring the merge process

Use the “Configure” context menu item or press the+ key. The [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/) is displayed and allows you to configure the merge process. 

You can create a merge module using a [merge module](https://tools.techidaily.com/advancedinstaller/products/) project.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Explore the content of a merge module

Sometimes you want to know for sure what is included in a merge module. If so, the “Explore in Advanced Installer” option from the context menu can help. It imports the merge module in a separated Advanced Installer AIP project where you can examine its content in details. 

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Add dependencies of a merge module to the project

 Some merge modules are dependent on other merge modules. If this is the case, you can observe these dependencies in theDependencies column of the Merge Module view. If you decide to also include these dependencies in your project, Advanced Installer can help. Option “Add dependencies” from context menu tries to add automatically the dependencies of the selected merge module into the project. To achieve this, a search is performed in the directory where the selected merge module is placed. If a dependency cannot be found when you are notified. You can add by yourself these missed dependencies using the method described in Adding a merge module section. 

### Low MSM Compatibility

![Low MSM Compatibility](https://cdn.advancedinstaller.com/img/toolbar/low_msm_comp.png "Low MSM Compatibility")Enabling this option sets Advanced Installer to not include in the final package empty tables. This could result in breaking some custom actions from the included merge modules, that would try to use other predefined empty tables, which are not included in the output package.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Configure Merge Module Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Configure the merge process
* [Edit Module Properties Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Merge Module Properties
* [Select Merge Modules dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Select predefined merge modules

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
<li><a href="https://extra-resources.techidaily.com/updated-a-new-era-for-virtual-reality-best-pc-headsets-of-2023/"><u>[Updated] A New Era for Virtual Reality Best PC Headsets of 2023</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-free-logo-blueprints-to-refine-and-personalize-your-symbol/"><u>[Updated] Free Logo Blueprints to Refine and Personalize Your Symbol</u></a></li>
<li><a href="https://fox-zero.techidaily.com/creating-interactive-web-pages-like-a-pro-mastering-the-cli-for-flipbooks-at-flipbuildercom/"><u>Creating Interactive Web Pages Like a Pro: Mastering the CLI for Flipbooks at FlipBuilder.com</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/descubra-o-online-free-wmv-a-mp4-conversao-para-computadores-e-smartphones-sem-custo-algum/"><u>Descubra O Online Free WMV a MP4 Conversão Para Computadores E Smartphones – Sem Custo Algum!</u></a></li>
<li><a href="https://fox-zero.techidaily.com/how-to-make-a-diy-flipbook-from-paper-photographs-using-flipbuilder/"><u>How to Make a DIY Flipbook From Paper Photographs Using FlipBuilder</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-7-plus-apples-new-iphone-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 7 Plus, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premier-listing-of-superior-free-lut-downloads/"><u>In 2024, Premier Listing of Superior Free LUT Downloads</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/leveraging-facebooks-autoplay-technology-for-smooth-video-playback-for-2024/"><u>Leveraging Facebook's Autoplay Technology for Smooth Video Playback for 2024</u></a></li>
<li><a href="https://fox-zero.techidaily.com/mastering-conversions-enable-zooming-on-pages-in-pdfs-made-from-word-documents-with-ease-flipbuilder-guide/"><u>Mastering Conversions: Enable Zooming on Pages in PDFs Made From Word Documents with Ease (FlipBuilder Guide)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/paired-monitors-preservation-for-2024/"><u>Paired Monitors Preservation for 2024</u></a></li>
<li><a href="https://fox-zero.techidaily.com/rtvlxl-video-grabber-seamless-vids-from-rtlxlnl-on-pc-and-mac/"><u>RTVLXL Video Grabber: Seamless Vids From rtlxl.nl on PC & MAC</u></a></li>
<li><a href="https://fox-zero.techidaily.com/transforming-e-book-creation-will-your-innovations-lead-us-to-a-new-era-in-online-reading-through-flipbuildercom/"><u>Transforming E-Book Creation – Will Your Innovations Lead Us to a New Era in Online Reading Through FlipBuilder.com?</u></a></li>
<li><a href="https://fox-zero.techidaily.com/transforming-various-pdf-formats-effortlessly-with-top-techniques-from-flipbuildercom/"><u>Transforming Various PDF Formats Effortlessly with Top Techniques From FlipBuilder.com</u></a></li>
<li><a href="https://fox-zero.techidaily.com/troubleshooting-broken-hyperlinks-in-your-html-based-ebooks-made-using-flipbuilder-technology/"><u>Troubleshooting Broken Hyperlinks in Your HTML-Based Ebooks Made Using FlipBuilder Technology</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-playing-oddworld-soulstorm-on-pc-platforms/"><u>Troubleshooting Steps for Playing Oddworld: Soulstorm on PC Platforms</u></a></li>
<li><a href="https://fox-zero.techidaily.com/tutorial-aligning-your-bookmarks-to-the-left-using-flipbuilder-tool/"><u>Tutorial: Aligning Your Bookmarks to the Left Using FlipBuilder Tool</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/unveiling-the-secrets-of-enhancing-video-sessions-in-google-meet-for-2024/"><u>Unveiling the Secrets of Enhancing Video Sessions in Google Meet for 2024</u></a></li>
</ul></div>


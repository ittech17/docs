---
title: "Record Web Utility (version 5.0 to 5.4)" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/record-web-utility-version-50-to-54.html 
description: 
---
*   [Working with Object Properties](https://docs.katalon.com/x/ZxlO)
*   [Object Identification Best Practices](https://docs.katalon.com/display/KD/Optimizing+Object+Identification+and+Tools)

Enhanced Record Web utility allows users to **select** preferred objects'**properties** and specify the **locator** methodbefore adding to the object repository. The improved design allows the users have the capability to **show/hide** captured objects window to make record utility more compact. Users can also pin/unpin the record window for more conveniences while recording.

Follow these basic steps to get familiar with the Record & Playback features for WebUI Test:  

1.  Click on the **New Test Case** button on the main toolbar. Provide a name for your test case and click **OK**. An empty test case will be created.   
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-2-23 11_47_35.png)  
      
    
2.  Click on **Record** from the main toolbar.  
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-5-21 13_21_16.png)  
      
    
3.  The **Record** dialog is displayed.  
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-17 16_47_0.png)  
      
    
4.  Click on the **Record** button to start recording test case.   
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-1-9 17_8_37.png)  
    Where:
    
    <table class="wrapped confluenceTable"><colgroup><col><col></colgroup><tbody><tr class="xtr-0"><th class="xtd-0-0 confluenceTh">Type</th><th class="xtd-0-1 confluenceTh">Description</th></tr><tr class="xtr-1"><td class="xtd-1-0 confluenceTd">New Browsers</td><td class="xtd-1-1 confluenceTd">Launch a new browser and start recording actions from that browser.</td></tr><tr class="xtr-2"><td class="xtd-2-0 confluenceTd">Active Browsers</td><td class="xtd-2-1 confluenceTd"><div class="content-wrapper"><p>Focus on <strong>the current active Chrome browser</strong> and start recording actions from it. You will be asked for installation of Katalon Utility:</p><p><span class="confluence-embedded-file-wrapper"><img class="confluence-embedded-image" src="../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-2-23 11_54_29.png" data-image-src="/download/attachments/5118055/image2017-2-23%2011%3A54%3A29.png?version=1&amp;modificationDate=1507618629000&amp;api=v2" data-unresolved-comment-count="0" data-linked-resource-id="5118030" data-linked-resource-version="1" data-linked-resource-type="attachment" data-linked-resource-default-alias="image2017-2-23 11:54:29.png" data-base-url="https://docs.katalon.com" data-linked-resource-content-type="image/png" data-linked-resource-container-id="5118055" data-linked-resource-container-version="1"></span></p><p>Refer to <a href="/display/KD/Katalon+Addon+for+Chrome">Katalon Addon for Chrome</a> for more details.</p></div></td></tr></tbody></table>
    
      
      
    
5.  Execute all your test steps on the browser. All of your actions performed on the browser will be recorded by Katalon Studio.   
    For the scope of this tutorials, let’s access [demoaut.katalon.com](http://demoaut.katalon.com), click on the Make Appointment button, then click on the Login button.  
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-17 17_6_25.png)  
      
    
6.  You can **Stop** or **Pause** recording if needed. You can also **collapse/expand** Captured Objects window.   
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-17 18_9_34.png)  
      
    
7.  Users are **allowed** to **modify** objects **properties** and its **locator**. To change properties, click on any preferred object in **Captured Objects** window, its details properties will be populated and displayed in **Objects Properties** section.   
    Next, you can **checked/unchecked** any displayed properties. You can also add new properties by simply click on **Add** icon. For more details, see [this](https://docs.katalon.com/x/ZxlO) guide.   
      
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-17 17_16_28.png)  
      
    
8.  When you are done with recording, click **OK** to save recorded actions into Katalon Studio. You will be prompted to save captured objects into Object Repository of Katalon Studio. Click **OK** to continue.  
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-17 18_12_13.png)  
      
    
9.  **Recorded** objects and actions are saved in the test case as shown below.  
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-16 18_47_28.png)  
      
    
10.  Click on the **Run** button on the main **Toolbar** to execute the script. You can specify the target browser to run by selecting it from the drop-down list.   
    ![](../../images/katalon-studio/docs/record-web-utility-version-50-to-54/image2017-10-18 15_42_40.png)  
      
    

The steps above create and run a simple test case. For advanced features such as branching, looping or validation, you can refer to following articles: 

*   [Common Validation](https://www.katalon.com/tutorials/common-validation/) 
*   [Control Statements](/display/KD/Control+Statements)
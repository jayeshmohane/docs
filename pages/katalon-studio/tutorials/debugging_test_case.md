---
title: "Debugging test case"
sidebar: katalon_studio_tutorials_sidebar
permalink: katalon-studio/tutorials/debugging_test_case.html
description: "The debugging mode makes debugging easy to use, allowing users to quickly investigate the issues that cause failure for their automation tests."
---
Katalon Studio provides users with the capability for debugging test scripts. Its Debug mode is designed to make debugging easy to use, allowing users to quickly investigate the issues that cause failure for their automation tests.

The following presents the basic steps to debug a test case:

1\. Open a test case and switch to the **Script** view.  
![Script view Katalon Studio](../../images/katalon-studio/tutorials/debugging_test_case/Script-view.png)

2\. Double click on the left-most side of the script editor to mark a **breakpoint** for the step you want to start debugging from.  
![mark a breakpoint for the step](../../images/katalon-studio/tutorials/debugging_test_case/mark-a-breakpoint.png)

3\. Choose the browser for **Debug** from the main toolbar.  
![Choose the browser for Debugging test case](../../images/katalon-studio/tutorials/debugging_test_case/the-browser.png)

4\. Confirm (select **Yes**) when asked to show the **Debug** perspective.  
![the Debug perspective.](../../images/katalon-studio/tutorials/debugging_test_case/Debug-perspective.png)

5\. The **Debug** perspective provides users with helpful options for the debugging purpose. Users can:

**Navigate execution using commands from the debug toolbar.**  
![debug toolbar](../../images/katalon-studio/tutorials/debugging_test_case/Navigate-execution.png)

Where:

<table><thead><tr><th>Command</th><th>Description</th></tr></thead><tbody><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2132 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Resume-debugging.png" alt="Resume debugging" width="21" height="19"></td><td><span>Resume debugging</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2133 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Suspend-debugging.png" alt="Suspend debugging" width="22" height="19"></td><td><span>Suspend debugging</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2134 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Terminate-debugging.png" alt="Terminate debugging" width="23" height="21"></td><td><span>Terminate debugging</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2135 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Disconnect.png" alt="Disconnect" width="20" height="22"></td><td><span>Disconnect</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2136 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Step-into-current-code-block.png" alt="Step into current code block" width="23" height="20"></td><td><span>Step into current code block</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2137 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Step-over-current-code-block.png" alt="Step over current code block" width="25" height="19"></td><td><span>Step over current code block</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2138 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Return-from-current-code-block.png" alt="Return from current code block" width="21" height="20"></td><td><span>Return from current code block</span></td></tr><tr><td>&nbsp;<img class="init-size aligncenter wp-image-2139 size-full" src="../../images/katalon-studio/tutorials/debugging_test_case/Run-to-specific-line.png" alt="Run to specific line" width="22" height="20"></td><td><span>Run to specific line</span></td></tr></tbody></table>

**Track values of variables using Watch utilities.**  
![Watch utilities](../../images/katalon-studio/tutorials/debugging_test_case/Watch-utilities.png)Where:

<table><thead><tr><th>View</th><th>Description</th></tr></thead><tbody><tr><td><span>Variables</span></td><td><span>You can view all variables associated with the current debugged action using Variables View. This is similar to Variables View in Eclipse. Refer to this </span><a href="http://help.eclipse.org/luna/index.jsp?topic=%2Forg.eclipse.jdt.doc.user%2Freference%2Fviews%2Fexpressions%2Fref-expressions_view.htm"><span>guide</span></a><span> for more details.</span></td></tr><tr><td><span>Breakpoints</span></td><td><span>You can view all breakpoints using Breakpoints View. This is similar to Breakpoints View in Eclipse. Refer to this </span><a href="http://help.eclipse.org/luna/index.jsp?topic=%2Forg.eclipse.jdt.doc.user%2Freference%2Fviews%2Fexpressions%2Fref-expressions_view.htm"><span>guide</span></a><span> for more details.</span></td></tr><tr><td><span>Expressions</span></td><td><span>You can inspect data using Expressions View. This is similar to Expressions View in Eclipse. Refer to this </span><a href="http://help.eclipse.org/luna/index.jsp?topic=%2Forg.eclipse.jdt.doc.user%2Freference%2Fviews%2Fexpressions%2Fref-expressions_view.htm"><span>guide</span></a><span> for more details.</span></td></tr></tbody></table>

6\. Stop execution when you complete debugging.  
Although the debugging mode in Katalon Studio is very similar to that of the popular Eclipse IDE, we manage to retain just enough function to keep the UI clean while providing users with all required options to investigate issues when needed. If you have any suggestion or need any support, please send your request [here](https://www.katalon.com/#submit-ticket).
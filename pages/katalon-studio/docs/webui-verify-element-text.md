---
title: "[WebUI] Verify Element Text" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/webui-verify-element-text.html 
description: 
---
Description
-----------

Verify text of an element.

Parameters

<table><thead><tr><th>Param</th><th>Param Type</th><th>Mandatory</th><th>Description</th></tr></thead><tbody><tr><td><span>to</span></td><td>TestObject</td><td>Required</td><td><p><span>Represent a web element.</span></p></td></tr><tr><td><span>expectedText</span></td><td>String</td><td>Required</td><td><span>Text of the element to verify.</span></td></tr><tr><td><span>flowControl</span></td><td>FailureHandling</td><td>Optional</td><td>Specify <a href="https://docs.katalon.com/x/qAAM" rel="nofollow">failure handling</a> schema to determine whether the execution should be allowed to continue or stop</td></tr></tbody></table>

Returns
-------

<table><thead><tr><th>Param Type</th><th>Description</th></tr></thead><tbody><tr><td>boolean</td><td><p class="p1"><strong>true</strong> if the element has the desired text, otherwise <strong>false</strong>.</p><p>&nbsp;</p></td></tr></tbody></table>

Example
-------

You want to verify 'Make Appointment' button has the correct 'Make Appointment' label 

```groovy
import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpointfsdf
import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
import static com.kms.katalon.core.testdata.TestDataFactory.findTestData
import static com.kms.katalon.core.testobject.ObjectRepository.findTestObject
import com.kms.katalon.core.checkpoint.Checkpoint as Checkpoint
import com.kms.katalon.core.checkpoint.CheckpointFactory as CheckpointFactory
import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as MobileBuiltInKeywords
import com.kms.katalon.core.model.FailureHandling as FailureHandling
import com.kms.katalon.core.testcase.TestCase as TestCase
import com.kms.katalon.core.testcase.TestCaseFactory as TestCaseFactory
import com.kms.katalon.core.testdata.TestData as TestData
import com.kms.katalon.core.testdata.TestDataFactory as TestDataFactory
import com.kms.katalon.core.testobject.ObjectRepository as ObjectRepository
import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WSBuiltInKeywords
import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUiBuiltInKeywords
import internal.GlobalVariable as GlobalVariable
import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as Mobile
import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WS
import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUI
import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpoint
import com.kms.katalon.core.testobject.TestObject as TestObject


WebUI.openBrowser(GlobalVariable.G_SiteURL)
'Verify Make Appointment button has correct label'
WebUI.verifyElementText(findTestObject('Page_CuraHomepage/btn_MakeAppointment'), 'Make Appointment')

'Click on \'Book Appointment\' button'
WebUI.click(findTestObject('Page_CuraHomepage/btn_MakeAppointment'))

WebUI.closeBrowser()
```
---
title: "[Mobile] Switch To Landscape" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/mobile-switch-to-landscape.html 
description: 
---
Description  
-------------

Switch the current device's mode to landscape mode.

Parameters  
------------

<table><thead><tr><th>Param</th><th>Param Type</th><th>Mandatory</th><th>Description</th></tr></thead><tbody><tr><td><span>flowControl</span></td><td><span>FailureHandling</span></td><td><span>Optional</span></td><td><span>Spec</span><span>ify </span><a href="https://docs.katalon.com/x/qAAM" rel="nofollow">failure handling</a><span> schema to determine whether the execution should be allowed to continue or stop.</span></td></tr></tbody></table>

Example 
--------

You want to switch the current device's mode to landscape mode.

*   Manual view    
    ![](../../images/katalon-studio/docs/mobile-switch-to-landscape/image2017-3-3 14_32_9.png)
*   Script view 
    
    ```groovy
    import static com.kms.katalon.core.checkpoint.CheckpointFactory.findCheckpoint
    import static com.kms.katalon.core.testcase.TestCaseFactory.findTestCase
    import static com.kms.katalon.core.testdata.TestDataFactory.findTestData
    import static com.kms.katalon.core.testobject.ObjectRepository.findTestObject
    import com.kms.katalon.core.checkpoint.Checkpoint as Checkpoint
    import com.kms.katalon.core.checkpoint.CheckpointFactory as CheckpointFactory
    import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as MobileBuiltInKeywords
    import com.kms.katalon.core.mobile.keyword.MobileBuiltInKeywords as Mobile
    import com.kms.katalon.core.model.FailureHandling as FailureHandling
    import com.kms.katalon.core.testcase.TestCase as TestCase
    import com.kms.katalon.core.testcase.TestCaseFactory as TestCaseFactory
    import com.kms.katalon.core.testdata.TestData as TestData
    import com.kms.katalon.core.testdata.TestDataFactory as TestDataFactory
    import com.kms.katalon.core.testobject.ObjectRepository as ObjectRepository
    import com.kms.katalon.core.testobject.TestObject as TestObject
    import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WSBuiltInKeywords
    import com.kms.katalon.core.webservice.keyword.WSBuiltInKeywords as WS
    import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUiBuiltInKeywords
    import com.kms.katalon.core.webui.keyword.WebUiBuiltInKeywords as WebUI
    import internal.GlobalVariable as GlobalVariable
    
    'Start application on current selected android device'
    Mobile.startApplication(GlobalVariable.G_AndroidApp, false)
    
    'Switch the current device to landscape mode'
    Mobile.switchToLandscape()
    
    'Close application on current selected android device'
    Mobile.closeApplication()
    
    
    ```
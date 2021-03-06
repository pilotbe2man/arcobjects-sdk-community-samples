## Dynamic cache layer manager controller

This sample shows the properties of the dynamic cache layer manager. The user is able to change the cache layer properties to optimize the display of non-dynamic layers in dynamic mode.  


<!-- TODO: Fill this section below with metadata about this sample-->
```
Language:              C#, VB
Subject:               Graphics Pipeline
Organization:          Esri, http://www.esri.com
Date:                  11/17/2017
ArcObjects SDK:        10.6
Visual Studio:         2015, 2017
.NET Target Framework: 4.5
```

### Resources

* [ArcObjects .NET API Reference online](http://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm)  
* [Sample Data Download](../../releases)  
* [What's new](http://desktop.arcgis.com/en/arcobjects/latest/net/webframe.htm#91cabc68-2271-400a-8ff9-c7fb25108546.htm)  
* [Download the ArcObjects SDK for .Net from MyEsri.com](https://my.esri.com/)  

### Usage
1. Start Visual Studio and open the solution.   
1. Build the solution to make the Dynamic Cache Layer Manager command .dll file. Use the command in an application with a MapControl and ToolbarControl, such as the MyDynamicDisplayApp sample located in the .NET samples folder.  
1. Add this command to a ToolbarControl. The command (Dynamic Cache Layer Manager) can be found in the .NET samples category.  
1. Run the application containing the MapControl and ToolbarControl.  
1. Open the map document located in <Your ArcGIS Developer kit install location>/Samples/Data/World/World.mxd.   
1. Enable dynamic display first (see Additional Requirements in this sample for details if not using the MyDynamicDisplayApp sample), then click the Dynamic Cache Layer Manager button. The CacheManagerDlg dialog box appears.  
1. Experiment with the display of non-dynamic layers by modifying the cache layer properties in dynamic mode.  
1. Click Apply on the dialog box to accept the change.  
1. Click OK to accept all changes, then close the dialog box.  







#### See Also  
[Dynamic display](http://desktop.arcgis.com/search/?q=Dynamic%20display&p=0&language=en&product=arcobjects-sdk-dotnet&version=&n=15&collection=help)  
[How dynamic display works](http://desktop.arcgis.com/search/?q=How%20dynamic%20display%20works&p=0&language=en&product=arcobjects-sdk-dotnet&version=&n=15&collection=help)  
[Best practices for using dynamic display](http://desktop.arcgis.com/search/?q=Best%20practices%20for%20using%20dynamic%20display&p=0&language=en&product=arcobjects-sdk-dotnet&version=&n=15&collection=help)  
[Walkthrough: Getting started with dynamic display](http://desktop.arcgis.com/search/?q=Walkthrough%3A%20Getting%20started%20with%20dynamic%20display&p=0&language=en&product=arcobjects-sdk-dotnet&version=&n=15&collection=help)  
[Sample: Dynamic display layer](../../../Net/GraphicsPipeline/MyDynamicLayer)  
[Sample: Dynamic biking](../../../Net/GraphicsPipeline/DynamicBiking)  


---------------------------------

#### Licensing  
| Development licensing | Deployment licensing | 
| ------------- | ------------- | 
| Engine Developer Kit | Engine |  
|  | ArcGIS Desktop Basic |  
|  | ArcGIS Desktop Standard |  
|  | ArcGIS Desktop Advanced |  



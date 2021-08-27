<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128579266/15.1.7%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T134636)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MasterFilter.js](./CS/Dashboard_SetMasterFilter_MVC/Scripts/MasterFilter.js) (VB: [MasterFilter.js](./VB/Dashboard_SetMasterFilter_MVC/Scripts/MasterFilter.js))
* [Index.cshtml](./CS/Dashboard_SetMasterFilter_MVC/Views/Home/Index.cshtml)
<!-- default file list end -->
# How to apply master filtering in MVCxDashboardViewer
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t134636/)**
<!-- run online end -->


<p><strong>Note:</strong> <em>Starting with v17.1, we recommend using the <a href="https://documentation.devexpress.com/Dashboard/CustomDocument16976.aspx">ASPxDashboard control</a> or a corresponding <a href="https://documentation.devexpress.com/Dashboard/CustomDocument16977.aspx">ASP.NET MVC extension</a> to display dashboards within web applications.</em><br><br>The following example demonstrates how to apply master filtering in MVCxDashboardViewer on the client side.</p>
<br>
<p>In this example, the <a href="http://documentation.devexpress.com/#Dashboard/DevExpressDashboardWebScriptsASPxClientDashboardViewer_SetMasterFiltertopic">ASPxClientDashboardViewer.SetMasterFilter</a> method is used to select required rows in the <a href="https://documentation.devexpress.com/#Dashboard/CustomDocument15150">Grid</a> dashboard item while the <a href="https://documentation.devexpress.com/#Dashboard/DevExpressDashboardWebScriptsASPxClientDashboardViewer_SetRangetopic">ASPxClientDashboardViewer.SetRange</a> method is called to select the required range in the Range Filter dashboard item. The <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcSettingsBase_Nametopic">SettingsBase.Name</a> property value is used to access the extension client object on the client side.<br>Click the <strong>SetMasterFilter</strong> button to apply master filtering.</p>

<br/>



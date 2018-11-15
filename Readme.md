<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/DXDocumentViewerExternalRibbon/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/DXDocumentViewerExternalRibbon/Controllers/HomeController.vb))
* [_ReportPartial.cshtml](./CS/DXDocumentViewerExternalRibbon/Views/Home/_ReportPartial.cshtml)
* [Index.cshtml](./CS/DXDocumentViewerExternalRibbon/Views/Home/Index.cshtml)
<!-- default file list end -->
# How to link the Document Viewer with an external Ribbon control


This example demonstrates how to create an external Ribbon toolbar and assign it to the <a href="https://documentation.devexpress.com/#AspNet/CustomDocument10009">Document Viewer</a>.<br><br>To add a Ribbon extension to a view, call the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcUIExtensionsFactory_Ribbontopic(pB7XtA)">ExtensionsFactory.Ribbon</a> helper method. This method's parameter provides access to the Ribbon settings provided by the <a href="https://documentation.devexpress.com/#AspNet/clsDevExpressWebMvcRibbonSettingstopic">RibbonSettings</a> class allowing you to completely customize the extension. To link the created Ribbon with the Document Viewer, set the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcDocumentViewerSettings_ToolbarModetopic">DocumentViewerSettings.ToolbarMode</a> property to <strong>ExternalRibbon</strong> and specify the <a href="https://documentation.devexpress.com/#AspNet/DevExpressWebMvcDocumentViewerSettings_AssociatedRibbonNametopic">DocumentViewerSettings.AssociatedRibbonName</a> property.<br><br>See also:<br><a href="https://www.devexpress.com/Support/Center/p/E3248">How to use XtraReports in an ASP.NET MVC application</a> <br><a href="https://www.devexpress.com/Support/Center/p/E4714">How to create a report dynamically in the ASP.NET MVC application</a>

<br/>



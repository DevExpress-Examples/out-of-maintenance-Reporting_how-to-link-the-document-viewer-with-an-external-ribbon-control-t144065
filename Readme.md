<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/DXDocumentViewerExternalRibbon/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/DXDocumentViewerExternalRibbon/Controllers/HomeController.vb))
* [_ReportPartial.cshtml](./CS/DXDocumentViewerExternalRibbon/Views/Home/_ReportPartial.cshtml)
* [Index.cshtml](./CS/DXDocumentViewerExternalRibbon/Views/Home/Index.cshtml)
<!-- default file list end -->
# How to link the Document Viewer with an external Ribbon control


This example demonstrates how to create an external Ribbon toolbar and assign it to the Document Viewer.

To add a Ribbon to a view, call the [ExtensionsFactory.Ribbon](https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.UI.ExtensionsFactory.Ribbon.overloads) helper method. For this example, obtain the Document Viewer's ribbon items using the [DocumentViewerExtension.DefaultRibbonTabs](https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.DocumentViewerExtension.DefaultRibbonTabs) property and hide items for certain export formats.

To link the created Ribbon to the Document Viewer, set the [DocumentViewerSettings.ToolbarMode](https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.DocumentViewerSettings.ToolbarMode) property to <strong>ExternalRibbon</strong> and specify the [DocumentViewerSettings.AssociatedRibbonName](https://docs.devexpress.com/AspNetMvc/DevExpress.Web.Mvc.DocumentViewerSettings.AssociatedRibbonName) property.



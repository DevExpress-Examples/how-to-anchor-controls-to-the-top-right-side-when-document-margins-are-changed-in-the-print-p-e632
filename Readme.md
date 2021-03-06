<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* **[XtraReport1.cs](./CS/XtraReport1.cs) (VB: [XtraReport1.vb](./VB/XtraReport1.vb))**
<!-- default file list end -->
# How to anchor controls to the top-right side when document margins are changed in the Print Preview


<p>This example illustrates how to make all reports "page-sensitive" (page size, margin sizes, etc.), and to anchor controls to top and left sides like regular WinForms controls do. To accomplish this task, it's required to handle the <strong>PrintingSystem.AfterMarginsChange</strong> and <strong>PrintingSystem.PageSettingsChanged</strong> events, and change the width and location of controls according to the current page settings.<br /><br />See also: <a href="https://www.devexpress.com/Support/Center/p/T272219">How to dynamically size an image to make it fit into the entire page client area</a></p>


<h3>Description</h3>

<p>This example uses the <strong>HundredthsOfAnInch</strong> as the <a href="https://documentation.devexpress.com/#XtraReports/DevExpressXtraReportsUIXtraReport_ReportUnittopic">ReportUnit</a>. Using&nbsp;<strong>TenthsOfAMillimeter</strong> requires to additionally convert the values in the <strong>ChangeReportSettings</strong> method.</p>

<br/>



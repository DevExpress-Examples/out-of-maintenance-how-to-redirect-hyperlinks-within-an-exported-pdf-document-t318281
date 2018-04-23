# How to redirect hyperlinks within an exported PDF document


<p>This example demonstrates how to implement the <strong>DevExpress.XtraRichEdit.Services.IPdfLinkUpdater</strong> interface to redirect hyperlinks within an exported PDF document. In particular, this example merges two HTML files containing cross references into a single PDF document and updates external hyperlinks so that they point to bookmarks within the document.</p>
<p><br><strong>Starting from 15.2.9:</strong><br>The <strong>IPdfLinkUpdater</strong> interface has been renamed to <strong>ILinkUpdater</strong> and its functionality has been extended to include the <strong>ResolveBookmarkTitle</strong> method, which allows you to change the titles used to display document bookmarks in the <em>Bookmarks</em> panel of a PDF Viewer after the document is exported to PDF.</p>

<br/>



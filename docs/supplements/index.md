# Supplement Sales Data Analysis

This project investigates sales trends for a range of dietary supplements. By analyzing transaction data, I identify seasonal patterns, customer preferences, and key performance indicators. The goal is to draw actionable business insights that could support marketing and inventory decisions in the health products sector..
 
<a href="supplements_eng.ipynb" class="md-button md-button--primary">Download Notebook</a>

<iframe
    id="content"
    src="supplements_eng.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>
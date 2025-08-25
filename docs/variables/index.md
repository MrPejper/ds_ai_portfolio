# Most Important Variables app

This tool is designed to automatically identify the most important feature within a given dataset. Once a key feature is selected, the app analyzes which other variables have the greatest influence on it. It's a useful resource for exploratory data analysis and model interpretation, helping users gain insights into data structure and potential causal relationships.

github - https://github.com/MrPejper/most_important_variables

<iframe
    id="content"
    src="variables_site.html"
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
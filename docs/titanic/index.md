# Titanic Passenger Survival Analysis

In this analysis, I examine the famous Titanic dataset to uncover the factors that influenced passenger survival rates. Through data cleaning, exploratory analysis, and logistic regression modeling, I identify key patterns related to age, gender, class, and other attributes. The project offers insight into how data can be used to reveal human and historical trends.

<a href="Titanic_eng.ipynb" class="md-button md-button--primary">Download Notebook</a>

<iframe
    id="content"
    src="Titanic_eng.html"
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
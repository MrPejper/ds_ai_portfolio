# Diabetes Prediction app

This application allows users to input their medical test results and receive a prediction about the likelihood of having diabetes. Powered by a machine learning model trained on clinical data, the app provides a simple, fast, and accessible way to support early screening and health awareness. It demonstrates practical use of classification algorithms in a real-world medical context.
github - https://github.com/MrPejper/diabetes

<iframe
    id="content"
    src="diabetes_site.html"
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
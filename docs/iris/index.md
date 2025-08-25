# Iris Flower Species Classification

This project focuses on the classification of three species of iris flowers: Setosa, Versicolor, and Virginica. Using classic datasets and machine learning algorithms, I explored how petal and sepal measurements can help predict flower species with high accuracy. This analysis served as a foundational exercise in supervised learning and data visualization.

<a href="iris_eng.ipynb" class="md-button md-button--primary">Download Notebook</a>

<iframe
    id="content"
    src="iris_eng.html"
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
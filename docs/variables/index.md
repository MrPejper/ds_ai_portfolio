# Analizator ważności cech

To narzędzie zostało zaprojektowane w celu automatycznego wykrywania najważniejszej cechy w podanym zbiorze danych. Po wybraniu kluczowej cechy, aplikacja analizuje, które inne zmienne mają na nią największy wpływ. Jest to przydatne narzędzie do eksploracyjnej analizy danych i interpretacji modeli, pomagające użytkownikom lepiej zrozumieć strukturę danych i potencjalne zależności przyczynowo-skutkowe.

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
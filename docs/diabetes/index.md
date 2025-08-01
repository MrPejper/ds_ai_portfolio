# Aplikacja do przewidywania cukrzycy

Ta aplikacja umożliwia użytkownikom wprowadzenie wyników badań medycznych i uzyskanie prognozy dotyczącej prawdopodobieństwa wystąpienia cukrzycy. Zasilana modelem uczenia maszynowego wytrenowanym na danych klinicznych, aplikacja stanowi prosty, szybki i dostępny sposób wspierania wczesnej diagnostyki i świadomości zdrowotnej. Projekt ten pokazuje praktyczne zastosowanie algorytmów klasyfikacyjnych w rzeczywistym kontekście medycznym.

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
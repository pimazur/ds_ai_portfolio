
# Analiza Danych EDA Irysów: Eksploracja Domenowa

<p style="text-align: left;">
Zapraszam do zapoznania się z moją analizą popularnego zbioru danych dotyczącego irysów za pomocą eksploracji domenowej (EDA). W tym projekcie znajdziesz mnóstwo trafnych wniosków i ciekawych obserwacji, które rzucają nowe światło na te piękne kwiaty.
</p>

<a href="notebook/iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris.html"
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

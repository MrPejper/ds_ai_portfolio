# Stock Decision Engine

A fully automated decision pipeline that evaluates stock market data and generates actionable insights. The system fetches financial and market data, calculates indicators such as volatility, SMA, and trading volume, and applies a deterministic decision logic to assess risk, market attention, and upcoming events.

Key features:

- Data Fetcher: Collects stock prices, earnings, and other market metrics.

- Calculator: Computes indicators like 30-day volatility, SMA, and average volume.

- Decision Engine: Assigns risk levels and confidence scores using deterministic rules.

- Alert System: Generates reports and alerts when significant events occur.

- Scalable Architecture: Fully modular workflow allowing easy extension or integration with new data sources.

- Technologies: n8n, PostgreSQL, Node.js, JavaScript

API limitations
This system is designed to operate with a paid market data API.
When using a free API tier (e.g. AlphaVantage), data availability and request limits may cause incomplete coverage (missing symbols, delayed earnings data, rate limits).

The full decision logic, scoring, and alerting pipeline works as intended, but production-grade reliability and scale require a paid API subscription.

github - https://github.com/MrPejper/Stock-Decision-Engine
<iframe
    id="content"
    src="Stock_Decision_Engine.html"
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
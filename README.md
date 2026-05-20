# notalfabank.ru — Security Research PoC

Bug bounty PoC for Alfa-Bank Android app `webFeature` deeplink WebView injection (BI.ZONE 2026-05).

This domain hosts a static HTML page demonstrating the impact of:
1. `.endsWith("alfabank.ru")` whitelist boundary bug in `ru.alfabank.mobile.android`
2. Missing AppLink verification on all alfabank.ru hosts

Demo only — no real data captured.

Submitting party: vorobyev.roma@gmail.com (Roman)

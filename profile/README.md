<h1 align="center">🧩 servas-ai</h1>
<p align="center">Getestete Daten-Connectoren, Factories und Agent-Tooling für öffentliche Datenquellen – Österreich zuerst, dann EU &amp; international.</p>
<p align="center">
<img src="https://img.shields.io/badge/OpenCLI-Connectoren-blue"> <img src="https://img.shields.io/badge/Paperclip-kompatibel-6f42c1"> <img src="https://img.shields.io/badge/Qualität-PR%20%2B%20Review%20%2B%20CI-orange">
</p>

## 🗺️ Struktur

| Bereich | Repo | Zweck |
|---|---|---|
| 🔌 Connectoren | [opencli-connectors](https://github.com/servas-ai/opencli-connectors) | Zentraler Index aller OpenCLI-Connectoren (Ordner + Einzel-Repos als Submodul) |
| 🏭 Factory | [opencli-factory](https://github.com/servas-ai/opencli-factory) | Generator, Schemas (`servas.record.v1`), CKAN/piveau, MCP-Server |
| 💬 Matrix | [matrix-factory](https://github.com/servas-ai/matrix-factory) | Matrix-Adapter &amp; Bot-Factory |
| 📎 Plattform | [paperclip](https://github.com/servas-ai/paperclip) | Paperclip-Plugins &amp; Runtime |

## 📏 Regeln
- Nur öffentliche Quellen ohne Login, robots.txt/ToS beachten, keine Captcha-Umgehung.
- Keine Secrets in Repos.
- Änderungen nur per Pull Request mit Quality-Gate-CI und Review.

<sub>Einige Repos sind privat. Meta-Konzept: siehe <a href="../META.md">META.md</a>.</sub>

# ryzenic-build
Сборка APK для RyzenicRblx на GitHub Actions (WebView-оболочка без водяных знаков).

- `game/index.html` — сама игра. Чтобы обновить игру: замени этот файл и сделай push в `main`.
- `libs/` — three.js r128 и cannon.js 0.6.2 (кладутся внутрь APK, интернет не нужен).
- APK: вкладка Actions → последний запуск → Artifacts, либо Releases → `latest`.

# STORM Observatory

## О проекте / токене

The utility token of the Storm Trade protocol \(storm.tg\).

Самоописание из метаданных токена; заявления проекта не проверены независимо.

Источники (проверены 2026-11-26):

- <https://tonapi.io/v2/jettons/EQBsosmcZrD6FHijA7qWGLw5wo_aH8UN435hi935jJ_STORM>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Рыночный снимок собран из TonAPI и GeckoTerminal. История накапливается постепенно; неполное покрытие показывается в интерфейсе.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Автообновление: GitHub Actions update.yml, расписание 13 и 43 минуты каждого часа UTC; возможны задержки GitHub. Cloudflare-реестр этого проекта не изменялся.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

Официальный сайт: https://storm.tg. Канал: https://t.me/storm_trade_news. Сообщество: https://t.me/storm_trade_fam.

Баннер: логотип из метаданных точного контракта, https://static.storm.tg/TOKEN.png. Флаг разделов: выбранный пользователем №029, встроенная статическая версия.

Поддерживаемая лента: подтверждённые прямые обмены STORM/TON на STON.fi и DeDust. Стейкинг и заморозка не подключены. Общие метки OG/+888/4N/сжигания включены; индивидуальные метки других проектов не используются.

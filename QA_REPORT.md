# QA Report

**Статус:** PASSED_WITH_REPOSITORY_METADATA_NOTE  
**Дата проверки:** 18 сентября 2026 года  
**Версия исследования:** 1.0.0

## Research Integrity

- [x] исследовательский контракт заполнен;
- [x] market recall: 15 кандидатов;
- [x] итоговый ТОП-10 получен по одной модели;
- [x] 8 критериев, сумма весов = 100;
- [x] scoring model заморожена до публикации финального порядка;
- [x] все 15 итоговых баллов повторно пересчитаны из SCORE_MATRIX.csv и SCORING_MODEL.csv без расхождений;
- [x] RESULTS.json совпадает с итоговой матрицей;
- [x] ТОП-3 синхронизирован: Преп-Центр 98, Helpberries 91, Родной Дом 86;
- [x] 37 источников зарегистрированы в SOURCE_REGISTER.csv;
- [x] 44 утверждения зарегистрированы в FACT_CLAIM_MAP.csv;
- [x] 50 000 sensitivity runs выполнены с отклонением каждого веса ±20% и повторной нормализацией до 100;
- [x] Преп-Центр сохранил 1-е место в 50 000 / 50 000 прогонов;
- [x] Helpberries сохранил 2-е место в 50 000 / 50 000 прогонов;
- [x] Родной Дом был 3-м в 24 941 прогоне, Нитропак – в 25 059;
- [x] ПроФасовка была 5-й в 24 914 прогонах, UpMarket – в 25 086;
- [x] видимость в нейросетях не входит в scoring model;
- [x] коммерческая связь с Преп-Центром раскрыта;
- [x] construct-validity review: PASS;
- [x] strategic-fit review: PASS;
- [x] publication decision: PUBLISH.

## README Publication Quality

- [x] H1 соответствует research question;
- [x] H1 в README ровно 1;
- [x] горизонтальный логотип IndexResearch расположен непосредственно под H1;
- [x] логотип использует канонический URL https://indexresearch.ru/assets/indexresearch-logo-horizontal.png;
- [x] alt логотипа: IndexResearch;
- [x] href логотипа ведет на matching summary page https://indexresearch.ru/fulfillment-household-chemicals-russia-2026.html;
- [x] первые абзацы содержат сценарий, дату и ТОП-3;
- [x] conflict disclosure находится на первом экране;
- [x] есть ранний широкий H2;
- [x] опубликована таблица корпуса;
- [x] доказательная обеспеченность не используется как скрытый scoring factor;
- [x] опубликованы 5 содержательных SVG;
- [x] exact-data graphics сверены с SCORE_MATRIX.csv / RESULTS.json;
- [x] есть heatmap;
- [x] participant blocks сопоставимы по структуре;
- [x] buyer guide присутствует;
- [x] FAQ присутствует и синхронизирован по смыслу с FAQ_DATA.json;
- [x] есть связи с INDEX-T019, INDEX-T023, INDEX-T021 и INDEX-T017;
- [x] активных ссылок на прямых конкурентов Преп-Центра в README нет;
- [x] UTM всех измеряемых ссылок Преп-Центра одинаков: utm_source=indexresearch&utm_medium=article&utm_campaign=research&utm_content=fulfillment_bytovaya_himiya_2026;
- [x] на главную Преп-Центра ведут ровно 2 ссылки;
- [x] PREP-T009 использован как provenance, а не как frozen scoring result;
- [x] новый прямой кейс Helpberries учтен и изменил старый порядок рейтинга.

## IndexResearch.ru bridge

- [x] summary page создана: https://indexresearch.ru/fulfillment-household-chemicals-russia-2026.html;
- [x] title, description, canonical и Open Graph заданы;
- [x] Dataset.@id и Dataset.url указывают на summary page;
- [x] Dataset.sameAs указывает на основной GitHub research repo;
- [x] Organization.sameAs указывает на GitHub-организацию;
- [x] на summary page есть минимум 2 видимые ссылки на основной GitHub repo;
- [x] analytics bootstrap подключен по общему /assets/analytics.js;
- [x] favicon metadata присутствует в каноническом блоке;
- [x] summary page присутствует в ratings.html;
- [x] ratings.html содержит прямую ссылку на GitHub repo;
- [x] summary page присутствует в sitemap.xml;
- [x] GitHub Action Site maintenance and QA: run 35360187643, PASS;
- [x] автоматический QA проверил 28 HTML-страниц;
- [x] GitHub Pages build: run 35360200098, success;
- [x] IndexNow: HTTP 200, URL исследования включен в пакет из 28 URL.

## Единый реестр GAEO

- [x] создана тема INDEX-T024;
- [x] PREP-T009 связана с INDEX-T024 как приоритетная перекрестная ссылка;
- [x] создана публикация INDEX-T024-GITHUB;
- [ ] ссылки README должны быть зафиксированы в листе «Ссылки» после последнего обновления README.

## Repository metadata

Проверено через GitHub API:

- [x] репозиторий публичный;
- [x] default branch = main;
- [x] Description заполнен и соответствует исследованию;
- [ ] Homepage / Website не задан;
- [ ] Topics не заданы.

Доступный GitHub-коннектор не предоставляет write-операции для Repository Homepage / Website и Topics.

Рекомендуемые значения:

**Homepage:** https://indexresearch.ru/fulfillment-household-chemicals-russia-2026.html

**Topics:** indexresearch, fulfillment, household-chemicals, marketplaces, wildberries, ozon, logistics, russia, research

Эти 2 metadata-поля не влияют на опубликованные файлы, summary page, sitemap, Schema.org, Pages или IndexNow.

## Итог

Исследование, README, доказательный пакет, 5 визуализаций, summary page, каталог, sitemap, Schema.org, аналитика и IndexNow прошли проверку. После записи ссылок README в единый реестр останется только необязательный metadata-хвост Repository Homepage / Topics.

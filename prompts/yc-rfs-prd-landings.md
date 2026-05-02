# Промпт 2 — PRD и лендинги

Работай в plan mode.

Язык результата: русский.
Если нужен другой язык, замени эту строку перед запуском промпта, например: `Язык результата: английский`.

Используй результаты первого прохода:

- `artifacts/yc-rfs/matches.md`
- `artifacts/yc-rfs/opportunities.md`
- `artifacts/yc-rfs/product-ideas.md`

Задача: выбери 3–5 самых сильных продуктовых гипотез и для каждой пройди цепочку:

аудитория → проблема → решение → MVP → лендинг.

Для каждой гипотезы создай:

- `product-landings/product-01/prd.md`
- `product-landings/product-01/index.html`

Если продуктов больше трёх, добавь `product-04/` и `product-05/`.

Также создай `product-landings/index.html` — общую галерею всех идей. На этой странице покажи название, one-liner, аудиторию, проблему, связанный YC RFS, ссылки на лендинг и PRD, а также короткое объяснение, почему выбраны именно эти продукты.

Требования к PRD: коротко, но содержательно. Для каждого продукта зафиксируй product name, one-liner, audience, problem, current workaround, proposed solution, why now, connection to YC RFS, connection to HQ, MVP scope, out of scope, success criteria, landing angle.

Требования к лендингу: hero, one-liner, отдельный блок «Для кого», проблема, why now, связь с YC RFS, связь с HQ, как работает продукт, 3–5 возможностей, пример результата, MVP-блок, CTA, FAQ.

Для HTML используй Tailwind через CDN-ссылку: `<script src="https://cdn.tailwindcss.com"></script>`. Не добавляй сборку, npm, Vite или другие зависимости.

Не делай generic AI consulting. Не пиши пустые фразы вроде “unlock your potential”. Не добавляй RFS-направления, которых не было в матчинге. Не выдумывай факты про HQ. Если идея основана на гипотезе — пометь это на общей странице. HTML должен открываться локально, без сборки.

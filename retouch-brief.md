# ТЗ на перегенерацию интерьерных фото (по правкам заказчика)

## Общие правила для всех кадров
- Никакого алкоголя: ни вина, ни пива, ни виски, ни графинов.
- Убрать «постановочные» мелочи: чашки с паром, подносы, открытые журналы и книги на столиках.
- Всё, что добавляется, должно быть в реальном масштабе, стоять на поверхности (контактная тень),
  а тени и блики должны совпадать с направлением солнца в кадре.
- Не менять архитектуру, мебель, свет, ракурс и цвет. Править только отмеченные зоны.

Общий негатив-промпт (английский, для SD / Firefly / Midjourney editor):
`floating objects, wrong scale, missing shadows, steam, alcohol, wine, beer, whiskey, clutter, cgi look, distorted perspective`

---

## 1. Гостиная, общий план с диваном Честерфилд (фото 1)
**Правка:** очистить оба столика на переднем плане: убрать чашки, поднос и открытый журнал на деревянном столе,
чашки, блюдца и вазу на белом столике справа.
**Prompt (inpaint по маске столиков):**
`clean empty wooden coffee table and white side table, natural wood grain texture, soft sunlight shadows from skylight, photorealistic interior photo`
Можно оставить одну аккуратную стопку из 2–3 книг на деревянном столе.

## 2. Вид сверху на диван Честерфилд (фото 2)
**Правка:** убрать поднос с сиденья дивана.
**Prompt:** `black tufted leather chesterfield sofa seat, empty, consistent leather folds and reflections`

## 3. Кухня, барная стойка у окна (фото 3)
**Правка:** убрать доску с круассанами и две чашки со стойки справа (неестественно, без пропорций и теней).
**Prompt:** `empty dark granite bar countertop by the window, soft daylight reflection, potted plant stays`

## 4. Гардеробная, крупный план (фото 4)
**Правка:** это гардероб для **верхней одежды**.
- Заменить рубашки и пиджаки на верхнюю одежду: 5–7 вещей с промежутками (пальто, тренч, куртка, парка).
- Убрать коробки и обувь с полки справа.
- Нижние полки: убрать ряды обуви и коробки. Допустимо 1–2 пары ботинок, без «склада».
**Prompt:** `walk-in closet for outerwear, a few wool coats, trench coat and a down jacket on wooden hangers with spacing, minimal, tidy, empty lower shelves, warm LED shelf lighting`

## 5. Мини-кухня с холодильником (фото 5)
- **Закрыть дверцу** верхнего шкафа (над микроволновкой).
- Чайник с чашками на подносе: идею оставить, но привести масштаб в норму. Поднос должен лежать
  на столешнице с контактной тенью. Чайник меньше, чашки размером с чайник ≈ 1:3 по высоте.
- Холодильник: **без алкоголя** и не как склад. Убрать вино, пиво и «пивные» бутылки.
  Оставить 3–4 бутылки воды, добавить фрукты (яблоки, лимоны, виноград) в контейнере или на полке.
**Prompt (холодильник):** `open built-in fridge, few sparkling water bottles, bowl of fresh fruit, apples, lemons, grapes, airy and tidy, not overstocked`
**Prompt (столешница):** `small black gooseneck kettle and two ceramic cups on a wooden tray, correct scale, soft contact shadows on countertop`

## 6. Вид с антресоли на кухню и столовую (фото 6)
- **Кирпичная стена над кухней пустая, туда что-то разместить:** большую абстрактную картину в чёрной
  раме или открытую полку с керамикой и растениями (в стиле лофт).
- Предметы на острове и обеденном столе (поднос, ваза, подсвечник, чашки) выглядят неестественно из-за
  пропорций и отсутствия теней. Либо убрать, либо оставить одну вазу с ветками в правильном масштабе и с тенью.
**Prompt (стена):** `large abstract black and white artwork in thin black frame hanging on red brick wall above kitchen, correct perspective from above`
**Prompt (стол):** `dining table with a single ceramic vase with branches, realistic scale, shadow consistent with window light`

## 7. Ванная с металлической панелью (фото 7)
**Правка:** идея с подносом для ванны хорошая, но выглядит неестественно.
Поднос должен лежать поперёк ванны **на обоих бортах**, в реальном размере (~70 см) и с тенью на бортике.
Отражение подноса должно быть в волнистой металлической стене. 1–2 свечи и флакон, без лишнего.
**Prompt:** `bamboo bath caddy resting across both rims of the bathtub, realistic size, one lit candle and amber bottle, soft shadows, reflection in wavy mirrored steel wall`
Если реалистично не получается, поднос убрать.

## 8. Гостиная, вид на лестницу и стеллаж (фото 8)
**Правка:** убрать поднос с чашками с журнального столика (журнал можно оставить закрытым или убрать).
**Prompt:** `empty rustic wooden coffee table, sunlight patches, photorealistic`

## 9. Прихожая (фото 9)
- **На стене слева от двери (отмеченная панель) нужна картина:** вертикальная, спокойная, в тонах
  бетона, коньяка и графита. Рама тонкая чёрная или дубовая.
- Гардероб справа (за стеклом) — **для верхней одежды**, как в п. 4. Убрать коробки на полу.
**Prompt (картина):** `vertical abstract painting in neutral beige, cognac and graphite tones, thin black frame, hanging on concrete wall panel next to entrance door, soft shadow`

## 10. Диван у кирпичной стены (фото 10)
**Правка:** убрать поднос с графином виски и стаканами (алкоголь). Книгу на столе оставить.
**Prompt:** `vintage leather trunk coffee table with one closed coffee table book, no tray`

## 11. Столовая у окна (фото 11)
**Правка:** справа у лестницы **пустая полка** стеллажа с лестницей: заполнить книгами и декором
так же, как основной стеллаж. Убрать отмеченный странный предмет (шар) сверху на металлическом стеллаже.
**Prompt:** `bookshelf filled with books, ceramic vases and a small plant, consistent with existing styling`

## 12. Вид с лестницы на гостиную (фото 12)
**Правка:** убрать поднос с чашками с дивана Честерфилд.
**Prompt:** `black tufted leather sofa with grey knitted throw, no objects on seat`

## 13. Гостиная, крупный план столиков (фото 13)
**Правка:** «это лишнее»: убрать поднос на приставном столике слева, чашки с паром и открытую книгу
на журнальном столе.
**Prompt:** `empty rustic wooden coffee tables, warm afternoon sunlight, realistic shadows`

---

### Рекомендуемый инструмент
Точечный inpaint (Photoshop Generative Fill / Firefly, Stable Diffusion Inpaint, Midjourney Vary Region)
по маске только отмеченных зон. Не перегенерировать весь кадр, иначе поплывут архитектура и свет.
После правки проверить: тени от новых предметов совпадают с солнечными полосами в кадре.

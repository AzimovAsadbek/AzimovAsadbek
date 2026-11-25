# Asadbek Azimov

Full-stack разработчик. Пишу на TypeScript, работаю с Next.js, NestJS и PostgreSQL. Подключаю языковые модели к данным приложений и автоматизирую задачи, которые сотрудники выполняют каждый день.

### TERAN · интернет-магазин чая

Покупатель спрашивает о чае на узбекском, русском или английском. Чат передаёт Gemini данные каталога, а сервер сверяет рекомендации с опубликованными товарами. В админ-панели сотрудники управляют остатками и готовят публикации для Telegram.

[Магазин](https://terantrade.uz/) · [Код чата и тесты](https://github.com/AzimovAsadbek/teran/tree/a1dd23cafaa94e11a5034599bb199b336bdf96a1/apps/api/src/assistant) · [Публикация в Telegram](https://github.com/AzimovAsadbek/teran/blob/main/docs/architecture/telegram.md)

### CareBridge AI · разбор обратной связи

Прототип для хакатона. Gemini определяет тему и приоритет анонимного отзыва. API проверяет ответ по схеме. Если модель недоступна, обращение всё равно получает приоритет по локальным правилам.

[Классификация отзывов](https://github.com/AzimovAsadbek/careBridge/blob/main/apps/api/src/ai/feedback-analysis.service.ts) · [Тесты резервного сценария](https://github.com/AzimovAsadbek/careBridge/blob/main/apps/api/src/ai/feedback-analysis.service.spec.ts)

### EduTech · обработка заявок в Telegram

Заявка с сайта сохраняется в PostgreSQL. Менеджер меняет её статус кнопкой в Telegram, а затем может выгрузить отфильтрованный список в Excel из админ-панели.

[Обработчик Telegram](https://github.com/AzimovAsadbek/eduTech/blob/main/src/server/modules/telegram/service.ts) · [Экспорт в Excel](https://github.com/AzimovAsadbek/eduTech/blob/main/src/server/modules/excel/service.ts)

### archAi · от описания дома к планировке

Gemini или Groq преобразует текстовое описание дома в параметры проекта. Пользователь проверяет предложение, после чего отдельный модуль строит по этим параметрам план этажей.

[Маршрутизация запросов к моделям](https://github.com/AzimovAsadbek/archAi/blob/main/packages/ai/src/router.ts) · [Построение плана](https://github.com/AzimovAsadbek/archAi/blob/main/packages/floor-plan-engine/src/layout.ts)

# AURORA.luxe — Модули системы

> Сводный план модулей проекта. Детальные описания по каждому модулю вынесены в отдельные файлы каталога [MODULES/](MODULES/).

## Условные обозначения

| Иконка | Тип покрытия |
|--------|-------------|
| ✅ | Полностью покрыто плагином |
| 🔧 | Плагин + частичная доработка |
| 🔌 | Нужен новый плагин (не установлен) |
| 🔌🔧 | Новый плагин + частичная доработка |
| 🛠️ | Полная кастомная разработка |

---

## Реестр плагинов

| Статус | Плагин | Версия / тариф | Модуль | Назначение | Лицензия | Стоимость | Приоритет |
|---|---|---|---|---|---|---|---|
| Установлен | WooCommerce | 10.3.8 | [ECOMMERCE.md](MODULES/ECOMMERCE.md) | E-commerce платформа | Бесплатный | Бесплатно | — |
| Установлен | Advanced Custom Fields PRO | 6.2.9 | [CUSTOM-FIELDS.md](MODULES/CUSTOM-FIELDS.md) | Кастомные поля и метаданные | Платный | $49/год | — |
| Установлен | Polylang Pro | 3.5.1 | [MULTILANGUAGE.md](MODULES/MULTILANGUAGE.md) | Мультиязычность WordPress | Платный | €99 (~$107)/год | — |
| Установлен | Polylang for WooCommerce | 1.6.3 | [MULTILANGUAGE.md](MODULES/MULTILANGUAGE.md) | Мультиязычность WooCommerce | Платный | €99 (~$107)/год | — |
| Установлен | Cyr-To-Lat | 6.6.0 | [URL-TRANSLIT.md](MODULES/URL-TRANSLIT.md) | Транслитерация URL | Бесплатный | Бесплатно | — |
| Установлен | WP Mail SMTP | 4.7.1 | [EMAIL-TRANSACTIONAL.md](MODULES/EMAIL-TRANSACTIONAL.md) | Транзакционные email | Бесплатный (Lite) | Бесплатно | — |
| Установлен | ЮKassa для WooCommerce | 2.13.1 | [PAYMENTS.md](MODULES/PAYMENTS.md) | Приём платежей | Бесплатный | Бесплатно | — |
| Установлен | Т-Банк | 3.0.7 | [PAYMENTS.md](MODULES/PAYMENTS.md) | Приём платежей | Бесплатный | Бесплатно | — |
| Установлен | Оплата Долями | 3.4.0 | [PAYMENTS.md](MODULES/PAYMENTS.md) | Рассрочка платежей | Бесплатный | Бесплатно | — |
| Установлен | Wordfence Security | 8.1.4 | [SECURITY.md](MODULES/SECURITY.md) | WAF и защита | Бесплатный (Free) | Бесплатно | — |
| Установлен | Imunify Security | 2.0.4 | [SECURITY.md](MODULES/SECURITY.md) | Сканирование и защита | Бесплатный | Бесплатно | — |
| Установлен | Duplicator Pro | 4.5.12 | [BACKUPS.md](MODULES/BACKUPS.md) | Бэкапы и миграция | Платный | $79/год | — |
| Установлен | Classic Editor | 1.6.7 | [CONTENT-EDITOR.md](MODULES/CONTENT-EDITOR.md) | Редактирование контента | Бесплатный | Бесплатно | — |
| Установлен | Интеграция Битрикс24 с CF7 | 2.1.5 | [CRM.md](MODULES/CRM.md) | CRM-интеграция | Бесплатный | Бесплатно | — |
| К установке | Rank Math SEO (Pro) | Pro | [SEO.md](MODULES/SEO.md) | SEO, schema, sitemap, hreflang | Freemium | $96/год | Критичный |
| К установке | CURCY — Multi Currency for WooCommerce | Pro | [MULTICURRENCY.md](MODULES/MULTICURRENCY.md) | Мультивалютность | Платный | $34 разово | Критичный |
| К установке | FiboSearch | Pro | [SEARCH.md](MODULES/SEARCH.md) | Поиск с автокомплитом | Freemium | $49/год | Критичный |
| К установке | JetSmartFilters | Crocoblock | [CATALOG-FILTERS.md](MODULES/CATALOG-FILTERS.md) | AJAX-фильтрация каталога | Платный | $43/год | Критичный |
| К установке | TI WooCommerce Wishlist | Premium | [WISHLIST.md](MODULES/WISHLIST.md) | Избранное | Freemium | $79/год | Критичный |
| К установке | Slider Revolution | Starter | [SLIDER.md](MODULES/SLIDER.md) | Слайдер видео/фото | Платный | $35/год | Критичный |
| К установке | Advanced Google reCAPTCHA | Free | [RECAPTCHA.md](MODULES/RECAPTCHA.md) | Защита форм входа/регистрации | Бесплатный | $0 | Критичный |
| К установке | FluentCRM | Pro | [EMAIL-MARKETING.md](MODULES/EMAIL-MARKETING.md) | Email-маркетинг и автоматизации | Freemium | $90/год | Важный |
| К установке | B2BKing | Startup | [B2B.md](MODULES/B2B.md) | B2B-роли, цены, документы | Freemium | $179/год | Важный |
| К установке | JivoSite | Pro, 1 агент | [LIVE-CHAT.md](MODULES/LIVE-CHAT.md) | Онлайн-чат и обратный звонок | Freemium | $504/год | Важный |
| К установке | WooCommerce Points and Rewards | Standard | [LOYALTY.md](MODULES/LOYALTY.md) | Баллы и кешбэк | Платный | $179/год | Важный |
| К установке | Custom Order Status for WooCommerce | Free | [ORDER-STATUSES.md](MODULES/ORDER-STATUSES.md) | Кастомные статусы заказов | Бесплатный | $0 | Важный |
| К установке | Product Size Chart Guide | Standard | [SIZE-GUIDE.md](MODULES/SIZE-GUIDE.md) | Размерная сетка | Freemium | $39/год | Важный |
| К установке | WooCommerce Pre-Orders | Standard | [PREORDER.md](MODULES/PREORDER.md) | Предзаказ товаров | Платный | $179/год | Важный |
| К установке | WP Accessibility / UserWay | Free | [ACCESSIBILITY.md](MODULES/ACCESSIBILITY.md) | Доступность и увеличение шрифта | Бесплатный | $0 | Важный |

> Итого установленные плагины: `~$342/год`
>
> Итого новые плагины: `~$1 506/год`
>
> Разовые покупки: `$34`
>
> Общий бюджет на плагины: `~$1 882/год`

---

## Реестр модулей

| # | Категория | Модуль | Файл | Покрытие | База / текущее решение | Целевая реализация | Часы |
|---|---|---|---|---|---|---|---:|
| 1 | Установлено | E-commerce: каталог, заказы, склад | [ECOMMERCE.md](MODULES/ECOMMERCE.md) | ✅ + доработка | WooCommerce | Каталог, checkout, заказы, склад, роли, точки интеграции с `1С` | 8 |
| 2 | Установлено | Кастомные поля и метаданные | [CUSTOM-FIELDS.md](MODULES/CUSTOM-FIELDS.md) | 🔧 | ACF PRO | Поля товаров, профилей, бейджей, данных Аватара и B2B | 12 |
| 3 | Установлено | Мультиязычность | [MULTILANGUAGE.md](MODULES/MULTILANGUAGE.md) | ✅ | Polylang Pro + Polylang for WooCommerce | RU / EN / CN, отдельный контент и переводы каталога | — |
| 4 | Установлено | URL / транслитерация | [URL-TRANSLIT.md](MODULES/URL-TRANSLIT.md) | ✅ | Cyr-To-Lat | ЧПУ и транслитерация URL | — |
| 5 | Установлено | Email (транзакционная отправка) | [EMAIL-TRANSACTIONAL.md](MODULES/EMAIL-TRANSACTIONAL.md) | ✅ | WP Mail SMTP | Регистрация, восстановление, статусы заказов | — |
| 6 | Установлено | Оплата | [PAYMENTS.md](MODULES/PAYMENTS.md) | ✅ | ЮKassa + Т-Банк + Оплата Долями | Онлайн-платежи и рассрочка | — |
| 7 | Установлено | Безопасность | [SECURITY.md](MODULES/SECURITY.md) | ✅ | Wordfence + Imunify | WAF, антивирус, защита от атак | — |
| 8 | Установлено | Бэкапы и миграция | [BACKUPS.md](MODULES/BACKUPS.md) | ✅ | Duplicator Pro | Резервное копирование и перенос сайта | — |
| 9 | Установлено | CRM-интеграция | [CRM.md](MODULES/CRM.md) | ✅ | Битрикс24 + CF7 | Передача лидов и заявок | — |
| 10 | Установлено | Редактирование контента | [CONTENT-EDITOR.md](MODULES/CONTENT-EDITOR.md) | ✅ | Classic Editor | WYSIWYG-редактирование | — |
| 11 | Критичный | Мультивалютность | [MULTICURRENCY.md](MODULES/MULTICURRENCY.md) | 🔌 | Нет | RUB / USD / EUR, переключатель, связка с регионом | 10 |
| 12 | Критичный | Фильтрация каталога (AJAX) | [CATALOG-FILTERS.md](MODULES/CATALOG-FILTERS.md) | 🔌 | Нет | AJAX-фильтры каталога по типу и атрибутам | 10 |
| 13 | Критичный | Избранное / Wishlist | [WISHLIST.md](MODULES/WISHLIST.md) | 🔌 | Нет | Гостевое и постоянное избранное | 12 |
| 14 | Критичный | Поиск с автокомплитом | [SEARCH.md](MODULES/SEARCH.md) | 🔌 | Нет | Текстовый поиск, подсказки, интеграция с поиском по фото | 12 |
| 15 | Критичный | Слайдер видео/фото | [SLIDER.md](MODULES/SLIDER.md) | 🔌 | Нет | Видео- и фотослайдер на главной | 12 |
| 16 | Критичный | SEO-оптимизация | [SEO.md](MODULES/SEO.md) | 🔌 | Нет | Метаданные, schema, sitemap, hreflang | 12 |
| 17 | Критичный | reCAPTCHA | [RECAPTCHA.md](MODULES/RECAPTCHA.md) | 🔌🔧 | Нет | reCAPTCHA v3 + логика после 5 неудачных входов | 8 |
| 18 | Критичный | Геолокация | [GEOLOCATION.md](MODULES/GEOLOCATION.md) | 🔌🔧 | Нет | Определение региона для языка, валюты и контента | 12 |
| 19 | Важный | Email-маркетинг | [EMAIL-MARKETING.md](MODULES/EMAIL-MARKETING.md) | 🔌 | Нет | Рассылки, сегментация, abandoned cart | 14 |
| 20 | Важный | SMS-рассылка | [SMS.md](MODULES/SMS.md) | 🛠️ | Нет | Интеграция с SMS-провайдером, шаблоны, логирование | 24 |
| 21 | Важный | Баллы / кешбэк | [LOYALTY.md](MODULES/LOYALTY.md) | 🔌 | Нет | Баллы за покупки и отзывы | 10 |
| 22 | Важный | Онлайн-чат + обратный звонок | [LIVE-CHAT.md](MODULES/LIVE-CHAT.md) | 🔌 | Нет | Коммуникации с клиентами через виджет | 8 |
| 23 | Важный | Кастомные статусы заказов | [ORDER-STATUSES.md](MODULES/ORDER-STATUSES.md) | 🔌 | Нет | Дополнительные статусы и цветовая логика | 8 |
| 24 | Важный | B2B / оптовые цены | [B2B.md](MODULES/B2B.md) | 🔌 | Нет | Роли байеров, оптовые цены, B2B-регистрация | 20 |
| 25 | Важный | Бейджи товаров | [PRODUCT-BADGES.md](MODULES/PRODUCT-BADGES.md) | 🔌 | Нет | Ручные и автоматические значки товаров | 8 |
| 26 | Важный | Размерная сетка | [SIZE-GUIDE.md](MODULES/SIZE-GUIDE.md) | 🔌 | Нет | Таблицы размеров RU / EU / US | 8 |
| 27 | Важный | Шеринг в соцсети | [SOCIAL-SHARING.md](MODULES/SOCIAL-SHARING.md) | 🔌 | Нет | Кнопки шеринга из карточки товара | 6 |
| 28 | Важный | Интеграция с 1С | [ONE-C-INTEGRATION.md](MODULES/ONE-C-INTEGRATION.md) | 🛠️ | Нет | Синхронизация заказов, остатков, номенклатуры | 56 |
| 29 | Кастом | Система Аватар / кастомизация | [AVATAR.md](MODULES/AVATAR.md) | 🛠️ | ACF PRO | Анкета, визуал Аватара, рекомендации | 48 |
| 30 | Кастом | Внутренний мессенджер | [MESSENGER.md](MODULES/MESSENGER.md) | 🛠️ | WP REST API | Клиент ↔ менеджер, файлы, unread, уведомления | 48 |
| 31 | Кастом | Личный стилист | [PERSONAL-STYLIST.md](MODULES/PERSONAL-STYLIST.md) | 🛠️ | ACF PRO | Привязка менеджера и блок стилиста в ЛК | 18 |
| 32 | Кастом | Поиск по фото | [PHOTO-SEARCH.md](MODULES/PHOTO-SEARCH.md) | 🛠️ | Внешний vision API | Загрузка фото и матчинг с каталогом | 40 |
| 33 | Кастом | Астрология / психология | [ASTROLOGY.md](MODULES/ASTROLOGY.md) | 🛠️ | ACF PRO | Астро- и психо-описания, рекомендации | 24 |
| 34 | Кастом | Автоподгрузка адресов (КЛАДР) | [KLADR.md](MODULES/KLADR.md) | 🛠️ | DaData API | Автокомплит адресов в checkout и ЛК | 16 |
| 35 | Кастом | Тёмная тема | [DARK-THEME.md](MODULES/DARK-THEME.md) | 🛠️ | Кастомная тема | Переключение светлой / тёмной темы | 16 |
| 36 | Кастом | Доступность (шрифт) | [ACCESSIBILITY.md](MODULES/ACCESSIBILITY.md) | 🔌🔧 | WP Accessibility / UserWay | A+ / A- в хедере, сохранение выбора | 8 |
| 37 | Кастом | Документооборот байера | [BUYER-DOCS.md](MODULES/BUYER-DOCS.md) | 🛠️ | ACF PRO + B2BKing | Загрузка сканов, статусы, уведомления | 18 |
| 38 | Кастом | Предзаказ товаров | [PREORDER.md](MODULES/PREORDER.md) | 🔌🔧 | WooCommerce Pre-Orders | Статус предзаказа и связка с кастомизацией | 8 |
| 39 | Кастом | AJAX-подгрузка «Показать ещё» | [AJAX-LOAD-MORE.md](MODULES/AJAX-LOAD-MORE.md) | 🛠️ | Кастомная тема | Подгрузка товаров без перезагрузки | 8 |
| 40 | Кастом | Hover-фото в каталоге | [HOVER-PHOTO.md](MODULES/HOVER-PHOTO.md) | 🔌🔧 | FLAVOR Variation Swatches / тема | Второе фото товара на hover | 6 |

---

## Сводка

| Показатель | Значение |
|---|---:|
| Модулей в реестре | 40 |
| Полностью покрыто установленными решениями | 8 |
| Частично покрыто / требует доработки | 7 |
| Нужен новый плагин | 14 |
| Кастомная разработка | 11 |
| Итого по разработке / доработке | 528 ч |

| Категория | Кол-во модулей |
|---|---:|
| Установлено | 10 |
| Критичные | 8 |
| Важные | 10 |
| Кастом | 12 |

---

## Стоимость работ

| Показатель | Значение |
|---|---:|
| Итого часов разработки | 528 ч |
| Ставка разработчика | $50/ч |
| **Общая стоимость работ** | **$26 400** |

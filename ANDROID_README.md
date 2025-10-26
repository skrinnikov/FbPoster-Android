@@
# FbPoster Android

Простой шаблон Android-приложения (Kotlin + Jetpack Compose + WorkManager) для:
- Авторизации через Facebook (заглушка, требуется интеграция SDK)
- Парсинга RSS (Rome)
- Публикации в группы Facebook через Graph API (упрощённо)

## Запуск
1. Откройте папку `android/` в Android Studio (версия Flamingo+ / Jellyfish+).
2. Дождитесь синхронизации Gradle.
3. Замените `facebook_app_id` в `app/src/main/res/values/strings.xml` на ID вашего приложения Facebook.
4. Запустите на устройстве/эмуляторе.

## Дальнейшие шаги
- Подключить Facebook Login SDK (инициализация SDK, CallbackManager, получение токена).
- Безопасно хранить токен (EncryptedSharedPreferences / AccountManager).
- Реализовать фоновые публикации через WorkManager (`PostingWorker`).
- Добавить настройки: список групп, ленты, интервал.





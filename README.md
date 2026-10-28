# Семейные финансы (Android, Kotlin, Compose, Room, MVVM)

## Сборка
1. Откройте папку проекта в Android Studio (Ladybug 2024.2+ / JDK 17). Gradle Wrapper и SDK подтянутся автоматически.
2. Подключите телефон (отладка по USB) или эмулятор и нажмите Run.
3. APK: Build → Build Bundle(s)/APK(s) → Build APK(s) → app/build/outputs/apk/debug/app-debug.apk

## Структура
- data/ — Room: сущности, DAO, база, репозиторий, резервная копия (JSON)
- ui/FinanceViewModel.kt — MVVM: состояние месяца, предупреждения, рекомендации
- ui/*Screen*.kt, Components.kt, Dialogs.kt — Jetpack Compose экраны и диаграммы

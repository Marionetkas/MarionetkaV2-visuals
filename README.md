# MarionetkaV2 — Fabric, Minecraft 26.1.x (Java 25)

Меню: Right Shift. Зум: C. Конфиг: config/marionetkav2.json

Вкладки: Визуал (HUD, Fullbright, Zoom) · Оружие · Небо · Скин.
Скин: положите 64x64 PNG в config/marionetkav2/skin.png (виден только вам).

## Как получить .jar без установки чего-либо
1. Создайте репозиторий на github.com, загрузите содержимое этой папки (включая .github).
2. Вкладка Actions -> build -> Run workflow (или просто сделайте push).
3. Через 2-4 минуты откройте запуск -> Artifacts -> MarionetkaV2-jar.

## Локальная сборка
JDK 25 + Gradle 9.4+:  `gradle build`  ->  build/libs/MarionetkaV2-2.0.0.jar
Нужны Fabric Loader 0.19+ и Fabric API для вашей версии 26.1.x.

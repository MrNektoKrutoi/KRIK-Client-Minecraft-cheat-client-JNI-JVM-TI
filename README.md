# KRIK Client (JVM TI) | Minecraft 1.16.5

[![Telegram Channel](https://img.shields.io/badge/Telegram-Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/KRIK_TGK)
[![Download Release](https://img.shields.io/badge/Download-Release-brightgreen?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MrNektoKrutoi/KRIK-Client/releases/download/1.16.5/KRIK_Client.zip)

![Version](https://img.shields.io/badge/Version-3.1.0-blue?style=for-the-badge&logo=c%2B%2B)
![Minecraft](https://img.shields.io/badge/Minecraft-1.16.5-green?style=for-the-badge&logo=minecraft)
![Type](https://img.shields.io/badge/Type-JVM__TI_Agent-red?style=for-the-badge)

**KRIK Client** — это продвинутый нативный чит-клиент для Minecraft версии 1.16.5. В отличие от обычных модов (Fabric/Forge), KRIK работает через **JVM Tool Interface (JVM TI)**, загружаясь как нативная библиотека (`.dll`). Это обеспечивает максимальную производительность, обход многих античитов и гибкость в работе.

---

## 📂 Структура проекта

В релизе вы получаете готовую папку `KRIK_Client/`. Исходный код не публикуется, только скомпилированные бинарные файлы.

| Файл | Описание | Язык |
| :--- | :--- | :--- |
| `start.exe` | **Лаунчер.** Запускает Minecraft с аргументами агента и инжектором. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| `install.exe` | **Установщик.** Загружает зависимости Minecraft 1.16.5. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) |
| `KRIK_3.1.0.dll` | **Ядро чита.** Скомпилированная JVM TI библиотека. | ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white) |
| `nickname.TXT` | **Конфиг.** Файл для указания вашего никнейма перед запуском. | — |
| `authlib-injector.jar` | **Authlib.** Позволяет играть без лицензии и видеть скины. | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white) |

---

## 🚀 Установка и Запуск

1.  **Скачайте архив** с последнего релиза или из Telegram канала [@KRIK_TGK](https://t.me/KRIK_TGK)
2.  Распакуйте папку `KRIK_Client` в удобное место.
3.  Запустите **`install.exe`**, чтобы скачать необходимые библиотеки и файлы Minecraft 1.16.5 (нужно сделать один раз).
4.  Откройте файл **`nickname.TXT`** и впишите туда желаемый никнейм.
5.  Запустите **`start.exe`**.

---

* **📥 Последний релиз:** [GitHub Releases](https://github.com/MrNektoKrutoi/KRIK-Client/releases)

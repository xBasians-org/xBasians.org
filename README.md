# xBasians.org
[xBasians.org Homepage](https://xBasians-org.github.io)

Knowledge and tools for **xBase developers** (Harbour, xHarbour, Visual FoxPro and other dBase descendants).  
This project shares accumulated experience in automating custom script creation, updating and building packages (including Python, Qt, and others) across multiple platforms.

---

## What you'll find here
- Scripts for building and updating packages (Python, Qt, etc.)
- Notes and resources on integrating xBase applications with modern technologies
- Cross-platform examples (Windows, Linux, Android, and more)

---

## Project goals
- Make it easier for xBase developers to work with modern toolchains  
- Preserve and share practical knowledge about automation and integration  
- Build a common resource for the xBase community  

---

## Getting started
1. Clone the repository:
   ```bash
   git clone https://github.com/xBasians-org/<repo>.git

...

## TODO — Environment & Compiler Setup

- [ ] **Выбор Windows SDK**  
      - Убедиться, что выбран SDK совместим с компилятором (MSVC / MinGW / Clang).  
      - Проверить пути к include/lib/dll.  

- [ ] **Выбор версии компилятора**  
      - Указать точные версии Visual Studio / MinGW / Clang.  
      - Проверить доступность `cl.exe` / `gcc` / `clang`.  
      - Настроить переменные окружения (`PATH`, `INCLUDE`, `LIB`).  

- [ ] **Выбор include/*.h**  
      - Собрать список необходимых заголовочных файлов для VFP, Harbour, HBQt.  
      - Проверить совместимость с SDK и версией компилятора.  

- [ ] **Настройка XBASE_WORKSPACE**  
      - Структура каталогов: VFP_Projects, HB_Projects, HBQT_Projects.  
      - Сохранение конфигураций и переменных окружения в `.bashrc` / `.zshrc` / PowerShell.  

- [ ] **Установка и проверка компиляторов**  
      - VFP 9 + Service Packs.  
      - Harbour + Qt (HBQt) + C/C++ toolchain.  
      - Проверка команд: `vfp`, `hbmk2`, `gcc --version`, `clang --version`.  

- [ ] **Библиотеки и зависимости**  
      - C стандартные библиотеки (glibc / musl) для Linux.  
      - Prebuilt Harbour libs / Qt libs для Windows.  
      - Доп. dev-пакеты (например, для 32-битной совместимости).  

- [ ] **Скрипты автоматизации**  
      - Скрипты для установки и обновления компиляторов и библиотек.  
      - Скрипты для генерации workspace структуры и переменных окружения.  

- [ ] **Документация и ссылки**  
      - README.md с инструкциями.  
      - Ссылки на Google Groups и GitHub Discussions.  
      - Шаблоны конфигурационных файлов для разных ОС.  

- [ ] **Проверка совместимости и тестов**  
      - Минимальный проект для сборки и запуска в VFP, Harbour, HBQt.  
      - Проверка работы на Windows, Linux, macOS.  

- [ ] **Опционально: CI/CD**  
      - GitHub Actions для проверки сборки проектов.  
      - Автоматические тесты для примеров и библиотек.  


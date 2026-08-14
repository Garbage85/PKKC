# PKKC v3.1

Программа для расчёта качественно-количественных и водно-шламовых схем обогащения.

Создана Сапожниковым С.Ю. как приложение на Microsoft Access. Текущая версия — настольное приложение на Python: Windows (готовый EXE) и Linux (запуск из исходников или своя сборка).

## Системные требования

- **Windows 7 и новее** — и **32-bit (x86)**, и **64-bit**  - Python 3.8 + PyInstaller 5.x (совместимость с Windows 7)
- Один универсальный **x86** EXE (на 64-bit Windows работает через WoW64)
- При необходимости: [Visual C++ Redistributable x86](https://learn.microsoft.com/ru-ru/cpp/windows/latest-supported-vc-redist)
- **Debian 11+ / Ubuntu 22.04+** — Python 3.8+, пакет `python3-tk`, графическая сессия (X11 или Wayland)


## Linux (Debian / Ubuntu)

Внешние Python-пакеты для запуска не нужны: достаточно стандартной библиотеки и Tkinter.

## Запуск из исходников (рекомендуется)

С ветки `main`:

```bash
git clone https://github.com/Garbage85/PKKC.git
cd PKKC
python3 -m pkkc
```

С другой ветки (например, ветка pull request):

```bash
git clone -b ИМЯ-ВЕТКИ --single-branch https://github.com/Garbage85/PKKC.git
cd PKKC
python3 -m pkkc
```

Если репозиторий уже склонирован:

```bash
cd PKKC
git fetch origin
git checkout ИМЯ-ВЕТКИ
python3 -m pkkc
```

# we — Wallpaper Engine CLI

Простая консольная утилита для управления Wallpaper Engine в Linux.

## 🚀 Возможности

* `we list` — показать список всех установленных обоев
* `we start [ID]` — запустить обои (можно указать ID)
* `we stop` — остановить обои
* `we restart [ID]` — перезапустить обои
* `we random` — запустить случайные обои
* `we status` — показать статус (запущены/остановлены)

## 📋 Требования

* **Wallpaper Engine** (куплен и установлен в Steam)
* **linux-wallpaperengine** (установлен из AUR или скомпилирован вручную)
* **Arch Linux + WM** (Hyprland, Sway и др.)

## 📦 Установка

### 1. Скачайте скрипт:
sudo curl -o /usr/local/bin/we [https://raw.githubusercontent.com/RRXVADIM14/wallpaper-engine-ctl-we-/main/we](https://raw.githubusercontent.com/RRXVADIM14/wallpaper-engine-ctl-we-/main/we)

2. Сделайте его исполняемым:
Bash

sudo chmod +x /usr/local/bin/we

📸 Пример работы
⚙️ Настройка

При необходимости отредактируйте переменные в начале скрипта (sudo nano /usr/local/bin/we):
Bash

WALLPAPER_ENGINE="/usr/sbin/linux-wallpaperengine"
SCREEN="HDMI-A-1" 
WALLPAPER_DIR="$HOME/.local/share/Steam/steamapps/workshop/content/431960"
DEFAULT_WALLPAPER="2370927443"                

📄 Лицензия

MIT

P.S. Проект не тестировался на других дистрибутивах Linux.


### 🔄 Напоминалка, как обновить это на GitHub:
В своем терминале выполните по очереди:
cd ~/we-github
nano README.md
# (Очистите старый текст, вставьте этот красивый вариант, сохраните: Ctrl+O, Enter, Ctrl+X)

git add README.md
git commit -m "Update README with Russian description and dynamic path"
git push

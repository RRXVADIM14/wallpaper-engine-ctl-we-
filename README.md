# we — CLI-утилита по приколу.
 для управления Wallpaper Engine на Linux. Работает? Работает. Не работает? Форкайте и чините. Я ушел в Gentoo.

## ⚠️ Статус проекта:
проект работает на Arch/Hyprland.
На других конфигах не тестировал — PR и фиксы приветствуются.

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

### 2. Сделайте его исполняемым:

sudo chmod +x /usr/local/bin/we

📸 Пример работы

<img width="1920" height="1080" alt="2026-05-21-100730_hyprshot" src="https://github.com/user-attachments/assets/67aaee00-10e4-4aa0-830d-c704c55a7121" />

⚙️ Настройка

При необходимости отредактируйте переменные в начале скрипта (sudo nano /usr/local/bin/we):


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

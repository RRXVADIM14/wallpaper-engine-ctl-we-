# we - Wallpaper Engine CLI

Простая консольная утилита для управления Wallpaper Engine

# Возможности

- `we list` — показать список всех установленных обоев
- `we start [ID]` — запустить обои (можно указать ID)
- `we stop` — остановить обои
- `we restart [ID]` — перезапустить обои
- `we random` — запустить случайные обои
- `we status` — показать статус (запущены/остановлены)


# Требования
Wallpaper Engine (куплен в Steam),
linux-wallpaperengine (установлен из AUR), Arch Linux

# Установка
## Скачайте скрипт
sudo curl -o /usr/local/bin/we https://raw.githubusercontent.com/RRXVADIM14/wallpaper-engine-ctl-we-/main/we

# Сделайте исполняемым
sudo chmod +x /usr/local/bin/we


# Пример:
<img width="1920" height="1080" alt="2026-05-20-224848_hyprshot" src="https://github.com/user-attachments/assets/3d7eb320-0670-4078-a67e-ca0904abdf63" />

# Настройка
## При необходимости отредактируйте переменные в начале скрипта:
WALLPAPER_ENGINE="/usr/sbin/linux-wallpaperengine"

SCREEN="HDMI-A-1" 

WALLPAPER_DIR="/home/пользователь/.local/share/Steam/steamapps/workshop/content/431960"

DEFAULT_WALLPAPER="2370927443"                

## Лицензия
 ## MIT
# 🔄 Как обновить README на GitHub
cd ~/we-github
nano README.md   
# вставьте русскую версию или оставьте английскую
git add README.md
git commit -m "Update README with Russian description"
git push

 P.S не тестировал на разных дистров линукс

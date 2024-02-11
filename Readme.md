Подготовка билда:
sudo lb config -d bookworm --debian-installer live --debian-installer-distribution bookworm --debian-installer-gui false --archive-areas "main contrib non-free non-free-firmware" --debootstrap-options "--variant=minbase" --memtest "memtest86+"
Очистка билда:
sudo lb clean
Начать билд:
sudo lb build

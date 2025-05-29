# Инструкция по установке Сryptopro csp на Arch (Manjaro) Linux
инструкция по установке cryptopro csp на арч (манжаро) линукс

Важно! Браузер должен быть установлен из AUR или Официального репозитория

1. Склонировать репозиторий из aur - `git clone https://aur.archlinux.org/cryptopro-csp-k1.git`</br>
2. Cкачать архив с пакетами криптопро в папку c клонированным репозиторием https://cryptopro.ru/sites/default/files/private/csp/50/13300/linux-amd64.tgz. Внимание, нужна авторизация на сайте криптопро</br>
3. `makepkg -si` в папке репозитория </br>
4. если рутокен, то драйвера устанавливаются эти: `sudo pacman -S pcsclite pcsc-tools libarchive`</br>


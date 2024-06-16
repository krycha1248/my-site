---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
classes: wide

---
# O mnie

## Wprowadzenie

Cześć! Jestem Krystian Włodek, pasjonat technologii z zamiłowaniem do administracji systemów i automatyzacji infrastruktury IT. Moje główne obszary zainteresowań to administrowanie serwerami, sieciami i chmurami. Dążę do tego, by zostać DevOps Engineer'em. Zachęcam do zapoznania się z moim doświadczeniem i osiągnięciami poniżej!

## Moje Kompetencje

### Umiejętności techniczne

1. **Systemy operacyjne:**
   - Znajomość systemów z rodziny Debian.
   - Znajomość systemu RouterOS (Mikrotik).

2. **Web serwery:**
   - Znajomość web serwerów (Linux, PHP, MySQL, Nginx, Redis).

3. **Serwery poczty:**
   - Podstawowa znajomość serwerów poczty (Postfix, Dovecot, Spamassassin, Rspamd).

4. **Automatyzacja i konfiguracja:**
   - Znajomość skryptów bash.
   - Znajomość Ansible.
   - Znajomość procesów CI/CD.
   - Znajomość narzędzia Github Actions.
   - Podstawowa znajomość technologii chmurowej OpenStack (OVH) od strony użytkownika.
   - Znajomość Terraform.

5. **Wirtualizacja i konteneryzacja:**
   - Podstawowa znajomość wirtualizacji (Proxmox).
   - Podstawowa znajomość Docker’a.

6. **Sieci komputerowe:**
   - Podstawowa znajomość sieci TCP/IP.
   - Znajomość tuneli VPN Wireguard.
   - Certyfikaty CCNA R&S i CCNAv7: Introduction to Networks.

7. **Inne technologie:**
   - Znajomość CMS WordPress.
   - Podstawowa znajomość oprogramowania AutoDesk AutoCAD.

### Certyfikaty i kwalifikacje

- 9/2019/2020 IT Essentials: PC Hardware and Software
- 10/2019/2020 CCNA R&S: Introduction to Networks
- 21/2020/2021 CCNAv7: Introduction to Networks
- Cisco CCNA Routing and Switching
- Kwalifikacja INF0.2
- Kwalifikacja INF0.3
- Certyfikat Autodesk Certified User (ACU)

## Projekty

W mojej sieci domowej korzystam z urządzeń sieciowych firmy MikroTik, które składają się z dwóch routerów. Pierwszy z nich pełni rolę brzegowego routera, zapory sieciowej, serwera VPN oraz kontrolera Capsman. Drugi natomiast działa jako punkt dostępowy.

Na brzegowym routerze skonfigurowałem kilka sieci VLAN, zapórę sieciową, kontroler Capsman dla sieci bezprzewodowych oraz serwer VPN (Wireguard).

Dodatkowo w mojej sieci działa fizyczny serwer z zainstalowanym Proxmox, który jest połączony z routerem poprzez łącze Trunk. Dzięki temu wszystkie kontenery i maszyny wirtualne na Proxmox mają dostęp do wszystkich sieci VLAN.

Na Proxmox uruchomione są głównie kontenery, na których działają różne usługi, takie jak Samba, FTP, Docker, testowy "klaster web" oraz serwer Minecraft, udostępniony publicznie.

Dodatkowo posiadam serwer VPS, na którym zainstalowany jest i skonfigurowany serwer ISPconfig 3. Na tym serwerze znajomi hostują swoje strony internetowe, bazy danych oraz obsługują pocztę w własnych domenach.

Aktywnie korzystam również z chmury publicznej (OpenStack) oraz narzędzi do automatyzacji infrastruktury chmurowej, takich jak Ansible, Terraform oraz GitHub Actions. Napisałem skrypty automatyzujące proces wdrażania instancji w chmurze, ich podstawową konfigurację oraz proces instalacji oprogramowania Jitsi Meet do wideokonferencji.

Wspólnie z kolegą, który zajmuje się tworzeniem aplikacji internetowych, stworzyłem automatyzację procesu wdrażania całego środowiska i aplikacji. Wkrótce planuję rozszerzyć automatyzację na proces wdrażania nowszych wersji aplikacji przy użyciu GitHub Actions oraz Ansible.

***

> Część projektów dostępna jest na moim [GitHubie](https://github.com/krycha1248). <br>
> W tym [kod źródłowy](https://github.com/krycha1248/my-site) tej strony.
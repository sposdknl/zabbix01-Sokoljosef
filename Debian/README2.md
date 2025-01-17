# Instalace

V tomto README najdete nstrukce jak projekt nainstalovat a spustit.

## Manuální instalace

Stáhněte všechny potřebné složky z repozitáře

Vytvořte Vagrantfile, který, vytvoří virtuální server přidejte je do repozitáře.

Specifikuje základní parametry (např. RAM 2GB, počet CPU 2, síťové nastavení portforward 22 a 80).

Zvolte distribuci Debian

Pokud použijete provisioning nástroje (např. Bash, Ansible), přidejte je do repozitáře.

Nainstalujte a nastavte webový server, například Apache nebo Nginx.

Nainstalujte databázi, jako je MySQL nebo PostgreSQL, případně doplňte o TimescaleDB.

Stáhněte a nainstalujte Zabbix server spolu s potřebnými komponentami.

Nastavte přístup k webovému rozhraní Zabbixu.

Nainstalujte Zabbix agent2.

Propojte agenta se serverem.

Zkontrolujte, že vše funguje podle zadání

## Automatizovaná instalace
Instalace Zabbix serveru

Vyberte vhodný nástroj, například Ansible nebo Bash.
Ujistěte se, že máte přístup k cílovým serverům pomocí SSH.
Nastavte strukturu projektu pro uložení skriptů nebo playbooků.

Instalace Zabbix agenta

Nakonfigurujte Zabbix server, aby používal vytvořenou databázi.

Aktualizujte systém a nainstalujte potřebné balíčky pro Zabbix server, včetně webového serveru a databáze.
Vytvořte databázi a uživatele pro Zabbix.

Automatizace pomocí nástroje

Nainstalujte Zabbix agenta na cílové servery.
Nakonfigurujte agenta tak, aby komunikoval se Zabbix serverem.

Zkontrolujte, že vše funguje podle zadání

Ověřte, že skripty fungují správně a že Zabbix server i agent komunikují.

Zkontrolujte, že vše funguje podle zadání

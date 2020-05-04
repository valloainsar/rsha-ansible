# RSHA Ansible skriptimine
Õppeaine nimeks oli Rakendusserverite Haldus. Antud õppeaine käigus sai loodud ansible skriptid, mis automatiseerivad veebilehe ning sisuhalduse (wordpressi) seadistamise. 
Ansible tarkvara kasutades on võimalik teostada masspaigaldust.
## Alustamine
Antud juhised annavad sulle võimaluse tutvuda skriptiga. Samuti on võimalus omal nahal järgi proovida, kuidas loodud skriptid toimivad.
Kui olete Linuxi masinatega vähem kokku puutunud, siis on mõistlik järgnevaid tegevusi teha root kasutaja all.
Antud praktikum sooritati kasutades Debian 9.12 OS-i.
1. Lisaks  on vaja installeerida ansible tarkvara ("apt update", "apt install ansible").
2. tuleks luua kataloog skriptide jaoks ("mkdir /etc/ansible/playbooks/")
Kõik skriptid tuleks luua "/playbook" kataloogi.
### Skripti valimine
Toimivaks lahenduseks on mõistlik kõik skriptid järjest käivitada.
### Skriptide installimine
1. Kopeeri kogu skript antud lingilt: https://github.com/valloainsar/rsha-.
2. Muudad avanenud skripti kõik read aktiivseks ning vajutad ctrl-c.
3. Ava putty.exe, ava nano-ga fail (test.txt), kuhu soovid skripti saada.
4. Parem klikk hiirel ning skript ongi Teie Linuxi masinas.
### Skripti käivitamine
1. # ansible /etc/ansible/playbooks/test.yml.
faili laiendid peavad nüüd olema "yml".
#### Lõpetussõnad
Kõik loodud skriptid on kõigile vabalt kasutamiseks. Skriptide sisu on mõistlik vastavalt vajadusele ka muuta, kindlasti tuleb seda teha sellisel juhul kui oled otsustanud veebilehe reaalselt kasutusele võtta.

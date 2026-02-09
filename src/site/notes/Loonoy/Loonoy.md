---
{"dg-publish":true,"permalink":"/loonoy/loonoy/","tags":["projekt","gardenEntry"],"created":"2025-10-14T22:58:11.836+02:00","updated":"2026-02-05T07:20:22.000+01:00"}
---



<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





</div></div>






[[Loonoy/Evidence hodin/Evidence hodin 2026-01\|Evidence hodin 2026-01]] / [[Loonoy/Výroba 6 ks\|Výroba 6 ks]] / 
# TODO
- [ ] #task Vývoj krytu na velký reproduktor.
- [ ] #task 3D Tisk / Vyrobit 2 sady sloupků (jeda už je v tisku)
- [ ] #task 3D Tisk / Vyrobit 1 sadu battery boxů (nebo dvě kdybych nahrazoval tu SN: 02)
- [ ] #task Testování došlých kabelů.
- [ ] #task Napsat zprávu pro Pepu.


# Vývoj
- [ ] #task [[Loonoy/Houpání na koberci\|Houpání na koberci]]
- [ ] #task [[Loonoy/Shánění pohonů\|Shánění pohonů]]
- [ ] #task [[Loonoy/Kabel USB-C prodlužka\|Kabel USB-C prodlužka]]







| hostname   | IP              | MAC               | Username | Heslo:    |
| ---------- | --------------- | ----------------- | -------- | --------- |
| loonoy-rpi | 192.168.124.103 | B8:27:EB:22:ED:BC | loonoy   | testheslo |



|             parametr | pozadí | Test IDEAL speeed | Test MAX speed |
| -------------------: | :----: | :---------------: | :------------: |
|       metoda měření: |  dBA   |        dBA        |      dBA       |
| max_speed_full_step: |        |        150        |      250       |
|        úroveň hluku: |  36,8  |       40,5        |      47,5      |
|        rozsah kroků: |        |        750        |      750       |
|         počet cyklů: |        |        10         |       10       |


# Porovnání verzí

|                         parametr | R0 (zadání) | R1 (1. prototyp) | R2 (2. prototyp) | R3 (3. prototyp) |
| -------------------------------: | ----------- | ---------------- | ---------------- | ---------------- |
|                       **ZÁVAŽÍ** |             |                  |                  |                  |
| Těžiště vůči dnu korpusu v ose Z | ❌ -60 mm    | ☑ +7,5 mm        |                  |                  |
|    Pracovní zdvih závaží v ose Y | ❌ 85 mm     | ☑ 145 (150) mm   |                  |                  |
|            Kompletní váha závaží | ❌ 4070 g    | ☑ 4909 g         |                  |                  |
|       Invazivní zásah do korpusu | ❌ ANO       | ☑ NE             |                  |                  |
|                        **POHON** |             |                  |                  |                  |
|   Typ pohonné jednotka actuátoru | NEMA 23     | NEMA 17          |                  |                  |
|           Jmenovitý proud pohonu | ❌ 2,8 A     | ☑ 1,5 A          |                  |                  |
|                    Moment pohonu | ❌ 0.55 N.m  | ☑ 0.4 0N.m       |                  |                  |
|              Dílů sestavy pohonu | ❌ 3         | ☑ 1              |                  |                  |
|           Pracovní délka trapézy | ❌ 267 mm    | 283 mm           |                  |                  |

# Výchozí řešení

- nohy jsou zapuštěný 70 mm do středového otvoru




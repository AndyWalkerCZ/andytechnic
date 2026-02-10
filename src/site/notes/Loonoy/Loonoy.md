---
{"dg-publish":true,"permalink":"/loonoy/loonoy/","tags":["projekt","gardenEntry"],"updated":"2026-02-11T00:12:59.070+01:00"}
---



<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/loonoy/loonoy-navigace/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">





---
- **Administrativa:** 🏠 [[Loonoy/Loonoy\|Home]] |🆗 [[Loonoy/Úkoly\|Úkoly]] |⏰[[Loonoy/Evidence hodin/Evidence hodin\|Evidence hodin]] 
- **Části:** [[Loonoy/Komponenty\|Komponenty]] | [[Loonoy/Spojovací materiál\|Spojovací materiál]] | [[Loonoy/Závaží/Závaží\|Závaží]] | [[Loonoy/Pohon/Pohon\|Pohon]] | [[Loonoy/Reprák/Reprák\|Reprák]] | [[Loonoy/Elektronika/Elektronika\|Elektronika]] | [[Loonoy/Měření hluku\|Měření hluku]]
- **Revize:** [[Loonoy/R0 - Zadání\|R0 - Zadání]] | [[Loonoy/R1 - 1. prototyp\|R1 - 1. prototyp]]
- [[Loonoy/Zkoušky/Zkoušky\|Zkoušky]]

---

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




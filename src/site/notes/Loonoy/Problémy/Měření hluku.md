---
{"dg-publish":true,"permalink":"/loonoy/problemy/mereni-hluku/","updated":"2026-02-11T09:02:49.000+01:00"}
---


# Provedené testy
## Test 24.10.2025

**Datum a čas testu:** 24.10.2025 10:30 
**Měřící přístroj:** Voltcraft SL-451
**Měřící metoda:** dBA
**Měřící místnost:** č 162 (kancelář/dílna)
**Stav sestavy:** Kompletní pohybový mechanizmus s odebraným koncový ložiskem
**Umístění mechanizmu:** ležící na stole
**Umístění hlukoměru:** držený v ruce směrován do prostoru

|                        parametr | pozadí | Test IDEAL speeed | Test MAX speed |
| ------------------------------: | :----: | :---------------: | :------------: |
| rychlost (max_speed_full_step): |        |        150        |      250       |
|              úroveň hluku (dB): |  36,8  |       40,5        |      47,5      |
|                   rozsah kroků: |        |        750        |      750       |
|                    počet cyklů: |        |        10         |       10       |

## Test 27.10.2025

**Datum a čas testu:** 27.10.2025 09:00 
**Měřící přístroj:** Voltcraft SL-451
**Měřící metoda:** dBA
**Měřící místnost:** č. 158 (sklad)
**Stav sestavy:** Kompletní pohybový mechanizmus s odebraným koncový ložiskem a motorem NEMA17 uloženým v mechovce 2x5 mm
**Umístění mechanizmu:** ležící na stole
**Umístění hlukoměru:** stojící na stole směřující do prostoru

|                        parametr | pozadí | Test IDEAL speeed | Test MAX speed |
| ------------------------------: | :----: | :---------------: | :------------: |
| rychlost (max_speed_full_step): |        |        150        |      250       |
|              úroveň hluku (dB): |  34,3  |        36         |       50       |
|                   rozsah kroků: |        |        750        |      750       |
|                    počet cyklů: |        |        30         |       30       |

## Test 27.10.2025

**Datum a čas testu:** 27.10.2025 10:11 
**Měřící přístroj:** Voltcraft SL-451
**Měřící metoda:** dBA
**Měřící místnost:** č. 162 (kancelář/dílna)
**Stav sestavy:** Kompletní pohybový mechanizmus s odebraným koncový ložiskem a motorem NEMA17 uloženým v mechovce 2x5 mm
**Umístění mechanizmu:** ležící na stole
**Umístění hlukoměru:** stojící na stole směřující do prostoru

|                        parametr | pozadí | Test IDEAL speeed | Test MAX speed |
| ------------------------------: | :----: | :---------------: | :------------: |
| rychlost (max_speed_full_step): |        |        150        |      250       |
|              úroveň hluku (dB): |  36,2  |        38         |       44       |
|                   rozsah kroků: |        |        750        |      750       |
|                    počet cyklů: |        |        30         |       30       |

# Vyhodnocení měření hluku
Na základě provedených testů ze dne 24. a 27.10.2025 za pomocí hlukoměru, jsem došel k závěru, že měření hlukoměrem (konkrétně pak Voltcraft SL-451), je čistě orientační a neprůkazné a nelze ho referovat s předchozími verzemi zařízení s mechanizmem Robertek.

**Důvody jenž vedou k neprůkaznosti:**
1. Udávaná provozní hodnota 35 dB je na úrovni nebo pod úrovní hluku pozadí ve dvou mnou testovaných oblastech. Čímž pádem by zařízení jednak nevydávalo žádný hluk a pak bez hodnoty hluku v pozadí není známa hodnota reálná plusová hluku v provozu. Mimo to není známa přesná konfigurace měřené sestavy, ani měřené oblast, absence měřící metody a ani směrování mikrofonu hlukoměru.
2. Z provedeného měření je patrné, že konstrukční změny vedou k pozitivním změnám na úrovní hluku vůči statickému stavu mechanizmu spolu s úrovní hluku na pozadí. Jejich reálné hodnoty se nedají v současné době oddělit. Výsledky jsou extrémně závislé na těchto faktorech:
	1. **Na typu místnosti** - velikostí, zástavbou zařizovacími předměty, umístěním v budově.
	2. **Na umístění hlukoměru** - na vzdálenosti od objektu a na tom kam mikrofon směru a to jestli do prostoru nebo nějakou dílčí měřenou část.
	3. **Na kalibraci** přístroje.
	4. **Na metodě měření** (A/C filtraci).
3. Mimo to je důležité, aby měřená soustava měla pokaždé shodnou konstrukční kompletnost a provozní parametry.

# Závěr
Měření hluku hlukoměrem je na základě výše nabytých zkušeností neprůkazné. Jedná se pouze o orientační metodu a bude daleko lepší k ní přistupovat na základě více nezávislých subjektivních hodnocení. Aby byla metoda průkazná tak by vyžadovala odhlučněnou audio místnost a kompletní měřený objekt pokaždé ve stejné konfigurací spolu s ideálně jedním kalibrovaným hlukoměrem.
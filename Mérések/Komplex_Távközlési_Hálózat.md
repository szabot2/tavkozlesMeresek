

# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:**  Szabó Tamás <br>
**A mérés tárgya:** Komplex Távközlési Hálózat Tervezése, Telepítése és Mérése <br>
**A mérés száma:** 2 <br>
**A mérés dátuma:** 2025.01.28 <br>
**A mérést vezette:** Sándor Péter   

**Évfolyam:** 13. E  
**Csoport:** GYAK 2  
**Helyszín:** V3 Labor

---

## 1. Mérés célja

A gyakorlat célja, hogy a diákok elsajátítsák a Mikrotik antennák beállításainak gyakorlati használatát. A feladat során a diákok csatlakoznak az LTE mobil hálózatra, optimalizálják a jelszinteket és vizsgálják a hálózat sávszélességét.

---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám |
| ----------------------------------- | ----------- | ------------- |
| LTE Antenna                         | Mikrotik LHG18       |           |
| Mikrohullámú Antenna szett          | Mikrotik nRay 60GHz  |           |
| SOHO Router                         | ASUS     |        |

---

## 3. **Mérési helyszín és környezet**
- **Antenna magassága**: 1,8 Méter
- **Környezet jellemzői**: Labor szobahőmérséklet
- **Adó távolsága**: 1.5 Méter
---

## 4. Hálózati Topológia

<img src="https://github.com/user-attachments/assets/3c57a0e8-68da-4e3c-8b93-9739f331e392" width="500">

## 5. Mérési eredmények 

RSSI -50dBm
RSRP -82dBm
SINR 21 dBm
RSRQ -15 dB

IP 100.82.157.99

| Antenna típusa    | Eredeti csatorna  | Áthelyezett csatorna | Eredeti frekvencia | Áthelyezett frekvencia | Bemeneti jelszint (dBu) | Kimeneti jelszint (dBu) |
|--------------------------|-------------------|----------------------|--------------------|------------------------|------------------------|------------------------|
| DVB-T Szoba Antenna | 28         | 41            | 530 Mhz            | 634 MHz                |             60          | 100           |
| DVB-T Szoba Antenna | 31         | 42            | 554 MHz            | 642 MHz                |             64          | 100           |
| DVB-T Szoba Antenna | 35         | 43            | 586 MHz            | 650 MHz                |             60          | 100           |
| DVB-T Szoba Antenna | 41         | 44            | 634 MHz            | 658 MHz                |             48          | 100           |
| DVB-T Szoba Antenna | 45         | 45            | 666 MHz            | 666 MHz                |             58          | 100           |
| DVB-T Szoba Antenna | 48         | 46            | 690 MHz            | 674 MHz                |             55          | 100           |

---

## 6. Grafikus ábrázolás
A grafon a sugárzott és a mért jelszint öszzehasonlítását mutatja meg.
![image](https://github.com/user-attachments/assets/68a310a3-8f5a-4919-8ac5-4b66c5e56b21)


## 7. Mérési eredmények elemzése
Az adatok alapján az alábbi következtetéseket lehet levonni:

- Az avasi adótoronyról érkező csatornákat sikeresen befogtuk és sorbarendeztük.
- Az sorbarendendezés után szépen egymás követték a csatornák és a spektrum analizátor ezt gyönyörűen ábrázolta is.
- A johansson eszközben állítottunk még egy 100 dBu-s erősítést is a kimenő csatornákra.
---

## 8. Konklúzió
A mérési folyamat során sikeresen végrehajtottuk a beérkező csatornák áthelyezését a Johansson 6700 Profiler antennaerősítő-szűrő segítségével. Az eszközt megfelelően konfiguráltuk, így a különböző antennák jeleit optimálisan kezeltük. Az áthelyezett csatornák közötti átmenet simán zajlott, és a spektrum analizátor segítségével nyomon tudtuk követni az eredményeket, melyek jól illeszkedtek az elvárásokhoz.

Az eszköz beállításainak finomhangolása során a kimeneti jelszintek stabilizálódtak, és sikeresen elértük a kívánt 100 dBu-s erősítést, amely lehetővé tette a csatornák megfelelő teljesítményének biztosítását. A mérések során tapasztalt zökkenőmentes működés és az eredmények megerősítették a beállítások hatékonyságát. A mérés során alkalmazott műszerek pontosan rögzítették a jelek viselkedését, és az adatok egyértelműen visszaigazolták a csatornák áthelyezésének sikerét.

## 9. Mérési nehézségek és eltérések
Egy-két mérési nehézség természetesen adódott:
- Figyelni kell, hogy a spektrum analizátornak a beállításai a méréshez legyenek beállítva.
- A Johansson profilert az feladat előtt alapértelmezett állapotba kell hozni, hogy ne ütközzön korábbi beállításkkal.

## 10. Javaslatok
Javasolt a mérések ismétlése annak érdekében, hogy a változó környezeti tényezők (például időjárási viszonyok) ne befolyásolják jelentősen a mért eredményeket. Az ismételt mérések segíthetnek biztosítani a stabil és megbízható adatokat.

## 11. Képek a mérésről, csatornákról.

<!-- ![image](https://github.com/user-attachments/assets/270034d2-6204-402b-beec-b33d94625ccf) -->
![image](https://github.com/user-attachments/assets/eea49038-78ba-4aa7-b748-05be064c1ecf)
![image](https://github.com/user-attachments/assets/cda10b04-0801-48d7-8b3a-eae618a4e805)





</details>


<br>

**Aláírás:** Szabó Tamás

**Dátum:** 2025.01.28

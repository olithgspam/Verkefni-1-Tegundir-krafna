# 📄 Software Requirements Specification (SRS)

## 1. Inngangur
### 1.1 Tilgangur
Tilgangur kerfisins er að bæta lífsgæði og öryggi þjónustunotenda á heimilum fyrir fatlaða, með því að bjóða upp á stafræna lausn sem veitir aðstoð í daglegu lífi. Kerfið nýtir gervigreind til að veita sálrænan stuðning, skráningu og skipulagningu á lyfjagjöf, og aðgengi að upplýsingum fyrir umönnunaraðila. Markmiðið er einnig að minnka álag á starfsfólk með sjálfvirkum lausnum.

### 1.2 Umfang
Kerfið mun veita:
- AI chatbot fyrir sálrænan stuðning og leiðbeiningar
- Lyfjaskipulagningu og áminningar
- Aðgang starfsfólks að skjölum, bjargráðum og upplýsingum um notendur
- Notendaviðmót fyrir þjónustunotendur
- Kerfið verður í fyrstu útgáfu aðgengilegt sem vef- og snjallsímaforrit með stuðningi fyrir íslenska notendur innan stofnana.

### 1.3 Skilgreiningar
| Hugtak | Skýring |
|--------|---------|
| SRS | Software Requirements Specification |
| Issue | Umræða/atriði í GitHub sem tengist ákveðinni kröfu |
| Chatbot | Spjallmenni sem svarar spurningum með gervigreind |
| Þjónustunotandi | Einstaklingur með fötlun sem fær þjónustu frá stofnun |
| Umönnunaraðili | Starfsmaður sem sinnir þjónustunotendum |

### 1.4 Tilvísanir
- ISO/IEC/IEEE International Standard - Systems and software engineering -- Life cycle processes -- Requirements engineering," in ISO/IEC/IEEE 29148:2018(E) , vol., no., pp.1-104, 30 Nov. 2018, doi: 10.1109/IEEESTD.2018.8559686.ISO/IEC/IEEE 29
- Kerfi sem við tókum til fyrirmyndar:
- https://www.memaxi.is/
- https://www.huginn.care/
- https://dala.care/

---

## 2. Almenn lýsing
### 2.1 Notendahópar
- Þjónustunotendur: Notendur með fötlun sem þurfa daglega þjónustu og stuðning
- Starfsfólk: Sjúkraliðar, félagsráðgjafar og annað fagfólk sem þjónustar notendur
- Aðstandendur: Fjölskyldumeðlimir sem fá aðgang að upplýsingum með samþykki notanda

### 2.2 Viðskiptaávinningur
- Stofnanir: Minnkar álag á starfsfólk með sjálfvirkum áminningum og upplýsingaflæði
- Starfsmenn: Aðgengi að skjótum upplýsingum og stuðningi þegar brugðist er við atvikum
- Þjónustunotendur: Eykur sjálfstæði og öryggi með notendamiðuðum stuðningi og minni háð annarra

---

## 3. Kröfur fyrir kerfið

### 3.1 Viðskiptakröfur
| ID  | Titill | Issue |
|-----|--------|-------|
| BR1 | Minnka tímalengd sem starfsfólk eyðir í lyfjaskipulagningu um 50% á 3 mánuðum | [#1](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/1) |
| BR2 | Auka sjálfstæði þjónustunotenda með daglegri notkun á AI stuðningsaðstoð | [#2](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/3) |

### 3.2 Kerfiskrafa
| ID  | Titill | Issue |
|-----|--------|-------|
| SR1 | Fjölbreytt aðgengi að kerfinu fyrir mismunandi | [#3](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/4) |

### 3.3 Fídusar (Features)
| ID  | Titill | Issue |
|-----|--------|-------|
| F1  | AI Chatbot | [#4](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/5) |
| F2  | Lyfjaskipulag og áminningar fyrir starfsfólk og þjónustunotendur | [#5](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/6) |
| F3  | Aðgangur starfsfólks að einstaklingsmiðuðum bjargráðum og viðbragðsleiðbeiningum | [#6](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/8) |

### 3.4 Notendakröfur
| ID  | Titill | Fídus | Issue |
|-----|--------|-------|-------|
| UR1 | Þjónustunotandi spjallar við AI-aðstoð | F1 | [#7](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/9) |
| UR2 | Þjónustunotandi fær sjálfvirk svör við daglegum spurningum | F1 | [#8](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/10) |
| UR3 | Starfsmaður skráir lyf og áætlaða tíma | F2 | [#9](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/11) |
| UR4 | Þjónustunotandi fær áminningu um lyfjagjöf | F2 | [#10](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/12) |
| UR5 | Starfsmaður skoðar viðbragðsleiðbeiningar fyrir tiltekinn notanda | F3 | [#11](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/13) |
| UR6 | Starfsmaður merkir viðbrögð eða skráir atvik eftir á | F3 | [#12](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/14) |

### 3.5 Virknikröfur
| ID  | Titill | Notendakrafa | Issue |
|-----|--------|--------------|-------|
| FR1 | [Virkni sem styður notendakröfu] | UR1 | [#13](../../issues/24) |
| FR2 | [Önnur virkni] | UR1 | [#14](../../issues/25) |
| FR3 | [Önnur virkni] | UR1 | [#15](../../issues/26) |
| FR4 | [Virkni] | UR2 | [#16](../../issues/27) |
| FR5 | [Virkni] | UR2 | [#17](../../issues/28) |
| FR6 | [Virkni] | UR2 | [#18](../../issues/29) |
| FR7 | [Virkni] | UR3 | [#19](../../issues/30) |
| FR8 | [Virkni] | UR3 | [#20](../../issues/31) |
| FR9 | [Virkni] | UR3 | [#21](../../issues/32) |
| FR10 | [Virkni] | UR4 | [#22](../../issues/33) |
| FR11 | [Virkni] | UR4 | [#23](../../issues/34) |
| FR12 | [Virkni] | UR4 | [#24](../../issues/35) |
| FR13 | [Virkni] | UR5 | [#25](../../issues/36) |
| FR14 | [Virkni] | UR5 | [#26](../../issues/37) |
| FR15 | [Virkni] | UR5 | [#27](../../issues/38) |
| FR16 | [Virkni] | UR6 | [#28](../../issues/39) |
| FR17 | [Virkni] | UR6 | [#29](../../issues/40) |
| FR18 | [Virkni] | UR6 | [#30](../../issues/41) |

### 3.6 Viðskiptareglur
| ID  | Titill | Issue |
|-----|--------|-------|
| BRG1 | [Viðskiptaregla] | [#31](../../issues/42) |
| BRG2 | [Viðskiptaregla] | [#32](../../issues/43) |


### 3.7 Gæðaeiginleikar
| ID  | Titill | Issue |
|-----|--------|-------|
| QR1 | [Gæðaeiginleiki] | [#33](../../issues/50) |
| QR2 | [Gæðaeiginleiki] | [#34](../../issues/51) |

### 3.8 Takmarkanir
| ID  | Titill | Issue |
|-----|--------|-------|
| C1 | [Takmörkun] | [#35](../../issues/52) |
| C2 | [Takmörkun] | [#36](../../issues/53) |

### 3.9 Ytri skil (Interfaces)
| ID  | Titill | Issue |
|-----|--------|-------|
| IF1 | [Ytra skil] | [#37](../../issues/54) |
| IF2 | [Ytra skil] | [#38](../../issues/55) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: ____________________

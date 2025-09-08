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
| FR1 | Þjónustunotandi spjallar við AI 1 | UR1 | [#13](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/15) |
| FR2 | Þjónustunotandi spjallar við AI 2 | UR1 | [#14](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/16) |
| FR3 | Þjónustunotandi spjallar við AI 3 | UR1 | [#15](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/17) |
| FR4 | Þjónustunotandi fær svör við daglegum spurningum 1 | UR2 | [#16](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/19) |
| FR5 | Þjónustunotandi fær svör við daglegum spurningum 2 | UR2 | [#17](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/20) |
| FR6 | Þjónustunotandi fær svör við daglegum spurningum 3 | UR2 | [#18](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/21) |
| FR7 | Starfsmaður skráir lyf og áætlaða tíma 1 | UR3 | [#19](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/22) |
| FR8 | Starfsmaður skráir lyf og áætlaða tíma 2 | UR3 | [#20](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/23) |
| FR9 | Starfsmaður skráir lyf og áætlaða tíma 3 | UR3 | [#21](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/25) |
| FR10 | Þjónustunotandi fær áminningu um lyfjagjöf 1 | UR4 | [#22]([../../issues/33](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/26)) |
| FR11 | Þjónustunotandi fær áminningu um lyfjagjöf 2 | UR4 | [#23](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/27) |
| FR12 | Þjónustunotandi fær áminningu um lyfjagjöf 3 | UR4 | [#24](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/29) |
| FR13 | Starfsmaður skoðar bjargráð og viðbragðsleiðbeiningar 1 | UR5 | [#25](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/30) |
| FR14 | Starfsmaður skoðar bjargráð og viðbragðsleiðbeiningar 2 | UR5 | [#26](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/33) |
| FR15 | Starfsmaður skoðar bjargráð og viðbragðsleiðbeiningar 3 | UR5 | [#27](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/35) |
| FR16 | Starfsmaður merkir viðbrögð eða skráir atvik eftir á 1 | UR6 | [#28](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/36) |
| FR17 | Starfsmaður merkir viðbrögð eða skráir atvik eftir á 2 | UR6 | [#29](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/39) |
| FR18 | Starfsmaður merkir viðbrögð eða skráir atvik eftir á 3 | UR6 | [#30](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/40) |

### 3.6 Viðskiptareglur
| ID  | Titill | Issue |
|-----|--------|-------|
| BRG1 | Aðgangsstýring gagna þjónustunotenda | [#31](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/18) |
| BRG2 | Tvíþætt staðfesting á lyfjabreytingum | [#32](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/24) |


### 3.7 Gæðaeiginleikar
| ID  | Titill | Issue |
|-----|--------|-------|
| QR1 | Kerfið skal vera aðgengilegt 99.8% af tímanum | [#33](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/28) |
| QR2 | Svartími spjallmennis skal vera innan við 2 sekúndur | [#34](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/31) |

### 3.8 Takmarkanir
| ID  | Titill | Issue |
|-----|--------|-------|
| C1 | Kerfið skal fylgja persónuverndarlögum | [#35](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/32) |
| C2 | Stuðningur við nýjustu útgáfur iOS og Android | [#36](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/34) |

### 3.9 Ytri skil (Interfaces)
| ID  | Titill | Issue |
|-----|--------|-------|
| IF1 | Auðkenning með rafrænum skilríkjum | [#37](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/37) |
| IF2 | Push-tilkynningar á snjalltæki | [#38](https://github.com/olithgspam/Verkefni-1-Tegundir-krafna/issues/38) |

---

## 4. Viðaukar
### 4.1 Orðalisti
- Skilgreina lykilhugtök.

### 4.2 Samþykktir
- Kennari: ____________________  
- Nemandi: ____________________

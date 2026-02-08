[English version here](./README.md)

# WHITE PAPER: REPUBLIKA TIGR
**Verze:** 1.0 (Genesis Edition)  
**Datum:** 8. února 2026  
**Status:** Interní výzkum a vývoj / Technický náhled  
**Architekt:** Zakladatel

---

## 1. Abstrakt
Republika TIGR je experimentální **protokol pro decentralizovanou správu (Governance)** běžící na blockchainu Solana. Cílem projektu je vytvořit funkční model digitální demokracie, který eliminuje potřebu centrálních prostředníků a nahrazuje je transparentním kódem (**Code is Law**). Systém je navržen tak, aby po dokončení fáze vývoje (R&D) fungoval plně autonomně v souladu s principy decentralizace.

## 2. Problém a Řešení
**Problém:** Tradiční modely správy trpí neprůhledností, náchylností ke zneužití moci a oligarchií.  
**Řešení TIGR:**
* **Immutable Ledger:** Všechna rozhodnutí a toky hodnot jsou transparentní a veřejně auditovatelné na blockchainu.
* **Meritokracie:** Vliv v síti není dán pouze kapitálem, ale prokázanou integritou, vzděláním a aktivitou (**Merit**).
* **Self-Custody:** Uživatelé mají výhradní kontrolu nad svými aktivy; neexistuje centrální správce majetku.
* **Sybil Resistance:** Individual Power Limit (IPL) a systém kaucí eliminují boty a falešné identity.  
  * *IPL zajišťuje, že žádná entita nemůže získat absolutní kontrolu nad hlasováním pouhou kumulací kapitálu – vliv je zastropován ve prospěch lidské majority.*

## 3. Technologická Architektura
Projekt využívá blockchain **Solana** pro jeho vysokou propustnost a nízké náklady.
* **Smart Contracts:** Logika správy je vynucována programy, které nelze zpětně měnit (po fázi Awakening).
* **On-Chain Governance:** Hlasování o parametrech sítě probíhá přímo na blockchainu.
* **Bezpečnost:** Systém je **non-custodial** — Architekt nedrží privátní klíče uživatelů.

## 4. Model Občanství (Genesis Mode)
Vstup do sítě (Občanství) je v R&D fázi striktně oddělen od finanční spekulace.
* **Žádný nákup tokenů:** Občanství se nekupuje za tokeny TIGR.
* **Civic Deposit (S-01/S-02):** Účastník skládá vratnou technickou kauci v nativním aktivu sítě (**SOL v hodnotě 10 USD pro Legáty / 30 USD pro Tribuny**).
* **Funkce kauce:** Slouží jako ochrana proti spamu (Sybil resistance) a důkaz integrity. Kauce je uložena v nezávislém smart kontraktu (Escrow) a je plně vratná při řádném výstupu ze sítě.

## 5. Tokenomika a Utilitární funkce
Token **TIGR** neslouží v této fázi jako investiční nástroj, ale jako **palivo pro governance**.
* **Role tokenu:** Hlasovací práva, penalizace (slashing) při útoku na síť, odměna za provoz uzlů Ghost Mesh.
* **Evoluce:** Přechod na využití tokenu TIGR pro kauce je technicky možný **pouze po plné decentralizaci (Awakening)**, což vylučuje vliv zakladatele na tržní poptávku.
* **Alokace zakladatele:** 0,0 % volných tokenů. Veškeré držené tokeny jsou buď uzamčeny (Vesting: 36 měsíců), nebo byly transparentně nakoupeny z veřejného trhu (**Skin in the Game**).

## 6. Roadmapa (Cesta k autonomii)
1. **Fáze Genesis (Současnost):** Interní testování, R&D, centralizovaná ochrana parametrů. **Cíl: Validace 150 Legátů a 150 Tribunů a obsazení všech křesel v orgánech moci.**
2. **Fáze Awakening (Oživení):** Automatická aktivace při dosažení plného kvóra. Revokace administrátorských práv Architekta. Předání kontroly do rukou on-chain governance.
3. **Fáze Sovereignty:** Plně autonomní provoz sítě a aktivace Protokolu likvidity (POL).

## 7. Právní a Regulatorní Rámec
Architektura je navržena s respektem k nařízení EU 2023/1114 (MiCA).
* **Plná decentralizace:** Projekt směřuje k modelu definovanému v **Recitálu 22 MiCA**, který vyjímá plně decentralizované protokoly bez zprostředkovatele z licenčních požadavků CASP.
* **Absence veřejné nabídky:** Projekt neprovádí veřejnou nabídku cenných papírů ani investičních tokenů. Vstup je řešen formou vratné kauce v SOL a složení zkoušek integrity.

---

# Právní prohlášení (Disclaimer)
Tento dokument a související materiály slouží výhradně pro informační, vzdělávací a technické účely. Nejedná se o investiční doporučení, finanční poradenství, nabídku k nákupu, prodeji nebo držení jakéhokoli aktiva. Obsah není určen k propagaci investičních produktů ani k získávání kapitálu. Projekt Republika TIGR je ve fázi výzkumu a vývoje (R&D). Veškeré popsané mechanismy, procesy a parametry se mohou v průběhu vývoje změnit.  

Tento dokument nepředstavuje white paper ve smyslu nařízení EU 2023/1114 (MiCA) a není určen jako dokumentace k veřejné nabídce kryptoaktiv. Token TIGR není investiční nástroj. V současné fázi neslouží k obchodování, spekulaci ani k získávání ekonomického prospěchu. Jeho role je čistě utilitární a vztahuje se k interním governance funkcím protokolu.  

Civic Deposit (kauce) není investicí. Jedná se o vratnou technickou záruku v nativním aktivu sítě (SOL), která slouží výhradně k Sybil‑resistance a integritě účastníků. Použití protokolu je na vlastní riziko. Autoři projektu nenesou odpovědnost za škody vzniklé použitím softwaru, chyby v kódu, nesprávnou interpretaci dokumentace nebo interakci s blockchainem. Vývoj a výzkum v této fázi zajišťuje společnost Tenis Dubeč s.r.o., IČO: 23653281.

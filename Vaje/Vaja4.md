**VAJA 4 – UX/UI zasnova aplikacije (Shieldy)**

**1️. Seznam zaslonov aplikacije**

Na podlagi izdelanega dizajna aplikacija vsebuje naslednje ključne zaslone:

1. Domov (Dashboard)
2. Rezultat analize – nevaren link (Phishing alert)
3. Rezultat analize – varen link
4. Learning / Izobraževalni zaslon

**2️. UX struktura (delovanje aplikacije)**

1. Domov (Dashboard)

Namen:
Uporabniku prikazuje trenutno varnostno stanje in omogoča hiter dostop do analize.

Akcije:

- Klik na “Scan Link” → začetek analize
- Klik na “Paste Message” → analiza sporočila
- Pregled zadnjih aktivnosti
- Klik na “Security Insights”

Navigacija:

- Spodnji meni:
- Home
- History
- Learning
- Settings
  
2. Rezultat – phishing (nevaren link)

Namen:
Uporabnika jasno opozori na nevarnost in poda konkretne korake.

Akcije:

- Pregled nevarnega URL-ja
- Branje razlage (“Why it’s dangerous”)
- Sledenje korakom:
  1. Ne vnašaj podatkov
  2. Zapri stran
  3. Izbriši sporočilo
- Klik “Report and Delete”

**Navigacija:**

- Nazaj na Home
- Dostop do History
  
**3. Rezultat – varen link**

Namen:
Uporabniku potrdi varnost in omogoči nadaljevanje.

Akcije:

- Pregled URL-ja
- Ogled “Verified Domain” informacije
- Klik “Open Link”
- Klik “Back to Home”

Navigacija:

Nazaj na Home
History

**4. Learning (izobraževanje)**

Namen:
Izobraževanje uporabnika o varnosti.

Akcije:

- Pregled “Tip of the day”
- Klik “Mark as Read”
- Pregled zgodovine analiz
- Dostop do “Quick Lessons”

Navigacija:

- Spodnji meni (Home, History, Learning, Settings)

  
**3️. UI postavitev (razpored elementov)**

Domov

Elementi:

- Profil (avatar + ime “Shieldy”)
- Security score (krožni indikator – 85, Good)
- Opis (“Your digital identity is protected”)
- Glavni CTA: Scan Link
- Secondary:
  1. Paste Message
  2. Last scan
-Security Insights (kartice)

Navigacija:

- Bottom navbar (4 ikone)
  
**Phishing rezultat**

Elementi:

- Velik rdeč warning icon
- Naslov: STOP! Potential Phishing Detected
- URL (highlightan)
- Status: “Blocked by Shieldy”
- Razlaga nevarnosti
- 3 koraki (cards)
- CTA: Report and Delete
- Secondary: Ignore warning

  **Safe rezultat**

Elementi:

- Zelen check icon
- Naslov: “This link is safe to visit!”
- URL
- Verified domain box
- Safety score (100/100)
- CTA:
- Open Link
- Back to Home
  
**Learning**

Elementi:

- Progress bar (Level + XP)
- Tip of the day (card)
- Recent scans list
- Quick lessons (cards)
  
**4️. UX skice / design**

**Domov ( Dashboard )**

<img width="522" height="1600" alt="image" src="https://github.com/user-attachments/assets/9db9ae1c-765c-4d45-8640-e040d39dea1c" />

*Slika prikazuje glavni zaslon z varnostnim score-om in možnostjo analize linka.*


**Phising Alert**

<img width="377" height="1600" alt="image" src="https://github.com/user-attachments/assets/65118bfa-ad29-41d2-9aec-1f2ce86ab352" />

*Slika prikazuje opozorilo na nevaren phishing link z razlago in ukrepi.*


**Safe result**

<img width="521" height="1600" alt="image" src="https://github.com/user-attachments/assets/a465f67f-8b50-4135-b66a-e36fbdd124ee" />

*Slika prikazuje potrditev varnega linka in dodatne informacije o domeni.*


**Learning**

<img width="479" height="1600" alt="image" src="https://github.com/user-attachments/assets/1ddc2607-20cc-41ce-a5be-761637c55efa" />

*Slika prikazuje napredek uporabnika in izobraževalne vsebine.*

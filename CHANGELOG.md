# Jurnal de modificări — Decibel

Format: [SemVer](https://semver.org/lang/ro/) MAJOR.MINOR.PATCH.

## 1.0.1 — 2026-10-27 (anterior: v1.0.0)

Stare: stabil · Offline: complet

Aplicat după mini-recenzia din 2026-10-27 (doar texte, fără funcții noi).

### Adăugat
- Explicație în limbaj simplu a ponderărilor de frecvență **A / C / Z** în fila „Măsurare” (sub selectorul de ponderare), în cele 8 limbi ale interfeței: A = urechea la niveluri moderate (zgomot, risc auditiv, dB(A)), C = aproape plată, păstrează joasele (zgomote puternice, vârfuri LCpeak), Z = fără ponderare. Textul reamintește că microfonul unui telefon nu este calibrat.
- README (toate cele 8 limbi): liniile „Stare: stabil” și „Offline: complet”.

### Deja existent în 1.0.0 (nemodificat; recenzia le cerea)
- Avertizare vizibilă permanent că microfoanele de telefon/laptop nu sunt calibrate, iar măsurătorile nu au valoare legală (banner „Orientativ.” și secțiunea „Despre și limite”).
- Asistent de calibrare cu calibrator acustic sau sonometru de referință (măsoară 10 s, calculează decalajul = referință − măsurat); aplicația NU pretinde acuratețe: fără calibrare valorile sunt în dBFS, iar incertitudinea afișată este doar orientativă.
- Jurnal local de sesiuni cu export CSV / JSON / `.fff.json` și tipărire.

### Neimplementat
- Nimic din recenzie nu a rămas neimplementat în acest depozit.

## 1.0.0 — 2026-10-14
- Prima versiune.

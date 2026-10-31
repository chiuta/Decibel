# Jurnal de modificări — Decibel

Format: [SemVer](https://semver.org/lang/ro/) MAJOR.MINOR.PATCH.

## 2.1.0 — 2026-10-31

Îmbină linia din hub (2.0.0, 2026-10-26) cu linia acestui depozit (1.0.1), ca aplicația să poată trece pe origine proprie fără pierderi.

- Ținte tactile: casetele de bifare măsurau 13–18 px; acum 24 px (WCAG 2.5.8). Măsurat pe 360×740: 0 ținte sub 24 px, 0 texte sub 12 px.
- Din hub: **Hartă personală de zgomot** (fila „Hartă”), modulele kit `store` și `dialog` (stocare cu prefix de slug), testul `tests/map.test.mjs`.
- Păstrat din depozit: explicația ponderărilor A/C/Z (1.0.1).
- Testele cu versiunea/data fixate au fost actualizate; testele axe cer `AXE_PATH` și nu au rulat aici.

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

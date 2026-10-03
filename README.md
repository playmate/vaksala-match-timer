# Vaksala SK Match – ensides-app

En förenklad matchtimer för Vaksala SK med ställning, målskyttar, byten, målvakt, speltid per halvlek, inställningar och sparad matchhistorik.

## Starta lokalt

```bash
cd ~/Downloads/fotboll-en-sida
python3 -m http.server 8080
```

Öppna sedan `http://localhost:8080`.

## Version

1.0.0

## 1.1.0
- Markera en aktiv eller bänkad spelare och klicka sedan på spelaren i motsatt grupp för ett direkt byte.
- Aktuell bytestid/bänktid blir orange efter 5 minuter och röd efter 7 minuter.
- Vid framtida APK-bygge: lägg till vibration när 7-minutersgränsen passeras.

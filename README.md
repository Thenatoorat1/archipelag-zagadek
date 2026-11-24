# Archipelag Zagadek

Izometryczna gra survivalowa w przeglądarce. Zbierasz surowce, rozwiązujesz zagadki, budujesz szałas i płyniesz łodzią na kolejne wyspy, a potem przez kamienny pierścień na Księżyc i obcą planetę Veyra.

## Jak uruchomić

Otwórz `index.html` przez serwer HTTP (muzyka i dźwięki ładują się z folderów `music/` i `sfx/`):

```
python3 -m http.server 8000
```

i wejdź na http://localhost:8000. Gra działa też z GitHub Pages.

## Sterowanie

- Klik / stuknięcie: chodzenie, zbieranie, walka
- Rolka: przybliżanie, wciśnięta rolka: przesuwanie mapy, C: powrót kamery do postaci
- Q / E: obrót kamery
- Telefon: dwa palce przybliżają i przesuwają mapę

## Zawartość

- 9 map: Wyspa Latarni, Wyspa Mgieł, Jaskinia Echa, Wyspa Szronu, Wyspa Ognia, Wyspa Piasków, Wyspa Pierścienia, Księżyc, Veyra
- Głód, pragnienie, temperatura, tlen, pogoda, dzień i noc
- Kreator postaci, umiejętności, warsztat, zadania od postaci
- Muzyka i efekty dźwiękowe wygenerowane w Magnific

# Loweda Site

Oficjalna strona internetowa firmy Loweda, specjalizującej się w konsultacjach ajurwedyjskich, masażach ajurwedyjskich, terapiach oczyszczających oraz aromaterapii.

## Informacje o projekcie

Strona została stworzona przy użyciu:

- [Eleventy](https://www.11ty.dev/) (generator stron statycznych)
- [Bootstrap 5](https://getbootstrap.com/) (framework CSS)
- [Bootstrap Icons](https://icons.getbootstrap.com/) (zestaw ikon)

## Uruchamianie lokalnie

1. Zainstaluj zależności projektu:
```
npm install
```

2. Uruchom serwer deweloperski:
```
npm start
```

3. Otwórz przeglądarkę pod adresem `http://localhost:8080`

## Budowanie projektu

Aby zbudować wersję produkcyjną strony:

```
npm run build
```

Pliki zostaną wygenerowane w katalogu `dist/`.

## Hostowanie

Strona może być hostowana na GitHub Pages, Netlify, Vercel lub innej platformie obsługującej statyczne strony internetowe.

## Opis

Minimalistyczny projekt zawierający:
- Stronę index.html z "Hello World"
- Konfigurację GitHub Actions do automatycznego wdrażania na GitHub Pages

## Instrukcja wdrożenia

1. Sklonuj to repozytorium do GitHub
2. GitHub Actions automatycznie wdroży stronę
3. W ustawieniach repozytorium (Settings → Pages):
   - Źródło: GitHub Actions
   - Opcjonalnie: Dodaj domenę niestandardową

## Konfiguracja domeny niestandardowej

Jeśli chcesz użyć własnej domeny:

1. W ustawieniach repozytorium (Settings → Pages):
   - W sekcji "Custom domain" wpisz swoją domenę i kliknij "Save"
   - Aktywuj opcję "Enforce HTTPS"

2. Skonfiguruj DNS u dostawcy domeny:
   - Dla domeny głównej (np. example.com): Dodaj rekordy A wskazujące na adresy IP GitHub Pages
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
   
   - Dla subdomeny www: Dodaj rekord CNAME wskazujący na twojanazwaużytkownika.github.io 
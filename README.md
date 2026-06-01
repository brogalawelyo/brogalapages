# Strona GitHub Pages z widgetem ElevenLabs

To jest prosta statyczna strona HTML wyświetlająca napis **Bartosz Rogala Welyo** oraz widget ElevenLabs ConvAI.

## Pliki

- `index.html` - gotowa strona do publikacji.

## Publikacja na GitHub Pages

1. Utwórz nowe repozytorium na GitHubie, np. `elevenlabs-widget-page`.
2. Wrzuć do repozytorium plik `index.html` z tej paczki.
3. Wejdź w **Settings → Pages**.
4. W sekcji **Build and deployment** wybierz:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Kliknij **Save**.
6. Po chwili strona będzie dostępna pod adresem podobnym do:
   `https://twoj-login.github.io/elevenlabs-widget-page/`

## Widget

Na stronie osadzony jest widget:

```html
<elevenlabs-convai agent-id="agent_1101kt0zw4azf8etjt5zy5vbc1yg" server-location="eu-residency"></elevenlabs-convai>
<script src="https://unpkg.com/@elevenlabs/convai-widget-embed" async type="text/javascript"></script>
```

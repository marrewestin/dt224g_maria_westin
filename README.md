# Beskrivning av webbplatsen
Den här webbplatsen är gjord som redovisning av moment 2 i kursen Introduktion till webbutveckling med HTML, CSS och JavaScript, DT224G.
På webbplatsen presenterar jag mig själv och min trädgård.
## Tekniker
De tekniker som använts är HTML och CSS.
## Publicering
Webbplatsen är publicerad på följande platser:
- https://marrewestin.github.io/dt224g_maria_westin/
- https://dt224g-maria-westin.netlify.app/
## Frågor
1. Vad är skillnaden mellan git add och git commit?
**Svar:** *git add* lägger till filer till staging area och *git commit* sparar filerna.
2. Varför använder man branches istället för att jobba direkt i main?
**Svar:** Med branches kan man göra förändringar som inte publiceras på den skarpa sidan förrän man är redo och gör en merge. På så sätt går det lätt att ångra om det inte blir bra, bara ta bort branchen. Flera personer kan jobba samtidigt i oliga branches utan att störa varandra. Och man kan låta någon godkänna branchen innan den mergas.
3. Vad händer rent praktiskt när man gör en merge?
**Svar:** När man gör en merge infogar man branchen i main så att main uppdateras med det som finns i branchen.
4. Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
**Svar:** Genom att pusha till GitHub sparas filerna och historiken, men att publicera på Netlify gör att webbplatsen blir synlig för besökare.
5. Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
**Svar:** Då skapar jag en .gitignore-fil och listar filnamnen på filerna som inte ska versionshanteras.
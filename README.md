# Σφουγγαρομύριο · project page

Project page and playable build of **Σφουγγαρομύριο** (first version: **Κάθοδος**, at /kathodos/), a Greek daily rarity game: seven prompts a day, fifty seconds each,
and the rarer your valid answer, the deeper you dive with the sponge divers of Kalymnos.

- Project page: https://ennui92.github.io/kathodos-site/
- Play: https://ennui92.github.io/kathodos-site/play/

`play/index.html` is `dist/kathodos-sfoungari.html` (KSHELL=shell-sfoungari.html KOUT=sfoungari node tools/build.js); `kathodos/index.html` is `dist/kathodos.html` from the game repo (`node tools/build.js`). Outside Claude the game
keeps your progress in the browser only; the shared "what others said" numbers need the Claude-hosted version.

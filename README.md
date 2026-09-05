# Pagine pubbliche di Seral

Le tre pagine che App Store e Google Play pretendono raggiungibili da un
indirizzo web: informativa privacy, cancellazione dell'account e una pagina di
assistenza con il contatto.

Questo repository è pubblico **solo perché GitHub Pages lo richiede**. Il codice
dell'app sta altrove, in un repository privato.

**Non modificare `privacy.html` a mano.** Il testo è generato da quello che
l'utente accetta dentro l'app, con `node scripts/genera-pagine-web.mjs` nel
repository dell'app: una modifica fatta qui verrebbe persa alla prossima
generazione, e nel frattempo la policy pubblicata direbbe una cosa diversa da
quella accettata.

# 💞 Il Quiz dei Cuori — Capitolo 2

Una single-page web app pensata per essere aperta sul telefono e passata in mano
a una persona. Sei domande a scelta multipla, tono romantico ma giocoso, e alla
fine una **rivelazione animata** con coriandoli e cuori.

È il **secondo mini-gioco** della serie, dopo la caccia ai cuori di [`/Mani`](../Mani/).

Tutto è in un unico `index.html` autonomo: CSS e JS inline, **nessuna dipendenza
esterna**, audio (chime, errore, fanfara) generato a runtime nel browser.

## ▶️ Come si gioca

- **Locale:** apri `index.html` in qualsiasi browser moderno.
- **Online (GitHub Pages):** `https://guidoputignano.github.io/Quiz/`

## 🎮 Meccanica

- Una domanda alla volta, un bottone per ogni opzione.
- La persona **vince sempre**: le risposte sbagliate si eliminano (con un piccolo
  suono di errore e un messaggio ironico), finché non si arriva a quella giusta.
- Alcune domande hanno **più risposte giuste**: ne basta una per andare avanti.
- Ogni risposta corretta mostra un messaggio dolce e un bottone **Avanti**.
- La domanda finale porta sempre alla **rivelazione**.

## 🛠️ Personalizzarlo

Apri `index.html` e modifica l'array `QUESTIONS` in cima allo `<script>`:
ogni opzione ha `t` (testo), `ok` (se fa avanzare) e `msg` (messaggio mostrato).
La schermata finale si modifica nella sezione `#reveal` dell'HTML. 💝

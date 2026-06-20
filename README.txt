TEST PENITENCIAR RP - VERSIUNEA 2

Structură:
- /candidat/index.html = pagina pe care o trimiți candidatului
- /candidat/candidate.js = întrebări fără răspunsuri corecte
- /evaluator/index.html = pagina evaluatorului
- /evaluator/evaluator.js = barem + corectare grilă + punctaj manual

Ce este schimbat față de prima variantă:
1. Pagina candidatului nu mai are acces la barem sau răspunsuri corecte în fișierele ei.
2. Candidatul completează testul și generează un link/cod pentru evaluator.
3. Evaluatorul deschide linkul primit și corectează testul.
4. Întrebările sunt asemănătoare, dar mai grele și mai aplicate pe procedură/RP.
5. Grila se corectează automat doar pe pagina evaluatorului.
6. Sub I și Sub III se corectează manual cu barem.

IMPORTANT PENTRU SECURITATE:
Dacă pui și folderul /evaluator pe același site public unde intră candidații, un candidat priceput ar putea ghici linkul.
Pentru confidențialitate mai bună:
- trimite candidaților doar linkul către /candidat/
- ține /evaluator/ doar pentru evaluatori, ideal pe un link separat sau într-un repo separat privat

Cum testezi local:
1. Deschide /candidat/index.html
2. Completează testul
3. Apasă „Finalizează testul”
4. Deschide linkul generat sau copiază codul în /evaluator/index.html

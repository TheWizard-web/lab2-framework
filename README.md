# Lucrare de laborator nr. 2. Cereri HTTP și șablonizare în Laravel
## Condiții
### Nr. 1. Pregătirea pentru lucru, instalarea Laravel
 * Întrebare: Ce vedeți în browser când deschideți pagina `http://localhost:8000?`
 - Când deschid pagina [http://localhost:8000](http://localhost:8000) după ce am pornit serverul încorporat Laravel cu comanda `php artisan serve`, apare pagina implicită de bun venit a Laravel.

Această pagină afișează un mesaj de tip **"Laravel"**.
Este o pagină de test care confirmă că Laravel a fost instalat și configurat corect și că serverul local funcționează.
### Nr. 2. Configurarea mediului
* Întrebare: Ce s-ar întâmpla dacă această cheie ar ajunge pe mâna unui răufăcător?
Dacă cheia aplicației setată în fișierul `.env` ar ajunge pe mâna unui răufăcător, acesta ar putea compromite securitatea aplicației. Cheia este utilizată pentru criptarea datelor sensibile, cum ar fi token-uri de autentificare, parole criptate și alte informații private. Un răufăcător ar putea:

- Decripta datele sensibile stocate în aplicație.
- Accesa și manipula informații confidențiale ale utilizatorilor.
- Genera token-uri falsificate pentru a accesa aplicația în mod neautorizat.

Practic, securitatea întregii aplicații ar fi compromisă, ceea ce ar putea duce la pierderea datelor și la încălcarea confidențialității.
### Nr. 3. Principiile de bază ale lucrului cu cererile HTTP
#### Nr. 3.1. Crearea rutelor pentru pagina principală și pagina "Despre noi"
#### Nr. 3.2. Crearea rutelor pentru sarcini
* Întrebare: Explicați diferența între crearea manuală a rutelor și utilizarea unui controller de resurse. Ce rute și ce nume de rute vor fi create automat?
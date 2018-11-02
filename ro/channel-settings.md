<!-- TITLE: Setările canalului -->
<!-- SUBTITLE: Descrierea setărilor canalului -->

# Setările canalului
Setările canalului sunt configurații specifice canalelor.

> Accesarea setărilor canalului

![Channel settings](/uploads/channel-settings/75-da-26-1.gif "Channel settings")

Setările canalului pot fi accesate cu cursorul peste canal și apăsând butonul, sau dând clic dreapta pe canal și apăsând ** Editare canal **. Trebuie să aveți permisiunea ** Gestionați canalul **, ** Gestionați permisiunile ** sau ** Gestionați permisiunile Webhooks ** pentru a putea accesa chiar meniul de setări al canalelor. Membrii cu permisiunea ** Gestionați canalul ** pot șterge, de asemenea, canalul.

# File

## Prezentare generală 

Fila Prezentare generală permite membrilor cu permisiunea ** Gestionare canal ** pentru a schimba numele canalului, subiectul canalului, intervalul slowmode sau configurația NSFW.

### Modul încet

Configurația slowmode modifică intervalul în secunde în care membrii care nu sunt imuni la slowmode trebuie să aștepte înainte de a trimite un alt mesaj. Pentru a fi imuni la modul slowmode, trebuie să aveți fie permisiunile ** Gestionați mesajele ** sau ** Gestionați canalele **. În client, intervalul poate fi schimbat doar la numerele afișate, dar prin intermediul roboților sau prin cererile API, acesta poate fi schimbat în orice, de la 0 (oprit) la 120 (max) secunde. Dacă intervalul este setat prin boti sau prin API, acesta va fi rotunjit la intervalul cel mai apropiat din setările canalului, dar va forța membrii să aștepte timpul configurat.

![Slowmode settings](/uploads/channel-settings/88-e-103-1.gif "Slowmode Settings")

### Permisiuni

Fila Permisiuni permite membrilor cu permisiunea ** Gestionați permisiunile ** să editeze rolul și permisiunile membrilor în cadrul canalului.

### Invitații

Fila Invitații permite membrilor cu permisiunea ** Gestionare canal ** pentru a șterge invitații pentru respectivul canal.

### Webhooks

Fila Webhooks permite membrilor cu permisiunea ** Manage Webhooks ** să gestioneze invitații pentru acel canal.
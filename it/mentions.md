<!-- TITLE: [IT] Menzioni -->
<!-- SUBTITLE: Notifica direttamente gli utenti -->

Le menzioni sono un modo per notificare direttamente un utente, più utenti o ruoli nei messaggi. Il loro scopo principale è di poter avere qualcuno in un canale o mostrare che stai parlando precisamente con loro. Puoi menzionare utenti o ruoli usando `@name`.

# Menzionare utenti
Quando menzioni un utente direttamente, riceveranno una notifica e il messaggio sarà evidenziato per loro. Non ci sono permessi di menzionare utenti individualmente. Per menzionare un utente nell'app su client o su web puoi iniziare a scrivere il loro nome, avere un menù di scelta pop-up o cliccare con il tasto destro l'utente e selezionare "Menziona". Sull'applicazione mobile devi solo premere sul nome o sulla foto profilo dell'utente e sarà menzionato nel messaggio.

# Menzionare ruoli
Quando menzioni un ruolo, tutti gli utenti che hanno accesso al canale avranno una notifica e il canale sarà evidenziato come se fossero menzionati direttamente. Per permettere ad un ruolo di essere menzionato da tutti, attivalo per quel ruolo sotto Impostazioni del server > Ruoli > Permetti a chiunque di @menzionare questo ruolo. A molti proprietari di server piacerà attivare questo per un breve periodo di tempo quando vogliono menzionare tutti gli utenti di un ruolo una volta e poi disattivarlo di nuovo quando fanno l'annuncio a un ruolo specifico.
# @everyone e @here
Usare `@everyone` e `@here` permette di menzionare tutti gli utenti con e senza ruoli. La differenza fra i due è che `@everyone` menziona anche gli utenti offline mentre `@here` solo i membri che sono online e non sono inattivi al momento.

# Menzionare usando gli ID
Puoi anche menzionare direttamente un utente o un ruolo usando l'ID. Il client sostituisce`@role` o `@username#discrim` con `<@&ID>` o `<@ID>` (rispettivamente) e viceversa automaticamente. Il motivo è che è usato perchè i nomi cambiano mentre gli ID no. Il client che non mostra le menzioni come il nome di un utente o di un ruolo possono essere ottenuti usando l'escape alla menzione. Questo può essere fatto scrivendo `\@name#discrim` o `\@role` e mostrerà l'ID ma verrà comunque taggato l'utente. Menzionare gli utenti tramite l'ID è comunemente usato dai bot.
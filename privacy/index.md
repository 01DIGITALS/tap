# Informativa sulla Privacy di Tap!

**Ultimo aggiornamento: 11 settembre 2026**

La presente informativa descrive come vengono gestiti i dati nell'applicazione Android **Tap!**, package `it.sanges.tap`.

Tap! è un'app per conservare e utilizzare carte fedeltà direttamente sul proprio dispositivo. È progettata secondo un principio di minimizzazione: le funzioni principali operano localmente e non richiedono un account Tap!, un backend dello sviluppatore, pubblicità, analytics o telemetria.

## 1. Titolare del trattamento

**Louis Sanges**  
Italia

Email: **louisbigdev@hotmail.com**

## 2. Dati gestiti localmente da Tap!

A seconda delle funzioni utilizzate, Tap! può elaborare sul dispositivo:

- valori e formati di codici a barre e QR Code;
- nome del negozio, nome della carta ed eventuali nomi personalizzati;
- eventuale saldo punti inserito manualmente dall'utente;
- stato delle carte Preferite;
- associazione facoltativa a un brand del catalogo locale;
- identificatori tecnici interni delle carte, dei negozi e dei codici;
- data di creazione e modifica dei record;
- numero locale di aperture di una carta e data dell'ultima apertura;
- eventuali note o informazioni già presenti nei dati importati;
- preferenze locali dell'app;
- immagini o screenshot selezionati volontariamente per leggere un codice;
- dati contenuti nei backup locali selezionati per esportazione o importazione.

Il numero di aperture e la data dell'ultima apertura sono metadati locali utilizzati dall'app e non rappresentano acquisti, transazioni o letture effettuate dal negozio.

Tap! non utilizza tali informazioni per creare profili pubblicitari o comportamentali e non le invia automaticamente allo sviluppatore.

## 3. Finalità e basi giuridiche

Le informazioni gestite localmente vengono utilizzate esclusivamente per fornire le funzioni richieste dall'utente, tra cui:

- creare e organizzare le carte fedeltà;
- visualizzare i relativi codici;
- effettuare ricerche;
- gestire le Preferite;
- leggere codici tramite fotocamera o immagini selezionate;
- effettuare backup e importazioni;
- garantire integrità, continuità e recupero tecnico della raccolta.

Nei limiti in cui il Regolamento (UE) 2016/679 sia applicabile ai trattamenti svolti direttamente dal Titolare, le basi giuridiche possono comprendere:

- l'esecuzione delle attività richieste dall'utente per fornire le funzionalità dell'app e rispondere alle sue richieste, ai sensi dell'art. 6, par. 1, lett. b) GDPR;
- l'adempimento di eventuali obblighi legali, ai sensi dell'art. 6, par. 1, lett. c) GDPR;
- il legittimo interesse del Titolare alla sicurezza, alla tutela dei propri diritti e alla corretta gestione delle richieste di assistenza, ove applicabile, ai sensi dell'art. 6, par. 1, lett. f) GDPR.

Tap! non effettua trattamenti per pubblicità, profilazione o marketing basato sulle carte fedeltà.

## 4. Account, pubblicità e tracciamento

Tap! non richiede la creazione di un account Tap!.

Tap! non contiene pubblicità e non integra SDK pubblicitari.

Tap! non utilizza sistemi di analytics o telemetria remota per monitorare il comportamento dell'utente.

Tap! non integra un servizio remoto di crash reporting.

I normali componenti Android e le librerie utilizzate sul dispositivo possono generare propri messaggi tecnici locali secondo il funzionamento della piattaforma.

## 5. Connessione Internet

Il manifest della build Android release corrente di Tap! non include i permessi Android `INTERNET` o `ACCESS_NETWORK_STATE`.

Non sono stati individuati client di rete o backend Tap! utilizzati per trasmettere la raccolta delle carte.

Alcune azioni volontarie possono tuttavia aprire applicazioni o servizi esterni, ad esempio:

- browser;
- Google Play;
- client email;
- provider di immagini configurati sul dispositivo.

Questi servizi possono utilizzare autonomamente una connessione Internet secondo il proprio funzionamento e le rispettive informative privacy.

## 6. Fotocamera

Tap! utilizza la fotocamera esclusivamente quando l'utente sceglie di scansionare un codice.

I frame vengono elaborati sul dispositivo tramite componenti Android e decoder locali.

Nel normale percorso dello scanner Tap! non salva fotografie o video dei frame acquisiti e non li invia a un server dello sviluppatore.

Il permesso fotocamera non è indispensabile per utilizzare Tap!: se viene negato, rimangono disponibili altri metodi, incluso l'inserimento manuale.

## 7. Immagini e screenshot

L'utente può selezionare volontariamente una fotografia o uno screenshot tramite il selettore immagini di Android.

Tap! legge esclusivamente il contenuto selezionato per individuare il codice.

Per eseguire questa operazione può essere creata temporaneamente una copia privata dell'immagine. La copia può contenere anche eventuali metadati incorporati nel file originale.

Nei normali percorsi di completamento, annullamento o errore, Tap! elimina le copie temporanee quando non sono più necessarie.

Se l'app viene interrotta improvvisamente, una copia temporanea può permanere fino alla successiva esecuzione del meccanismo di pulizia.

Un errore del filesystem può impedire la rimozione; i residui possono permanere se le successive operazioni di pulizia non vengono eseguite o non riescono.

L'immagine originale selezionata dall'utente non viene cancellata o modificata da Tap!.

Il selettore Android può consentire di scegliere contenuti forniti da servizi esterni o cloud configurati sul dispositivo. Se il provider selezionato deve recuperare il contenuto tramite Internet, tale operazione è effettuata dal provider e non costituisce un upload dell'immagine eseguito da Tap!.

## 8. Conservazione delle carte e cancellazione

Le carte rimangono nel database locale fino a quando l'utente non decide di modificarle o eliminarle oppure fino alla cancellazione dei dati dell'app o alla disinstallazione.

Quando viene eliminata una carta, Tap! prevede un breve periodo durante il quale l'operazione può essere annullata.

Successivamente la carta viene eliminata dal database quando l'app ha la possibilità di completare la relativa operazione di pulizia.

Se il processo viene interrotto o si verifica un errore tecnico, la cancellazione definitiva può essere completata al successivo avvio o alla successiva attività di manutenzione del database.

Tap! utilizza copie tecniche temporanee durante alcune operazioni di migrazione o recovery del database.

Le copie non più necessarie vengono normalmente eliminate.

In caso di database danneggiato o illeggibile, il database e un'eventuale copia di recovery possono rimanere localmente, anche con i dati della raccolta, senza una scadenza automatica, per preservare una possibilità di recupero.

Questi meccanismi non costituiscono una copia remota della raccolta.

## 9. Backup ed esportazione

Tap! consente all'utente di creare volontariamente un backup locale della raccolta.

Il backup corrente:

- è un file JSON;
- non viene cifrato da Tap!;
- contiene un checksum SHA-256 utilizzato per verificarne l'integrità;
- non contiene una firma digitale che certifichi l'autore del file;
- viene salvato nella cartella condivisa `Download/Tap` del dispositivo.

Il backup può contenere dati delle carte, negozi, alias, codici, Preferite, saldo punti manuale, brand associato, metadati locali d'uso e preferenze previste dal formato.

Non contiene le immagini temporanee utilizzate durante la scansione o l'importazione.

Poiché il backup viene salvato fuori dallo spazio privato dell'app, può essere accessibile alle applicazioni o ai servizi autorizzati dall'utente a leggere tale spazio.

Tap! non carica automaticamente il backup su un proprio servizio cloud.

L'utente è responsabile della conservazione e della protezione dei file esportati.

## 10. Importazione dei backup

L'importazione viene avviata volontariamente dall'utente.

Tap! verifica struttura, versione e checksum prima di integrare i dati e completa i controlli di coerenza prima di confermare definitivamente le modifiche.

In caso di errore, le modifiche della transazione vengono annullate.

L'importazione aggiunge i dati compatibili alla raccolta esistente e non sostituisce automaticamente l'intero database.

Duplicati o conflitti possono essere ignorati secondo le regole dell'app.

Un vecchio backup conservato dall'utente può contenere una carta eliminata successivamente dall'app. Se l'utente decide volontariamente di importare nuovamente quel backup, tale carta può essere reintrodotta.

Questo comportamento è distinto dai meccanismi automatici di recovery del database.

## 11. Backup Android

Il backup automatico Android dei dati privati di Tap! è disabilitato nella configurazione dell'app.

Sono inoltre configurate esclusioni per i normali meccanismi Android di cloud backup e device transfer applicabili all'app.

Questa configurazione non riguarda i file di backup che l'utente ha volontariamente esportato nella cartella `Download/Tap` né eventuali copie successive create dall'utente tramite altri servizi.

## 12. Google Play

Dalla schermata Informazioni l'utente può scegliere di aprire la scheda di Tap! su Google Play o visualizzare le altre app dello sviluppatore.

La funzione **“Valuta Tap!”** apre manualmente la scheda dell'app su Google Play.

Nella versione 1.0 la richiesta automatica di recensione tramite Google Play In-App Review è disabilitata.

Tap! non acquisisce o memorizza il voto o il testo delle recensioni pubblicate su Google Play.

L'utilizzo di Google Play è soggetto alle condizioni e all'informativa privacy di Google.

## 13. Contatto email e assistenza

L'utente può scegliere volontariamente di contattare il Titolare tramite email.

Tap! tenta di aprire il client email disponibile sul dispositivo precompilando esclusivamente il destinatario:

**louisbigdev@hotmail.com**

Tap! non precompila automaticamente oggetto, testo, carte, codici, fotografie, backup o allegati.

L'utente può però decidere volontariamente di aggiungere informazioni o file al proprio messaggio.

In tal caso tali dati vengono trasmessi tramite il servizio email scelto dall'utente e possono essere ricevuti dal Titolare.

Le comunicazioni ricevute vengono conservate per il tempo necessario a gestire la richiesta e, ove necessario, per adempiere a obblighi di legge o per accertare, esercitare o difendere un diritto.

## 14. Informativa privacy su GitHub Pages

La presente informativa è pubblicata tramite GitHub Pages, servizio fornito da GitHub.

La pagina è disponibile all'indirizzo https://01digitals.github.io/tap/privacy/.

La raccolta delle carte memorizzata in Tap! non viene inviata a GitHub per effetto della pubblicazione o della consultazione di questa pagina.

Quando l'utente visita volontariamente la pagina mediante un browser, GitHub può trattare dati tecnici della visita, incluso l'indirizzo IP, secondo la propria informativa privacy.

GitHub può effettuare trattamenti e trasferimenti internazionali dei dati tecnici relativi all'utilizzo del proprio servizio secondo le proprie condizioni, infrastrutture e garanzie applicabili.

Tap! non aggiunge all'URL della privacy policy valori delle carte, identificatori della raccolta o parametri di tracciamento.

Nella build Android corrente il link alla presente informativa è disponibile nella sezione Privacy dell'app e viene aperto tramite il browser di sistema.

Tap! non utilizza una WebView interna per visualizzare questa pagina e non aggiunge all'URL dati della raccolta o parametri di tracciamento.

## 15. Tastiere, accessibilità e altre funzioni Android

Come le normali applicazioni Android, Tap! utilizza componenti del sistema operativo per visualizzare e modificare testi.

La tastiera scelta dall'utente può ricevere il testo digitato.

I servizi di accessibilità eventualmente abilitati sul dispositivo possono ricevere le informazioni necessarie a rendere accessibile l'interfaccia.

Se l'utente copia del testo oppure sceglie volontariamente un'azione Android di elaborazione del testo, il contenuto selezionato può essere consegnato al componente o all'applicazione scelta.

Tap! non determina quali tastiere, servizi di accessibilità o applicazioni di elaborazione siano installati sul dispositivo e non controlla il loro eventuale utilizzo della rete.

## 16. Destinatari dei dati

Le informazioni relative alle carte vengono elaborate principalmente da componenti locali sul dispositivo.

L'utilizzo locale di tecnologie quali SQLite, CameraX, Flutter o decoder di codici non implica che i dati delle carte vengano automaticamente inviati agli autori di tali tecnologie.

Tap! non comunica automaticamente la raccolta:

- al Titolare;
- ai negozi rappresentati dalle carte;
- ai gestori dei relativi programmi fedeltà;
- a servizi pubblicitari o analytics.

Dati possono invece essere comunicati a soggetti esterni quando l'utente sceglie volontariamente di utilizzare servizi esterni, ad esempio un provider di immagini, Google Play, un browser, un client email o un servizio al quale decide di trasferire un backup.

Il trattamento svolto da tali soggetti avviene secondo le rispettive condizioni e informative privacy.

## 17. Trasferimenti verso paesi terzi

Tap! non invia automaticamente la raccolta delle carte a server del Titolare situati nell'Unione europea o in paesi terzi.

L'utilizzo volontario di servizi esterni può invece comportare trattamenti effettuati anche al di fuori dello Spazio Economico Europeo.

In particolare, la consultazione di questa informativa tramite GitHub Pages comporta un'interazione con i servizi GitHub.

Gli eventuali trasferimenti internazionali effettuati da GitHub, Google, provider email, provider immagini o altri servizi scelti dall'utente sono disciplinati dalle rispettive informative, condizioni e garanzie applicabili.

Tap! non allega automaticamente i dati della raccolta quando apre i normali collegamenti esterni previsti dall'app.

## 18. Log e diagnostica

Tap! non utilizza un servizio remoto di crash reporting.

La diagnostica controllata direttamente dall'app è limitata e progettata per evitare di registrare integralmente i codici delle carte o gli URI selezionati.

Android, CameraX, Flutter, plugin e altre librerie locali possono generare autonomamente messaggi tecnici o diagnostici sul dispositivo.

La conservazione di tali log di sistema dipende da Android e non è controllata direttamente da Tap!.

## 19. Minori

Tap! non richiede la creazione di un account, l'età o la data di nascita dell'utente.

L'app non contiene funzionalità progettate per raccogliere dati di minori per finalità pubblicitarie, di profilazione o marketing.

L'utente può tuttavia inserire liberamente informazioni nei campi previsti dall'app. Tap! non analizza tali contenuti per stabilire se riguardino persone minorenni.

## 20. Esercizio dei diritti

Nei casi in cui il Regolamento (UE) 2016/679 sia applicabile, l'interessato può esercitare i diritti previsti dalla normativa, tra cui, quando ne ricorrono i presupposti:

- accesso ai propri dati;
- rettifica;
- cancellazione;
- limitazione del trattamento;
- opposizione;
- portabilità dei dati;
- revoca del consenso, ove il trattamento sia basato sul consenso, senza pregiudicare la liceità del trattamento precedente alla revoca.

Le richieste possono essere inviate a:

**louisbigdev@hotmail.com**

Il Titolare risponde alle richieste secondo i termini e le modalità previste dal GDPR.

Non esiste un account Tap! dal quale sia necessario “disiscriversi”.

### Dati conservati esclusivamente sul dispositivo

La raccolta delle carte non viene trasmessa automaticamente allo sviluppatore.

Per tali dati l'utente dispone direttamente delle funzioni dell'app per modificare o eliminare le singole carte e delle funzioni Android per cancellare completamente i dati locali o disinstallare l'app.

Il Titolare non può accedere a distanza alla raccolta conservata esclusivamente sul dispositivo dell'utente e non può cancellarla da remoto per suo conto.

### Dati comunicati direttamente al Titolare

Se l'utente ha comunicato volontariamente dati personali al Titolare, ad esempio mediante una richiesta di assistenza via email, può chiedere la cancellazione di tali dati scrivendo allo stesso indirizzo, nei casi e nei limiti previsti dall'art. 17 GDPR.

La cancellazione può non essere effettuata quando la conservazione sia necessaria per adempiere a un obbligo legale o per accertare, esercitare o difendere un diritto o negli altri casi previsti dalla normativa.

L'interessato ha inoltre diritto di proporre reclamo all'autorità di controllo competente.

Per l'Italia:

**Garante per la protezione dei dati personali**

## 21. Cancellazione dei dati locali

L'utente può eliminare le singole carte tramite Tap!.

Può inoltre cancellare tutti i dati privati dell'app tramite le impostazioni Android oppure disinstallando l'app.

La cancellazione dei dati dell'app non elimina automaticamente:

- backup precedentemente esportati in `Download/Tap`;
- copie dei backup realizzate dall'utente;
- immagini o screenshot originali presenti sul dispositivo o presso provider esterni;
- dati volontariamente inviati tramite email o altri servizi esterni.

Tali elementi devono essere gestiti separatamente dall'utente o, quando applicabile, mediante richiesta al relativo titolare del trattamento.

L'eliminazione di una carta all'interno di Tap! prevede inizialmente un breve periodo durante il quale l'operazione può essere annullata. La cancellazione definitiva dal database viene completata quando l'app esegue la relativa operazione di pulizia.

La cancellazione dei dati locali non costituisce una garanzia di cancellazione forense dal supporto fisico del dispositivo.

Un backup precedentemente esportato rimane indipendente dalla raccolta corrente. Se contiene una carta successivamente eliminata dall'app, l'utente può reintrodurla scegliendo volontariamente di importare nuovamente quel backup.

## 22. Sicurezza e minimizzazione

Tap! è progettata per limitare i dati e i permessi utilizzati alle funzioni necessarie.

Le funzioni principali sono eseguite localmente e il manifest Android della build release corrente non include i permessi `INTERNET` o `ACCESS_NETWORK_STATE`.

Tap! non integra un backend destinato a ricevere la raccolta delle carte, sistemi di analytics o telemetria remota, SDK pubblicitari o un servizio remoto di crash reporting.

Il backup automatico Android dei dati privati dell'app è disabilitato nella configurazione di Tap!.

Il file di backup esportato volontariamente non è cifrato da Tap!. Il checksum SHA-256 contenuto nel backup viene utilizzato per verificarne l'integrità rispetto al checksum presente nel file, ma non costituisce una firma digitale e non autentica l'autore o la provenienza del backup.

Poiché il backup viene salvato nella cartella condivisa `Download/Tap`, l'utente è invitato a conservarlo e gestirlo con attenzione e a proteggerne eventuali copie.

Tap! applica meccanismi tecnici locali per ridurre la permanenza non necessaria di file temporanei e copie di lavoro. Tali meccanismi non costituiscono una garanzia di cancellazione forense e possono essere condizionati da interruzioni del processo, errori del filesystem o malfunzionamenti del dispositivo.

Nessun sistema informatico può garantire una sicurezza assoluta. L'utente è pertanto invitato a proteggere adeguatamente il proprio dispositivo, il relativo sistema di sblocco e gli eventuali file esportati.

## 23. Modifiche alla presente informativa

La presente informativa può essere aggiornata per riflettere modifiche delle funzionalità di Tap!, della normativa applicabile, dei requisiti delle piattaforme di distribuzione o dei servizi esterni effettivamente utilizzati.

La data indicata all'inizio della pagina identifica la versione corrente del presente testo.

Qualora vengano introdotte modifiche sostanziali ai trattamenti descritti, l'informativa verrà aggiornata e saranno adottate, quando richieste dalla normativa applicabile, modalità appropriate per informare gli interessati.

Una modifica della presente informativa non comporta automaticamente l'introduzione di nuove funzionalità o nuovi trattamenti nell'app.

## 24. Contatti

Per informazioni relative alla presente informativa, per richieste in materia di protezione dei dati o per esercitare i diritti previsti dalla normativa applicabile, è possibile contattare:

**Titolare del trattamento**  
Louis Sanges  
Via Alessandrini, 8  
43039 Salsomaggiore Terme (PR)  
Italia

**Email:** louisbigdev@hotmail.com

Per i dati conservati esclusivamente sul dispositivo dell'utente, il Titolare non dispone di accesso remoto alla raccolta Tap! e non può modificarla o cancellarla a distanza.

Per i dati eventualmente comunicati volontariamente al Titolare, ad esempio tramite email, le richieste relative ai diritti dell'interessato possono essere inviate all'indirizzo sopra indicato.

---

**Applicazione:** Tap!  
**Package Android:** `it.sanges.tap`  
**Versione dell'informativa:** 11 settembre 2026  
**Piattaforma attualmente supportata:** Android

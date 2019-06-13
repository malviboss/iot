# iot
IoT for Monitoring

Il progetto grails contiene il codice sorgente del progetto IoT for Monitoring del gruppo Gabbanini, Malvestiti, Prendi, Massacci, Pincini

Il core del progetto è contenuto nella cartella grails-app in cui vengono create classi e modelli, controlli, viste.

Nella cartella conf ci sono tutte le configurazioni di grails, l'accesso e lettura del DB, i plugin installati, i dati di bootstrap all'avvio ed il mapping degli URL.

Nella cartella jobs ci sono i job che servono per la lettura costante del servizio REST.

Nella cartella services ci sono metodi utilizzati all'interno del job.

Per poter far girare il progetto è necessario installare grails 2.5.4, java 8 ed avere un db mysql (uno in localhost alla porta 8889 per sviluppo in locale ed il remoto alla porta 3306.

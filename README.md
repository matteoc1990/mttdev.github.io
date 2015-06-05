# telnext.github.io

Aggiungere un post
------------------

Creare un file **anno-mese-giorno-titoloDelPost.md** che andrà inserito all'interno della cartella **_post**

###*Template di base*
<blockquote>
<p>---<br>
title: titolo del post<br>
category: nome del team<br>
---<br>
contenuto in Markdown
</p>
</blockquote>

Uso di git da terminale
-----------------------

###*Configurazione*

- git config --global user.name "*username*"
- git config --global user.email "*email*"

###*Repository*

Dentro la directory, **git init** per creare un nuovo repository

checkout di un repository: **git clone percorsoRepository**

###*Ambiente di lavoro*


**Tre alberi**

* *Directory di lavoro* : contiene i files
* *Index* : spazio di transito per i files
* *Head* : ultimo commit fatto

###*Validazione e aggiunta*

Propongono modifiche aggiungendole all'index:

***git add nomeDelFile***

***git add * ***

Per validare le modifiche fatte

***git commit -m "Messaggio"***

fatto questo ci siamo spostati nell'***HEAD***

###*Invio delle modifiche*

Per spostarci dalla copia locale al repository remoto

***git push origin master***

al posto di *master* eventualmente inserisci il 'branch' in cui vuoi inviare i cambiamenti

###*Aggiornamento repository locale*

Per aggiornare il repository locale alla commit più recente

***git pull***

in sintesi esegue una fetch e una merge delle modifiche fatte in remoto

Per maggiori info ***man git***

Gui
=======

Disponibile solitamente di default gitk

Altrimenti per Win o Mac applicativo scaribabile direttamente da GitHub








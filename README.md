# HackInBoSafeEdition2020

# iOS Forensics Lab

Benvenuti alla pagine di preparazione per il lab "live" su "iOS Forensics" di HackInBoSafeEdition 2020 che si terrà <b>Sabato 30 Maggio 2020</b>

L’obiettivo della demo/workshop è:

<ol>
<li>illustrare come effettuare una acquisizione full file system di un dispositivo iPhone utilizzando il jailbreak checkra1n e lo script iOS BFU Triage
<li>illustrare come analizzare l’acquisizione del dispositivo ottenuto con strumenti open source 
</ol>

Il processo di jailbreak utilizzando checkra1n sarà illustrato attraverso slides.
La parte di acquisizione sarà una <b>demo live</b>

Per poter eseguire in autonomia la parte di acquisizione attivamente è necessario utilizzare un computer con sistema operativo MacOSX ed effettuare prima del workshop il processo di jailbreak, seguendo le istruzioni disponibili a questi link:

1.	https://checkra.in/
2.	https://doubleblak.com/blogPosts.php?id=12

<b>#DISCLAIMER#</b>

<b>Utilizzare il jailbreak solo ed esclusivamente su dispositivi di test!</b>

Il secondo link contiene anche le istruzioni per la configurazione dell'ambiente di lavoro dello script iOS BFU Triage, che potete scaricare qui

https://github.com/RealityNet/ios_bfu_triage/blob/master/ios_bfu_triage.sh

La parte di analisi sarà una <b>demo live<b>.

Per poter seguire la demo live in pratica, sono necessari alcuni prerequisiti:

1.	Installare Python 3.7.4 o superiore
2.	Scaricare https://github.com/abrignoni/iLEAPP
3.	Verificare la disponibilità nel proprio sistema di tutte le dipendenze Python necessarie per lo script
    Dovrebbe essere sufficiente eseguire pip install -r requirements.txt dalla cartella dove avete estratto iLEAPP 
2.	Scaricare l'immagine di test che sarà utilizzata durante la demo
https://github.com/abrignoni/iLEAPP
  

In linea di principio il tool funzionano su Windows/Mac/Linux.

Durante la demo sarà utilizzato un Mac, ma se scaricati e configurati opportunamente i tool possono essere utilizzati su tutte le piattaforme. 

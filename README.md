# HackInBoSafeEdition2020

# iOS Forensics Lab

Benvenuti alla pagina di preparazione per il lab "live" su "<b>iOS Forensics</b>" di HackInBoSafeEdition 2020 che si terrà <b>Sabato 30 Maggio 2020</b>

L’obiettivo della demo/workshop è:

<ol>
<li>illustrare come effettuare una acquisizione full file system di un dispositivo iPhone utilizzando il jailbreak <b>checkra1n</b> e lo script <b>iOS BFU Triage</b>
    <li>illustrare come analizzare l’acquisizione del dispositivo con il tool opensource <b>iLeapp</b>
</ol>

Il processo di jailbreak utilizzando checkra1n <b>sarà illustrato attraverso slides</b>.
<br>
La parte di acquisizione sarà una <b>demo live</b>

<b>Per poter seguire live la parte di acquisizione è necessario utilizzare un computer con sistema operativo MacOSX ed effettuare, <b>prima del workshop</b>, il processo di jailbreak</b>, seguendo le istruzioni disponibili ai link:

1.	https://checkra.in/
2.	https://doubleblak.com/blogPosts.php?id=12

<b>
#DISCLAIMER#
<br>
Utilizzare un dispositivo di test e non il proprio dispositivo personale
<br>
#FINE DISCLAIMER#
</b>
<br>

Il secondo link contiene anche le istruzioni per la configurazione dell'ambiente di lavoro dello script iOS BFU Triage, che potete scaricare qui

https://github.com/RealityNet/ios_bfu_triage/blob/master/ios_bfu_triage.sh

<b>Utilizzare il jailbreak solo ed esclusivamente su dispositivi di test!</b>

La parte di analisi sarà una <b>demo live</b>.

Per poter seguire la demo live in pratica, sono necessari alcuni prerequisiti:

1.	Installare Python 3.7.4 o superiore
2.	Scaricare https://github.com/abrignoni/iLEAPP
3.	Verificare la disponibilità nel proprio sistema di tutte le dipendenze Python necessarie per lo script
    Dovrebbe essere sufficiente eseguire pip install -r requirements.txt dalla cartella dove avete estratto iLEAPP 
4.	Scaricare l'acquisizione di test che sarà utilizzata durante la demo da http://bit.do/HackInBoSafeEdition2020
    <B>#ATTENZIONE#</b>
    <br>
    L'acquisizione è un file ZIP, contenente un file TAR.
    <br>
    Per poter seguire la demo "live" è necessario unzippare il file ZIP e avere il file TAR (ovvero, <b>non</b> fare untar)

In linea di principio il tool iLEAPP funziona su Windows/Mac/Linux, quindi questa parte può essere eseguita su diverse piattaforme.
Durante la demo sarà utilizzato un Mac, ma se scaricati e configurati opportunamente i tool possono essere utilizzati su tutte le piattaforme. 

Per chi volesse seguire unicamente la parte di analisi finale, all'URL è disponibile anche il report finale generato da iLEAPP, in formato HTML (compatibile con tutto)



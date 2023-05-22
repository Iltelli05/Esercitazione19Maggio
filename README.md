# Tutorial creazione repository
## Creare una repository e file README.cd
Come creare una repository su git hub:
- Crea una cartella sul Desktop (Es: "Esercitazione19Maggio")
- Eseguire questo comando su git bash:
```cd $HOME/Desktop/Esercitazione19Maggio```
Questo comando deve contenere il percorso per arrivare alla cartella
- Creare con il file README.md sul blocco note che sarà il repository Git, e scrivere sul file la traccia dell'esercizio o il tutorial per creare il repository. Salvare il file.
- Fare l'accesso su Github.com con nome utente e password
- Cliccare su new (come nell'immagine sotto):

![image](https://github.com/Iltelli05/Esercitazione19Maggio/assets/129155620/37ab8f93-924a-4330-b9fd-2013aba3db79)
- Nella creazione del file bisogna creare la repository seguendo queste impostazioni (!!!NON CREARE IL README DI DEFUALT!!!) segui la foto sottostante

![image](https://github.com/Iltelli05/Esercitazione19Maggio/assets/129155620/978db7ff-3e5d-4a91-845b-b09d89898abd)


## Configurazione del repository locale e sincronizzazione
Eseguire questi comandi in oridine su git bash:
``` git init  # Inizializza il repository locale
   git add README.md  # Inserimento del file README.md nell'area di staging
   git commit -m "first commit"  # Creazione del primo commit, che serve a sincronizzare il repository locale con lo stage
   git branch -M main  # Creazione del branch main, da usare come default
   git remote add origin https://github.com/<username>/Esercitazione16maggio  # Connessione del repository remoto al repository locale
   git push -u origin main  # Sincronizzazione del repository remoto con quello locale
```

## Aggiunta dei file alla repository
- Selezionare i file che si vogliono condividere ed inserirli sulla cartella sul desktop.
- una volta aggiunti nella cartella biaogna andare su git bash e eseguire i seguenti comandi:
```git add . # Inserimento di tutti i nuovi file della cartella nell'area di staging
git commit -m "commit dei file" # Creazione del commit, che serve a sincronizzare il repository locale con lo stage
git push -u origin main # Sincronizzazione del repository remoto con quello locale
```













# Come aggiungere comandi / foto / titoli
#### Comandi:
Per inserire i comandi come sopra bisogna utilizzare il carattere " ` " che si scrive con la combinazione Alt + 96.
#### Foto:
 - Fare lo screenshoot con Windows + Shift Sx + S.
 - Incollare con ctrl + v e aspettare che carichi il link.
 #### Titoli:
 Per fare i titoli bisogna utilizzare il # in base a quanti cancelletti si utilizzano vengono creati i titoli (usare il seguente layout "# Titolo").

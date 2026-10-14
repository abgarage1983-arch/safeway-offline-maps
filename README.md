# Mappe offline SafeWay

Questo progetto ospita i pacchetti cartografici per SafeWay. I pacchetti completi
sono ancora in preparazione: saranno disponibili nella sezione **Releases**.

## Contenuto dei pacchetti

- Cartografia locale: strade, località, aree verdi e acqua.
- Dati stradali per calcolare percorsi senza connessione con BRouter.
- Indirizzi e punti di salvezza: assistenza sanitaria, PIT, pronto soccorso,
  ospedali e polizia, nei limiti della copertura OpenStreetMap.
- Catalogo con dimensioni effettive e impronte SHA-256 dei file.

La distribuzione è prevista per tutte le 20 regioni italiane. L'opzione Italia
riutilizza gli stessi file regionali e stradali: non richiede una seconda copia
completa dei pacchetti già scaricati.

## Uso in SafeWay

Quando la versione offline e i pacchetti saranno disponibili, aprire
**Impostazioni → Mappe offline** e scegliere Italia oppure le regioni desiderate.
Il download viene avviato dall'utente. I file restano sul telefono senza login;
gli aggiornamenti sono manuali. Non serve un account GitHub per scaricare.

## Fonti e attribuzione

Cartografia, indirizzi, punti di salvezza e dati stradali derivano da
[OpenStreetMap contributors](https://www.openstreetmap.org/copyright), ODbL.
L'estratto italiano è fornito da
[Geofabrik](https://download.geofabrik.de/europe/italy.html).

Il motore di calcolo dei percorsi è [BRouter](https://github.com/abrensch/brouter),
licenza MIT. Le celle stradali sono fornite da
[BRouter segments](https://brouter.de/brouter/segments4/).

La selezione regionale usa confini derivati da ISTAT, forniti da
[geojson-italy](https://github.com/guglielmo/geojson-italy), CC-BY.
I tasselli cartografici che attraversano un confine sono conservati interi.

La data dei pacchetti indica la preparazione dei dati; non costituisce verifica
dell'apertura attuale di ogni struttura. Sono escluse le destinazioni note come
camere mortuarie, dismesse e il vecchio ospedale di Legnano.

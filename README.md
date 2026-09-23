# Barattolo 🫙⚡ — release ufficiali dell'app Android

[Barattolo](https://barattolo.store) è il mercatino in satoshi: compri e
vendi oggetti veri, e il pagamento è protetto da un deposito di
garanzia Lightning (escrow).
Questa pagina ospita **solo le release** dell'app Android (APK firmato):
il codice del progetto vive altrove.

L'app è un involucro leggero (~2 MB) del sito: tutto quello che vedi
arriva da barattolo.store, l'APK non contiene dati né segreti.

## Come installare

**Download diretto** — scarica l'APK dall'ultima
[release](../../releases/latest) e aprilo sul telefono (serve il permesso
«installa da fonti sconosciute», solo la prima volta).

**Con Obtainium** (aggiornamenti automatici) — in
[Obtainium](https://github.com/ImranR98/Obtainium) tocca ➕ e incolla:

```
https://github.com/kreamistudio-crypto/barattolo-releases
```

**Con Zapstore** — cerca «Barattolo» in [Zapstore](https://zapstore.dev):
le release sono firmate con la chiave Nostr dedicata indicata in
`zapstore.yaml`.

## Verificare il download (facoltativo ma sano)

Ogni release porta accanto all'APK il suo `sha256`. Sul telefono o sul
computer:

```
sha256sum barattolo-X.Y.apk
```

Il risultato deve coincidere con quello scritto nelle note di rilascio.
Gli aggiornamenti sono comunque protetti da Android stesso: un APK
firmato con una chiave diversa dalla nostra viene rifiutato.

## Verificare l'app installata, con AppVerifier

Per controllare che l'app che hai sul telefono sia proprio la nostra,
incolla in [AppVerifier](https://github.com/soupslurpr/AppVerifier)
queste due righe: il nome del pacchetto e l'impronta SHA-256 del
certificato con cui firmiamo ogni APK, la stessa per tutte le versioni.

```
store.barattolo.app
2F:3F:5E:68:94:AB:A0:B8:E4:39:B7:28:9D:55:50:D5:0E:22:37:15:F3:A8:E6:4F:2C:49:38:BC:D5:A2:C2:3C
```

Le stesse due righe stanno nelle note di ogni release e sul sito, in
fondo a [Il pagamento protetto](https://barattolo.store/sicurezza#app).

## Domande

Il posto giusto è il bot Telegram: [@ilbarattolobot](https://t.me/ilbarattolobot).

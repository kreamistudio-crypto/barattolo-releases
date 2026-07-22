# Barattolo 🫙⚡ — release ufficiali dell'app Android

[Barattolo](https://barattolo.store) è il mercatino in satoshi: compri e
vendi oggetti veri, il pagamento è protetto da un escrow Lightning e la
commissione è l'1%. Questa pagina ospita **solo le release** dell'app
Android (APK firmato): il codice del progetto vive altrove.

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

## Domande

Il posto giusto è il bot Telegram: [@ilbarattolobot](https://t.me/ilbarattolobot).

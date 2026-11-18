# Feed prodotti Ranin Cornici per ChatGPT

Ogni 6 ore una GitHub Action scarica il catalogo da
`https://ranincornici.com/collections/all?view=chatgpt-feed` (template `collection.chatgpt-feed.liquid` nel tema Shopify)
e lo pubblica qui come file CSV:

**https://crossave.github.io/ranin-chatgpt-feed/feed.csv**

Questo è l'URL da usare in ChatGPT Business Hub → Prodotti → "Usa un URL ospitato".

Per forzare un aggiornamento: Actions → "Aggiorna feed ChatGPT" → Run workflow.

Nota: se cambi il tema pubblicato su Shopify, copia anche il file `templates/collection.chatgpt-feed.liquid` nel nuovo tema.

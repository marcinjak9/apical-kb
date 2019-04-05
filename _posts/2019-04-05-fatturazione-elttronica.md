---
date: 2019-04-05
title: Fatturazione Elettronica
description: L'integrazione con Fatture in Cloud consiste nella sincronizzazione delle vendite dei store di Apical direttamente su Fatture in cloud.
categories:
  - amministrazione
type: Document
---

## Descrizione Feature

L'integrazione con **Fatture in Cloud** consiste nella sincronizzazione delle vendite dei store di Apical direttamente su [Fatture in cloud](https://www.fattureincloud.it/2019/).
Dal 1 gennaio 2019 vige la norma della fatturazione elettronica, che è supportata da Fattura in Cloud, [https://www.fattureincloud.it/2019/](https://www.fattureincloud.it/2019/)

![Fattura in cloud](/images/fic-home3.jpg)

## Tutorial

1. Bisogna avere un account Fatture in Cloud, in caso contrario registralo qui.
2. Nella dashboard di Fatture in Cloud vai su **Api>Mostra API UID e API KEY**
3. Copia i due valori visualizzati: **API UID e API Key** come nell'immagine.

![Fattura in cloud](/images/fic-api.png)

4. Nella Dashboard di Apical vai dentro le configurazioni del tuo store: 
**Ecommerce > Store > Store desiderato**
5. In fondo alla pagina trovi una sezione chiamata "Fatture in Cloud Api" dove dovrai inserire le credenziali precedentemente copiate
6. Inoltre dovrai inserire la mail con cui hai configurato Fatture in cloud e il tuo codice IVA per il calcolo delle imposte.

![Fattura in cloud](/images/fic-store.png)

Una volta completato questo procedimento le tue fatture verranno generate automaticamente a ogni acquisto, nel caso in cui sia un acquisto a rate verranno generate alla fine dell'ultima rata pagata.

Dentro il dettaglio di un Ordine nella dashboard di Apical potrai visualizzare se è stata emessa una fattura per quell'ordine (immagine sotto).

![Fatture in cloud ordine](/images/fic-ordine.png)

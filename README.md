Analiza i priprema: Učitala sam podatke i primjetila da model ignorira klasu ravnoteže (B) jer je previše rijetka u odnosu na ostale.
Inžinjerstvo značajki: Poboljšala sam model tako da sam izraćunala fizičku silu (težina * ravnoteza), dajući stroju jasniju logiku za učenje.
Oprimizacija i balansiranje: Koristeći class_weight='balanced', model je prisiljen obratiti pozornost na rijetke primjere, čime sam postigla točnost od 90% i uspješno
'probudila' prepoznavanje ravnoteže.

Korišten je dataset sa Kagglea ("https://www.kaggle.com/datasets/mysticvalley/balance-scale?resource=download").
Projekt odrađen u Jupyer Notebooku.

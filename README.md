
# API REST con Symfony

Questo progetto è stato creato per capire e imparare come costruire un API REST Service partendo da zero utilizzando Symfony.

Prendi spunto da questa guida per creare da zero il progetto:

https://www.binaryboxtuts.com/php-tutorials/how-to-make-symfony-5-rest-api/

N.B.: attualmente c'è un bug sul pacchetto "doctrine/annotations", ricordati di utilizzare la versione 1.14.2 e non la versione 2 altrimenti non funzioneranno gli attributi di PHP 8 al posto delle annotations.

Come fare:

nel tuo composer.json sostituisci

```javascript
"doctrine/annotations": "2.*"
```

con 


```javascript
"doctrine/annotations": "1.*"
```


Suggerimenti:

Installare Symfony CLI

https://symfony.com/doc/current/setup.html


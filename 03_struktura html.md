### Struktura HTML dokumentu

Každý HTML dokument má pevně danou strukturu, která se skládá z několika základních částí:

1. **`<!DOCTYPE html>`** – Deklarace typu dokumentu, která říká prohlížeči, že jde o HTML5 dokument.
2. **`<html>`** – Kořenový element, který obaluje celý obsah stránky.
3. **`<head>`** – Sekce, kde jsou umístěny informace o dokumentu, jako je název stránky (`<title>`), odkazy na styly (CSS), metadata a další.
4. **`<body>`** – Hlavní obsah stránky, který vidí uživatel. Zde jsou nadpisy, odstavce, obrázky, odkazy a další viditelné prvky.
5. **`</html>`** – Značka ukončující celý HTML dokument.

Základní struktura HTML dokumentu vypadá takto:

```html
<!DOCTYPE html>
<html lang="cs">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Název stránky</title>
  </head>
  <body>
    <!-- Obsah stránky -->
  </body>
</html>

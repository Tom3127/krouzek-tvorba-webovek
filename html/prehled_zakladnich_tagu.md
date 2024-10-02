# Základní HTML elementy a jejich příklady použití

1. **`<html>`**
   - Základní kořenový element HTML dokumentu.
   - Příklad:
     ```html
     <html>
       <head></head>
       <body></body>
     </html>
     ```

2. **`<head>`**
   - Obsahuje metadata o dokumentu.
   - Příklad:
     ```html
     <head>
       <title>Název stránky</title>
     </head>
     ```

3. **`<title>`**
   - Určuje název stránky, který se zobrazuje v záložce prohlížeče.
   - Příklad:
     ```html
     <title>Moje webová stránka</title>
     ```

4. **`<meta>`**
   - Definuje metadata stránky.
   - Příklad:
     ```html
     <meta charset="UTF-8">
     <meta name="description" content="Popis stránky">
     ```

5. **`<body>`**
   - Obsahuje viditelný obsah stránky.
   - Příklad:
     ```html
     <body>
       <h1>Vítejte na mé stránce</h1>
       <p>Toto je text.</p>
     </body>
     ```

6. **`<header>`**
   - Definuje záhlaví stránky nebo sekce. Obvykle obsahuje nadpisy nebo navigaci.
   - Příklad:
     ```html
     <header>
       <h1>Nadpis stránky</h1>
       <nav>
         <a href="#home">Domů</a>
         <a href="#about">O nás</a>
       </nav>
     </header>
     ```

7. **`<footer>`**
   - Definuje zápatí stránky nebo sekce. Obvykle obsahuje copyright, odkazy na zásady ochrany soukromí apod.
   - Příklad:
     ```html
     <footer>
       <p>2024 Moje webová stránka</p>
     </footer>
     ```

8. **`<h1>` až `<h6>`**
   - Nadpisy různých úrovní.
   - Příklad:
     ```html
     <h1>Hlavní nadpis</h1>
     <h2>Druhý nadpis</h2>
     ```

9. **`<p>`**
   - Definuje odstavec textu.
   - Příklad:
     ```html
     <p>Toto je odstavec textu.</p>
     ```

10. **`<a>`**
    - Hypertextový odkaz.
    - Příklad:
      ```html
      <a href="https://google.com">Klikněte sem</a>
      ```

11. **`<img>`**
    - Vkládá obrázek.
    - Příklad:
      ```html
      <img src="obrazek.jpg" alt="Popis obrázku">
      ```

12. **`<ul>`**
    - Neuspořádaný (odrážkový) seznam.
    - Příklad:
      ```html
      <ul>
        <li>Položka 1</li>
        <li>Položka 2</li>
      </ul>
      ```

13. **`<ol>`**
    - Uspořádaný (číslovaný) seznam.
    - Příklad:
      ```html
      <ol>
        <li>Položka 1</li>
        <li>Položka 2</li>
      </ol>
      ```

14. **`<li>`**
    - Položka seznamu.
    - Příklad:
      ```html
      <ul>
        <li>První položka</li>
        <li>Druhá položka</li>
      </ul>
      ```

15. **`<div>`**
    - Obecný blokový kontejner.
    - Příklad:
      ```html
      <div>
        <h2>Oddíl stránky</h2>
        <p>Text v oddílu.</p>
      </div>
      ```

16. **`<span>`**
    - Obecný inline kontejner.
    - Příklad:
      ```html
      <p>Tento <span style="color: red;">text</span> je červený.</p>
      ```

17. **`<b>`**
    - Zobrazuje tučný text.
    - Příklad:
      ```html
      <p>Toto je <b>tučný</b> text.</p>
      ```

18. **`<i>`**
    - Zobrazuje kurzívu.
    - Příklad:
      ```html
      <p>Toto je <i>kurzívou</i> psaný text.</p>
      ```

19. **`<u>`**
    - Zobrazuje podtržený text.
    - Příklad:
      ```html
      <p>Toto je <u>podtržený</u> text.</p>
      ```

20. **`<link>`**
    - Vkládá odkaz na externí zdroje (např. CSS).
    - Příklad:
      ```html
      <link rel="stylesheet" href="styl.css">
      ```


21. **`<table>`**
    - Definuje tabulku.
    - Příklad:
      ```html
      <table>
        <tr>
          <th>Nadpis 1</th>
          <th>Nadpis 2</th>
        </tr>
        <tr>
          <td>Buňka 1</td>
          <td>Buňka 2</td>
        </tr>
      </table>
      ```

22. **`<tr>`**
    - Řádek tabulky.
    - Příklad:
      ```html
      <tr>
        <td>Buňka 1</td>
        <td>Buňka 2</td>
      </tr>
      ```

23. **`<th>`**
    - Nadpisová buňka tabulky.
    - Příklad:
      ```html
      <th>Jméno</th>
      ```

24. **`<td>`**
    - Datová buňka tabulky.
    - Příklad:
      ```html
      <td>Jan</td>
      ```

25. **`<form>`**
    - Definuje formulář pro uživatelský vstup.
    - Příklad:
      ```html
      <form action="/submit" method="post">
        <input type="text" name="jmeno" placeholder="Zadejte jméno">
        <button type="submit">Odeslat</button>
      </form>
      ```

26. **`<input>`**
    - Vstupní prvek formuláře.
    - Příklad:
      ```html
      <input type="text" name="email" placeholder="Zadejte email">
      ```

27. **`<button>`**
    - Definuje tlačítko.
    - Příklad:
      ```html
      <button type="submit">Odeslat</button>
      ```

28. **`<br>`**
    - Zalomení řádku.
    - Příklad:
      ```html
      <p>První řádek.<br>Druhý řádek.</p>
      ```

29. **`<hr>`**
    - Vodorovná oddělovací čára.
    - Příklad:
      ```html
      <hr>
      ```

30. **`<script>`**
    - Obsahuje nebo odkazuje na JavaScriptový kód.
    - Příklad:
      ```html
      <script>
        alert('Ahoj světe!');
      </script>
      ```

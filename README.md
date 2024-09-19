# Parsing-data-from-txt-to-html-with-model
Vreau sa copiez datele dintr-un fisier txt intr-un fisier html, dupa modelul index.html

# Codul din oricare din cele 2 fisiere .py face urmatorul lucru:

1. Copiaza toate informatiile din fisierul bebe.txt, trecandu-le prin modelul index.html, si apoi salveaza intr-o noua pagina html in functie de titlul articolului.
2. Articolele din bebe.txt sunt despartite prin cuvantul "IDEE" urmat sau precedat de cateva ---
3. Titlurile articolelor, la fel ca si denumirea noilor fisiere html, sunt reprezentate de prima linie de sub linia care contine cuvantul -- IDEE ---

   # De exemplu:

----- IDEE 29------
Tinerii care au obținut nota 10 la examenele

in acest caz, denumirea fisierului va fi: tinerii-care-au-obtinut-nota-10-la-examenele.html

Iar <title> va fi: "Tinerii care au obținut nota 10 la examenele", adica <title>Tinerii care au obtinut nota 10 la examenele</title>

De asemenea codurile .py au si alte transformari, precum scoaterea diacriticilor si parsarea anumitor link-uri.

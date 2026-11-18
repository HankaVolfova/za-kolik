# Za kolik? — Cenová laboratoř

Výuková pomůcka předmětu Marketing (Škoda Auto Vysoká škola). Studenti v sedmi krocích stanoví cenu produktu své fiktivní firmy: z nákladů, zákaznické sondy a konkurence. Pak ověří ekonomické výsledky a stáhnou shrnutí jako PDF.

- Běží celá v prohlížeči. Nemá backend, registraci ani analytiku.
- Data se ukládají jen v prohlížeči studenta (localStorage). Mezi členy týmu se projekt předává exportem a importem souboru JSON.
- Fonty jsou uložené přímo v repozitáři, stránka nic nenačítá z cizích serverů.

## Soubory

- `index.html` — celá aplikace
- `html2pdf.bundle.min.js` — knihovna pro vytvoření PDF (html2pdf.js 0.10.2, MIT)
- `fonts/` — písma Fraunces a Plus Jakarta Sans (SIL Open Font License)

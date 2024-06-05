# Úvod
Co by měl splňovat efektivní a dobře fungující vývojový tým? Jaké jsou standardy ve středně velkém vývojovém týmu do 10 lidí, který vyvíjí velké aplikace pro nadnárodní firmy? Aplikací kolem osmdesáti.

> 🚩 Disclaimer: Tohle není finální verze a pravděpodobně nikdy nebude, příští dva měsíce se k tomu plánuji několikrát vrátit a zároveň schválit několik PR od odstatních vývojářů.

# Historie
Začátky byly šílené. Kód zálohovaný pouze na serveru a pokud na tom pracovali dva lidé, tak si to navzájem přepisovali. V šablonách podmínky na správné načtení fungující verze jQuery, protože v jednom kontroleru fungovala pouze jedna verze a v jiném jiná.

# Zk(r)oušená láska
Jakákoliv práce je strašně snadná, pokud ji milujete a baví Vás. V dlouhodobém měřítku je hrozně znát, jestli Vás třeba večer baví číst články o novinkách ve Vaší technologii a podobě. A pak ty věci dokola zkoušet, jestli něco přinesou. Není dobré být dogmatický, ale vyzkoušet co nejvíc různých alternativ.

# Obecné postupy
 - Snadno udržovatelný a robustní kód na nejnovější technologii (všechy aplikace běžící na nejnovějších verzích technologií `n-1` patch verze)
 - Společné moduly (uživatelský modul) vyčlené do samostatných celků
 - Dodržování principů usnadňující vývoj (agile, waterfall, mvc, DI)
 - Zastupitelnost a čitelný kód pro celý tým, dodržování coding standard a best-practise
 - Snadné zaškolení nováčků, vše dokumentované a žádný legacy kód (případně ošetřený unit testy)
 - DevOps přes automatizované testování, statické analýzy, reporting
 - Bezpečnost je automatická (peneterační testy, aktualizace dle CVE)

# Základy
- Zaškolení lidí, fórum, vzdělávání
- Procesy (ORM - GRUF)
- Databáze & databázová vrstva
- Messaging
  
## Balíčkovací systém
- Správa závislostí hlavně kvůli kompabilitě a průběžné aktualizaci (NPM pro věřejnou část, PHP Composer pro kód).
- Interní balíčky (například uživatelský modul, který dostává pravidelné aktualizace) v případě desítek aplikací

## IDE
- Kvalitní [IDE](https://cs.wikipedia.org/wiki/V%C3%BDvojov%C3%A9_prost%C5%99ed%C3%AD) je základ

## Verzování
- Verzování

# Vývoj
- Vývojové prostředí
- Docker
- XAMPP
- Coding standard
- Statická analýza
- Unit testy
- Profiler
- Code review
- Šablonovací systém

# Údržba
- Logování chyb
- (CI/CD)
- Health check
- Migrační příručky (rector)
  
# Bezpečnost
- CVE

# Ostatní
- AI







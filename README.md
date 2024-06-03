# Úvod
Co by měl splňovat efektivní a dobře fungující vývojový tým? Jaké jsou standardy ve středně velkém vývojovém týmu do 10 lidí, který vyvíjí velké aplikace pro nadnárodní firmy?

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

# Seznam kategorií
- Jádro (Interní balíčky)
- Zaškolení lidí
- Docker
- Vývojové prostředí
- IDE
- Coding standard
- Statická analýza (komplice)
- Health check
- CI/CD
- CVE
- Unit testy
- Verzování
- Procesy (ORM - GRUF)
- Code review
- Migrační příručky (rector)
- Databáze & databázová vrstva
- Assety (NPM)
- Školení, fórum, vzdělávání
- Láska a amatérismus
- Composer
- Profiler
- Logování chyb
- Messaging
- AI






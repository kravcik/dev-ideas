# Úvod
Co by měl splňovat efektivní a dobře fungující vývojový tým? Jaké jsou standardy ve středně velkém vývojovém týmu do 10 lidí, který vyvíjí velký počet (vyšší desítky) aplikací také pro nadnárodní firmy? 

Je to hodně široké téma a abstrahovat deset let do několika odrážek není snadné, každý bod bych rád následně rozpracoval do článku.

> 🚩 Disclaimer: Tohle není finální verze a pravděpodobně nikdy nebude, příští dva měsíce se k tomu plánuji několikrát vrátit a zároveň schválit několik PR od odstatních vývojářů.

# Historie
Šílené začátky. Kód zálohovaný pouze na FTP serveru a pokud na tom pracovali dva lidé, tak si to navzájem přepisovali. V šablonách podmínky na správné načtení fungující verze jQuery, protože v jednom kontroleru fungovala pouze jedna verze a v jiném jiná. Jeden obrovský presenter (controller), který měl přes deset tisíc řádků. Verzování ani zálohování neexistovalo.

# Zk(r)oušená láska
Jakákoliv práce je strašně snadná, pokud ji milujete a baví Vás. V dlouhodobém měřítku je velmi znát, jestli Vás třeba večer baví číst články o novinkách ve Vaší technologii. A pak ty věci dokola zkoušet, jestli něco přinesou. Není dobré být dogmatický, ale vyzkoušet co nejvíc různých alternativ a vybrat to, co se pro Vás hodí nejlépe.

# Obecné postupy
 - Snadno udržovatelný a robustní kód na nejnovější technologii
 - Společné moduly vyčlené do samostatných celků spravované přes privátní balíčky
 - Dodržování principů usnadňující vývoj (agile, scrum, waterfall, MVC, DI)
 - Zastupitelnost a čitelný kód pro celý tým, dodržování coding standard a best-practise
 - Snadné zaškolení nováčků, vše dokumentované a ošetřený unit testy
 - DevOps přes automatizované testování, statické analýzy, reporting
 - Bezpečnost je automatická (peneterační testy, aktualizace dle CVE)

# Základy
- Zaškolení lidí, fórum, vzdělávání
- Ticketovací systém
- Procesy (ORM - GRUF)
- Databáze & databázová vrstva
- Messaging
  
#### Balíčkovací systém
- Správa závislostí hlavně kvůli kompabilitě a průběžné aktualizaci (NPM pro věřejnou část, PHP Composer pro kód).
- Interní balíčky (například uživatelský modul, který dostává pravidelné aktualizace) v případě desítek aplikací

#### IDE
- Kvalitní [IDE](https://cs.wikipedia.org/wiki/V%C3%BDvojov%C3%A9_prost%C5%99ed%C3%AD) je základ

#### Verzování
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
- Nejnovější technologie
  
# Bezpečnost
- CVE
- Šifrování dat

# Ostatní
- AI
- 







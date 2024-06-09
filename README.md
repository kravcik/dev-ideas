# Úvod
Co by měl splňovat efektivní a dobře fungující tým vývojářů? Jaké jsou standardy ve středně velkém týmu (do 10 lidí), který vyvíjí vyšší desítky aplikací? Jaká je nutná úroveň také pro nadnárodní firmy? 

Je to hodně široké téma a abstrahovat patnáct let zkušeností do několika odrážek není snadné, každý bod bych rád následně rozpracoval do článku.

> 🚩 Disclaimer: Tohle není finální verze a pravděpodobně nikdy nebude, příští dva měsíce se k tomu plánuji několikrát vrátit a zároveň schválit několik nápadů (PR vítány) od odstatních vývojářů.

# Historie
Začátky byly punk, ale dnes máme špičkově nastavené automatizované procesy. Kód byl zálohovaný pouze na FTP serveru a pokud na něm pracovali dva lidé, tak si jej navzájem přepisovali. V šablonách podmínky pro správné načtení fungující verze jQuery, protože v jednom kontroleru fungovala pouze jedna verze a v jiném jiná. Jeden obrovský presenter (controller), který měl přes deset tisíc řádků. Verzování ani zálohování neexistovalo.

# Zk(r)oušená láska
Jakákoliv práce je strašně snadná, pokud ji milujete a baví Vás. V dlouhodobém měřítku je velmi znát, jestli Vás třeba večer baví číst články o novinkách ve Vaší technologii. A pak ty věci dokola zkoušet, jestli něco přinesou. Není dobré být dogmatický, ale vyzkoušet co nejvíc různých alternativ a vybrat tu, co se pro Vás hodí nejlépe.

# Obecné postupy
 - Snadno udržovatelný a robustní kód na nejnovější možné technologii
 - Společné moduly vyčleněné do samostatných celků spravované přes privátní balíčky
 - Dodržování principů usnadňujících vývoj (agile, scrum, waterfall, MVC, DI)
 - Zastupitelnost a čitelný kód pro celý tým, dodržování coding standard a best-practise
 - Snadné zaškolení nováčků, vše dokumentované a ošetřené unit testy
 - DevOps přes automatizované testování, statické analýzy, reporting
 - Bezpečnost je automatická (peneterační testy, aktualizace dle CVE)

> ⬇️ A níže záčíná ta pravá džungle, která by to měla obsáhnout a vysvětlit těch pár vět výše

# Základy
- Zaškolení lidí, fórum, (samo)vzdělávání
- Řízení vývoje, ticketovací systém
- Procesy (ORM - GRUF)
- Vrstvy aplikace (databáze apod.)
  
#### Balíčkovací systém
- Správa závislostí hlavně kvůli kompatibilitě a průběžné aktualizaci (NPM pro věřejnou část, PHP Composer pro kód).
- Interní balíčky (například uživatelský modul, který dostává pravidelné aktualizace) v případě desítek aplikací
- Kvalitní IDE
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
- Rozdělení configů (local, server, config)
- Validace uživatelských vstupů
- Správa rolí

# Ostatní
- AI
- Open source
- Fórum a články
- Messaging
- Vytvoření projektu - composeru otázky a nastavování projektu






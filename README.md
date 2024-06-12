# Úvod
Co by měl splňovat efektivní a dobře fungující vývojový tým? Jaké jsou standardy ve středně velkého týmu (do 10 lidí), který vyvíjí vyšší desítky aplikací? Jaká je nutná úroveň také pro nadnárodní firmy? 

Je to hodně široké téma a abstrahovat patnáct let zkušeností do několika odrážek není snadné, každý bod bych rád následně rozpracoval do článku.

> 🚩 Disclaimer: Tohle není finální verze a pravděpodobně nikdy nebude, příští dva měsíce se k tomu plánuji několikrát vrátit a zároveň schválit několik nápadů (PR vítány) od odstatních vývojářů.

# Historie
Začátky byly punk, ale dnes máme špičkově nastavené automatizované procesy. Kód byl zálohovaný pouze na FTP serveru a pokud na tom pracovali dva lidé, tak si to navzájem přepisovali. V šablonách podmínky na správné načtení fungující verze jQuery, protože v jednom kontroleru fungovala pouze jedna verze a v jiném jiná. Jeden obrovský presenter (controller), který měl přes deset tisíc řádků. Verzování ani zálohování neexistovalo.

# Zk(r)oušená láska
Jakákoliv práce je strašně snadná, pokud ji milujete a baví Vás. V dlouhodobém měřítku je velmi znát, jestli Vás třeba večer baví číst články o novinkách ve Vaší technologii. A pak ty věci dokola zkoušet, jestli něco přinesou. Není dobré být dogmatický, ale vyzkoušet co nejvíc různých alternativ a vybrat to, co se pro Vás hodí nejlépe.

# Obecné postupy
 - Snadno udržovatelný a robustní kód na nejnovější možné technologii
 - Společné moduly vyčlené do samostatných celků spravované přes privátní balíčky (KISS, DRY)
 - Dodržování principů usnadňující vývoj (agile, scrum, waterfall, rozdělení rolí aka odstínění programátorů od bussiness logiky)
 - Zastupitelnost a čitelný kód pro celý tým, dodržování coding standard
 - Snadné zaškolení nováčků (list co musí zaškolený člověk splňovat pod době X), vše dokumentované a ošetřené unit testy
 - DevOps přes automatizované testování, statické analýzy, reporting
 - Bezpečnost! (peneterační testy, CVE, aktualizace balíčků, správa serverů je u nás externí)

> ⬇️ A níže záčíná ta pravá džungle, která by to měla obsáhnout a vysvětlit těch pár vět výše

# Základy
- (Samo)zaškolení lidí, fórum, vzdělávání, zdravý kolektiv
- Řízení vývoje, ticketovací systém
- Procesy (ORM, GRUF aka CRUD s Grido a Formulářem - nadstavba zrychlující vývoj)
- Vrstvy aplikace (databáze apod.)
  
#### Balíčkovací systém
- Správa závislostí hlavně kvůli kompabilitě a průběžné aktualizaci (NPM pro věřejnou část, PHP Composer pro kód).
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

# Ostatní
- AI
- Open source
- Fórum a články
- Message broker (RabbitMQ)
- Vytvoření projektu - (cmd provede základní vytvořením projektu - chcete crony, rabbity "press yes")






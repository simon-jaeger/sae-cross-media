- Installiere einen lokalen PHP-Server: https://www.mamp.info
- Nimm bei der Installation den Hacken bei MAMP PRO weg – die Standardversion genügt.
- Lege eine Datei `index.php` in deinem Root an (Windows: `C:/MAMP/htdocs/index.php` Mac: `Applications/MAMP/htdocs/index.php`)
- Schreibe folgenden Inhalt in die Datei: `<?php phpinfo();`
- Starte MAMP und öffne deine Website, in dem du mit dem Browser auf die
  URL `localhost` navigierst. (Bei Mac `localhost:8888`)
- Leider bietet MAMP keinen Live-Reload. Als Alternative kannst du die
  Chrome-Extension [Auto Refresh Plus](https://autorefresh.io/) verwenden.

![](mamp.png)

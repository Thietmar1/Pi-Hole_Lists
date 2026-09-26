# Pi-Hole Lists
Hier sind meine Pi-Hole Listen zu finden. Diese werden nur ab und zu gepflegt. Nutzt zum Blockieren von Werbung, Tracker, Malware und betrügerischen Webseiten lieber andere :)

Here you can find my Pi-Hole lists. These are maintained only from time to time. For blocking ads, trackers, malware and fraudulent websites, please use others :)

## Technitium (Advanced Blocking)
`Technitium-Allowed.json` enthält die Allow-List im Format der Advanced-Blocking-App (`allowed` / `allowedRegex`). Die beiden Arrays in die gewünschte Gruppe der App-Config übernehmen.
Hinweis: Technitium erlaubt bei `allowed` auch alle Subdomains. Domains wie `google.com` stehen deshalb als exakte Regex in `allowedRegex`.

`Technitium-Allowed.json` contains the allow list in the Advanced Blocking app format (`allowed` / `allowedRegex`). Copy both arrays into the desired group of the app config.
Note: Technitium's `allowed` also allows all subdomains, so domains like `google.com` are listed as exact regex in `allowedRegex`.

# How To

## Was ist der Sinn von dem Prompt?

Das Ziel ist es unabhängig der Webseite eine Zusammenfassung des Artikels zu erhalten.
Der Fokus liegt hauptsächlich auf Ransomware News Artikel und kann bei Bedarf abgewandelt werden.


## Wie benutzt man den Prompt?

Zuerst kopiert ihr den kompletten Prompt und fügt diesen in ChatGPT oder vergleichbar ein. Im Anschluss kopiert man den kompletten Artikel inkl. Werbung, Impressum usw. und fügt diesen am Ende des Prompts ein und sendet dann die Anfrage ab.

Ich empfehle die Bezahlvariante zu verwenden oder ChatGPT 4o, wenn es für alle kostenfrei zur Verfügung steht.
Lokale LLMs habe ich nicht getestet dürften aber auch problemlos funktionieren. Abhängig der verwendeten AI/LLM kann es sein, dass man den Prompt anpassen muss.

## Beispiel

zu analysierender Text:
https://www.bleepingcomputer.com/news/security/teamviewers-corporate-network-was-breached-in-alleged-apt-hack/

Ergebnis mit ChatGPT 4o

```JSON
{
  "Datum-des-Vorfalls": "26-06-2024",
  "Überschrift": "TeamViewer Netzwerkkompromittierung durch APT-Gruppe",
  "Angriffsart": "APT Angriff",
  "Schwachstelle": "n/a",
  "Angreifer": "Midnight Blizzard",
  "Angreifer-Herkunft": "Russland",
  "Name-des-Ziels": "TeamViewer",
  "Ziel/Industrie": "Software",
  "Art-des-Ziels": "Firma",
  "Größe-des-Ziels": "640000 Kunden",
  "business-impact": "mittel",
  "Anzahl-kompromittierter-Accounts": "n/a",
  "Beschreibung-business-impact": "Keine Kundendaten betroffen, interne IT-Systeme beeinträchtigt",
  "gestörte-Arbeitsbereiche": "Interne IT-Systeme",
  "Handlungsempfehlungen": "Überprüfung der Remote-Desktop-Protokolle auf ungewöhnliche Aktivitäten; Implementierung von erweiterten Überwachungs- und Detektionssystemen",
  "Zusammenfassung-des-Artikels": "TeamViewer meldete am 26. Juni 2024 eine Kompromittierung seines internen IT-Netzwerks durch die russische staatlich unterstützte Hackergruppe Midnight Blizzard. Es gibt keine Hinweise darauf, dass das Produktumfeld oder Kundendaten betroffen sind. Die Untersuchungen dauern an, und das Unternehmen konzentriert sich auf die Sicherung der Systemintegrität. Ein IT-Sicherheitsprofi berichtete zuerst über den Vorfall, und verschiedene Sicherheitsunternehmen haben vor der Ausnutzung von TeamViewer durch die Hackergruppe APT29 gewarnt."
}
```





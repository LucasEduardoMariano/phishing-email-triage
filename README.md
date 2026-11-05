# Phishing Email Triage and Investigation

## Overview

This project documents a basic phishing email triage and investigation conducted using a fictional email impersonating Microsoft Account Security.

The investigation examines sender information, email content, suspicious URLs, potential domain impersonation, and social engineering techniques. It also evaluates the potential security risks associated with the message and documents the limitations of the analysis.

The goal was to identify suspicious indicators, collect relevant evidence, assess the potential threat, and produce a structured investigation report without interacting with external websites or potentially malicious resources.

## Objectives

- Examine sender information and identify potential domain impersonation.
- Analyse email content and identify suspicious characteristics.
- Identify potentially malicious URLs and assess associated security concerns.
- Recognise social engineering techniques, including urgency and fear-based manipulation.
- Evaluate the potential security risks associated with the email.
- Document relevant evidence and investigation findings.
- Provide appropriate security recommendations.
- Communicate conclusions and limitations through evidence-based reporting.

## Tools and Technologies

- Windows PowerShell
- PowerShell `Select-String`
- Manual email inspection
- Phishing indicator analysis
- Social engineering analysis
- Security risk assessment
- Markdown documentation

## Project Structure

| File | Description |
|---|---|
| `sample_email.txt` | Contains the fictional suspicious email used as the investigation sample. |
| `investigation_report.md` | Documents the investigation methodology, identified indicators, technical analysis, risk assessment, and security recommendations. |
| `README.md` | Contains project documentation and an overview of the investigation. |

## Investigation and Key Findings

### Sender Analysis

The sender address was identified as `security@micr0soft-support.example`.

The domain contains a zero instead of the letter "o" in the word "Microsoft". This is a lookalike domain characteristic commonly associated with brand impersonation and phishing attempts.

The sender information was considered suspicious and inconsistent with an official Microsoft communication.

### Email Content Analysis

The email used a generic greeting and claimed that unusual activity had been detected on the recipient's Microsoft 365 account.

It threatened account suspension within 24 hours unless the recipient completed an immediate identity verification process.

This language was identified as an example of urgency-based social engineering, intended to pressure the recipient into taking action without independently verifying the message.

### URL Analysis

The email contained the following external verification URL:

`http://micr0soft-verification.example/secure-login`

The URL uses a lookalike domain and the HTTP protocol, which does not encrypt communication between the browser and the website.

The destination was not accessed or tested. Therefore, its actual behaviour and legitimacy were not independently verified.

### Security Assessment

The combination of a suspicious sender domain, brand impersonation, an external verification link, and urgency-based language indicates a likely phishing attempt.

**Classification:** Likely Phishing

**Risk Level:** High

If a recipient followed the link and submitted their credentials, those credentials could potentially be exposed.

However, no actual malicious activity, credential theft, or account compromise was established during this investigation.

## Limitations

The investigation was based exclusively on the content of a fictional email created for educational purposes.

Original email headers were not available. Consequently, SPF, DKIM, and DMARC authentication results could not be examined, and the sender's actual identity could not be verified.

No live URLs or external domains were accessed. Domain ownership, website behaviour, and actual malicious activity were therefore not investigated.

The PowerShell analysis was limited to searching the email text for predefined indicators. It was not a dedicated email forensic tool, automated phishing detection system, or malware analysis solution.

The final assessment represents an evidence-based evaluation of the available email content rather than confirmation of a real phishing campaign.

## Skills Demonstrated

- Phishing email triage
- Email content analysis
- Sender and domain inspection
- Identification of lookalike domains
- Suspicious URL analysis
- Social engineering identification
- Basic PowerShell text analysis
- Evidence collection and documentation
- Security risk assessment
- Security recommendations
- Technical reporting

## Disclaimer

This project was conducted using a fictional email created exclusively for educational purposes. No real organisation, employee account, or external website was investigated.

No suspicious links were accessed, no credentials were submitted, and no unauthorised activity was performed.

---

# Phishingmailanalyse en onderzoek

## Overzicht

Dit project beschrijft een basisanalyse en onderzoek van een mogelijke phishingmail aan de hand van een fictief bericht dat zich voordoet als een officiële beveiligingsmelding van Microsoft Account Security.

Het onderzoek richt zich op de gegevens van de afzender, de inhoud van de e-mail, verdachte URL's, mogelijke domeinimitatie en technieken van social engineering. Daarnaast worden de mogelijke beveiligingsrisico's van het bericht beoordeeld en de beperkingen van de analyse gedocumenteerd.

Het doel was om verdachte indicatoren te herkennen, relevante bewijzen te verzamelen, de mogelijke dreiging in te schatten en een gestructureerd onderzoeksrapport op te stellen zonder externe websites of mogelijk schadelijke bronnen te bezoeken.

## Doelstellingen

- De gegevens van de afzender onderzoeken en mogelijke domeinimitatie herkennen.
- De inhoud van de e-mail analyseren en verdachte kenmerken identificeren.
- Mogelijk schadelijke URL's identificeren en de bijbehorende beveiligingsrisico's beoordelen.
- Technieken van social engineering herkennen, waaronder tijdsdruk en manipulatie door angst.
- De mogelijke beveiligingsrisico's van de e-mail inschatten.
- Relevante bewijzen en onderzoeksresultaten documenteren.
- Passende beveiligingsaanbevelingen formuleren.
- Conclusies en beperkingen onderbouwen met concrete bevindingen.

## Gebruikte tools en technologieën

- Windows PowerShell
- PowerShell `Select-String`
- Handmatige e-mailanalyse
- Analyse van phishing-indicatoren
- Analyse van social engineering
- Beoordeling van beveiligingsrisico's
- Markdown-documentatie

## Projectstructuur

| Bestand | Beschrijving |
|---|---|
| `sample_email.txt` | Bevat de fictieve verdachte e-mail die als onderzoeksmateriaal werd gebruikt. |
| `investigation_report.md` | Bevat de onderzoeksmethode, vastgestelde indicatoren, technische analyse, risicobeoordeling en beveiligingsaanbevelingen. |
| `README.md` | Bevat de projectdocumentatie en een overzicht van het onderzoek. |

## Onderzoek en belangrijkste bevindingen

### Analyse van de afzender

Het e-mailadres van de afzender werd geïdentificeerd als `security@micr0soft-support.example`.

Het domein bevat het cijfer nul in plaats van de letter "o" in het woord "Microsoft". Dit is een kenmerk van een misleidend domein dat kan worden gebruikt om een merk na te bootsen bij phishingpogingen.

De gegevens van de afzender werden als verdacht beschouwd en waren niet consistent met een officiële communicatie van Microsoft.

### Analyse van de e-mailinhoud

De e-mail gebruikte een algemene aanspreking en beweerde dat er verdachte activiteit was vastgesteld op het Microsoft 365-account van de ontvanger.

Er werd gedreigd met de opschorting van het account binnen 24 uur, tenzij de ontvanger onmiddellijk zijn identiteit zou verifiëren.

Dit taalgebruik werd geïdentificeerd als een voorbeeld van social engineering waarbij tijdsdruk wordt gecreëerd. Het doel hiervan is om de ontvanger onder druk te zetten zodat die actie onderneemt zonder het bericht eerst onafhankelijk te controleren.

### URL-analyse

De e-mail bevatte de volgende externe verificatielink:

`http://micr0soft-verification.example/secure-login`

De URL gebruikt een misleidend domein en het HTTP-protocol, dat de communicatie tussen de browser en de website niet versleutelt.

De bestemming werd niet bezocht of getest. Daardoor werden het werkelijke gedrag en de legitimiteit van de website niet onafhankelijk gecontroleerd.

### Beveiligingsbeoordeling

De combinatie van een verdacht afzenderdomein, merkimitatie, een externe verificatielink en taalgebruik dat tijdsdruk creëert, wijst op een waarschijnlijke phishingpoging.

**Classificatie:** Waarschijnlijk phishing

**Risiconiveau:** Hoog

Als een ontvanger de link zou openen en zijn inloggegevens zou invoeren, zouden deze gegevens mogelijk kunnen worden buitgemaakt.

Tijdens dit onderzoek werd echter geen daadwerkelijke kwaadaardige activiteit, diefstal van inloggegevens of compromittering van een account vastgesteld.

## Beperkingen

Het onderzoek was uitsluitend gebaseerd op de inhoud van een fictieve e-mail die voor educatieve doeleinden werd opgesteld.

De oorspronkelijke e-mailheaders waren niet beschikbaar. Daardoor konden de SPF-, DKIM- en DMARC-authenticatieresultaten niet worden onderzocht en kon de werkelijke identiteit van de afzender niet worden geverifieerd.

Er werden geen echte URL's of externe domeinen bezocht. Het domeineigenaarschap, het gedrag van de website en eventuele daadwerkelijke kwaadaardige activiteiten werden bijgevolg niet onderzocht.

De PowerShell-analyse was beperkt tot het doorzoeken van de e-mailtekst naar vooraf bepaalde indicatoren. Het was geen gespecialiseerde tool voor e-mailforensisch onderzoek, een geautomatiseerd phishingdetectiesysteem of een oplossing voor malwareanalyse.

De eindbeoordeling is een onderbouwde evaluatie van de beschikbare e-mailinhoud en vormt geen bevestiging van een echte phishingcampagne.

## Aangetoonde vaardigheden

- Phishingmails analyseren en beoordelen
- Analyse van e-mailinhoud
- Controle van afzendergegevens en domeinen
- Herkennen van misleidende domeinen
- Analyse van verdachte URL's
- Herkennen van social engineering
- Basisanalyse van tekst met PowerShell
- Bewijsmateriaal verzamelen en documenteren
- Beoordeling van beveiligingsrisico's
- Formuleren van beveiligingsaanbevelingen
- Technische rapportage

## Disclaimer

Dit project werd uitgevoerd met behulp van een fictieve e-mail die uitsluitend voor educatieve doeleinden werd opgesteld. Er werd geen echte organisatie, werknemersaccount of externe website onderzocht.

Er werden geen verdachte links geopend, geen inloggegevens ingevoerd en geen ongeautoriseerde activiteiten uitgevoerd.

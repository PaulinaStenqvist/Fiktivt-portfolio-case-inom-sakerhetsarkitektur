SveaCare – Säkerhetsarkitektur & Resiliens

Fiktivt portfolio-case inom säkerhetsarkitektur

Ett arkitekturcase där jag designar en säker och motståndskraftig vårdmiljö – från verksamhetens behov och risker till målarkitektur, arkitekturbeslut, implementationsplan och validering.

Case overview

SveaCare är en fiktiv vårdorganisation som hanterar känslig patientinformation genom kliniska applikationer, diagnostiksystem, identitetstjänster, databaser, backupinfrastruktur och tredjepartsintegrationer.

Den centrala arkitekturfrågan är:

> Hur kan systemen förbli tillräckligt sammankopplade för att stödja vårdverksamheten, utan att ett komprometterat konto eller system kan slå ut hela miljön?

Mitt angreppssätt

Jag utgår från verksamhetens behov, risker och krav och arbetar därefter fram tekniska lösningar.

Arbetet omfattar bland annat:

* Zero Trust som övergripande designprincip
* STRIDE-baserad hotmodellering
* Riskanalys och riskmatris
* Identitets- och åtkomstarkitektur
* RBAC och least privilege
* Nätverkssegmentering
* Backup- och återställningsarkitektur
* Loggning och incidenthantering
* Architecture Decision Records (ADR)
* Implementationsroadmap
* Säkerhetstestning och validering

Centrala arkitekturbeslut

Separata privilegierade konton
Administrativt arbete separeras från normalt användararbete.

Nätverkssegmentering
Miljön delas upp i zoner för att begränsa lateral förflyttning och blast radius.

Isolerad backup
Backup separeras administrativt från produktion och skyddas med starkare återställningsbarriärer.

Resultat

Caset resulterar i en målarkitektur, riskregister, fem Architecture Decision Records, resiliens- och återställningsstrategi, testplan samt en principiell 12-månaders implementationsplan.

https://github.com/PaulinaStenqvist/Fiktivt-portfolio-case-inom-sakerhetsarkitektur/blob/main/SveaCare-Security-Architecture-Case.pdf

Case study
Detta är ett fiktivt portfolio-case. Antaganden och exempelvärden är tydligt separerade från sådant som skulle behöva verifieras i en verklig miljö.


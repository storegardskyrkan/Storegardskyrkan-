# Storegårdskyrkan

## Målarkitektur

Outlook-kalender
(webbkalender@storegardskyrkan.se)

↓

Microsoft Graph

↓

GitHub Action

↓

events.json

↓

kalender.html

↓

storegardskyrkan.se

---

## Verifierat

✅ kalender.html läser events.json

✅ GitHub Actions fungerar

✅ Microsoft Graph fungerar

✅ Graph kan läsa användarkalendrar

✅ Outlook-kategorier kan användas för filtrering

---

## Ej lämpligt

❌ Microsoft 365-gruppkalender

Anledning:
Graph App Permissions kan läsa gruppen,
men gruppens kalenderhändelser gav AccessDenied.

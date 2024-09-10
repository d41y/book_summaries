# Real-World Bug Hunting

## Bug Bounty Basics

*In diesem Kapitel wird es um die basic Begriffe im Kontext von Bug Bounties und um die einfache Funktionen und Arbeitsschritte, die beim Aufruf einer Website stattfinden.*

__Keylearnings__

- GET Request auf '/' -> Root-Verzeichnis der Website
- MIME Sniffing durch Browser, um den Medientyp zu bestimmen (bspw. text/html)
    - kann durch den header 'X-Content-Type-Options:nosniff' verhindert werden
- DOM (document object model) ermöglicht es, mit Hilfe von JS den HTML- und CSS-Code der Website zu manipulieren
- HTTP ist stateless, also jede Anfrage wird wie eine komplett neue Anfrage behandelt
    - um Probleme, die damit einhergehen (jedes mal neu anmelden) zu vermeiden -> bspw. Cookies

## HTTP Parameter Pollution

__Keylearnings__

## CSRF

__Keylearnings__


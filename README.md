# FlexiDesk - Office Resource Management System

## O projekcie
FlexiDesk to nowoczesna platforma typu SaaS zaprojektowana dla zespołów pracujących w trybie hybrydowym. Rozwiązanie oferuje uproszczony proces rezerwacji miejsc pracy w tym biurek, sal konferencyjnych. Projekt łączy lekkość nowoczesnych narzędzi webowych z architekturą klasy korporacyjnej, zapewniając wydajność, skalowalność i bezpieczeństwo.

## Problem i rozwiązanie
Wiele systemów rezerwacji jest skomplikowanych, nieintuicyjnych i "ciężkich". Może to prowadzić do unikania takich narzędzi przez pracowników. FlexiDesk zapewnia:
- **Szybkie rezerwacje** Rezerwacja powinna być prosta i zająć maksymalnie 30 sekund.
- **Zarządzanie rezerwacjami "widmo"** Przy rezerwacji sali/biurka i braku potwierdzenia rezerwacji za pomocą skanu kodu qr lub hasła w określonym czasie od rozpoczęcia godziny rezerwacji, system automatycznie odwoła rezerwację.
- **Uprawnienia użytkowników** Osoby z odpowiednimi uprawnieniami mają przydzielone typy rezerwacji, które mogą wykonywać.
- **Wysoką wydajność i responsywność** System jest w stanie przetworzyć jednocześnie wiele rezerwacji w tym samym czasie i zarządzać "kolizjami".

## Repozytorium zawiera:
- **Elementy Analizy Biznesowej** w tym katalog Business_Discovery zawierający opis problemu, wymagania, profil psychologiczny użytkownika oraz analizę rynku.
- **Diagramy** w tym katalogi Process_Modeling_BPMN, zawierający procesy biznesowe oraz System_Architecture_UML, zawierający diagramy architektury systemu.
- **Projekt UI** w tym mockupy, w tym prosty kod oraz symulację ruchu użytkownika wraz z badaniami i refleksjami.

## Technologie (Planowane/Użyte)
- **Analiza:** BPMN 2.0, UML, User Stories
- **Baza danych:** Oracle SQL
- **Backend:** Java 17, Spring Boot
- **Frontend:** React

## Wykorzystane narzędzia
- **Visual Paradigm Community Edition**
- **Camuda Modeler**
- **DataGrip**
- **Docker**
- **dbdiagram.io** - https://dbdiagram.io

## Uwagi
System rezerwacji został wykonany w ramach projektu ćwiczeniowego. Nazwa systemu została wygenerowana przez sztuczną inteligencję (chatGPT model 5.2). Zbieżności w nazwie systemu są przypadkowe.

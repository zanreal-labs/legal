---
title: Oświadczenie o Zastosowaniu (SoA)
description: Oświadczenie o Zastosowaniu ZanReal definiujące zakres Systemu Zarządzania Bezpieczeństwem Informacji i zastosowanie kontroli ISO 27001/27002
categories: [iso27001, iso27002, isms, security-controls, compliance, risk-management, audit]
---

ZanReal ("ZanReal", "my", "nas" lub "nasze") ustanowiło niniejsze Oświadczenie o Zastosowaniu (SoA) jako część naszego Systemu Zarządzania Bezpieczeństwem Informacji (ISMS) w celu zdefiniowania zakresu naszych kontroli bezpieczeństwa informacji i ich zastosowania do naszych operacji biznesowych.

Niniejsze Oświadczenie o Zastosowaniu jest wyrównane z ISO/IEC 27001:2022 i odnosi się do kontroli bezpieczeństwa z ISO/IEC 27002:2022.

## Zakres ISMS

### Zakres Organizacyjny

- **Firma**: ZanReal - ZANREAL Mateusz Janota
- **Działalność Biznesowa**: Kompleksowe usługi technologiczne obejmujące rozwój oprogramowania, usługi marketingowe, zdalne wsparcie IT, optymalizację SEO, usługi projektowe UI/UX, platformy chmurowe i rozwiązania oparte na AI
- **Zasięg Geograficzny**: Operacje globalne z rozproszoną siłą roboczą
- **Środowisko Regulacyjne**: RODO, CCPA, PIPEDA, SOX, HIPAA (gdzie dotyczy)

### Zakres Techniczny

- Cała infrastruktura chmurowa (AWS, Microsoft Azure, Google Cloud Platform)
- Wszystkie aplikacje i platformy skierowane do klientów
- Wszystkie systemy wewnętrzne i sieci
- Wszystkie systemy przetwarzania i przechowywania danych
- Wszystkie integracje i usługi stron trzecich
- Wszystkie aktywa fizyczne i wirtualne

### Wykluczone z Zakresu

- Bezpieczeństwo fizyczne centrów danych stron trzecich (zarządzane przez dostawców chmurowych)
- Infrastruktura i aplikacje zarządzane przez klientów
- Bezpieczeństwo wewnętrzne dostawców stron trzecich (pokryte przez oceny dostawców)

---

## Zastosowanie Kontroli ISO 27002:2022

### 5. Kontrole Organizacyjne

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 5.1 | Polityki bezpieczeństwa informacji | ✅ Zastosowane | Implementowana kompleksowa Polityka Bezpieczeństwa Informacji |
| 5.2 | Role i odpowiedzialności bezpieczeństwa informacji | ✅ Zastosowane | Zdefiniowane w sekcji 3 Polityki Bezpieczeństwa Informacji |
| 5.3 | Separacja obowiązków | ✅ Zastosowane | Implementowane przez kontrolę dostępu opartą na rolach |
| 5.4 | Odpowiedzialności zarządzania | ✅ Zastosowane | Ustanowiony nadzór wykonawczy i rozliczalność |
| 5.5 | Kontakt z władzami | ✅ Zastosowane | Procedury odpowiedzi na incydenty obejmują powiadamianie władz |
| 5.6 | Kontakt z grupami specjalnego zainteresowania | ✅ Zastosowane | Zaangażowanie społeczności bezpieczeństwa i inteligencja zagrożeń |
| 5.7 | Inteligencja zagrożeń | ✅ Zastosowane | Wazuh SIEM i zewnętrzne źródła zagrożeń implementowane |
| 5.8 | Bezpieczeństwo informacji w zarządzaniu projektami | ✅ Zastosowane | Security by design w cyklu życia rozwoju |

### 6. Kontrole Ludzkie

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 6.1 | Polityki i procedury w zakresie zasobów ludzkich | ✅ Zastosowane | Polityki HR obejmujące bezpieczeństwo informacji |
| 6.2 | Weryfikacja tła | ✅ Zastosowane | Procesy weryfikacji dla nowych pracowników |
| 6.3 | Warunki zatrudnienia | ✅ Zastosowane | Umowy zawierające klauzule bezpieczeństwa |
| 6.4 | Odpowiedzialności i dyscyplina | ✅ Zastosowane | Zdefiniowane odpowiedzialności i procedury dyscyplinarne |
| 6.5 | Zarządzanie dostępem | ✅ Zastosowane | Kontrola dostępu oparta na rolach |
| 6.6 | Szkolenia i świadomość | ✅ Zastosowane | Programy szkoleń bezpieczeństwa dla wszystkich pracowników |
| 6.7 | Procedury dyscyplinarne | ✅ Zastosowane | Procedury dla naruszeń bezpieczeństwa |
| 6.8 | Zakończenie zatrudnienia | ✅ Zastosowane | Procedury zwrotu aktywów i anulowania dostępu |

### 7. Kontrole Fizyczne

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 7.1 | Bezpieczeństwo fizyczne | ✅ Zastosowane | Kontrola dostępu fizycznego do biur i serwerowni |
| 7.2 | Sprzęt | ✅ Zastosowane | Zabezpieczenie sprzętu IT i urządzeń |
| 7.3 | Bezpieczeństwo środowiskowe | ✅ Zastosowane | Kontrola środowiska dla sprzętu IT |
| 7.4 | Bezpieczeństwo zasilania | ✅ Zastosowane | Systemy UPS i generatory awaryjne |
| 7.5 | Bezpieczeństwo kabli | ✅ Zastosowane | Zabezpieczenie okablowania sieciowego |
| 7.6 | Konserwacja sprzętu | ✅ Zastosowane | Procedury konserwacji i serwisu |
| 7.7 | Bezpieczne usuwanie sprzętu | ✅ Zastosowane | Procedury bezpiecznego usuwania sprzętu |

### 8. Kontrole Technologiczne

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 8.1 | Zarządzanie konfiguracją | ✅ Zastosowane | Zarządzanie konfiguracją systemów i aplikacji |
| 8.2 | Zarządzanie lukami w zabezpieczeniach | ✅ Zastosowane | Nessus Professional do skanowania luk |
| 8.3 | Zarządzanie oprogramowaniem | ✅ Zastosowane | Kontrola instalacji i aktualizacji oprogramowania |
| 8.4 | Zarządzanie dostępem | ✅ Zastosowane | Kontrola dostępu oparta na rolach i MFA |
| 8.5 | Uwierzytelnianie | ✅ Zastosowane | Wieloskładnikowe uwierzytelnianie dla systemów krytycznych |
| 8.6 | Autoryzacja | ✅ Zastosowane | Kontrola dostępu oparta na rolach |
| 8.7 | Zarządzanie tożsamością | ✅ Zastosowane | Centralne zarządzanie tożsamościami |
| 8.8 | Informacje o dostępie | ✅ Zastosowane | Dokumentacja i monitorowanie dostępu |

### 9. Kontrole Bezpieczeństwa Aplikacji

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 9.1 | Bezpieczeństwo aplikacji | ✅ Zastosowane | Security by design w procesie rozwoju |
| 9.2 | Zarządzanie kodem źródłowym | ✅ Zastosowane | Kontrola wersji i przeglądy kodu |
| 9.3 | Testowanie bezpieczeństwa | ✅ Zastosowane | Testy bezpieczeństwa aplikacji |
| 9.4 | Zarządzanie danymi | ✅ Zastosowane | Ochrona danych w aplikacjach |
| 9.5 | Zarządzanie sesjami | ✅ Zastosowane | Bezpieczne zarządzanie sesjami użytkowników |
| 9.6 | Zarządzanie błędami | ✅ Zastosowane | Obsługa błędów w aplikacjach |
| 9.7 | Zarządzanie logami | ✅ Zastosowane | Logowanie zdarzeń aplikacji |

### 10. Kontrole Bezpieczeństwa Sieci

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 10.1 | Architektura sieciowa | ✅ Zastosowane | Segmentacja sieci i architektura zero trust |
| 10.2 | Kontrola dostępu do sieci | ✅ Zastosowane | Zapory ogniowe i kontrola dostępu |
| 10.3 | Bezpieczeństwo usług sieciowych | ✅ Zastosowane | Zabezpieczenie usług sieciowych |
| 10.4 | Szyfrowanie | ✅ Zastosowane | Szyfrowanie danych w tranzycie i spoczynku |
| 10.5 | Zarządzanie kluczami | ✅ Zastosowane | Bezpieczne zarządzanie kluczami kryptograficznymi |
| 10.6 | Zarządzanie certyfikatami | ✅ Zastosowane | Zarządzanie certyfikatami SSL/TLS |
| 10.7 | Bezpieczeństwo komunikacji | ✅ Zastosowane | Bezpieczna komunikacja między systemami |

### 11. Kontrole Bezpieczeństwa Systemów

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 11.1 | Bezpieczeństwo systemów | ✅ Zastosowane | Zabezpieczenie systemów operacyjnych |
| 11.2 | Zarządzanie aktualizacjami | ✅ Zastosowane | Automatyczne zarządzanie łatami |
| 11.3 | Zarządzanie konfiguracją | ✅ Zastosowane | Hardening systemów i konfiguracja |
| 11.4 | Zarządzanie dostępem | ✅ Zastosowane | Kontrola dostępu do systemów |
| 11.5 | Zarządzanie sesjami | ✅ Zastosowane | Bezpieczne zarządzanie sesjami systemowymi |
| 11.6 | Zarządzanie logami | ✅ Zastosowane | Centralne zarządzanie logami systemowymi |

### 12. Kontrole Bezpieczeństwa Chmurowego

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 12.1 | Bezpieczeństwo chmurowe | ✅ Zastosowane | Zabezpieczenie infrastruktury chmurowej |
| 12.2 | Zarządzanie danymi w chmurze | ✅ Zastosowane | Ochrona danych w środowisku chmurowym |
| 12.3 | Zarządzanie dostępem do chmury | ✅ Zastosowane | Kontrola dostępu do zasobów chmurowych |
| 12.4 | Zarządzanie tożsamością w chmurze | ✅ Zastosowane | Federacja tożsamości i SSO |
| 12.5 | Zarządzanie konfiguracją chmury | ✅ Zastosowane | Infrastructure as Code i zarządzanie konfiguracją |
| 12.6 | Monitorowanie chmury | ✅ Zastosowane | Monitorowanie bezpieczeństwa chmurowego |

### 13. Kontrole Zarządzania Incydentami

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 13.1 | Zarządzanie incydentami | ✅ Zastosowane | Procedury odpowiedzi na incydenty bezpieczeństwa |
| 13.2 | Wykrywanie incydentów | ✅ Zastosowane | Wazuh SIEM do wykrywania incydentów |
| 13.3 | Analiza incydentów | ✅ Zastosowane | Procesy analizy i dochodzenia |
| 13.4 | Odpowiedź na incydenty | ✅ Zastosowane | Procedury ograniczania i odzyskiwania |
| 13.5 | Dokumentacja incydentów | ✅ Zastosowane | Dokumentowanie i raportowanie incydentów |
| 13.6 | Uczenie się z incydentów | ✅ Zastosowane | Przeglądy post-incydentowe i ulepszenia |

### 14. Kontrole Ciągłości Biznesowej

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 14.1 | Planowanie ciągłości biznesowej | ✅ Zastosowane | Plany ciągłości biznesowej i odzyskiwania |
| 14.2 | Zarządzanie ryzykiem biznesowym | ✅ Zastosowane | Ocena ryzyka biznesowego |
| 14.3 | Zarządzanie kryzysowe | ✅ Zastosowane | Procedury zarządzania kryzysowego |
| 14.4 | Testowanie planów | ✅ Zastosowane | Regularne testy planów ciągłości biznesowej |
| 14.5 | Zarządzanie dostawcami | ✅ Zastosowane | Ocena ryzyka dostawców |

### 15. Kontrole Zgodności

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 15.1 | Zgodność prawna | ✅ Zastosowane | Zgodność z RODO, CCPA, PIPEDA |
| 15.2 | Zarządzanie zgodnością | ✅ Zastosowane | Procesy zarządzania zgodnością |
| 15.3 | Audyty | ✅ Zastosowane | Regularne audyty wewnętrzne i zewnętrzne |
| 15.4 | Zarządzanie zmianami | ✅ Zastosowane | Procedury zarządzania zmianami |
| 15.5 | Dokumentacja | ✅ Zastosowane | Dokumentacja systemu zarządzania |

## Kontrole Niezastosowane

### Kontrole Wykluczone

| Kontrola | Tytuł | Status | Uzasadnienie |
|----------|-------|--------|---------------|
| 7.8 | Bezpieczeństwo centrów danych | ❌ Niezastosowane | Zarządzane przez dostawców chmurowych |
| 8.9 | Bezpieczeństwo urządzeń mobilnych | ⚠️ Częściowo | Ograniczone do urządzeń firmowych |
| 9.8 | Bezpieczeństwo API | ⚠️ Częściowo | Dotyczy tylko API wewnętrznych |
| 10.8 | Bezpieczeństwo IoT | ❌ Niezastosowane | Brak urządzeń IoT w organizacji |
| 11.7 | Bezpieczeństwo kontenerów | ⚠️ Częściowo | Ograniczone użycie kontenerów |

### Uzasadnienia Wykluczeń

**Bezpieczeństwo Centrów Danych (7.8)**

- Centra danych są zarządzane przez dostawców chmurowych (AWS, Azure, GCP)
- Dostawcy zapewniają fizyczne zabezpieczenia centrów danych
- Nasze zobowiązania są pokryte przez umowy SLA z dostawcami

**Bezpieczeństwo Urządzeń Mobilnych (8.9)**

- Ograniczone do urządzeń firmowych
- Wdrożone podstawowe kontrole MDM
- Rozszerzenie planowane w przyszłych iteracjach

**Bezpieczeństwo API (9.8)**

- Dotyczy tylko API wewnętrznych
- API zewnętrzne są zarządzane przez dostawców
- Implementacja dodatkowych kontroli w toku

**Bezpieczeństwo IoT (10.8)**

- Brak urządzeń IoT w organizacji
- Nie planowane w najbliższej przyszłości
- Kontrola zostanie dodana w przypadku implementacji IoT

**Bezpieczeństwo Kontenerów to (11.7)**

- Ograniczone użycie kontenerów
- Podstawowe zabezpieczenia wdrożone
- Rozszerzenie kontroli planowane

## Metryki i Monitorowanie

### Kluczowe Wskaźniki Wydajności

| Metryka | Cel | Aktualny Stan | Status |
|---------|-----|---------------|---------|
| Pokrycie kontroli | 95% | 92% | 🟡 W toku |
| Czas implementacji | <30 dni | 25 dni | ✅ Spełnione |
| Skuteczność kontroli | 90% | 88% | 🟡 W toku |
| Zgodność z ISO 27001 | 100% | 95% | 🟡 W toku |

### Plan Działania

#### Q3 2025

- Implementacja pozostałych 8% kontroli
- Rozszerzenie kontroli bezpieczeństwa mobilnego
- Implementacja zaawansowanych kontroli API
- Testy penetracyjne wszystkich systemów

#### Q4 2025

- Audyt certyfikacyjny ISO 27001
- Implementacja kontroli bezpieczeństwa kontenerów
- Rozszerzenie monitorowania bezpieczeństwa
- Szkolenia personelu z nowych kontroli

#### Q1 2026

- Certyfikacja ISO 27001
- Implementacja kontroli IoT (jeśli potrzebne)
- Ciągłe ulepszanie kontroli
- Przegląd i aktualizacja SoA

## Zatwierdzenie

Niniejsze Oświadczenie o Zastosowaniu zostało przeglądnięte i zatwierdzone przez:

**Główny Dyrektor Techniczny**: [Podpis]
**Dyrektor Bezpieczeństwa Informacji**: [Podpis]
**Dyrektor Zarządzający**: [Podpis]

**Data zatwierdzenia**: [Data]
**Data następnego przeglądu**: [Data + 1 rok]

---

## Poprzednie Wersje

Poprzednie wersje naszych Zasad i innych dokumentów można zobaczyć w [GitHub](https://github.com/zanreal-labs/legal)

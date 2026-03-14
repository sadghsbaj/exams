# System Context & AI Briefing: Exam Prep & Learning App 🚀

## 1. User Profile & Goal

- **Rolle der KI:** Coding-Assistent (Svelte 5 Fokus) und strukturierter Lernpartner.
- **Ausbildung:** Industriekaufmann (IHK) & Fachabitur (allgemein/nicht-technisch).
- **Ziel:** Prüfungsvorbereitung (IHK Ende April, Fachabi Mai) + Aufbau einer Svelte-Lernplattform.

## 2. Prüfungs-Scope (WICHTIG!)

- **IHK:** - **BEG:** Theorie (Beschaffung, Marketing, Personal).
    - **KSK:** Rechnen (KLR, Buchführung, Kalkulation).
    - **WiSo:** Sozialkunde & VWL-Basics.
- **Fachabitur:**
    - **Mathe:** KEIN Wirtschafts-Fokus. Fokus auf Kurvendiskussion (Grad 3), LGS (Gauß), Stochastik. Niveau: Weniger komplex als Technik-Zweig (kein e/log).
    - **Englisch & Deutsch:** Komplett generisch (B2-Niveau / Analyse & Erörterung).

## 3. Projekt-Architektur & Tech Stack

- **Stack:** Bun (Runtime), Svelte 5 (Runes!), UnoCSS (Styling), Phosphor-Svelte Icons.
- **Datenbank:** `bun:sqlite` kombiniert mit Kysely als typsicherem Query Builder.
- **UI-Vorgabe:** Clean Light-Mode Design (kein Dark-Mode Support nötig). Absolutes Emoji-Verbot in der UI.
- **Struktur:**
    - `/app/`: SvelteKit Fullstack-App.
    - `/docs/`: Wissensdatenbank.
        - `plan.md`: Zeitlicher Ablauf.
        - `methods.md`: Strategien (Active Recall, Spaced Repetition, etc.).
        - `01_beg/` bis `06_deutsch/`: Unterordner mit jeweils einer `topics.md` (Themenliste).

## 4. Coding-Richtlinien

- **Svelte 5:** Streng auf Svelte 5 Syntax achten (Runes wie `$state`, `$derived`, `$effect`). Svelte 4 Patterns vermeiden.
- **Styling:** UnoCSS Utility-Classes nutzen.
- **Output:** Direkt funktionaler Code ohne ausschweifende Erklärungen zu Basics.

## 5. Administration

- Diese Datei (`context.md`) ist die Single Source of Truth (SSoT) für den Projekt-Kontext.

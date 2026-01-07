[ENG below]

# 🍳 Przepiśnik

> **Przepiśnik** to osobista, cyfrowa książka kucharska, która pozwala zapisywać przepisy kulinarne z różnych źródeł internetu w jednym, spójnym formacie.

Projekt powstaje **frontend-first** i jest tworzony od zera jako element portfolio programistycznego.

---

## 🎯 Problem

Przepisy są dziś rozproszone:

* różne strony internetowe
* pliki PDF
* zdjęcia w telefonie
* notatki tekstowe

Brakuje jednego miejsca, w którym można je:

* zebrać
* ustandaryzować
* wygodnie przeglądać
* wyszukiwać i filtrować

---

## 💡 Rozwiązanie

**Recipe Vault** umożliwia użytkownikowi tworzenie własnej bazy przepisów poprzez:

* ✍️ ręczne dodawanie przepisów
* 🔗 import z linków (parsowanie treści – etap późniejszy)
* 📄 dodawanie plików PDF (podgląd bez opuszczania aplikacji)
* 🖼️ dodawanie zdjęć

Wszystkie przepisy są zapisywane w **jednolitym modelu danych**, niezależnie od źródła.

---

## 🧩 Kluczowe funkcjonalności (MVP)

* lista przepisów użytkownika
* widok szczegółów przepisu
* dodawanie / edycja / usuwanie przepisu
* zapis danych po stronie frontendu (localStorage)

---

## 🛠️ Stack technologiczny

* **Next.js**
* **TypeScript**
* React Hooks
* localStorage (tymczasowe źródło danych)

> Backend, autoryzacja oraz parsowanie stron zostaną dodane w kolejnych etapach.

---

## 🧠 Architektura

Projekt rozwijany jest etapami:

* najpierw UI i logika frontendu
* jasno zdefiniowany model danych
* logika wydzielona do custom hooków
* komponenty maksymalnie proste i czytelne

Decyzja o rozpoczęciu od frontendu pozwala skupić się na:

* UX
* architekturze
* jakości kodu

---

## 🗺️ Roadmap

* [x] Inicjalizacja projektu
* [x] Podstawowy layout aplikacji
* [ ] Model danych przepisu
* [ ] CRUD przepisów (manualne dodawanie)
* [ ] Import przepisu z linku (mock)
* [ ] Obsługa plików PDF
* [ ] Obsługa zdjęć
* [ ] Wyszukiwanie i tagi
* [ ] Autoryzacja użytkownika
* [ ] Backend API

---

## 📸 Preview

*(wkrótce)*

---

## 🚀 Uruchomienie projektu

```bash
npm install
npm run dev
```

---

## 📌 Status projektu

Projekt w trakcie aktywnego rozwoju.

Celem jest stworzenie aplikacji, która może być:

* realnie używana
* łatwo rozwijana
* solidnym elementem portfolio frontendowego.


--------------

# 🍳 Recipe Vault

> **Recipe Vault** is a personal digital cookbook that allows users to save recipes from all over the internet in one clean, unified format.

The project is built **frontend-first** from scratch and serves as a portfolio project focused on architecture, UX, and code quality.

---

## 🎯 Problem

Recipes today are scattered across many places:

* various cooking websites
* PDF files
* photos saved on phones
* handwritten or text notes

There is no single place where users can:

* collect them
* standardize their format
* browse them comfortably
* search and filter them easily

---

## 💡 Solution

**Recipe Vault** provides a personal recipe library where users can add recipes in multiple ways:

* ✍️ manual text input
* 🔗 importing from external links (content parsing – planned)
* 📄 uploading PDF files (previewed directly in the app)
* 🖼️ uploading images

All recipes are stored using a **unified data model**, regardless of their original source.

---

## 🧩 Core Features (MVP)

* user recipe list
* recipe details view
* add / edit / delete recipes
* client-side data persistence (localStorage)

---

## 🛠️ Tech Stack

* **Next.js**
* **TypeScript**
* React Hooks
* localStorage (temporary data layer)

> Backend, authentication, and content parsing will be added in later stages.

---

## 🧠 Architecture

The project is developed incrementally:

* UI and frontend logic first
* clearly defined domain models
* business logic extracted into custom hooks
* simple, readable components

Starting with a frontend-first approach allows focus on:

* user experience
* clean architecture
* maintainable code

---

## 🗺️ Roadmap

* [x] Project initialization
* [x] Basic application layout
* [ ] Recipe data model
* [ ] Recipe CRUD (manual input)
* [ ] Import recipe from URL (mock)
* [ ] PDF support
* [ ] Image uploads
* [ ] Search and tags
* [ ] User authentication
* [ ] Backend API

---

## 📸 Preview

*(coming soon)*

---

## 🚀 Running the project

```bash
npm install
npm run dev
```

---

## 📌 Project status

The project is under active development.

The goal is to build an application that is:

* actually usable
* easy to extend
* a strong frontend portfolio piece.


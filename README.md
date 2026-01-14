[PEnglish version README](README.en.md)

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

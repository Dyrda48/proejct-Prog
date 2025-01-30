# 📦 **PostalSystem – System Zarządzania Przesyłkami Pocztowymi**  

**PostalSystem** to aplikacja konsolowa do zarządzania przesyłkami pocztowymi, obsługująca różne role użytkowników oraz kontrolę dostępu opartą na RBAC (Role-Based Access Control).

## 🔧 **Główne funkcjonalności**  
- 🔑 **Autoryzacja i uwierzytelnianie** – system logowania z weryfikacją hasła i model ról użytkowników.  
- 🏷 **Zarządzanie użytkownikami** – administratorzy mogą dodawać, usuwać i przeglądać użytkowników.  
- 📦 **Zarządzanie przesyłkami** – rejestracja, usuwanie i śledzenie statusu przesyłek.  
- 🚚 **Przypisywanie kurierów** – możliwość przypisania kurierów do przesyłek.  
- 📜 **Rejestrowanie zdarzeń** – automatyczny zapis działań (logowania, zmiany statusów, zarządzanie użytkownikami).  
- 🔒 **RBAC (Kontrola dostępu oparta na rolach)**:
  - **Administrator** – pełny dostęp, zarządzanie użytkownikami i przesyłkami.  
  - **Kurier** – możliwość aktualizacji statusu przesyłek.  
  - **Klient** – przeglądanie informacji o swoich przesyłkach.  

## 🏗 **Struktura projektu**  
- `Models/` – modele danych (użytkownicy, przesyłki).  
- `Services/` – logika biznesowa (zarządzanie użytkownikami, przesyłkami, bezpieczeństwem).  
- `Interface/` – interfejsy dla elastyczności systemu.  
- `UI/` – konsolowe menu interakcji z użytkownikiem.  

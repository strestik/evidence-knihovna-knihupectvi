# Informační systém pro knihovnu a knihkupectví **BookFlow** 
**BookFlow** je jednoduchý webový systém pro evidenci knih, členů a prodejů.  
Cílem je propojit funkce knihovny (půjčování a správa výpůjček) a knihkupectví (evidence zásob a prodej), čímž se zefektivní práce zaměstnanců a zpřehlední celý provoz.

--- 

### Cílová skupina  
- Knihovníci a zaměstnanci knihkupectví  
- Vedoucí pobočky nebo správce knihovny  
- Registrovaní čtenáři a zákazníci  

### Cíl systému  
Systém nahrazuje papírové katalogy a ruční evidenci knih.  
Umožňuje jednoduše spravovat knižní fond, výpůjčky, rezervace i prodej knih.  
Zaměstnanci mají přehled o dostupnosti titulů, zákazníci mohou sledovat své výpůjčky a rezervace.  

---

## Základní funkce (Role a oprávnění)

### **Čtenář / Zákazník (běžný uživatel)**  
- Prohlíží katalog knih (dostupnost, popis, cena).  
- Vytváří a sleduje své **rezervace** a **výpůjčky**.  
- Může hodnotit přečtené knihy nebo přidat krátkou recenzi.  
- Vidí historii svých výpůjček a nákupů.  

### **Knihovník / Prodavač**  
- Přidává nové knihy do katalogu (včetně autorů, ISBN, žánrů).  
- Eviduje výpůjčky a vrácení knih.  
- Vede přehled o prodeji knih a skladových zásobách.  
- Spravuje rezervace čtenářů.  

### **Vedoucí / Administrátor**  
- Spravuje uživatele (čtenáře i zaměstnance).  
- Nastavuje ceny, poplatky za pozdní vrácení a slevy.  
- Sleduje statistiky – nejčtenější knihy, nejaktivnější čtenáře, tržby z prodeje.  
- Exportuje data (např. měsíční přehled výpůjček a prodejů).
- ![povolení](https://github.com/strestik/evidence-knihovna-knihupectvi/blob/main/Analogická%20tabulka.pdf)

---

## Spravovaná data  

| Kategorie | Příklad uchovávaných údajů |
|------------|-----------------------------|
| **Knihy** | Název, autor, ISBN, žánr, vydavatel, dostupnost, cena |
| **Čtenáři / Zákazníci** | Jméno, kontakt, typ účtu, historie výpůjček a nákupů |
| **Výpůjčky** | Kniha, datum výpůjčky, termín vrácení, stav |
| **Rezervace** | Kniha, datum vytvoření, platnost, stav |
| **Prodeje** | Produkt, cena, datum, způsob platby |
| **Zaměstnanci** | Jméno, role (knihovník, prodavač, vedoucí), přihlašovací údaje |

---

## Možnosti rozšíření do budoucna  
- Modul pro **online objednávky knih** a **rezervaci výpůjček** přes webové rozhraní.  
- Automatická **upozornění e-mailem nebo SMS** při blížícím se termínu vrácení knihy.  
- Integrace s databází ISBN pro **automatické doplňování informací o knihách**.  
- Pokročilé **statistiky čtenářských trendů** (nejoblíbenější žánry, autoři, období).  
- Evidence **skladových zásob a dodavatelů** pro knihkupectví.  


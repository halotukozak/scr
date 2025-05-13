Model AADL: Ekspres do kawy
# Dane studenta
Imię i nazwisko: Bartłomiej Kozak
E-mail: bkozak@student.agh.edu.pl

# Opis modelowanego systemu
## Opis ogólny
Model przedstawia system automatycznego ekspresu do kawy zaprojektowany z wykorzystaniem języka AADL. System składa się z komponentów odpowiedzialnych za obsługę interfejsu użytkownika, przygotowywanie napoju oraz zarządzanie zasobami (woda, kawa, mleko). 

Planowane komponenty systemu:

UserInterface – odpowiada za odbiór poleceń od użytkownika i prezentację stanu urządzenia

DrinkPreparator – realizuje proces przygotowania napoju

ResourceManager – kontroluje ilość dostępnych składników

Controller – centralna jednostka sterująca, nadzorująca przebieg działania systemu

## Opis dla użytkownika
Użytkownik ma możliwość wyboru rodzaju napoju (np. espresso, cappuccino, latte) poprzez intuicyjny panel dotykowy. Po zatwierdzeniu wyboru, urządzenie automatycznie analizuje dostępność zasobów i rozpoczyna proces parzenia. W przypadku braku któregoś ze składników, użytkownik otrzymuje stosowny komunikat z sugestią uzupełnienia zasobów.

System został zaprojektowany z naciskiem na niezawodność i bezpieczeństwo działania, a jego model AADL umożliwia analizę potencjalnych punktów awarii, komunikacji między komponentami oraz możliwości dalszego rozwoju funkcjonalności.

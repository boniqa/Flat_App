# Flat_App

1. Cel biznesowy
Portal społecznościowy, do wyszukiwania noclegów i do tworzenia własnych ogłoszeń. Aplikacja będzie dawała możliwość wyszukiwania, wyboru noclegu, rezerwacji i kontaktowanie się z właścicielami miejsc noclegowych.

2. Model danych
Użytkownik: [imie, nazwisko, mail, hasło, opis użytkownika ]
- tworzenie konta,
- logowanie, 
- wyświetlanie profilu,
- edycja danych,
- wyświetlanie swoich wiadomości,
- kasowanie konta,
- wyświetlanie/dodawanie/usuwanie/edycja własnych ogłoszeń,
- historia “zamówień”

Ogłoszenia [nazwa, opis miejsca, ilosc pokoi, adres, zdjęcia-linki ]
- tworzenie ogłoszeń,
- edycja ogłoszeń,
- kasowanie ogłoszeń,
- przypisanie rezerwacji/ zapytanie o rezerwację→ formularz wysyłany do właściciela
 
Rezerwacje [ stan, dni ( ? )]:
- trzyma stan terminów- wolne/zajęte

Wiadomości [data, treść, id_ odbiorca, id_nadawca, id_ogłoszenia, stan ]:
- tworzenie I wysyłanie wiadomości do użytkownika,
- kasowanie,
- wyświetlanie wszystkich- odczytane, nieodczytane
- wyświetlanie po użytkowniku- konwersacja z danym użytkownikiem

3. Widoki
- Strona logowania
- strona główna, z wyświetlonymi najnowszymi ogłoszeniami
- konto użytkownika
- edycja danych użytkownika
- edycja ogłoszenia
- tworzenie nowego ogłoszenia
- wiadomości użytkownika
- widok ogłoszenia: informacje na ten temat, wyświetlanie rezerwacji, wyświetlanie danych własiciela, miejsce na wysłanie wiadomości, miejsce na zapytanie rezerwację

4. procesy- scenariusze
- logowanie/zakładanie konta → wyszukiwanie ogłoszeń → oglądanie ogłoszenia → wybór wolnego terminu → wysyłanie zapytania o termin
- logowanie/zakładanie konta → tworzenie ogłoszenia → potwierdzanie/odrzucanie zapytań o rezerwacje
-  logowanie/zakładanie konta → tworzenie ogłoszenia → edycja ogłoszenia/edycja swojego konta

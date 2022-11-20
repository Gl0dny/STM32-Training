# Zadanie domowe
- Dla lekcji [#10 – ekspander portów (SPI), quiz](https://forbot.pl/blog/kurs-stm32l4-ekspander-portow-spi-quiz-id47763).

**Uwaga:** Rozwiązywanie zadań domowych nie jest obowiązkowe, jednak pozwala na dokładniejsze zrozumienie i utrwalenie treści przekazywanych w kursie.

- [ ] Rozwiąż powyższy quiz (patrz strona lekcji).
- [ ] Rozbuduj naszą bibliotekę o funkcję MCP_GPIO_WritePin, dzięki której będzie można sterować pracą konkretnego wyjścia ekspandera, podając jako argument numer wyjścia (od 0 do 7) i stan, który ma zostać ustawiony (0 lub 1).
- [ ] Dodaj do biblioteki również funkcję MCP_GPIO_ReadPin, dzięki której możliwe będzie sprawdzanie stanu wyjścia. Funkcja powinna jako argument przyjmować numer pinu do sprawdzenia, a wynik powinien być zwracany jako 0 lub 1.
- [ ] Rozbuduj funkcję MCP_GPIO_ReadPin, tak aby sprawdzała, czy wybrany przez nas pin został wcześniej ustawiony faktycznie jako wyjście. Jeśli nie, to funkcja powinna zwrócić kod błędu −1.

# Odpowiedzi
**Uwaga:**  Jeśli rozwiązanie zadań domowych wymaga utworzenia projektu i modyfikacji kodu, to powinnien on być zamieszczony w `homework\homework_project_1` (albo `homework\homework_project_2` itd.).  

W innym przypadku odpowiedzi można zamieścić poniżej (pisemnie):

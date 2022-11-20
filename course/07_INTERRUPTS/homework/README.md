# Zadanie domowe
- Dla lekcji [#7 – przerwania sprzętowe, obsługa błędów](https://forbot.pl/blog/kurs-stm32l4-7-przerwania-sprzetowe-obsluga-bledow-id46583).

**Uwaga:** Rozwiązywanie zadań domowych nie jest obowiązkowe, jednak pozwala na dokładniejsze zrozumienie i utrwalenie treści przekazywanych w kursie.

- [ ] Wróć do programu, w którym zliczaliśmy w przerwaniu naciśnięcia przycisku. Sprawdź, jak zachowa się układ przy różnych ustawieniach przerwań (np. wyzwalanie przy obu zboczach).
- [ ] Dodaj do układu drugi przycisk i drugi licznik naciśnięć. Sprawdź, czy działanie układu jest zakłócane przez drgania styków. Jeśli tak, to rozwiąż ten problem (cyfrowo lub filtrem RC).
- [ ] Napisz program, który w procedurze obsługi przerwania SysTick będzie wysyłał przez UART aktualną wartość licznika SysTick podzieloną przez 1000. Sprawdź telefonem, czy taki sekundnik działa poprawnie i jak na jego dokładność wpływa sposób formatowania danych – porównaj wersję „%d\n” oraz „Aktualny czas: %d\n”.

# Odpowiedzi
**Uwaga:**  Jeśli rozwiązanie zadań domowych wymaga utworzenia projektu i modyfikacji kodu, to powinnien on być zamieszczony w `homework\homework_project_1` (albo `homework\homework_project_2` itd.).  

W innym przypadku odpowiedzi można zamieścić poniżej (pisemnie):

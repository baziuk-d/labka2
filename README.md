## labka2
# Рівень 1 Варіант 3
Ви граєте в альтернативний варiант покеру, де кожен гравець має в руках N карт, i метою гри є набрати якомога довшу групу послiдовних карт. Колода складається з карт, якi мають числову величину. Також, в колодi присутнi джокери. Якщо в руцi гравця є джокери, вiн може присвоїти кожному будь-яку величину на власний розсуд. Вам роздали карти. Визначте довжину найдовшої послiдовностi карт, яку ви можете скласти.

Вхiднi данi масив цiлих чисел вiд 0 до 1000000 включно — величини окремих карт в руцi. Загальна кiлькiсть карт в руцi не перевищує 10000. Джокери позначаються величиною 0.

Перехiд через верхню межу» не дозволяється — [999999, 1000000, 1, 2] не вважається коректною послiдовнiстю.

Ваша функція має повертати довжину найдовшої послiдовної групи, яку можна скласти з виданих карт.

Для перевірки виконання роботи реалізованого алгоритму слід використати бібліотеку unittest та перевірити роботу вашої функції на прикладах, наведених вище

Приклад 1 cards = 0 10 15 50 0 14 9 12 40

Результат 7 Пояснення: Можна замiнити один джокер на 11, iнший — на 13, i скласти таку послiдовнiсть: 9, 10, 11, 12, 13, 14, 15.

Приклад 2 cards =1 1 1 2 1 1 3 Результат 3

Приклад 3 cards = 5 6 5 6 5 6 5 6 5 6 5 0 0 Результат 4

Для перевірки виконання роботи реалізованого алгоритму слід використати бібліотеку unittest та перевірити роботу вашої функції на прикладах, наведених вище


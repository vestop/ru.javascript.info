importance: 5

---

# Расставить супергероев по полю

В этой задаче вы можете проверить своё понимание сразу нескольких аспектов Drag’n’Drop и DOM.

Сделайте так, чтобы элементы с классом `draggable` можно было переносить мышкой. Как мяч в этой главе.

Требования к реализации:

- Используйте делегирование событий для отслеживания начала перетаскивания: только один обработчик событий `mousedown` на документе.
- Если элементы подносят к верхней/нижней границе окна – оно должно прокручиваться вверх/вниз, чтобы позволить дальнейшее перетаскивание.
- Горизонтальная прокрутка отсутствует (чуть-чуть упрощает задачу, её просто добавить).
- Элемент при переносе, даже при резких движениях мышкой, не должен даже частично попасть вне окна.

Демо слишком велико для размещения здесь, перейдите по ссылке ниже.

[demo src="solution"]

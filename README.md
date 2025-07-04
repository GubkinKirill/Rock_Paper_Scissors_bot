# 🎮 Telegram-бот: Камень, ножницы, бумага

## Что?

Telegram-бот, с которым можно сыграть в простую игру **«Камень, ножницы, бумага»**.

## Зачем?

Чтобы:

- Продемонстрировать работу с обычными кнопками Telegram.
- Показать шаблон простого Telegram-проекта.
- Просто поиграть с ботом в классическую игру.

## Что должен уметь бот?

- Отправлять клавиатуру с кнопками: `Камень`, `Ножницы`, `Бумага`.
- Генерировать случайный выбор из этих трёх элементов.
- Обрабатывать выбор пользователя.
- Определять победителя и сообщать результат.

## Дополнительный функционал

❌ Не предусмотрен.

---

## 📲 Взаимодействие с ботом

### Команда `/start`

- Бот приветствует пользователя.
- Предлагает сыграть в игру, отправляя клавиатуру с кнопками:
  - `Давай!`
  - `Не хочу!`
- Предлагает прочитать правила командой `/help`.

#### Возможные действия пользователя:

1. Нажать кнопку `Давай!`.
2. Нажать кнопку `Не хочу!`.
3. Отправить команду `/help`.
4. Отправить произвольное сообщение.

---

### Нажатие на кнопку `Давай!`

- Бот отправляет сообщение: `Отлично! Делай свой выбор!`
- Отправляет клавиатуру с кнопками:
  - `Камень`
  - `Ножницы`
  - `Бумага`

#### Возможные действия пользователя:

1. Нажать одну из кнопок: `Камень`, `Ножницы`, `Бумага`.
2. Отправить команду `/help`.
3. Отправить произвольное сообщение.

---

### Выбор хода (Камень / Ножницы / Бумага)

- Бот:
  - Генерирует случайный выбор.
  - Определяет победителя.
  - Отправляет результат игры.
  - Предлагает сыграть снова с клавиатурой: `Давай!`, `Не хочу!`.

---

### Нажатие на кнопку `Не хочу!`

- Клавиатура сворачивается.
- Бот отправляет сообщение:  
  _"Хорошо. Если, вдруг, захочешь сыграть — открой клавиатуру и нажми «Давай!»"_

---

### Команда `/help`

- Бот присылает:
  - Правила игры.
  - Предложение сыграть.
  - Клавиатуру с кнопками `Давай!`, `Не хочу!`.

---

### Произвольное сообщение

- Бот отвечает:  
  _"Извини, я тебя не понимаю. Попробуй нажать кнопку или отправь /help"_

# Hangman

## Description

This is a console version of the classic letter guessing game called [Hangman](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0)).

You are shown a set of blank letters that match a word and you have to guess what these letters are to reveal the hidden word.

You can make no more than 7 mistakes before you lose the game.

The game was written on [Ruby](https://www.ruby-lang.org/ru/).

## Usage

Ruby must be [installed](https://www.ruby-lang.org/ru/documentation/installation/) for running the program.

Clone repository:

```
git clone https://github.com/zorkostreis/hangman.git
```

Run the program:

```
ruby main.rb
```

Try to quess the word:

```
Слово: __ __ __ __
            _______
            |/
            |
            |
            |
            |
            |
            |
            |
          __|________
          |         |

"Ошибки (0): "
У Вас осталось ошибок: 7
Введите следующую букву:
```

## Adding new words

To add new words to the game write them in `data/words.txt`

Every word must be written on a new line:

```
ЁЖИК
ЙОГА
КОТ

```

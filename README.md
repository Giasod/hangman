# Игра "Виселица" / The Hangman Game
Привет! Это знаменитая игра ["Виселица"](https://cutt.ly/noWn37W), написанная на языке Ruby(v.2.7.1p83). 

Hi! This is the famous game ["The Hangman"](https://cutt.ly/1oWmrcp), written in Ruby(v.2.7.1p83). 

## Суть игры / The point of game 
Есть загаданное слово, которое игрок должен отгадать. На это даётся 7 попыток.
Каждая ошибка это шаг к виселице. Количество ошибок, ваш статус "висельника" и слово, которое надо отгадать,
находятся у вас на экране.

There is a mysterious word that the player must guess. There are seven attempts at this.
Every mistake is a step towards the gallows. The number of errors, your "gallows" status and the word you have to guess,
are on your screen.

### Как добавить новые слова / How to add new words
Чтобы добавить новые слова в игру, пройдите в `/data/words.txt` и запишите туда нужные слова.

In order to add new words to the game, go to `/data/words.txt` and write down the necessary words there.

### Как запустить игру у себя на компьютере / How to run the game on your computer
Для запуска программы вам нужно предпринять следующие шаги:
```
git clone git@github.com:Giasod/hangman.git
cd ./hangman
bundle
bundle exec ruby hangman.rb
```

Готово! Вы восхитительны!

In order to run the program on your local machine, you have to take several steps:
```
git clone git@github.com:Giasod/hangman.git
cd ./hangman
bundle
bundle exec ruby hangman.rb
```

Voila! You're breathtaking!

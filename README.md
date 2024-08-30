# awesome_tmux

Этот репо по управлению tmux, потому что я часто их забываю.


## Outside the session

Список сессий – `tmux ls`

Создать сессию без имени (имя будет номером этой сессии) – `tmux new`

Создать сессию с именем – `tmux new -s sample_text`

Присоединиться по имени – `tmux a -t sample_text`

Присоединиться в последнюю сессию – `tmux a`

Выйти из сессии, не убивая её – `Ctrl+B, D`

Убить сессию – прописать в ней `exit`

Убить сессию по имени – `tmux kill-ses -t sample_text`

## Inside the session

### Окна

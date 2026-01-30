Это оригинальный шаблон и все ассеты, которые загружаются и используется в Friday Night Funkin AI Engine. Форкни этот Github Репозиторий, что бы сделать мод на Friday Night Funkin AI Engine.

Всё готово? Введи в Friday Night Funkin AI Engine данную ссылку, что бы загрузить твой мод: https://raw.githubusercontent.com/<Твой Github никнейм>/<Названия репозитория>/refs/heads/main

# Как добавить песнями из мода или оригинального FNF?

1. Скопируй папку Chart из FNF GAME/assets/data/songs/<песня> в GITHUB/songs
2. Скопируй аудио трека и голоса из FNF GAME/assets/songs/<песня> в GITHUB/songs/<песня>
3. Готово. Песня должна работать, если загрузить её вручную по имени.

# Круто, с песнями разобрались. Что насчёт персонажей?

1. Скопируй JSON файл из FNF GAME/assets/data/characters/<НАЗВАНИЕ ПЕРСОНАЖА> в GITHUB/assets/characters
2. Скопируй XML файл из FNF GAME/assets/shared/images/characters/<НАЗВАНИЕ ПЕРСОНАЖА>.xml в GITHUB/assets/characters
3. Скопируй PNG файл из FNF GAME/assets/shared/images/characters/<НАЗВАНИЕ ПЕРСОНАЖА>.png в GITHUB/assets/characters
4. Готово, НО... *прочитай внизу текст*

# Персонажей из FNF >1.0.0 сложнее импортировать!

FNF >1.0.0 разделяет спрайты на несколько PNG файлов. Например, для Pico необходимо скопировать не только Pico_Playable.png, но и Pico_Censored.png, Pico_Shooting.png, Pico_Death.png, pico-cheer.png, pico-yeah.png, Pico_Intro и Pico_Burps. К сожалению, понять какие png файлы необходимо скачать можно лишь после того, как вы рассмотрите JSON файла персонажа.


*Github может обновлять файлы до 5 минут, если вы не увидели никаких изменений, просто подождите, пока Github наконец обновит или добавит новые файлы на сервера.*
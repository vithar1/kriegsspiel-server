# Kriegsspiel

1. создать id в виде кода который будет отправляться на фронт
и будет в тайне, по нему будет определятся какой игрок ходит
и нельзя будет обмануть походив не тому

2. проверить не возникнет ли проблем из-за того что можно 
создать сколько угодно игроков(сделал эту херню для возможности)
играть >2 игрокам

3. класс GameManager на самом деле int 
player = 0; и т.д. это кастыль на мой взгляд и в реальном 
проекте это надо исправить

4. добавить в игру таймер чтобы на выполнение хода у игрока
было определённое время

5. сделать возможность дальнего боя*

6. Добавить разные цели в игре

7. Каждый тип юнитов должен обладать своими уникальными 
особенностиями то есть функциями

8. Попробовать сделать присвоение unitType в видах войск
c помощью рефлексии и запизнуть это в родительский класс
чтобы не писать одно и тоже 

## Быстрые заметки на время разработки
первое время планирую не включать регионы



## Описание
### Правила игры
Цель уничтожить все вражеские войска(пока) потом будут разные цели
### Коммиты
Коммит делается так:
- сначала номер задачи, если дополнение не предполагаетзадачу
 то цифра "0"
- имя разработчика
- краткое описание

Знак рааздеоитель между пунктаами "-"
   
**Пример:**
    
    3423-odin-create_map

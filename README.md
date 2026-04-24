# MayLAN Modpack

Модпак для ванильного сервера MayLAN Craft.

## Как пользоваться репозиторием?
Модпак создаётся при помощи инструмента packwiz.  
Скачать его можно здесь: [github.com/packwiz/packwiz/actions](github.com/packwiz/packwiz/actions)

### Команды для создания конечной сборки:
* Создать сборку для CurseForge:
```
packwiz curseforge export
```
* Создать сборку для Modrinth:
```
packwiz modrinth export
```
### Команды для редактирования сборки:
* Добавить мод:
```
packwiz modrinth install [mod]
```
* Обновить мод:
```
packwiz update [mod]
```
* Обновить все моды:
```
packwiz update --all
```
* Удалить мод:
```
packwiz remove [mod]
```
* Если обновлён конфиг или добавлен любой другой сторонний файл, делаем:
```
packwiz refresh
```
*Все остальные команды доступны в документации на английском языке: https://github.com/MayLAN-Craft/modpack/blob/main/docs/packwiz.md*

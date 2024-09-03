# Устранение проблемы с горячей клавишей Alt+F4 на клавиатуре A4Tech

### На клавиатурах A4Tech нажатие горячих клавиш `Fn`+`Alt`+`F4` (или `Alt`+`F4`, если `Fn` заблокирован `Fn`+`Esc`) выполняет действие поиска вместо стандартного действия закрытия окна.

### Скрипт [AutoHotkey](https://www.autohotkey.com/) `a4tech-alt_f4.ahk` переназначает клавиши `Alt` и `Search` на `Alt`+`F4`.

+ ### Исполняемый файл [`a4tech-alt_f4.exe`], скомпилированный из скрипта AutoHotkey, можно поместить в папку запуска Windows:

```
C:\Users\{username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
```

+ ### Либо через диалоговое окно «Выполнить» ввести в появившемся окне shell:startup и в альтернативном списке автозагрузки копируем/создаем ярлык файла `a4tech-alt_f4.exe`

### Проверено на клавиатуре A4Tech Fstyler FX50
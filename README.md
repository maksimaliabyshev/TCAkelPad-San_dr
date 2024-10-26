## Description

Обновлённая сборка AkelPad от San_dr<br/>
Плагин Total Commander внутреннего просмотра [TC AkelPad Plugin](https://wincmd.ru/plugring/TCAkelPad.html)<br/>
Текстовый редактор AkelPad.exe v4.9.9 r4449 x86 [Valery Kurenkov](https://www.dropbox.com/scl/fo/dm0dm3s1pcabygl1bboqa/h?rlkey=ps9l702knqn145uaf3vz6sqtj&dl=0)<br/>
Special for [Total Commander Titan](https://rutracker.org/forum/viewtopic.php?t=5324469) - Portable by pcDenPro<br/>

Lister:

- Клавиши 1..8 - переключают различные режимы просмотра
- Клавиша 4 - переключает плагины, которые сопоставлены с mime-типом файла
- Клавиша F4 - включает/отключает режим редактирования AkelPad

AkelPad:

- F1 - восстановить основную панель
- F11 - Fullscreen (Ctrl+F11/Alt+F11)
- Ctr+/ - закомментировать строку/несколько строк
- Ctrl+Shift+T - вернуть последний закрытый файл 
- Win+Up/Win+Down - максмизировать/минимизировать окно редактора, если куда то убежало
- В Lister не доступно "Главное меню", оно есть на основной панели или через ПКМ
- Alt+E - бинды горячих клавиш
- Alt+P - плагины

Если после переключения в режим редактирования через F4 и обратно на чтение,<br/> 
Lister перестал реагировать на кнопки, нужно нажать Ctrl+Tab, что бы фокус переключился на Lister.<br/>

Начертания внутренних шрифтов Nerd Font Proto можно поменять через "Диалог выбора" шрифта,<br/> 
так как редактор самостоятельно может менять только 4 начертания.

Если редактор стал подтормаживать при открытии файлов,<br/>
значит включена "Проверка орфографии" (Spell Checker).<br/>
Переключатель на основной панели.

## Download

[TCAkelPad-San_dr/releases](https://github.com/maksimaliabyshev/TCAkelPad-San_dr/releases)<br/>

## Install

Открыть архив **TCAkelPad.7z** в TC, он автоматически предложит установить плагин.
       
Если TC предложит установить в раздел w<u>d</u>x плагинов: 
   
    %COMMANDER_PATH%\Plugins\wdx\TCAkelPad

То нужно поменять на w<u>l</u>x и стрелками (слева) повысить приоритет, что бы стоял в очереди выше другого редактора:
    
    %COMMANDER_PATH%\Plugins\wlx\TCAkelPad
    

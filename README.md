# Endless-sketchfab-online-on-Babylon.js

Итак в нулевой версии я создал бесконечную процедурную чанковую генерацию по XYZ вы летите, и в каждом кусочке случайным образом сгенерированная модель OBJ из случайно сгенрированных в случайном в этом кубе vertex, и faces без повторов с другими моделями.

[Endless sketchfab on Babylon.js (Version 0) | Babylon.js Playground](https://playground.babylonjs.com/#05DKC5#0)

Но нам нужно как-то систематизировать свойства случайной генерации что-бы это был не хаос случайных точек и граней а что-то похожее на что-то осмысленное! 

[Endless sketchfab on Babylon.js (Version 1 - Ordered generation) | Babylon.js Playground](https://playground.babylonjs.com/#X3PFLO#0)

Теперь нужнро добавить телепорт что улететь далеко и увидеть если там чт-то похожее на что-то отличное хаоса бесконечного океана моделей.

[Endless sketchfab on Babylon.js (Version 2 - With the ability to teleport) | Babylon.js Playground](https://playground.babylonjs.com/#QP3FYQ#0)

И теперь мы сделаем так что-бы размер куба для генерации случайной OBJ модели расширялся при каждой послежующей итерации...

[Endless sketchfab on Babylon.js (Version 3 - Serpentine paths) | Babylon.js Playground](https://playground.babylonjs.com/#K3VHFW#0)

Теперь нужно сделать локальную версию что-бы сделать два поля для количества vertex, и faces что-бы переключатся на индивидульно выбранную случайно сгенерируванную OBJ моедль. 

[Endless sketchfab on Babylon.js (Version 4 - Local version with input fields for the model) | Babylon.js Playground](https://playground.babylonjs.com/#DYVLK6#0)

Добавим к локальной версии кнопка случайно авто перемещения что-бы быстро переключаться на случайную OBJ моедль с опредленной скоростью.

[Endless sketchfab on Babylon.js (Version 5 - With the auto-switch button) | Babylon.js Playground](https://playground.babylonjs.com/#NF2G0G#0)

Но нужно починить эту кнопку случайного перемещения что-бы вещественные числа работали, и можно было переключятся за милисекунды времени.

[Endless sketchfab on Babylon.js (Version 6 - With the auto-switch button FIXED version) | Babylon.js Playground](https://playground.babylonjs.com/#V1JEJB#0)

Теперь нужно добавить диапазоны для случайного переключения от минимального до максимального диапазона vertex, и faces.

[Endless sketchfab on Babylon.js (Version 7 - With an automatic switch button, and fields for the range of random switch) | Babylon.js Playground](https://playground.babylonjs.com/#WMZUW3#0)

Ну и всё в приницпе мы получили бесконечный скечтфаб осталось только починить всякие мелочи вроде того что-бы при переклбчение на одну, и туже модель была одна, и та же модель что, и чем была раньше.

[Endless sketchfab on Babylon.js (Version 8 - FULL version) | Babylon.js Playground](https://playground.babylonjs.com/#6JBWT3#0)

Осталось только внести финальный штрих в картину сделав какие нибудь опциональные версии например сделать кнопку в которую вы загружаете OBJ модель, и создает бесконечный подиум где при каждой последующей итерации модель выбранная изменят одну случайную vertex, и таким образом до бесконечности всевозможные перестановки она превращаются во что угодно что только может быть.

[Endless sketchfab on Babylon.js (Version 9 - The version with the model download and all possible changes to this model) | Babylon.js Playground](https://playground.babylonjs.com/#F7EZDH#1)

[Endless sketchfab on Babylon.js (Version 10 - Version without endless podium only one podium with model number) | Babylon.js Playground](https://playground.babylonjs.com/#BNHYA4#0)

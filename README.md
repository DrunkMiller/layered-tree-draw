## Руализация layered-tree-draw алгоритма

*В replit.com уже есть собранный jar используйте его для быстрого рисования графа*  
*Команда запуска jar:* `kotlin -classpath main.jar MainKt "path to graph file"`  
*пример:* `kotlin -classpath main.jar MainKt "examples/binary-tree-42n"`

*В папке examples есть подготовленные примеры графов*

- **ReadGraphml.kt** - Чтение графа из graphml файла
- **LayeredTreeAlgorithm.kt** - Реализация алгоритма
- **GraphGraphics.kt** - Инструменты отрисовки графа

При инициализации GraphGraphics задается:
- `fillColor` - цвет заливки вершин
- `borderColor` - цвет ребер и границ вершин
- `xPadding` - размер сетки по оси x
- `xPadding` - размер сетки по оси y
- `bezierEdges` - флаг отрисовки ребер с помощью кривых Безье
- `nodeTitle` - флаг вывода на изображение графа идентификаторов вершин
- `grid` - флаг вывода сетки на изображение графа


| **Компилятор** | **Время**                                     | **1 исходник** | **5 исходников** |
|----------------|-----------------------------------------------|----------------|------------------|
| **msvc**       | **Время пересборки без предкомп.** **хедера** | 1,460          | 3,768            |
|                | **Время пересборки с предкомп. хедером**      | 1,700          | 3,025            |
|                | **Изменение времени пересборки**              | +16%           | -20%             |
| **gcc**        | **Время пересборки без предкомп.** **хедера** | 0,001094       | 0,003768         |
|                | **Время пересборки с предкомп. хедером**      | 0,001587       | 0,004591         |
|                | **Изменение времени пересборки**              | +45%           | +22%             |
| **clang**      | **Время пересборки без предкомп.** **хедера** | 0,001009       | 0,003211         |
|                | **Время пересборки с предкомп. хедером**      | 0,001573       | 0,004469         |
|                | **Изменение времени пересборки**              | +59%           | +39%             |
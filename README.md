### Этот репозиторий содержит плагин для автоматической генерации кода в нотации "Каналы - фильтры" для IDE Intellij Idea.
 
Установка:

+ установить IDE Intellij Idea 2022 или старше (возможно, работает и ниже, но не тестировалось);
+ клонировать репозиторий и открыть его в IDE, дождаться Gradle - синхронизации;
+ нажать отладка или запуск для запуска в IDE;
+ откроется новое окно с IDE в котором справа (где вкладка Gradle) будет боковая вкладка DFD Code Generator.

#### TODO
Здесь перечислены пункты, которые находятся в процессе разработки.

#### Важные:
+ устранить баг при наведении коннектора в угол блока - пропадают стрелки;
+ попадание в эллипс коннектором - баг, отладить;
+ не настроена валидация коннекта блоков;
+ нет проверки выхода блока за размеры полотна;
+ одинаковые имена в блоках - не валидируется;
+ язык ввода в блоках - не валидируется;
+ валидация пакета кода;
+ валидация инпут / аутпут блоков;
+ валидация диаграммы на пустоту и основные элементы.

#### Второстепенные:
+ курсор на украшении не меняется корректно;
+ нет системы управления z последовательностью (для блоков и коннекторов);
+ нет сглаживания коннекторов;
+ устранить пересчет каждого коннектора в каждом кадре;
+ нет текстового конфига для строковых ресурсов.
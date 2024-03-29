# **Добро пожаловать в Git!**

Любой творческий процесс состоит из набора итераций (повторений). Художник рисует эскизы, фотограф делает несколько кадров, студент создаёт файлы. Каждая такая попытка имеет ценность. Она позволяет остановиться и убедиться, что работа идёт в правильном направлении.
___

В отличие от художников, разработчики не используют скетчбуки. Историю их проектов хранит отдельная программа — система контроля версий (англ. Version Control System, или коротко VCS).
___

*Для обозначения систем контроля версий используют не только аббревиатуру VCS, но и SCM (от англ. Source Control Management — «система управления исходным кодом»)*.
___

Система контроля версий, или VCS, — это программное обеспечение, которое помогает отслеживать изменения в программах, текстовых файлах, больших документах, веб-сайтах и так далее. 
Одно изменение или группу изменений в VCS называют *ревизией* или *версией*. Каждая такая ревизия содержит информацию о том, что изменилось, кто внёс изменения, когда это было и иногда комментарии к изменению.
Основные функции системы контроля версий:
- хранит историю изменений в виде отдельных ревизий;
- позволяет манипулировать историей: например, менять порядок ревизий, полностью удалять версии, возвращаться назад в истории;
- помогает анализировать изменения: например, кто и когда вносит изменения, кто чаще всего вносит изменения в определённый файл и так далее.
Одна из ключевых особенностей современных систем контроля версий — поддержка параллельной работы нескольких пользователей, в том числе над одним файлом. Именно поэтому VCS так популярны у разработчиков.
___

Система контроля версий — общее название ряда продуктов, таких как Git, Mercurial, Subversion и других. Git - самый популярный среди разработчиков инструмент контроля версий!

## **Основные команды и правила работы в Git**

Чтобы Git начал следить за изменениями в файлах, их сначала нужно «подключить» к нему. Для этого вы должны превратить папку с файлами вашего проекта в Git-репозиторий.
___

1. *git init* - команда инициализирует папку как Git-репозиторий
2. *git status* - позволяет увидеть текущее состояние репозитория
3. *git add* - позволяет подготовить к сохранению файлы в папке-репозиторие
4. *git commit* - команда фиксирует текущее состояние файла, подготовленного для сохранения
*Коммит (commit) — одна из основных сущностей в Git (и в других системах контроля версий). Коммит гарантирует, что изменения будут сохранены в истории и при необходимости к ним можно будет «откатиться».*
5. *git log* - выводит список коммитов
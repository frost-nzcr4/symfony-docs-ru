Symfony2 для пользователей symfony 1
============================

Приложения
------------

В проекте symfony 1 распространено иметь несколько приложений: например, одно для
фронтэнда и одно для бэкэнда.

В проекте Symfony2 вам надо создать только одно прилоежение (приложение для
блога, интернет приложение и т. д.). В большинстве случаев, если вам необходимо
создать второе приложение, то лучше будет создать другой проект и разделить
некоторые бандлы между ними.

Если вам надо разделить фронтэнд и бэкэнд функции некоторых бандлов, создайте
подпространства имён для контроллеров, подпапки для шаблонов, различные
семантические настройки, разделите настройки маршрутизации и т. д.

.. tip::

    Прочтите определения :term:`Project` и :term:`Application`, а также
    :term:`Bundle` в словаре.
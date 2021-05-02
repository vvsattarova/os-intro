
# Лабораторная работа №4

## Операционные системы

### Саттарова Вита Викторовна

### 2021

#### Цели и задачи

Познакомиться с операционной системой Linux, получить практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной системы.

1.	Установить необходимое ПО
2.	Изучить информацию об учётных записях, текстовых консолях и графических интерфейсах
3.	Научиться работать с текстовыми консолями (включать, заходить в под именем пользователя, выходить)
4.  Научиться работат с разными графическими средами и перемещаться между ними (Gnome, KDE, Xfce)
5.  Рассмотреть установленные по умолчанию приложения в разных графических средах

#### Объект и предмет исследования

Объект исследования – учётная запись пользователя, текстовые консоли, графические среды.
Предмет исследования – изучение особенностей работы с текстовыми консолями и разными графическими средами, получение знаний об учётной записи пользователя, анализ установленных по умолчанию приложений.

#### Условные обозначения и термины

Условные обозначения и термины отсутствуют

#### Теоретические вводные данные

**Linux** — многопользовательская операционная система, т.е. несколько пользователей могут работать с ней одновременно с помощью терминалов.
**Определение 1.** *Компьютерный терминал* — устройство ввода–вывода, основные функции которого заключаются в вводе и отображении данных.
**Определение 2.** *Текстовый терминал* (терминал, текстовая консоль) — интерфейс компьютера для последовательной передачи данных.
Процедура регистрации в системе обязательна для Linux. Каждый пользователь операционный системы имеет определенные ограничения на возможные с его стороны действия: чтение, изменение, запуск файлов, а также на ресурсы: пространство на файловой системе, процессорное время для выполнение текущих задач (процессов).
**Определение 3.** *Учётная запись пользователя* (user account) — идентификатор пользователя, на основе которого ему назначаются права на действия в операционной системе.
**Определение 4.** *Входное имя пользователя* (Login) — название учётной записи пользователя.
**Определение 5.** *Виртуальные консоли* — реализация концепции многотерминальной
работы в рамках одного устройства.
На компьютерах с операционной системой типа Linux может быть установлено несколько графических сред. Например, Gnome, KDE, Xfce.

#### Техническое оснащение и выбранные методы проведения работы

Техническое оснащение: персональный компьютер, интернет, виртуальная машина.
Методы: анализ предложенной информации, загрузка необходимых для выполнения программ и настройка машины, выполнение работы по указанному алгоритму, получение дополнительной информации из интернета.

#### Выполнение лабораторной работы

1.	Ознакомилась с теоретическим материалом, подготовила компьютер для выполнения лабораторной работы, открыла вирутальную машину, подготовленную для работы. (рис. -@fig:001) (рис. -@fig:002)

![Название рисунка](image/image1.jpg){ #fig:001 width=70% }

![Название рисунка](image/image2.jpg){ #fig:002 width=70% }

2.	Рассказала об особенностях выполнения работы на моей машине, открыла текстовую консоль. На моей работе было доступно 5 текстовых консолей.   

3.	Я перемещалась между консолями, однако для этого предварительно нужно было сделать вход в текстовую консоль. Для этого я использовала комбинацию клавиш Ctrl+Alt+Fn, (n=2..6). (рис. -@fig:003) (рис. -@fig:004) (рис. -@fig:005) (рис. -@fig:006) (рис. -@fig:007)

![Название рисунка](image/image3.jpg){ #fig:003 width=70% }

![Название рисунка](image/image4.jpg){ #fig:004 width=70% }

![Название рисунка](image/image5.jpg){ #fig:005 width=70% }

![Название рисунка](image/image6.jpg){ #fig:006 width=70% }

![Название рисунка](image/image7.jpg){ #fig:007 width=70% }

4.	Я перемещаясь между консолями, по-очереди заходила в них, для этого я использовала логин пользователя, пароля у моего пользователя не было, поэтому графы с паролем не появлялось, однако если бы он был, то символы бы не отображались. (рис. -@fig:008) 

![Название рисунка](image/image8.jpg){ #fig:008 width=70% }

5.	Я завершила консольный сеанс, по-очереди для каждой консоли, для этого я использовала комбинацию клавиш Ctrl+D. (рис. -@fig:009)

![Название рисунка](image/image9.jpg){ #fig:009 width=70% }

6.	Переключилась на графический интерфейс, для этого я нажала комбинацию клавиш Ctrl+Alt+F1. На моей виртуальной машине необходимо использовать именно эту комбинацию клавиш, а не указанную в работе Ctrl+Alt+F7, потому что (рис. -@fig:010)

![Название рисунка](image/image10.jpg){ #fig:010 width=70% }

7.	Необходимо было ознакомиться с менеджером рабочих столов, однако у меня машина новая, по умолчанию был только один рабочий стол, а менеджера рабочих столов также не было, я не смогла его установить, однако создала файл, изменяя который можно прееключаться между рабочими столами. (рис. -@fig:011) 

![Название рисунка](image/image11.jpg){ #fig:011 width=70% }

8.  На моей машине была только одна графическая среда - GNOME, он по-умолчанию запускался. Я переключалась между рабочими столами при помощи файла или команды. Регистрироваться в них было не нужно, так как я заходила в них через перезапуск машины, поэтому я выполняла регистрацию на входе. Разницу я комментировала в видео, по-очереди для каждого. Для выполнения работы дополнительно я устанавливала графические среды KDE, Xfce. (рис. -@fig:012) (рис. -@fig:013) (рис. -@fig:014) (рис. -@fig:015) (рис. -@fig:016)

![Название рисунка](image/image12.jpg){ #fig:012 width=70% }

![Название рисунка](image/image13.jpg){ #fig:013 width=70% }

![Название рисунка](image/image14.jpg){ #fig:014 width=70% }

![Название рисунка](image/image15.jpg){ #fig:015 width=70% }

![Название рисунка](image/image16.jpg){ #fig:016 width=70% }
 
9.  Я изучила список установленных по умолчанию программ, показала его на видео и частично прочитала названия некоторых. Программы рассортированы по группам с учётом их предпочтительного применения. Я запускала браузер Firefox, текстовый Kwrite и терминал, текстового процессора у меня по-умолчанию не было установлено. Могу сказать, что все приложения открываются абсолютно одинаково на всех рабочих столах. (рис. -@fig:017) (рис. -@fig:018) (рис. -@fig:019) (рис. -@fig:020) (рис. -@fig:021) (рис. -@fig:022) (рис. -@fig:023) (рис. -@fig:024) (рис. -@fig:025)

![Название рисунка](image/image17.jpg){ #fig:017 width=70% }

![Название рисунка](image/image18.jpg){ #fig:018 width=70% }

![Название рисунка](image/image19.jpg){ #fig:019 width=70% }

![Название рисунка](image/image20.jpg){ #fig:020 width=70% }

![Название рисунка](image/image21.jpg){ #fig:021 width=70% }

![Название рисунка](image/image22.jpg){ #fig:022 width=70% }

![Название рисунка](image/image23.jpg){ #fig:023 width=70% }

![Название рисунка](image/image24.jpg){ #fig:024 width=70% }

![Название рисунка](image/image25.jpg){ #fig:025 width=70% }

Подробное пояснение по каждому из рабочих столов можно увидеть на видео.

#### Полученные результаты

Изучена информация, касающаяся пользователей системы, текстовых консолей, графических сред, были рассмотрены текстовые консоли и 3 графических среды. Между текстовыми консолями и графическими средами было возможно переключение. 

#### Анализ результатов

Работу получилось выполнить по инструкции, однако были некоторые различия, связанные с различием между устройствами, на которых выполняется работа.

#### Заключение и выводы

В результате работы я познакомилась с операционной системой Linux, получила практические навыки работы с консолью и некоторыми графическими средами операционной системы.
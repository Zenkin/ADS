# ADS

## О проекте

![drone station](https://github.com/Zenkin/ADS/blob/main/Pictures/Станция.jpg "Дрон станция")

Проект представляет собой полностью автономный робототехнический комплекс (далее «Дрон станция» или РТК) для автономной зарядки дрона и его управления, состоящий из наземной станции и девайса, прикрепляемого к дрону. «Дрон станция» способна работать с большим количеством квадрокоптеров под управлением автопилота PX4 версии 1.9.0 и выше. Наземная станции выполняет автоматическую посадку, центровку относительно контактов модуля питания, зарядку и защиту от внешних факторов окружающей среды. Девайс, прикрепляемый к квадрокоптеру, управляет полетом дрона и его позиционированием в воздухе и при посадке. Также он служит для связи со станцией, как по сотовой связи, так и по сети Wi-Fi. Опционально можно подключить стик для обработки нейронных сетей – Movidius Neural Compute Stick 2 для расширения функционала. Весь процесс может контролироваться дистанционно оператором.

Мы предлагаем комплексное решение, которое превращает обычный квадрокоптер в мощную систему и обеспечивает операторов качественными данными, избегая при этом рисков безопасности и простоев в работе. Данный РТК можно использовать: на нефтегазовых объектах, где требуются частые осмотры во избежание сбоев; как автоматическое решение по сбору аэрофотоснимков на горнодобывающих объектах; как более эффективный, экономичный и безопасный процесс инспекции, который обеспечивает более тщательный мониторинг и контроль, в то время как вы можете продолжаете свою деятельность в обычном формате. Данная разработка легко конфигурируема под конкретные задачи, что позволяет экономить большое количество денежных средств на сложных и рутинных задачах.

## Новизна и актуальность

Квадрокоптеры используются для проведения мониторинга местности, сбора данных, наблюдения за различными объектами.  Однако их использование требует подзарядки аккумуляторов. 
Исходя из этого возникла потребность разработать систему, которая бы минимизировала участие человека и автоматизировала процесс мониторинга. 
Существующие проекты как отечественных, так и зарубежных компаний, предлагают проприетарные компоненты и программное обеспечение. Наша разработка является универсальным решением, совместимым с любым дроном, работающим под популярным открытым автопилотом − PX4.

## Стадия реализации

На текущем этапе разработки были детально проработаны все элементы наземной станции и подвесного устройства в программном комплексе SolidWorks, а также промоделированы основные механические элементы и проверена их работоспособность. Была разработана большая часть программного обеспечения и произведены тесты работоспособности отдельных модулей станции.
![box](https://github.com/Zenkin/ADS/blob/main/Pictures/Бокс.jpg "Бокс")

## Технические характеристики

Работа комплекса заключается в следующем. При обнаружении дроном факта разряда батареи он возвращается на станцию. С помощью специальной системы центровки происходит центровка коптера с посадочным полем станции, далее аппарат подключается к зарядному устройству, и начинается процесс зарядки. Также станция оборудована специальной крышей, защищающей дрон от неблагоприятных погодных явлений. После зарядки и при позволяющей полеты погоде крыша открывается, и дрон продолжает выполнять поставленные перед ним задачи.
Основные технические характеристики разрабатываемой станции:
1.	Размеры дрона: от 290 х 290 х 120 мм до 560 х 570 х 200 мм
2.	Размер посадочной станции (в закрытом виде/ в открытом виде): в закрытом состоянии 1045 x 1125 x 920 мм / В открытом состоянии 1800 x 1125 x 850 мм.
3.	Напряжение, выдаваемое зарядным устройством: от 11 В до 17 В\
4.	Выходной ток: от 2 А до 3.5А
5.	Максимальная скорость ветра при посадке мультикоптера: до 3 м/c
6.	Температурные ограничения: от минус 10 до 25 градусов по Цельсию
7.	Совместимость с дронами: система автопилота PX4 (1.9.0 и выше). Интерфейс USB.

## Экономические показатели

Стоимость разработки на текущем ее этапе складывается непосредственно из себестоимости комплектующих, которые необходимы для ее сборки и заработной платы участников. Сумма на комплектующие равняется около 500 000 рублей, а на заработную плату – 600 000 рублей. Таким образом себестоимость «Дрон станции» составляет около 1 100 000 рублей.

На сегодняшний день проект находится на 3 этапе разработки. По нашим расчетам необходимый объем инвестиций, сопоставим с себестоимостью текущей разработки. Данные средства планируется потратить на изменения внешнего вида станции, чтобы придать ей более современный, легкий и минималистичный вид, что приведет к повышению ее конкурентоспособности на рынке, так как на данном этапе мы разрабатываем макет, который подтверждает работоспособность идеи. На ряду с этим необходима закупка компонентов для нового прототипа и доработки выявленных на текущем этапе недочетов в программном обеспечении и конструкторских решениях.

Проект предусматривает создание макета, на котором можно будет проводить демонстрацию работоспособности всего разрабатываемого комплекса. Планируемый срок завершения создания макета 1 квартал 2021 года.

## Конкурентные преимущества

В процессе мониторинга рынка БПЛА были выявлены следующие конкуренты:
1)	Airbotics. Компания предоставляет автономный взлет и посадку, разработанного этой компанией квадрокоптера, а также автономную загрузку и замену аккумулятора, которая реализуется манипулятором, встроенным в платформу. Имеет закрытый исходный код. Нет возможности посадки какого-либо другого мультикоптера на данную площадку.
Сайт компании: https://www.airoboticsdrones.com/;

2)	COEX. Компания предоставляет посадочную станцию для разработанного специально под нее квадрокоптера, которая включает в себя автономную контактную подзарядку квадрокоптера. Имеет закрытый исходный код. Нет возможности посадки какого-либо другого мультикоптера на данную площадку.
Сайт компании: https://ru.coex.tech/;

3)	DroneBox. Автономный ангар для дрона, играющий роль хранилища, взлетно-посадочной площадки, источника питания и пункта связи.
Сайт компании: https://www.h3dynamics.com/;

4)	Scout. БПЛА оборудован камерами, работающими в разных диапазонах спектра. Станция с ангаром, устойчивым к погодным условиям, также используется для передачи и обработки данных, собранных дроном.
Сайт компании: https://www.american-robotics.com/;

5)	Jack. В станции есть приборы погодного мониторинга, которые определяют, насколько безопасны условия для полета. К системе можно докупить дополнительные док-станции с БПЛА, которые синхронизируются в единый комплекс. Каждая станция обслуживает только один БПЛА.
Сайт компании: http://www.aerovinci.com/.


## Публикации по проекту

По тематике проекта имеется 30 публикаций. Последнии из них:
1. Kosareva E., Zenkin A., Kirilenko I., Kapitonov A. Quadrotor Control Parameters Optimization Using Gradient Descent Method // CEUR Workshop Proceedings - 2020, Vol. 2590, pp. 1-10
2. Kapitonov A., Berman I., Manaenko V., Rzhevskiy V., Bulatov V., Zenkin A. Robonomics as a Blockchain-based Platform for Unmanned Traffic Management of Mobile Vehicles // International Workshop on Research, Education and Development on Unmanned Aerial Systems, RED-UAS 2019 - 2019, pp. 9-17
3. Zenkin A., Berman I., Pachkouski K., Pantiukhin I., Rzhevskiy V. Quadcopter Simulation Model for Research of Monitoring Tasks // Proceedings of the 26th Conference of Open Innovations Association FRUCT - 2020, pp. 449-457

## Преакселерационные программы в рамках проекта
* RUSBASE YOUNG AWARDS
* Инрадел
* ItmoTech
* «Кубок Преактум»

## Мероприятия проекта
* Зимняя школа Университета ИТМО «Тебе решать!»
* Круглый стол «Технические науки»
* IX Конгресс молодых ученых
* Стипендиальная программа Владимира Потанина 2019/2020
* VIII Конгресс молодых ученых
* Выступление в прямом эфире на 78 канале
* Fest HSE

## Достижения проекта
* Золотая медаль олимпиады «Я-Профессионал»
* Хакатон Junction 2019
* Международные соревнования Robotex 2018
* Международные соревнования Robotex 2019
* Всероссийские соревнования Rukami
* Конкурс грантов для студентов вузов, расположенных на территории СПБ, аспирантов вузов, отраслевых и академических институтов, расположенных на территории СПБ
* Международные соревнования Drohnenrennen in Ilmenau 2019
* Конкурс на лучшие научные работы, выполненные слушателями и курсантами военных образовательных учереждений высшего образования Министерства обороны Российской Федерации в 2018 году
* Грант ВТБ
* Движение смелых
* «УМНИК» ЦИФРОВАЯ РОССИЯ 2019

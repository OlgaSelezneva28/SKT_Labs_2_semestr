Курс "Современные компьютерные технологии".
2 семестр.
Изучение языка C#

 Формулировка задания
1. Разработать на основе структур модуль, предоставляющий базовые операции над данными, содержащими учетную информацию предметной области:
           Квитанция продажи автомобилей. Название и дата выпуска автомобиля; Название и адрес автосалона; имя и телефон продавца; дата и цена продажи.
           
2. Разработать классы дата, строка, вектор. 
В качестве полей класса из задания 1 ис-пользовать объекты классов дата и строка. Реализовать класс таблица на основе класса вектор. 
Для исключения дублирования данных учетной информации характеристики, от-носящиеся к различным понятиям предметной, 
реализовать в виде отдельных классов. В классах, отражающих их взаимосвязь использовать указатели на определенные классы.

3. Определить следующие операции для класса из задания 2, классов дата и строка :
=,  == ,<= ,>=, >>, <<.
Дополнительно для класса строка определить +, +=.
Дополнительно для класса дата определить  ++ , -- , сложение и вычитание целого числа

4. Разработать абстрактный класс Obj,  который будет использоваться в качестве базового класса для всех типов данных. 
Он содержит чистые виртуальные функции, которые опре-деляют свойства, общие для всех объектов. 
К ним относятся свойства копирования и уда-ления объектов, их сравнения, а также возможность получить реальное имя типа данных.
Более частными свойствами являются свойства объектов, связанных с возможностью их ввода-вывода на различные устройства. 
Для описания таких свойств ввести абстрактный класс InOut, наследованный от Obj. Все классы предыдущего задания наследовать от класса InOut.
 Для хранения  каждого вида объектов классов предметной области в оперативной памяти необходимо использовать один класс таблицы.

5. Разработать проект при помощи шаблона Windows Forms Application так, чтобы исполнение каждой операции начиналось после нажатия 
соответствующей командной кнопки на форме. Команды меню должны дублировать кнопки на форме. Ввод данных для формирования записей и условий поиска 
производится с помощью текстовых полей textBox. Для конвертирования типа данных String* в тип данных char*можно использо-вать функции модуля MyConvert.  
Просмотр всех записей и результатов выполнения за-просов должно производится с помощью списка listView.
В программе должно быть предусмотрено использование стандартных диалогов Windows для сохранение всех запи-сей в файл и чтение из файла. 

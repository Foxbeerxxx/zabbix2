# Домашнее задание к занятию "`Zabbix часть 2`" - `Татаринцев Алексей`


---

### Задание 1

`Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста`

1. `Открываем Zabbix и открываем Настройки - Шаблоны`
![1](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img1.jpg)`

2. `Задаем имя новому шабону Test CPU1 and Ram `
![2](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img2.jpg)`

3. `добавляем Item - Test CPU LOAD`
![3](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img3.jpg)`

![4](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img4.jpg)`

4. `Создаю Item по загрузке Ram.`
![5](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img5.jpg)`

5. `Как итог в шаблоне есть два item`
![6](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img6.jpg)`


---

### Задание 2

`Добавьте в Zabbix два хоста и задайте им имена <фамилия и инициалы-1> и <фамилия и инициалы-2>. Например: ivanovii-1 и ivanovii-2.`

1. `У меня старый ноутбук и добавить могу только 1  агент`
![7](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img7.jpg)`

2. `Меняю zabbix_agenttd.cong, а точнее параметр server=`
![8](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img8.jpg)`

3. `Данные по хосту начали подтягиваться `
![9](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img9.jpg)`



---

### Задание 3

`Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent`

1. `Мой хост`
![10](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img10.jpg)`

2. `Прикрепленный к нему  шаблон Linux by Zabbix Agent и мой Test load Ram`
![11](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img11.jpg)`

3. `Все значения тянет, мой Item пишет что Ivalid first parametr`
![12](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img12.jpg)`


### Задание 4

`Создайте свой кастомный дашборд`

1. `Захожу в панели и нажимаю Создать панель`
![13](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img13.jpg)`

2. `Имя TestPanelTatarincev`
![14](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img14.jpg)`

3. `Поместил на него нагрузку по оперативной памяти, нагрузку по процессору, список проблем (критичные и важные) на хосте Tatarincev1 и время`
![15](https://github.com/Foxbeerxxx/zabbix2/blob/main/img/img15.jpg)`



....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

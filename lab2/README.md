# Лабораторная работа №2
## Здесь я постараюсь полностью рассказать и показать на что у меня ушло много часов жизни

### Part 1
#### Начало лабораторной работы: Установка ОС и настройка RAID и LVM

Самое начало работы
просто менюшка с информацией о дисках

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part1/1.nachalo_ustanovki.png)


На этом скрине мы уже настроили RAID

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part1/4.Nastroika_RAID.png)

Туть мы закончили настройку LVM

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part1/7.konechnaya_nastroika_LVM.png)

Вот такую красивую информацию о дисках и RAID мы получили в начале работы, после копирования раздела /boot

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part1/10.pervaya_informatsiya_o_diskah.png)
![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part1/11.pervaya_informatsiya_o_RAID.png)

### Part 2
#### В ходе работы отпадает один SSD, мы на ходу заменяем его и благодаря LVM сохраняем все данные и копируем на новый диск

При проверке ВМ на работоспособность после отключения SSD была показана такая информация о дисках и RAID

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part2/2.VM_rabotaet.png)
![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part2/3.proverka_statusa_RAID_posle_udaleniya_ssd1.png)

Информация о дисках после замены SSD на новый и добавления его в RAID

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part2/5.dobavlenie_v_RAID_ssd3.png)
![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part2/6.rezultat_v_mdstat.png)

Конечный результат части 2

![alt text](https://github.com/2kazbek/lab_git/blob/master/lab2/screenshots/part2/7.rezultat_zadaniya2.png)
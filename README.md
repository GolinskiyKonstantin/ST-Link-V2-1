# ST-Link v2.1 REV Type-C

Программатор ST-Link V2-1 это внутрисхемный отладчик и программатор для микроконтроллеров серий STM32.
Программатор имеет SWD SWO RESET UART ( логический уровень 3.3 Вольта но с 5 Вольтовой логикой тоже работает 
имеет конвертор уровней ) интерфейсы для работы с любым STM32 микроконтроллером, установленным на программируемой плате

Поддержка автоматического обновления встроенного программного обеспечения, чтобы обеспечить последующая поддержку компании ST

Gerber_ST-Link v2.1 REV Type-C.zip - Gerber файл платы

Protected-2-1-Bootloader.bin - прошивка

Процесс установки:

	1) Устанавливаем из текущего архива программу STM32 ST-LINK Utility v4.3.0 именно эту версию ( с более поздними работать не будет ).
	
	2) Заливаем Protected-2-1-Bootloader.bin через SWD или DFU ( кому как удобнее ) на наш созданный программатор.

	3) Подключаем только что прошитый наш программатор через UCB и в программе ST-LINK Utility v4.3.0 выбираем -ОБНОВЛЕНИЕ.
	
	4) нам предложит несколько вариантов : нам нужен STM32 + VCP + MSD выбираем его и жмем обновить.

	5) Далее качаем последнюю версию программы STM32CubeProgrammer и в ней обновляем наш девайс до последней прошивки.
	
	6) для работы версии 2-1 и VCP устанавливаем драйвера которые идут в данном архиве.
	
## ФОТО ГОТОВОГО ИЗДЕЛИЯ:
![](https://github.com/GolinskiyKonstantin/ST-Link-V2-1/blob/master/image/ST_Link_V2-1_Type-C_2.jpg)
![](https://github.com/GolinskiyKonstantin/ST-Link-V2-1/blob/master/image/ST_Link_V2-1_Type-C_4.jpg)
![](https://github.com/GolinskiyKonstantin/ST-Link-V2-1/blob/master/image/ST-Link_v2-1_REV_Type-C_1.png)
![](https://github.com/GolinskiyKonstantin/ST-Link-V2-1/blob/master/image/ST-Link_v2-1_REV_Type-C_2.png)


По всем вопросам пишите: golinskiy.konstantin@gmail.com


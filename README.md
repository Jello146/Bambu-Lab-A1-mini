# Bambu-Lab-A1-mini

26.11.2023

Привязка к аккаунту принтера Bambu Lab A1 mini.

1. Нужен ноутбук или компьютер с wifi.
2. Мобильный телефон с установленной программой Bambu Handy с заведенным там аккаунтом (Для китайских версий принтеров требуется аккаунт с номером Китая, который в большестве случаев предоставляет продавец). (https://bambulab.com/en/download/app)
3. Bambu Lab A1 mini c ограничением региона Китай.

Начинаем:
I. Установка, регистрация, настройка VPN с китайским ip адресом на ноутбуке (компьютере):
   
   1. Качаем VPN (https://www.transocks.com/en.html) :
      
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/7f76c729-91bd-4c36-90ef-49485fb85aaa)
      
   2. Устанавливаем :
      Ставим галку, если не стоит и нажимаем кнопку.
      
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/c9685022-8695-40eb-b37b-4ec258e0825d)
      
      Устанавливаем драйвер для сетевого адаптера.
      
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/7766a1ef-ac3f-44ba-871b-10c1df2215e0)
      
      Завершаем установку.
      
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/6f2c6bd4-9839-411e-a98f-c91f2e9ea654)
      
   3. После завершения установки программа сама запустится и приступаем к регистрации:
      Нажимаем сюда и появится окно регистрации.
      
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/1bc18f7d-0d63-48f7-b89b-9ac0bef7090b)
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/0659da6c-b213-4807-9acf-ee7dc69f51bc)
      
      Регистрация:
        1.Выбираем +7
        2.Вводим свой номер телефона
        3.Придумываем пароль
        4.Получаем код на свой телефон (У меня получилось с 3-й попытки, каждая попытка 60 секунд таймаута)
        5.Вводим код.
        6.Завершаем регистрацию.
      
      ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/f806546f-53a0-471c-ba16-bcb5e566f837)

      РЕГИСТРАЦИЯ ДАЕТ 3 ДНЯ БЕСПЛАТНОГО ИСПОЛЬЗОВАНИЯ.

II. Настройка transocks и windows.

   Transocks:
  
   Врубаем глобальный режим:
  
   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/89d1bf11-40b3-4cda-b051-29d37356ad68)

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/525e52e0-9a17-48d3-a969-e238d254fdf2)

   Включаем использование TAP адаптера:

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/71d518d2-2b95-4c33-b308-1ae33bab1729)

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/2409fec9-0af1-4927-a7ff-e0705b6d642c)

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/6000f9c8-c2e3-448b-9745-13569255183d)

   Если подключиться не получается или пропадает интернет после подключения к vpn, то можно попробовать брать другой сервер для подключения (обычно не плохо работает Пекин (BeiJing)):
   
   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/a0897fd5-17db-42ec-8a7e-7118004d257d)

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/9ae5fe9a-92a1-4953-bd35-78ec30b06591)


   Windows:
   
   Включаем Мобильный xoт-спот в windows (10,11):
  
   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/b4f0e453-68c4-43e9-880f-7a1d88fd7037)

   Открываем Сетевые подключения и там должны быть два интресующих нас адаптера (на разных системах могут выглядеть по разному, но суть одна) :
      1. Это VPN 2. Это раздается wifi

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/4528ddcd-871e-4488-bd5d-c56f776cad7b)


   Открываем свойтва адаптера для VPN и даем доступ на раздачу траффика в адаптер с раздачей wifi.

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/5dcae213-48c6-45f5-9f63-ae5c601e3883)

III. Привязываем Bambu Lab A1 mini к аккаунту:
   Запускаем VPN.
   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/338be9a6-e824-4c99-86f0-82ac96f96634)
   
   Проверяем ip на ноутбуке (компьютере) через https://chkip.info/ .

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/dd366602-e57c-4c76-a527-fdcb76c4915e)

   Подключаемся телефоном к раздаче wifi c ноутбука (компьютера) и проверяем ip, должен быть китайский.

   ![image](https://github.com/Jello146/Bambu-Lab-A1-mini/assets/34299327/5c1848ff-1be3-4eea-9b60-b7c9386920fa)
   

   Если все получилось, то подключаем наш Bambu Lab A1 mini к раздаче wifi с ноутбука (компьютера). И начинаем стандартную процедуру регистрации:
   
   1.На принтере переходим Setting -> Account, на этот раз там должен сгенерироваться QR-код.
   
   2.На телефоне открываем приложение Bambu Handy нажимаем добавить новый принтер, затем сканировать QR-код.
   
   3.Откроется сраница привязки, соглашаемся с соглашениями и нажимаем связать.
   
   4.Готово. Мне сразу прилетело обновление, я так и обновился через VPN (надеюсь обновления теперь будут работать и через обычную сеть, но проверить пока не удалось, новые не выходили).
      
   5.Отключаемся от розданного wifi и подключаемся к обычному wifi. VPN можно удалить, так как работает он 3 дня, а дальше либо за деньги, либо зарегистриваться с нового номера.

   


   








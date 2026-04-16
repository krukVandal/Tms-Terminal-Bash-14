# Оптимизация, поиск и исправление ошибок в bash
1. Отладка скрипта через set -x -v -n, намеренно допустил ошибку и вывел её.

<img width="826" height="756" alt="image" src="https://github.com/user-attachments/assets/f873ab71-cbdc-40da-9ab4-e15e16023258" />

2. Запустил скрипт и проверил работоспособность скрипта по предложенному материалу.

<img width="1220" height="754" alt="image" src="https://github.com/user-attachments/assets/dc141057-e477-4a3c-bce9-a36ebd9dc03c" />

3. Провел мелкую оптимизацию и защиту кода.

<img width="1220" height="754" alt="image" src="https://github.com/user-attachments/assets/883660f4-22cd-44ff-8d18-89d78603a156" />

# Дополнительные задания по bash
1. 
 - Написать скрипт, для для мониторинга systemd-службы
 - имя службы задается через позиционный аргумент
 - проверяется налилчие указанной в аргументе функции
 - если она существует - раз в минуту проверяется работает она или нет
 - если НЕ работатет - производится попытка запустить службу (3 попытки с интервалом 5 секунд)
 - после каждой попытки проверяет, запустилась сулжба или нет
 - все действия логируются в файл checker.log в формате
 - написать systemd unit для запуска скрипта как systemd-службы

<img width="1220" height="754" alt="image" src="https://github.com/user-attachments/assets/d156af13-ddfb-474f-b516-190b5b749418" />

<img width="1220" height="754" alt="image" src="https://github.com/user-attachments/assets/75de85ab-a8eb-4f26-a7da-4359759b67ef" />

2. 
 - Написать скрипт для управления приложением simple-server
 - запуск процесса в фоновом режиме с перенаправлением stdout и stderr в файл simple-server.log
 - остановка процесса
 - проверка работоспособности приложения (curl)
 - все действия логируются в файл simple-server-control.log

<img width="1220" height="654" alt="image" src="https://github.com/user-attachments/assets/afba190c-6705-4441-b1be-2438a0eff124" />

<img width="1220" height="716" alt="image" src="https://github.com/user-attachments/assets/d934ad6a-0501-4931-ba80-3e470da88d77" />



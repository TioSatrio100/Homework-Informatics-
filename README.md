## лаборатория домашних заданий
Это задание предназначено для изучения использования **cron** для автоматизации различных системных задач. Вы выполните две части задания: **Простое задание** и **Основное задание**.



## **Простое задание: Автоматическое создание резервной копии директории**

### Вопросы:
1. Напишите простой скрипт bash для создания резервной копии определенной директории. Убедитесь, что резервная копия сохраняется в файл с именем, содержащим дату создания.
2. Добавьте команду в **cron** для автоматического выполнения резервного копирования каждый день в 07:00.
3. Запишите процесс создания резервной копии в лог-файл, который будет содержать время выполнения операции.
4. Документируйте шаги настройки **cron** для выполнения этой задачи.



## **Основное задание: Управление многозадачностью и автоматизация ежедневных отчетов**

### Вопросы:
1. Напишите три скрипта bash, которые выполняют следующие задачи:
   - Очищают директорию `/tmp` каждый час.
   - Отправляют ежедневный отчет о состоянии системы (использование процессора, памяти и активных процессов) по электронной почте каждый день в 07:00.
   - Выключают компьютер автоматически каждый день в 23:00, если нет активных пользователей.
2. Добавьте все эти скрипты в **cron** для автоматического выполнения по расписанию.
3. Документируйте результаты выполнения каждого скрипта. Приложите логи или скриншоты, показывающие успешное выполнение задач.
4. Объясните, как вы убедились, что каждая задача выполняется по расписанию и не мешает другим задачам.

## Ресурсы

1. [Cron Job Tutorial ](https://crontab.guru/)
2. [Create cron job or schedule jobs using bash scripts in Linux or Unix](https://www.golinuxcloud.com/create-schedule-cron-job-shell-script-linux/)
3. [How I use cron in Linux](https://opensource.com/article/17/11/how-use-cron-linux)
4. [Understanding Crontab in Linux With Examples](https://linuxhandbook.com/crontab/)

# AVAstr_microservices

## (Training Repository OTUS)
---
**<details><summary>15_Homework (Docker-2)</summary>**
**В рамках HW было изучено:**

  * Работа с **`Docker-2`**:
   * Сравнение выводов:
	* 1) docker run --rm -ti tehbilly/htop
	* 2) docker run --rm --pid host -ti tehbilly/htop

	* при первой команде выводятся процессы только внутри докера
	* при второй команде выводятся процессы и докера и хостовой машины

   * Создал docker-host
   * Создал свой образ
   * Развернул приложение в контейнере через GCP
   * Загрузил свой образ в Docker Hub и оттуда развернул свой образ, успешно
   * Возобновил работу travis CI для работы с новым репозиторием

</details>

**<details><summary>16_Homework (Docker-3)</summary>**
**В рамках HW было изучено:**

  * Работа с **`Docker-3`**:
   * Работа с докер-образом
   * Запуск приложения в докере
   * Разделение приложения на компоненты
   * Запуск и проверка приложения как микросервисное
   * Оптимизация размера образов (alpine)

</details>

**<details><summary>17_Homework (Docker-4)</summary>**
**В рамках HW было изучено:**

  * Работа с **`Docker-4`**:
   * Создал сетевые интерфейсы none/host/bridge
   * Приложение и базу разнес по разным сетям, а после настроил связь (front_net/back_net)
   * Просмотрел цепочку настрйоки изменения сетей в контейнерах и на хосте
   * Использовал docker-compose для работы с приложением
   * Использовал несколько переменных для работы ocker-compose через файл .env
   * docker-compose формирует имя для своих сущностей по принципу <Имя директории проекта>_<Имя сервиса>_<Порядковый номер>

</details>

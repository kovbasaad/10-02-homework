# Домашнее задание к занятию "`10.2 Кластеризация`" - `Ковбаса Анна`



### Задание 1

*В чем различие между SMP и MPP системами?*

В SMP системах для всех процессоров используется одна основная память и система ввода-вывода, в MPP системах каждый процессор фактически включен в модуль, представляющий собой отдельный компьютер (память, устройства ввода-вывода, сетевой адаптер)

---

### Задание 2

*В чем отличие сильно связанных и слабо связанных систем?*

В слабо связанных системах используется распределенная память (отдельная для каждого процессора) и другие ресурсы; в как сильно связанных - память общая

---

### Задание 3

*Какие преимущества отличают кластерные системы от обычных серверов?*

- масштабируемость,
- отказоустойчивость, 
- отсутствие ограничений на размер узлов и кластеров,
- высокий коэффициент готовности,
- соотношение цена/производительность,
- возможность совместного использования вычислительных ресурсов нескольких машин для решения одной задачи

---

### Задание 4

*Приведите примеры типов современных кластерных систем?*

1. Отказоустойчивые кластеры (High-availability clusters, HA, кластеры высокой доступности): Pacemaker; VMware vSphere; Proxmox VE; XenServer; Openstack
2. Кластеры с балансировкой нагрузки (Load balancing clusters): PostgreSQL, nginx, HAProxy 
3. Вычислительные кластеры (High performance computing clusters, HPC): Azure, NCSA NT Supercluster, Beowulf
4. Системы распределенных вычислений:  kafka, AWS, BOINC 

---

### Задание 5

*Где используется сервис Kafka, rabitMQ?*

- Масштабные Internet of Things-системы: для организации передачи данных с датчиков, сенсоров, контроллеров и других конечных устройств.
- Системы аналитики, финансовые системы: для мониторинга событий и трекера потребления потоков данных пользователями в режиме реального времени.
- Социальные сети, телеком-операторы, онлайн-игры: передача и обработка данных.
- Системы геопозиционирования:  передача сообщений между онлайн- и офлайн-системами, а также для интеграции средств мониторинга в инфраструктуру.


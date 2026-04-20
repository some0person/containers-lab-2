# Часть 1. Подготовка инфраструктуры

## 1.1 Установка Minikube и kubectl

### 1.1.1 Установка kubectl

![alt text](image.png)

### 1.1.2 Установка Minikube

![alt text](image-1.png)

### 1.1.3 Запуск Minikube с драйвером Docker

![alt text](image-2.png)

## 1.2 Настройка доступа к GHCR

![alt text](image-3.png)

![alt text](image-4.png)

## 1.3 Подготовка репозитория

![alt text](image-5.png)

# Часть 2. Знакомство с kubectl и базовыми концепциями

## 2.1 Первые команды kubectl

### Задание 2.1.1: Исследуйте кластер

![alt text](image-6.png)

![alt text](image-7.png)

![alt text](image-8.png)

![alt text](image-9.png)

### Самостоятельно!: Сохраните вывод команды kubectl get nodes -o wide в файл nodes.txt и включите его в отчет.

![alt text](image-10.png)

## 2.2 Работа с подами (Pods)

### Задание 2.2.1: Работа с подом

![alt text](image-11.png)

![alt text](image-12.png)

![alt text](image-13.png)

![alt text](image-14.png)

![alt text](image-15.png)

![alt text](image-16.png)

### Самостоятельно! Создайте под с вашим Go-приложением из ЛР1 (образ из GHCR). Убедитесь, что он запускается, но обратите внимание, что без базы данных он будет падать с ошибкой. Сохраните логи упавшего пода в файл crash-logs.txt

![alt text](image-17.png)

![alt text](image-18.png)

![alt text](image-19.png)

![alt text](image-20.png)

![alt text](image-21.png)

## 2.3 Работа с ReplicaSet

### Задание 2.3.1: Управление ReplicaSet

![alt text](image-22.png)

![alt text](image-23.png)

![alt text](image-24.png)

## 2.4 Работа с Deployment

### Задание 2.4.1: Разверните Deployment

![alt text](image-25.png)

![alt text](image-26.png)

![alt text](image-27.png)

![alt text](image-28.png)

### Самостоятельно создайте Deployment для PostgreSQL, убедитесь, что поды PostgreSQL и Go-App запускаются, проверьте логи Go-App — он должен пытаться подключиться к PostgreSQL, но не сможет, так как сервиса еще нет

![alt text](image-29.png)

![alt text](image-30.png)

![alt text](image-31.png)

![alt text](image-32.png)

![alt text](image-33.png)

## 2.5 Работа с Service

### Задание 2.5.1: Создайте и протестируйте сервисы

![alt text](image-34.png)

![alt text](image-35.png)

![alt text](image-36.png)

![alt text](image-37.png)

## 2.6 Полный стек приложения

![alt text](image-38.png)

# 3. Эксперименты с масштабированием

## 3.1 Масштабирование до 5 реплик

![alt text](image-39.png)

![alt text](image-40.png)

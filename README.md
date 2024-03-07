# Домашнее задание к занятию "10. Helm" - Баранков Антон"

### Задание 1. Подготовить Helm-чарт для приложения
1. Необходимо упаковать приложение в чарт для деплоя в разные окружения.  
2. Каждый компонент приложения деплоится отдельным deployment’ом или statefulset’ом.  
3. В переменных чарта измените образ приложения для изменения версии.  

### Задание 2. Запустить две версии в разных неймспейсах
1. Подготовив чарт, необходимо его проверить. Запуститe несколько копий приложения.  
2. Одну версию в namespace=app1, вторую версию в том же неймспейсе, третью версию в namespace=app2.  
3. Продемонстрируйте результат.  

**Немного не понял задание, поэтому на всякий случай сделал не 3 одинаковые копии с разным именем версий, а чтобы в каждой версии с разным именем запускались приложения с разными версиями.**  

[Chart helm](./img/helm)  


![Скриншот](img/1.JPG)


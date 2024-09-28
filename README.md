# FPV controller overlay for OBS

Визуализация положения стиков в HTML для отображения в OBS и других стриминговых программах, поддерживающие отображение браузера как слоя.

[![FPV STICK OVERLAY](https://img.youtube.com/vi/pNcTPkidWYE/0.jpg)](https://www.youtube.com/watch?v=pNcTPkidWYE)

Демонстрация 👆

# Настройка

1. Скачайте весь репозиторий

2. Добавьте источник браузер и укажите локальный файл index.html 
   
   ![OBS vonfig.png](https://github.com/recoshet/FPV-controller-overlay-OBS/blob/main/img/OBSconfig.png?raw=true)

Настройте ширину `520` и высоту `270`. Для оптимизации можете ограничить FPS (тестировал на встроенной видюхе). 

CSS: `body { background-color: rgba(0, 0, 0, 0); overflow: hidden; }`

3. Маппинг каналов в изначально назначен на `AETR` , рекомендую создать новую модель в аппаратуре. Либо можете поправить номера каналов в исходном коде.

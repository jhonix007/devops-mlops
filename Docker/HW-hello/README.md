# Домашняя работа: Docker и микросервисная архитектура

- Базовый образ: `continuumio/miniconda3:latest`
- Рабочая директория: `/app`
- Скрипт: `1.sh` → выводит `Hello Netology`
- Пакеты: `mlflow`, `boto3`, `pymysql`

## Сборка
```bash
docker build --progress=plain -t netology-ml:netology-ml . 2>&1 | tee build.log


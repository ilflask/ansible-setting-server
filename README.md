# Быстрое развертывания OpenVPN

## Настройка
Файле cluster нужно указать список серверов для развертывания

## Запуск установки
Команда:

```bash
ansible-playbook -i inventory config.yml -K
```
## Файл для client openVPN
Файлы будет в директори ./config/*

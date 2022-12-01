# Как запустить

## Vagrant

1. Качаем centos/8:

```
vagrant box add centos/8 --force
```

2. Запускаем
```
vagrant up
```

3. Подключаемся по ssh
```
vagrant ssh slynellP3
```

## Мы в виртуалке

1. Зайти под root-ом (меняем пароль на любой и заходим)
```
sudo passwd root
su -
```

2. Копируем на виртуалку все файлы

3. Запускаем `setup.sh`
4. Запускаем `deploy.sh` (!!! Важно проверить пути для yaml файлов)
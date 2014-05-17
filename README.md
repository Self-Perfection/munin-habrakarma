munin-habrakarma
================

Самый легковесный Хабра-кармограф для munin!

Установка (на примере дистрибутива с systemd):

```bash
sudo wget -O /etc/munin/plugins/habrakarma_ВАШЛОГИН https://github.com/Self-Perfection/munin-habrakarma/raw/master/habrakarma_ && sudo chmod -c 755 /etc/munin/plugins/habrakarma_* && sudo systemctl restart munin-node
```

В команде выше нужно указать ваш настоящий логин в пути файла для сохранения скрипта и, возможно, заменить команду перезапуска munin-node на специфичную для вашего дистрибутива. *ВСЁ*

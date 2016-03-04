В дополнение к выбору конфигурации самого приложения вы можете также настраивать Ember CLI. Эти конфигурации можно составить, если добавить их в файл `.ember-cli` в корне приложения. Или можно передать их в качестве аргументов в командную строку программы.

Например, часто требуется изменить порт, с которого Ember CLI обслуживает приложение. Это можно сделать, если передать номер порта из командной строки так: `ember server --port 8080`. Чтобы сохранить эту конфигурацию, отредактируйте файл `.ember-cli` таким образом:

```json
{
  "port": 8080
}
```

Чтобы просмотреть весь список опций командной строки, запустите `ember help`. 
# Dron

Запускатор команд

Вместо написания `bash` скриптов

## Пример конфига

Файл `dron.yaml`

> Все приведенные конфиги актуальны и рабочие.  
> Файл примера - не актуальный и нужен только для разработки

### v1 [31.10.2020]

```yaml
commands:
  - name: up_www
    args:
      arg0: WiRight
      arg2: Reader
    commands:
      - echo hello $arg0
```

Если в примере нет чего-то - значит не реализовано
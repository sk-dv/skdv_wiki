### Crear usuario

```
~$ adduser <username>`
~$ usermod -aG sudo,www-data <username>
```


Configurar SSH para el nuevo usuario

```
~$ su - <username>
~$ mkdir ~/.ssh
~$ chmod 700 ~/.ssh
~$ nano ~/.ssh/authorized_keys // put ssh pub key here
~$ chmod 600 ~/.ssh/authorized_keys
```

### Consola conectadas

Conocer terminales conectadas

```
~$ who | w
```

Lista de PID de las consolas conectadas

```
~$ ps -ft <terminal-id>
```

### Matar proceso

```
~$ kill -9 <process-id>
```
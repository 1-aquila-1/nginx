<b>Arquivo do nginx</b>
- nginx.conf

Caminho do arquivo: `/etc/nginx/`

<b>.conf - Verificar se a configuração feita no arquivo de configuração está correto</b>
```
nginx -t
```

<b>nginx.conf</b>

`worker_processes`

A variável `worker_processes` recebe os seguintes valores:

-  `auto` Significa que o nginx vai utilizar toda a capacidade da máquina, como: memória, CPU etc.

Exemplo:
```
worker_processes auto;
```
Podemos também limitar a quantidade de recurso que o nginx pode utiliza da máquia.

Exemplo:
```
worker_processes 4;
```



`events`

Nesta variável são determinada o números de workers que o nginx pode trabalha. O recomendado é deixa como está.

```

```
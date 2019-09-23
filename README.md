
## Monitaramento de dados
Vazamento de dados pode ser um problema para as
- Empresas
- Funcionários
- Clientes

Dessa forma monitorar é preciso, assim evitando ao maximo possiveis problemas.

Vamos imaginar como seria se um administrador tem suas credencias vazadas.

Ou então uma startup tem seu codigo vazado para a internet, já imaginou o problema ?

### Vazamentos emails clientes e funcionarios
Sabendo isso vou compartilhar alguns projetos que auxiliam na busca de vazamentos de emails e que pode nos ajudar.
```sh
https://haveibeenpwned.com/
```
> Com o haveibeenpwned conseguimos ver se algum email já teve alguma senha comprometida.


### Vazamento de keys
Infelizmente muitos desenvolvedores acabam inserindo em commits chaves que não deviam fazer parte do codigo e quando o projeto é publico isso fica ainda pior pois outras pessoas podem ter acesso a elas.
```sh
https://github.com/search?q=remove+key&type=Commits
```

### Monitorar Pastebins
Pastebin é um site que nos auxilia tendo a possibilidade de criar uma anotação como um bloco de notas, onde podemos editar e ainda configurando para nunca apagar.

Claro que com eles outras soluções apareceram como o
- gist.github.com  
- ghostbin

Mas infelizmente são muito usados tambem para hospedar vazamentos e sempre é bom monitorar para ver se não temos informações sensiveis.

Podemos usar o google e tecnicias de google hacking para analisar, podemos usar
```sh
"aluno.green@gmail.com" site:pastebin.com
"98116-9227" site:pastebin.com
"greenmind" site:pastebin.com
```

## SIEM
O software identifica e categoriza incidentes e eventos, além de analisá-los.

O software oferece dois objetivos principais, que são: fornecer relatórios sobre incidentes e eventos relacionados à segurança, como logins bem-sucedidos e com falha, atividade de malware e outras possíveis atividades mal-intencionadas e enviar alertas se a análise mostrar que uma atividade é executada em conjuntos de regras predeterminados e, portanto, indica um possível problema de segurança.

## Conclusão
Unindo esses pontos conseguimos evitar possiveis acidentes e se ouver algum monitorar o mas rapido possivel para a melhor tomada de decisão.

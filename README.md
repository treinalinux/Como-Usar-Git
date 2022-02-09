# COMO USAR O GIT

Vamos aprender como usar o git e github

Primeiro é importante entender que o git é um comando, que pode criar um repositório local para controle de versão e também pode enviar para respositórios remotos.
O githup é um hub com vários projetos e repositórios.

Acho que a melhor forma de explicar seria, quando você precisa enviar um presente dentro de um caixa de presentes:

Você vai para uma loja e compra um presente e envia para alguém.

Se você quiser quebrar o texto acima, certamente deve enteder a lógica do git:

- git init: Você vai comprar um presente;
- git add presente: Você adiciona um presente comprado na caixa de presentes:
- git commit -m 'Dedicatória: Para alguém muito especial': Você escreve uma dedicatória para alguém;
- git push -u origin main: Você envia o presente para alguém remoto;

Bom, espero que tenho entendido, mas vamos ver explicar os comando do git para melhor entendimento.

---

## CRIANDO CHAVES

Criando chaves privadas e públicas para usar no github.


Aqui vamos criar uma chave do tipo '-t' rsa, com um tamanho em bits '-b' de 4096. Tal chave será usada em repositórios remotos.

Execute o comando abaixo e depois apenas dê enter até ele criar a chave, no caso será sem senha.

```bash
ssh-keygen -t rsa -b 4096

```

---

## GIT

### COMANDOS GIT

#### INICIANDO 

Iniciando um repositório local


```bash
git init
```

#### ADICIONANDO

Comando 'git add' é usado para adicionar um ou mais arquivos em staging

Vamos adicionar primeiro um arquivo.

```bash
git add arquivo.py

```

Agora vamos adicionar todos os arquivos que estiverem no diretório e subdiretórios.


```bash
git add --all
```

#### STANGING

É a área de preparação para commits, onde vemos a coleção de arquivos alterados ou criados que farão parte do próximo commit


#### STATUS

Mostra o ambiente de staging, basicamente você verá a lista de arquivos alterados.

```bash
git status
```

#### COMMIT

O commit com  '-m' na mais é do que aquela mensagem que você coloca em uma caixa de presente, um dedicatória curta que faz sentido com o presente.

O commit é um marcador no tempo, ele vai te ajudar quando precisar voltar alguns alterações. Por isso, é importando usar o '-m' para passar uma mensagem que faça sentido para uma ou mais alterações.

O ideal seria a cada alteração, commitar tal mudança.

```bash
git commit -m 'novidades: melhorias na compressão dos backups'
```


####  

```bash

```



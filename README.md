# Criação de um Phishing com o Kali Linux
Neste desafio de projeto foi criado um Phishing para capturar senhas de login do Facebook.

## Ferramentas
- Kali Linux
- setoolkit

## Configurando o Phishing no Kali Linux
- Abrir o terminal e executar o comando de acesso ao root: ``` sudo su ```
- Iniciar o setoolkit: ``` setoolkit ```

![Passo 01](./imagens/Passo%2001.png "Passo 01")

- Selecionar o tipo de ataque: ``` Social-Engineering Attacks ```

![Passo 02](./imagens/Passo%2002.png "Passo 02")

- Selecionar o vetor de ataque: ``` Web Site Attack Vectors ```

![Passo 03](./imagens/Passo%2003.png "Passo 03")

- Selecionar o método de ataque: ``` Credential Harvester Attack Method ```

![Passo 04](./imagens/Passo%2004.png "Passo 04")

- Método de ataque: ``` Site Cloner ``` 

![Passo 05](./imagens/Passo%2005.png "Passo 05")


- Obter o endereço da máquina: ``` ifconfig ```
- Neste exemplo, usarei a URL para clone: [http://www.facebook.com](http://www.facebook.com/)


![Passo 06](./imagens/Passo%2006.png "Passo 06")
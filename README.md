# APPSendEmail

Esse Projeto foi construido na linguagem PHP, utilizando a bliblioteca PHPMailer que foi projetado para enviar e-mails com segurança e facilidade via servidor web. Sendo um projeto bastante simples, intuitivo e seguro.

## Requisitos

Para executar o projeto, será necessário instalar os seguintes programas:

- [Apache: Necessário para a linguagem PHP](https://httpd.apache.org/download.cgi)
- [XAMPP: Servidor necessário para rodar a aplicação](https://www.apachefriends.org/pt_br/download.html)
- [Netbenas: Recomendação de IDE](https://netbeans.apache.org//kb/docs/php/quickstart_pt_BR.html)

## Desenvolvimento

Para iniciar o desenvolvimento, é necessário clonar o projeto do GitHub num diretório de sua preferência:

```shell
cd "diretorio de sua preferencia"
git clone git@github.com:HugoFillipe/AppSendEmail.git
```

O comando irá baixar todas dependências do projeto e criar um diretório. Assim podendo executar o codigo em algum navegador, se alguma coisa falhar, o console do proprio navegador vai acusar o erro.

## Configuração

A biblioteca PHPMiler que se encontra dentro da arquivo "processo_envio.php" requer um Email + senha para que o processor de host ocorrá, sem esses critérios o processo de envio de e-mail não ocorrerá. 

Para executar o projeto, é necessário utilizar o Xampp para o apache rodar no servidor local e o arquivo "app_send_mail" ficará dentro da pasta "C:\xampp\htdocs" para que assim todos os arquivos estejam alocados dentro do Xampp, podendo assim rodar no Localhost.


## Finalidade

O projeto foi desenvolvido com a finalidade de Envio de E-mail de forma rápida e segurá ultilizando-se da linguagem PHP.


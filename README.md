# Notas do Qualisaude

## Sobre o projeto
Este projeto foi desenvolvido para permitir que os alunos do Qualisaúde visualizem o envio de seus trabalhos e respectivos prazos de forma simples e organizada.

A aplicação foi construída utilizando **HTML, CSS e JavaScript**.

A motivação para o desenvolvimento surgiu da dificuldade dos alunos em acompanhar seus envios pelo AVA, sendo necessário o envio semanal de relatórios em PDF. Com esta solução, alunos e orientadores podem acessar essas informações de maneira mais prática e rápida.

## Pré-requisitos

- Conta no GitHub  
- Conta no Netlify (hospedagem gratuita)  
- Conta no JSONbin.io (armazenamento gratuito)  
- Git instalado no computador  

## Configuração inicial (executar apenas uma vez)

1. Acesse o site jsonbin.io, crie uma conta e crie um novo Bin com o seguinte conteúdo:
```json
{"init": true}```
2.Copie o BIN ID gerado
3.Vá em Account → API Keys, crie uma chave e copie
4.Abra o index.html e preencha as duas linhas:

```const JSONBIN_ID  = 'seu_bin_id_aqui';
const JSONBIN_KEY = 'sua_api_key_aqui'; ```

5.Faça o deploy dos dois arquivos no Netlify conectando ao repositório GitHub

## Uso semanal

Acesse o site, clique em Admin, digite a senha
Faça upload do .xlsx exportado do Google Sheets
Os dados são salvos na nuvem automaticamente — todos os usuários verão a versão atualizada
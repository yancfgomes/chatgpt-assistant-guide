# Como Utilizar o ChatGPT como Copiloto de Programação 

## Sumário

1. [Regras do Jogo](#1-regras-do-jogo)
2. [Pair Programming with ChatGPT](#2-pair-programming-with-chatgpt)
    - [Solicitando unidades com conjuntos de regras](#solicitando-unidades-com-conjuntos-de-regras)
    - [Criando Funções Explicitadas](#criando-funções-explicitadas)
    - [Criando Testes Unitários Com GPT](#criando-testes-unitários-com-gpt)
    - [Desacoplando Códigos](#desacoplando-códigos)
    - [Utilizando Racional de Código](#utilizando-racional-de-código)
    - [Convertendo Códigos e Tornando-os Mais Amigáveis](#convertendo-códigos-e-tornando-os-mais-amigáveis)
3. [Documentações Profissionais e Instantâneas](#3-documentações-profissionais-e-instantâneas)
    - [Forma Genérica (não comum no dia a dia)](#forma-genérica-não-comum-no-dia-a-dia)
    - [Modelo Específico](#modelo-específico)
    - [Comentários Baseados em Templates](#comentários-baseados-em-templates)
4. [Utilidades](#4-utilidades)
    - [GPT as a Mentor](#gpt-as-a-mentor)
    - [Cheat-Sheet](#cheat-sheet)

## 1. Regras do Jogo

- Primeiro saiba o que você quer fazer
- Segundo, código extenso fica com respostas quebradas. Trabalhe com nível de unidade (função)

## 2. Pair Programming whith ChatGPT

• Solicitando unidades com conjuntos de regras
```
Crie uma função que retorne somente os numeros de um conteúdo Alfanúmerico

{REGRAS}:
> Linguagem: Javascript
> Input: code:string
> output: numberld:number
> aplique boas práticas de clean code
```
• Criando Funções Explicitadas
```
Implemente a lógica da função abaixo em <linguagem>:
<code with comments>

```


• Criando Testes Unitários Com GPT


```
Implemente testes unitários para a função abaixo

{REGRAS}:
> linguagem x
> utilize a biblioteca y
> crie pelo menos 3 testes unitários

<code>

```

• Desacoplando Códigos

```
refatore o código abaixo aplicando os conceitos de clean code e single responsability

{REGRAS}:
> linguagem x
> crie um código que seja testável
> e implemente ao menos 1 teste utilizando <framework de teste>

```


• Utilizando Racional de Código

```
me explique o que essa função em linguagem x está fazendo e adicione comentários:
<code>

```

• Convertendo Códigos e Tornando-os Mais Amigáveis


```
converta esse código de linguagem x para linguagem y e adicione comentários:
<code>

```

```
refaça o código de uma maneira mais simples e entendível por humanos

```

## 3. Documentações Profissionais e Instantâneas

• Forma Genérica (não comum no dia a dia)
```
faça uma documentação da função abaixo:
<code>

```

• Modelo Específico
```
crie uma documentação para a função abaixo, no mesmo modelo dessa documentação <documentação>
<code>
```
• Comentários Baseados em Templates
```
adicione o modelo de comentário abaixo na função linguagem x abaixo
<modelo>
<code>

```

## 4. Utilidades 
•GPT as a Mentor
```
me ajude a criar este projeto abaixo me indicando como fazer e quais bibliotecas utilizar para construir da maneiraa mais práticas

{REGRAS}
> linguagem: TypeScript (exemplo)
> plataforma node (exemplo)
> crie no padrão de clean Arch

{FEATURES}
> realizar o upload de uma imagem
> validar o número de cartão de crédito de um usuário

```
• Cheat-Sheet

```
crie uma Cheat-Sheet para os principais comandos de power shell (exemplo)

```




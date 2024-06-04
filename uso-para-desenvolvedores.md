### Curso: Formação ChatGPT for Devs - DIO

#### Módulo 2: Uso para Desenvolvedores

#### Curso: Como Utilizar o ChatGPT para Simular Entrevistas Técnicas

1. **GPT como Entrevistador**
    - Exemplo de prompt:
        ```
        [ Comporte-se como se fosse um entrevistador técnico SENIOR EM FRONT-END, ESPECIALISTA EM REACT e me entreviste para uma posição de desenvolvedor front-end Júnior
        {REGRAS}
        > Tente manter um diálogo amigável comigo
        > Me faça 5 perguntas para uma vaga de desenvolvedor front-end júnior
        > Me faça uma pergunta por vez se possível
        > Me faça perguntas sobre as temáticas: React, Javascript e CSS (requisitos da vaga)
        > Tente avaliar minhas skills técnicas e minhas soft skills
        > Ao final, me dê um feedback sobre minhas respostas ]
        ```

2. **Entre no DNA Técnico da Empresa Desejada**
    - Tenha no GitHub um exemplo de projeto que tenha relação com a vaga desejada:
        - Demonstra domínio de uma plataforma de Git, trabalho em equipe e organização
    - Tenha um README do projeto selecionado e o seu README do perfil
    - Tenha um LinkedIn sincronizado com o GitHub
    - Não "atire para todos os lados"

3. **Entre no DNA da Soft Skills da Empresa Desejada**
    - "Dossiê" da empresa
        - Exemplo de prompt:
            ```
            [ faça um resumo em bullet points sobre a cultura da empresa X ]
            ```
    - É útil para descobrir coisas em comum entre você e a empresa

4. **Como ir Além do ChatGPT**
    - Entrevista simulada VS Entrevista Real
        - Linguagem corporal
        - Tom de voz
        - Treine essas entrevistas falando no espelho ou com alguém
        - Brain dumps: compartilhamento de dicas de processos seletivos
        - Pesquise o LinkedIn e GitHub de funcionários da empresa para entender o DNA da empresa

#### Curso: Refatorar Códigos

5. **Refatoração de códigos**
    - Limpar e organizar o código sem mudar sua funcionalidade
    - Melhorar a estrutura, legibilidade e eficiência do código
    - Reduzir a dívida técnica
    - Regra da Fatoração: nada pode "quebrar"

#### Curso: Praticando Refatoração

6. **Clonando o Projeto**

7. **Códigos eficientes**
    - Leve ao chat pequenos pedaços para refatorar, como funções, por causa do limite do ChatGPT
        - Exemplo de prompt:
            ```
            [ reescreva o código <linguagem> abaixo de uma maneira mais eficiente e aplicando boas práticas e me explique depois as regras aplicadas <código> ]
            ```
        - Exemplo de prompt:
            ```
            [ aplique <modificação> no código ]
            ```

8. **Melhorando a organização do seu projeto**
    - Exemplo de prompt:
        ```
        [ converta o código abaixo para utilizar uma estrutura diferente de organização <código> ]
        ```

9. **Single Responsibility com ChatGPT (+recomendada)**
    - Princípio de Responsabilidade Única
        - Cada classe, função ou arquivo deve ter apenas uma razão para mudar
        - Exemplo de prompt:
            ```
            [ quebre o arquivo em outros arquivos, onde cada um tem uma responsabilidade única e me explique o que foi feito: <código> ]
            ```

10. **Simplificação de código**
    - Exemplo de prompt:
        ```
        [ simplifique o bloco de código abaixo e me explique o que foi feito: <código> ]
        ```
    - Um código melhor não significa um código com menos linhas
    - Não simplifique tudo!

11. **Código mais legível**
    - Exemplo de prompt:
        ```
        [ refatore o código para tornar ele mais legível para uma leitura mais humana: <código> ]
        ```

12. **Aplicar paradigmas de programação**
    - Exemplo de prompt:
        ```
        [ converta o código para o paradigma de POO: <código> ]
        ```

13. **Insights de limpeza no seu código (+recomendada)**
    - Exemplo de prompt:
        ```
        [ remova do código, partes desnecessárias nessa função ]
        ```

14. **Modularizando seu código (organiza o código por seções) (+recomendada)**
    - Exemplo de prompt:
        ```
        [ modifique esse código para torná-lo mais modular: <código> ]
        ```

15. **Conjunto de boas práticas (+ genérica, após as outras modificações anteriores)**
    - Exemplo de prompt:
        ```
        [ aplique as boas práticas do clean code no código abaixo e me explique o que foi feito: <código> ]
        ```

16. **Refatorando a estrutura de pastas e combinando técnicas**
    - Aconselhável consultar no início do projeto
    - Exemplo de prompt:
        ```
        [ crie uma sugestão de estrutura de pastas mais organizada para projetos que contenham arquivos <linguagem de programação> e com boas práticas ]
        ```
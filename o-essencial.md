**Formação ChatGPT**

    - O ChatGPT é a interface
    - O algoritmo por trás do ChatGPT é o algoritmo DaVinci
    - Cria conteúdos inéditos

---

**ChatGPT - O Essencial**

----
  1. **Prompts assertivos para ChatGPT**

        - **Prompts ricos - modelo de perguntas**
  

        - **FTAE**:
          - **Estrutura do prompt**: Me `[FUNÇÃO]` um `[TIPO DE TEXTO]` sobre `[assunto]` nesse `[estilo]`

            ```bash
            Função: (escreva/resuma/traduza/crie tópicos)
            ```

            ```bash
            Tipo de texto: (roteiro/post para blog/artigo/poema/postagem para instagram)
            ```

            ```bash
            Assunto: (I.A, futebol, música, filme... etc)
            ```

            ```bash
            Estilo: (personalidade, escritor, filósofo)
            ```

          - **Exemplos**:

            - Me [crie tópicos] um [artigo] sobre [macarrão]
            - Me [escreva] um [texto] sobre [inteligência artificial]

          - **Tom de voz**

            - **Direcionamento da comunicação**: Escreva para quem aquela comunicação deve ser direcionada para calibrar o entendimento e naturalidade da resposta


            ```bash
            me explique como se fosse (para uma criança de 10 anos, de um jeito mais sênior)
            ```

          - **Exemplos**:
            
            - Me escreva em formato de carrossel do instagram uma postagem sobre programação me explicando o que é DOCKER em um estilo informal e descontraído como se tivesse sido postado por um influencer de tecnologia, `explique como se fosse para uma criança de 10 anos`
            - Me escreva em formato de carrossel do instagram uma postagem sobre programação me explicando o que é DOCKER em um estilo informal e descontraído como se tivesse sido postado por um influencer de tecnologia, `explique com um tom de voz mais sênior`

---

   2. **Técnica Prompt 3R**:

         ```bash
            Me escreva um artigo sobre primeiros passos no Docker, em tom de conversa com uma criança de 10 anos. Agora, use os itens em {RESUMO} para o {ROTEIRO} seguindo as {REGRAS}
            {RESUMO}
            [Autoridade]: Felipe, um desenvolvedor Fullstack
            [Avatar]: Desenvolvedores Júniors
            [Problema]: Como instalar o Docker
            {ROTEIRO}
            Olá eu sou [Autoridade] e vou ajudar o [Avatar]
            Hoje vamos resolver o [Problema]
            {REGRAS}
            > Siga o {ROTEIRO} acima e substitua os elementos entre [ ] por aqueles listados em {RESUMO} acima.
            > Mantenha o tom e ritmo, mas reescreva as palavras em {ROTEIRO} para que seja diferente do original, expandindo ou mudando conforme necessário.
         ```

        
---

   3. **ACT Commands - Seu ChatGPT como Assistente Virtual**

        - **Comandos de interação**:

            - **Resumo de Livro**:
                ```bash
                me escreva sobre o livro "nome" em formato de bullet points, em um tom de voz simplificado.
                ```
                ```bash
                me resuma o livro "nome" em formato de bullet points em um tom de voz simplificado, resumindo os principais capítulos
                ```

            - **Cronograma**:
              ```bash
                - Exemplo: Crie um cronograma de estudos sobre <assunto> dividido em módulos e tópicos, onde eu possa aprender X em Y dias com Z h de estudo por dia. Organize por dia da semana (Opcional?)
              ```
            - **Cronograma de Estudos para uma Vaga Pretendida**:
                ```bash
                - Exemplo: Crie um cronograma de estudo para que eu consiga estudar e me preparar para a vaga abaixo:
                <descrição da vaga>
                ```

            - **Simulando Console**:
                - Exemplo: act as a JavaScript console

            - **Consultor Especialista Virtual de UI/UX**:
                - Exemplo: Comporte-se como um consultor de UI/UX e responda me ajudando tudo com as dimensões da imagem e dicas de como implementar da melhor maneira

            - **Use o ChatGPT como Banco de Dados**:
                - Exemplo: act as a SQL terminal
                - Exemplo: create a table with name, age, and description with 10 values randomics

            - **Commits Semânticos com ChatGPT**:
                - Exemplo: act as a commit message generator always semantics commits

            - **Atuação com Regras**:
                - Exemplo: Comporte-se como se fosse um especialista de front-end sênior que está me orientando a programar melhor
                - Regras:
                    > Sempre que eu te informar o que estou fazendo faça um checklist de boas práticas de front-end
                    > Sempre que eu te informar o que estou fazendo, ao final, envie uma sugestão de código
                - Interaja com o chat mostrando o que você quer fazer no projeto, ao invés de perguntar para o chat 

            - **Ativando o modo tutorial de prompt do ChatGPT**:
                - Exemplo: Act as a ChatGPT prompt generator

            - **Criando uma ferramenta de posicionamento profissional**:
                - Regras:
                    > Me ajude no que postar: crie um calendário de sugestões de posts de engajamento para o meu LinkedIn
                    > Sempre fale de Javascript: sempre sugira posts referente a Javascript
                    > Me ajude a encontrar imagens: sugira sites ou ferramentas para construir essas imagens

            - **Criando versões artificiais de figuras famosas**:
                - Exemplo: Act as 'Character' from 'Movie/Book/Anything'

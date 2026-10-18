# Prompts por etapa da comunicação de evidências

Troque o que está entre colchetes. Ao fim de cada etapa há um ponto de conferência humana: a etapa seguinte só começa depois dele. Texto com dado pessoal ou informação restrita não vai para ferramenta aberta.

### 1 · Definir público e decisão

```
Vou transformar o texto abaixo numa versão curta. Antes de escrever qualquer coisa, me ajude a definir o público. Faça três perguntas, uma de cada vez: quem vai ler, o que essa pessoa precisa decidir e o que ela já sabe sobre o tema. Depois, resuma as respostas em uma frase: "Para [quem], que precisa decidir [o quê]". Não resuma o texto ainda.
Texto: [cole o texto ou anexe o arquivo]
```

Conferência humana: a frase de público e decisão está escrita antes do primeiro pedido de versão.

### 2 · Marcar o que não pode mudar

```
Leia o texto abaixo e liste, sem resumir nem reescrever: o achado principal; cada achado com o grau de certeza que o texto dá (efeito, sem efeito, inconclusivo); o contexto de cada estudo citado (país, etapa, público, formato, tamanho); as limitações do método, inclusive as que só aparecem na seção de método; e as recomendações que o texto faz. Para cada item, copie entre aspas o trecho literal e a página. Não acrescente nada que não esteja no texto.
Texto: [cole o texto ou anexe o arquivo]
```

Conferência humana: quem conhece o tema confere a lista, e as limitações de método estão nela.

### 3 · Pedir a versão com estrutura e regras

Use o prompt da versão que precisa. Cole a lista da etapa 2 junto com o texto, se quiser reforçar o que não pode mudar.

Prompt 1 · resumo para liderança

```
Transforme o texto abaixo num resumo de uma página para a liderança de uma organização, seguindo exatamente esta estrutura: pergunta; o que se sabe; com que segurança; o que isso permite decidir e o que não permite; limites. Regras: não acrescente nenhuma informação, número ou recomendação que não esteja no texto; mantenha o grau de certeza de cada achado (se o texto diz que o efeito é inconclusivo, o resumo diz inconclusivo); mantenha o país e o contexto dos estudos; não use adjetivos de destaque. No fim, liste as frases do texto original em que cada parte do resumo se apoia.
[texto]
```

Prompt 2 · roteiro de apresentação

```
Com base só no texto abaixo, escreva um roteiro de apresentação de cinco minutos em cinco blocos: a pergunta e por que importa; o achado principal; com que segurança; o que isso significa para a decisão; o que ainda não se sabe. Para cada bloco, uma mensagem central em uma frase e o que dizer em até 80 palavras. Mesmas regras: nada que não esteja no texto, grau de certeza mantido, contexto dos estudos explícito.
[texto]
```

Prompt 3 · nota interna

```
Com base só no texto abaixo, escreva uma nota de até 150 palavras para a comunicação interna de uma organização: o que é o estudo, o que mostra, com que segurança e onde ler mais. Linguagem simples, sem jargão, sem exagero. Não acrescente nada que não esteja no texto.
[texto]
```

Conferência humana: a versão segue a estrutura do modelo e traz a lista dos trechos em que se apoia.

### 4 · Conferir numa conversa separada

Prompt de conferência (rodar num chat novo)

```
Abaixo estão um texto original e uma versão curta feita a partir dele. Para cada frase da versão curta, diga se ela está sustentada pelo original, citando o trecho literal. Classifique cada frase como: sustentada; afirma mais do que o original; não está no original; muda o contexto. Se a sua avaliação apontar qualquer diferença entre a frase e o original, a frase não pode ser classificada como sustentada. Liste à parte as limitações do original que a versão curta deixou de fora. Não reescreva a versão curta.
Texto original: [texto]
Versão curta: [versão]
```

Conferência humana: toda frase com avaliação que aponta diferença está fora da coluna "sustentada".

### 5 · Decidir frase a frase

```
Abaixo estão a versão curta e a conferência feita antes. Monte uma tabela com uma linha por frase da versão curta: frase, trecho do original que a sustenta (ou "sem trecho"), página e a classificação da conferência. Não decida nada: deixe uma coluna "decisão da equipe" em branco. Marque as frases que trazem recomendação, contagem ("três fatores", "quatro prioridades") ou número.
Versão curta: [cole a versão]
Conferência: [cole a conferência]
```

Conferência humana: a equipe preenche a decisão de cada frase; frase sem trecho sai, recomendação que a fonte não faz sai ou vira pergunta.

### 6 · Revisão por outra pessoa

```
Você vai revisar uma versão curta feita por outra pessoa, com o texto original ao lado. Para cada pergunta do checklist abaixo, responda sim ou não e aponte a frase da versão curta que motivou a resposta. Não reescreva a versão.
Checklist: O achado principal é o mesmo da fonte? O grau de certeza foi mantido (efeito, sem efeito, inconclusivo)? As limitações principais aparecem? Todo número está na fonte? O contexto dos estudos (país, etapa, tamanho) está dito? A recomendação cabe no que a evidência mostra? Quem lê sabe o que fazer com isso?
Texto original: [texto]
Versão curta: [versão]
```

Conferência humana: quem revisa não escreveu a versão e lê com o original aberto.

### 7 · Registrar

```
Organize um registro curto desta versão com: público e decisão, fonte (título, autoria e data, como estão no original), versão final, prompts usados, ferramenta e data, e as frases que mudaram depois da conferência, com o motivo. Use só as informações abaixo; o que faltar, marque [preencher].
Informações: [cole]
```

Conferência humana: o registro fica guardado junto da versão final e da fonte.

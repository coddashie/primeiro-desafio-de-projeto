![cute cinnamoroll](https://64.media.tumblr.com/33fc946e9008b52a7a308ced1cbb9b13/tumblr_p5gw99AxGx1w9xu55o1_400.png =100x100)

# Conteúdo de abertura - Aula 1

## Introdução ao Pensamento Computacional

  
  

Pensamento computacional
: Processo de pensamento envolvido na expressão de soluções em passos computacionais ou algoritmos que podem ser implementados no computador.

  

:grey_exclamation: *Baseado em 4 pilares:*

Decomposição

: Dividir um problema complexo em subproblemas.

  

Reconhecimento de Padrões

: Identificar padrões ou tendências.

  

Abstração

: Extrapolar o conceito do problema para uma forma generalista.

Design de algoritmos
: Automatizar: definir passo a passo para a solução do problema.

  
  

> ==definir solução== > ==testar solução== > ==aperfeiçoar solução==




## Habilidades Complementares


Raciocínio Lógico
: Forma de pensamento estruturado ou raciocínio, que permite encontrar a conclusão ou determinar a resolução de um problema.

**Classificação**
 - Indução: induzir a partir da observação
 - Dedução: inverso da indução
 - Abdução: supor a partir da observação

Inferência
: Sintética > *abdução / indução*
Analítica > *dedução*

:star: Aperfeiçoamento: a partir de uma solução encontrar pontos de melhora e refinamento.

Decomposição
: Dado um problema complexo, devemos quebrá-lo em problemas menores. Portanto, problemas mais fáceis e gerenciáveis.

Padrões
: Generalizar, com objetivo de obter resolução para problemas diferentes.

Abstração
: Processo intelectual de isolamento de um objeto da realidade. Generalização (na lógica) é a operação intelectual que consiste em reunir numa classe geral, um conjunto de seres ou fenômenos similares.

Algoritmos
: Instruções executadas passo a passo para concluir uma tarefa.

---
**Construção de Algoritmos:**

*==Narrativa:==*
- sem conceitos novos
- utiliza linguagem natural
- diversas interpretações

*==Fluxograma:==*
 - simples entendimento
 - utilização de símbolos pré-definidos
 - conhecimento prévio da estrutura e dos símbolos

*==Pseudocódigo:==*
 - regras definidas
 - [Portugol](https://portugol-webstudio.cubos.io/)
 - passos a serem seguidos


# Aula 2

## O que é lógica?

Problema
: Questão que foge a uma determinada regra. Desvio de percurso, que impede de atingir um objetivo com eficiência e eficácia.

Lógica
: Organização e planejamento das instruções, assertivas em um algoritmo, a fim de viabilizar a implantação de um programa.

## Técnicas da Lógica de Programação

**Técnica linear:**
 - modelo tradicional
 - não tem vínculo
	 - estrutura hierárquica
	 - programação de computadores
	 - modelo de desenvolvimento e resolução
 - ordenação de elementos por uma única propriedade
	 - execução sequenciada
	 - recursos limitados
	 - única dimensão

**Técnica estruturada:**
 - organização, disposição e ordem dos elementos essenciais que compõem um corpo (concreto ou abstrato)

**Técnica Modular:**
 - partes independentes
 - controlada por um conjunto de regras

> Modelo padrão:
> ==dados de entrada== > ==processo de transformação== > ==dados de saída==


# Aula 3

## Tipologia e Variáveis

**Tipos**
 - Numéricos
	 - inteiros
	 - reais
 - Caracteres
 - Lógicos
	 - booleano
	 - verdadeiro (1) / falso (2)

Variável
: Pode assumir qualquer um dos valores de um determinado conjunto de valores. Restringida ao seu tipo.


 - ==ação==
	 - modificação de estado
 - ==controle==
	 - vigiada

Constante
: Fixo, estável. Ex.: pi = 3,14


## Instruções Primitivas

 - Linguagem de palavras-chave (vocabulário) de uma determinada programação que tem por finalidade comandar um computador que irá tratar os dados.
 - ==Entrada, processamento e saída.==

## Estruturas Condicionais
Estrutura Condicional
: Dado o estado de uma coisa, existe uma condição para aquilo acontecer.

> **==condição:==**
> - *satisfeita* > operação
> - *inverdade* > exceção

**Simples:**
 - condição
	 - operação
	
**Composta:**
 - condição
	 - exceção
	 - operação

**Encadeada:**
 - condição
	 - condição
		 - exceção
		 - operação
	 - operação


## Operadores Relacionais

> =="="== igual a 
> =="<>"== diferente de
> ==">"== maior que
> =="<"== menor que
> ==">="== maior ou igual a
> =="<="== menor ou igual a


## Operadores Lógicos

### :star: AND
| Condição 1 | Condição 2 | Resultado  |
|------------|------------|------------|
| Falsa      | Falsa      | Falso      |
| Verdadeira | Falsa      | Falso      |
| Falsa      | Verdadeira | Falso      |
| Verdadeira | Verdadeira | Verdadeiro |
---

### :star: OR

| Condição 1 | Condição 2 | Resultado  |
|------------|------------|------------|
| Falsa      | Falsa      | Falso      |
| Verdadeira | Falsa      | Verdadeiro |
| Falsa      | Verdadeira | Verdadeiro |
| Verdadeira | Verdadeira | Verdadeiro |

---
### :star: NOT
| Condição   | Resultado  |
|------------|------------|
| Verdadeira | Falso      |
| Falsa      | Verdadeiro |
---

## Estruturas de Repetição

 - Laços, repetição, loop
 - Condições de parada:
	 - nº de repetições pré-fixada
	 - condição a ser satisfeita
	 
| ==enquanto ... faça== | ==repita ... até== | ==para ... de ... até ... faça== |
|----------------|----------|-------------|

***Enquanto:***
 - teste lógico: início
 - nº de repetições: indefinido
 
***Repita:***
 - teste lógico: final
 - nº de repetições: indefinido
 - 
***Para ... de ... até:***
 - teste lógico: início
 - nº de repetições: definido


## Vetores e Matrizes

Vetor
: Caracterizado por uma variável dimensionada com tamanho pré-fixado.

Matriz
: Tabela organizada em linhas e colunas no formato ==m x n==, onde ==m== representa o nº de ==linhas== horizontal e ==n==, o nº de colunas ==vertical==.

## Funções
 - Blocos de instruções que realizam tarefas específicas. Modularização do programa.
 - Blocos de instruções (código), identificados por nomes e parâmetros.

==definição --- nome --- invocação --- variável local*==
###### *destruída ao encerrar a função.


## Instruções de entrada e saída

Entrada
: Inserção e recebimento de dados do mundo real por meio de ação de alguma interface.

Saída
: Impressão de dados do mundo abstrato/digital por meio de alguma interface.

---
==**Saída**==
 - **Programada**
	 - condicional (aguarda o dispositivo)
	 - incondicional
 - **Por interrupção**
	 - definida pelos periféricos


# Aula 4

## Introdução às Linguagens de Programação

Problemas Computacionais
: Objeto de discussão que possui instruções passo a passo que são mais facilmente resolvíveis em ambiente computacional.


==**Problemas de**==
 - decisão
 - busca
 - otimização


## Como o computador entende o programa?


**Código fonte:**
 - tradução
 - interpretação


==**Tradução**== *(execução + rápida e programas menores)*
1. Gera programa objeto
2. Executa programa objeto


==**Interpretação**== *(execução + lenta e maior flexibilidade)*
1. Programa fonte executado diretamente
 
 ## Características de um programa

***Diretrizes de desenvolvimento de programas:***
 - legibilidade
 - redigibilidade
 - confiabilidade
 - custo
 - 
## Análises de código

==**Análise Léxica**== 
 - **Particionar**
	 - elementos denominados tokens
 - **Classificar**
	 - elementos identificadores, números, strings, ...
 - **Eliminar**
	 - comentários, caracteres em branco, ...

==**Análise Sintética**== 
 - Corretude do programa
 - Depende da linguagem de programação utilizada

==**Análise Sintética**== 
 - lógica do programa
 - ex.: ~~if (x = 0)~~ if (x == 0) (erro de semântica, significado)

## Paradigmas de Programação
 - Forma de resolução de problemas com diretrizes e limitações específicas de cada paradigma utilizando linguagem de programação.

==**Classificação:**==
 - orientação a objeto
 - procedural
 - funcional
 - estruturado
 - computação distribuída
 - lógico
 ---
**Paradigma Estruturado**
 - sequência
 - decisão
 - iteração (funções, laços, condições)
---
**Orientação a Objeto**
 - baseado na utilização de objetos e suas interações
 - análogo ao mundo real

> **Objeto:**
	>  - atributos: o que tenho
	>  - métodos: sou capaz de fazer
	>  - estados: como faço

> **Pilares de orientação a objeto:**
>  - herança
>  - encapsulamento
>  - polimorfismo
>  - abstração
---
**Herança**
:  - Classe mãe: comportamento e estados gerais
	 - Classe filha: comportamento e estado específicos

> :star: A classe filha herda caraterísticas (atributos e métodos) da classe mãe.

---
---
![cute cinnamoroll 2](https://64.media.tumblr.com/1663f6ce80b36f0dc7e12f0695018c44/tumblr_p5gw99AxGx1w9xu55o2_400.png =100x100)

---
---

# Introdução ao Git e ao Github

## Navegação via command line interface
**Comandos básicos para um bom desempenho no terminal**
 - mudar de local: cd (windows e linux)
 - listar os conteúdos: dir (windows)| ls (linux)
 - criar pastas/arquivos: mkdir (windows e linux)
 - deletar pastas/arquivos: del/rmdir (windows) | rm -rf (linux)
 - limpar tela: cls (windows) | clear / ctrl+L (linux)

## Funcionamento do Git

SHA1
: Secure Hash Algorithm.
Conjunto de caracteres identificador de 40 dígitos.
 - openssl sha1 + nomedoarquivo/objetointerno

Objetos internos do Git
: Blobs - sha1 dos arquivos
Trees - aponta p/ Blobs (sha1 + nome do arquivo)
Commits - aponta p/ Trees (características acima + parente + autor + mensagem + timestamp)

> :star: "ls -a": mostra arquivos/repositórios ocultos

> :star: "mv ______ ./______": move para outro local

> :star: "git status": confere status

> :star: "git add nome_do_arquivo"/"git add *" (geral)/"git add ."

> :star: "git commit -m mensagemdocommit": insere comentário do commit

## Ciclo de vida

Untracked (não há ciência de)
: Untracked 

Tracked (há ciência de)
: Unmodified
Modified
Staged
----

 - Untracked > Staged: adiciona o arquivo
 - Unmodified > Modified: edita o arquivo
 - Modified > Stage: "stage" o arquivo
 - Unmodified > Untracked: remove o arquivo
 - Staged > Unmodified: commit
---
Servidor
: remote repository

-- :star: --

Ambiente de Desenvolvimento
: working directory
staging area
local repository


---
---
![cute cinnamoroll 3](https://i.pinimg.com/originals/91/d9/9b/91d99b2aee7343d8c702d5fa44e3c399.png =100x60)


---
---
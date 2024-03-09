O que é o Microsoft Pilot?????

O Microsoft Copilot permite a utilização da IA Generativa para vários propósitos. Este estudo demonstrará como acessar esta ferramenta e usufruir de algumas funcionalidades.

### Conhecendo a interface inicial do Microsoft Copilot
1) O Copilot pode ser acessado através do link [copilot.microsoft.com](https://copilot.microsoft.com/?azure-portal=true), utilizando sua conta Microsoft pessoal

2) O Microsoft Copilot usa IA generativa para aprimorar os resultados de pesquisa do Bing. O que isso significa é que, ao contrário da pesquisa isolada, que retorna conteúdo existente, o Microsoft Copilot pode reunir novas respostas com base na modelagem de linguagem natural e nas informações da Web
   
3) Na parte inferior da tela, há uma janela do tipo ***Pergunte-me qualquer coisa***. À medida que você insere prompts na janela, o Copilot usa todo o thread de conversa para retornar respostas.
    >![alt text](readmeFiles/images/000.png)

4) O Copilot permite trabalhar com 3 tipos de ***estilos de conversas***. Cada estilo retorna um esquema de cor, uma saudação e dicas iniciais de prompt diferentes. Os estilos são:
    * **Mais Criativo** (recomendado para respostas imaginativas e inovadoras, embora possam faltar em precisão):
        >![alt text](readmeFiles/images/001A.png)

    * **Mais Balanceado** (recomendado para saídas altamente detalhadas e precisas, mas potencialmente menos criativas):
        >![alt text](readmeFiles/images/001B.png)

    * **Mais Preciso** (recomendado para um equilíbrio entre criatividade e precisão):
        >![alt text](readmeFiles/images/001C.png)

Nas próximas seções, serão exploradas 3 funções bastante úteis do Copilot: *geração de textos*, *geração de imagens* e *geração de códigos para programação*.

<br>

### Utilizando prompts para geração de respostas
Este á função mais amplamente utilizada no Copilot e, também, em outras ferramentas de IA Generativa.

Trata-se da utilização de prompts para realização de pesquisas por meio de conversas, por meio de linguagem natural, se tornando uma alternativa bem mais avançada e amigável em relação aos motores de buscas convencionais, como Bing e Google, por exemplo.
> [!NOTE]
> Dois termos serão muito utilizados nesta seção (e nas seguintes), dentro do contexto de IA Generativa e merecem uma ligeira explicação. São eles:
>
> ***Prompt*** (Comumente relacionado à **Engenharia de *Prompts***): É um texto em linguagem natural que solicita que a IA generativa execute uma tarefa específica
>
> ***Threads***: (linhas de execução): São sequências de instruções que fazem parte de um processo principal

A geração de textos ocorre da seguinte forma:
- Digite um *prompt* e pressione **<kbd>Enter</kbd>**. Neste exemplo, o *prompt* utilizado foi:
   ```
   Me diga 3 prós e 3 contras de viajar de motorhome pelo Brasil
   ```

- Para esta pesquisa, foi utilizado o estilo de conversação **Preciso**, buscando um equilíbrio entre criatividade e precisão. Esta foi a resposta gerada:
   > ![alt text](readmeFiles/images/002.png)

- A reposta retorna marcadores que possuem links paras as fontes de dados que foram utilizadas na pesquisa:
   >![alt text](readmeFiles/images/003.png)

- Além disso, o Copilot sugere novos *prompts*:
   >![alt text](readmeFiles/images/004.png)

- Ao clicar em uma destas sugestões, ele continua a conversa, aproveitando as *threads* anteriores, e somente para quando finaliza a pesquisa e/ou o usuário interrompe a execução, por meio da opção **Parar de Responder**:
   >![alt text](readmeFiles/images/005.png)

- Digitando um novo *prompt* e pressionando **<kbd>Enter</kbd>**, a conversa também continua, utilizando do histórico de *threads* para a contextualização, como no exemplo abaixo:
   ```
   Qual destes é o mais barato?
   ``` 
  >![alt text](readmeFiles/images/006.png)

- Para iniciar uma nova conversa, sem qualquer tipo de relação com a conversa anterior, basta clicar em **Novo tópico**:
   >![alt text](readmeFiles/images/007.png)

- Existe uma outra interface, dentro da ferramenta, na qual é possível avaliar o texto gerado, copiá-lo e/ou fazer o dowload. O nome dela é **NOTEBOOK**:
   >![alt text](readmeFiles/images/008.png)

- Pro fim, vale citar que, tanto na interface do **NOTEBOOK** quanto na interce **COPILOT**, ao invés de digitar um prompt, você pode ditá-lo, utilizando o ícone de microfone:
   >![alt text](readmeFiles/images/009.png)

<br>

### Utilizando prompts para geração de imagens
Outra função bastante interessante no uso do Copilot é a geração de imagens a partir de prompts.

Este recurso pode ser utilizado tanto para fins recreativos como para demandas do dia-a-dia, inclusive profissionais.

Eis como gerar as imagens:

A geração de textos ocorre da seguinte forma:
- Tal qual ocorre na geração de textos, digite um *prompt* e pressione **<kbd>Enter</kbd>**. Neste exemplo, o *prompt* utilizado foi:
   ```
   Crie uma imagem para ser utilizada no jogo Forza Horizon 5, sendo os carros uma VW Kombi apostando
   corrida com um VW Beatle. Como pano de fundo, coloque uma estrada à beira-mar.
   ```

- Como se trata de um prompt com fins de recreação, foi utilizado o estilo de conversação **Criativo**, permitindo que a pesquisa pudesse "viajar" um pouco. Estas foram as imagens geradas:
   >![alt text](readmeFiles/images/010.png)


- Note que, no rodapé da imagem, aparece a "Powered by DALL-E". Isto ocorre devido ao fato do Copilot utilizar o DALL-E para a geração de imagens.
   > O ***DALL-E*** é uma rede rede neural treinada pela OpenAI com base em modelos de linguagem grandes (LLM) e que cria imagens a partir de legendas de texto para uma ampla gama de conceitos expressáveis em linguagem natural.

- Outra informação que é trazida no rodapé é a palavra **Designer**. Ela indica qual GPT o Copilot utilizou para gerar a imagem
   > ***GPT*** (*Generative Pre-Trained Transformer* ou Transformador Pré-treinado Generativo): São modelos de predição de linguagem baseados em redes neurais construídos na arquitetura *Transformer*. Eles analisam consultas em linguagem natural, conhecidas como solicitações, e preveem a melhor resposta possível com base em sua compreensão da linguagem.

- Na data de hoje (09/Mar/2023), que é quando este projeto foi escrito, o Copilot conta com 5 GPTs diferentes, com propostas diferentes, conforme print a seguir:
   > ![alt text](readmeFiles/images/011.png)

- Além disso, é possível utilizar *plugins*, desenvolvidos por terceiros, para melhorar/especializar o contexto dos prompts, limitados a 3 por conversa. O usuário deve ter consciência de que o teor das conversas serão sempre compartilhadas com os *plugins* utilizados. Segue um print de exemplo de alguns destes *plugins* disponíveis:
   > ![alt text](readmeFiles/images/012.png)

<br>

### Utilizando prompts para geração de códigos
Por fim, e não mais importante, o Copilot traz uma função que auxilia os desenvolvedores na criação de códigos de programação.

Esta opção pode ser muito útil durante a codificação, pois auxilia o desenvolvedor na construção e ajustes de códigos das mais variadas linguagens de programação

- Segue um exemplo de utilização desta função:

   ```
   Escreva um código em Python, contendo uma classe genérica, com atibutos e métodos genéricos, além
   de um objeto instanciando-a. Este código será utilizado pelo usuário como modelo para criar suas
   próprias classes.
   ```

- Além de retornar a sintaxe, o Copilot traz uma breve descrição de como utilizar o código gerado:
   > ![alt text](readmeFiles/images/013.png)


- Segue o código retornado, caso queira utilizá-lo em algum momento:

   ~~~Python
   class MinhaClasse:
       def __init__(self, atributo1, atributo2):
           self.atributo1 = atributo1
           self.atributo2 = atributo2
   
       def metodo1(self):
           print(f'Método 1 chamado. Atributo 1: {self.atributo1}')
   
       def metodo2(self):
           print(f'Método 2 chamado. Atributo 2: {self.atributo2}')


   # Instanciando a classe
   objeto = MinhaClasse('valor1', 'valor2')
   
   # Chamando os métodos
   objeto.metodo1()
   objeto.metodo2()
   ~~~



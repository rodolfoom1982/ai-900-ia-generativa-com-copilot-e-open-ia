O que é o Microsoft Pilot?????

O Microsoft Copilot permite a utilização da IA Generativa para vários propósitos. Este estudo demonstrará como acessar esta ferramenta e usufruir de algumas funcionalidades.

### Conhecendo a interface inicial do Microsoft Copilot
1) O Copilot pode ser acessado através do link [copilot.microsoft.com](https://copilot.microsoft.com/?azure-portal=true), utilizando sua conta Microsoft pessoal

2) O Microsoft Copilot usa IA generativa para aprimorar os resultados de pesquisa do Bing. O que isso significa é que, ao contrário da pesquisa isolada, que retorna conteúdo existente, o Microsoft Copilot pode reunir novas respostas com base na modelagem de linguagem natural e nas informações da Web
   
3) Na parte inferior da tela, há uma janela do tipo ***Pergunte-me qualquer coisa***. À medida que você insere prompts na janela, o Copilot usa todo o thread de conversa para retornar respostas.
    >![alt text](readmeFiles/images/000.png)

4) O Copilot permite trabalhar com 3 tipos de ***estilos de conversas***. Cada estilo retorna um esquema de cor, uma saudação e dicas iniciais de prompt diferentes. Os estilos são:
    * **Mais Criativo** (recomendado para respostas imaginativas e inovadoras, embora possam faltar em precisão):
        >![alt text](readmeFiles/images/001.png)

    * **Mais Balanceado** (recomendado para saídas altamente detalhadas e precisas, mas potencialmente menos criativas):
        >![alt text](readmeFiles/images/001B.png)

    * **Mais Preciso** (recomendado para um equilíbrio entre criatividade e precisão):
        >![alt text](readmeFiles/images/001C.png)

Nas próximas seções, serão exploradas 3 funções bastante úteis do Copilot: *geração de textos*, *geração de imagens* e *geração de códigos para programação*.

<br>

### Utilizando prompts para geração de respostas
- Digite um *prompt* e pressione em **<kbd>Enter</kbd>**

   > **Nota**: Um *prompt*, dentrod da **Engenharia de *Prompts***, é um texto em linguagem natural que solicita que a IA generativa execute uma tarefa específica

- Neste exemplo, o *prompt* utilizado foi:
   ```
   Me diga 3 prós e 3 contras de viajar de motorhome pelo Brasil
   ```

- Para esta pesquisa, foi utilizado o estilo de conversação **Preciso**, buscando um equilíbrio entre criatividade e precisão. Está foi a resposta gerada:
   > ![alt text](readmeFiles/images/002.png)

- A reposta retorna marcadores que possuem links paras as fontes de dados que foram utilizadas na pesquisa:
   >![alt text](readmeFiles/images/003.png)

- Além disso, o Copilot sugere novos *prompts*:
   >![alt text](readmeFiles/images/004.png)

- Ao clicar em uma destas sugestões, ele continua a conversa, aproveitando as *threads* anteriores, e somente para quando finaliza a pesquisa e/ou o usuário interrompe a execução, por meio da opção **Parar de Responder**:
   >**Nota**: *Threads* (linhas de execução), dentro do contexto de **Engenharia de *Prompts***, são sequências de instruções que fazem parte de um processo principal
   
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


![alt text](readmeFiles/images/010.png)
![alt text](readmeFiles/images/011.png)
![alt text](readmeFiles/images/012.png)





```

```


```
Crie uma imagem para ser utilizada no jogo Forza Horizon 5, sendo os carros uma VW Kombi apostando
corrida com um VW Beatle. Como pano de fundo, coloque uma estrada à beira-mar.
```


```
Escreva um código em Python, contendo uma classe genérica, com atibutos e métodos genéricos, além
de um objeto instanciando-a. Este código será utilizado pelo usuário como modelo para criar suas
próprias classes.
```





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

![alt text](readmeFiles/images/013.png)

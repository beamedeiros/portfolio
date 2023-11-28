# Beatriz Medeiros de Oliveira Santos

## Introdução

Olá, sejam bem-vindos!!

Sou Beatriz Medeiros de Oliveira Santos (mais conhecida por Bea), estudante de Banco de Dados pela FATEC Prof. Jessen Vidal no período noturno. 

Tenho 21 anos e trabalho como estagiária na empresa Soluções Sophia, responsável por Gestão de Escolas e Bibliotecas. <br/>

<img src="https://user-images.githubusercontent.com/74321890/200823701-ea0c19fc-e79b-4e1d-9361-1d8fa1cade6a.jpg" width="300"/>

### Meus principais conhecimentos

#### Java
<p align="justify">
Na faculdade, fiquei reponsáveis por trabalhar com back-end e uma das principais linguagens aprendidas e requisitadas foi Java.

Utilizei para o desenvolvolvimento de API's e serviços com o auxílio do framework Spring Boot e também do framework Hibernate. 

Por conta desta experiência, Java e seu ecossistema para desenvolvimento web é onde possuo maior contato. 

#### Javascript
<p align="justify">
JavaScript foi uma linguagem que aprendi ainda antes da graduação. Meu primeiro estágio (técnico em informática) na Embraer possibilitou que eu trabalhasse com JavaScript junto com o framework React.

Trabalhei por 1 ano e 8 meses com UX, front-end e requisições HTTP, desenvolvendo uma plataforma web que tem como objetivo automatizar e facilitar a visualização de máquinas e processos para os operadores.

Atualmente trabalho com desenvolvimento web utilizando o framework VueJS.

#### Projetos Integradores durante a graduação
<p align="justify">
Durante a minha gradução, trabalhei no desenvolvimento de trabalhos chamados de "Projetos integradores". Um projeto integrador tem o objetivo de solucionar um problema do mundo real, utilizando os conhecimentos adquiridos durante a graduação.<br/>

Abaixo, todos estes projetos serão descritos, detalhando o problema, solução proposta (e entregue), e os aprendizados extraídos de cada um deles.

# Projeto 1: 1º Semestre de 2021

### Parceiro Acadêmico

Fatec Prof. Jessen Vidal (proposta realizada pelo docente responsável pela disciplina que ordenou o projeto)

![image](https://user-images.githubusercontent.com/74321890/221617740-afbc3809-af92-43e8-bc11-698eeffb4bf4.png)

A Fatec é uma Faculdade Pública Estadual e todos os cursos oferecidos são gratuitos.

### Visão do Projeto

Neste projeto propõe-se o desenvolvimento de uma aplicação em python para reconhecer voz e atuar conforme os comandos do usuário.
Com o propósito de trazer para os estudantes em geral uma forma mais centralizada e organizada de cuidar da vida acadêmica e se manter atualizado em suas atividades, a Athena- Assistente Pessoal de Estudos reúne diversas ferramentas úteis em um único lugar.

[<img src="https://user-images.githubusercontent.com/74321890/221615575-d2721589-5e18-438c-b8f3-4e6dfe50d199.png" width="40%">](https://www.youtube.com/watch?v=E_I9MvQs9BE "Athena vídeo Demonstração")

Link do repositório do projeto: https://github.com/silvercod3/Athena

### Tecnologias adotadas na solução

<details><summary>Python</summary>
<p align="justify">

>O Python é uma linguagem de programação amplamente usada em aplicações da Web, desenvolvimento de software, ciência de dados e machine learning (ML). Os 
desenvolvedores usam o Python porque é eficiente e fácil de aprender e pode ser executada em muitas plataformas diferentes. O software Python pode ser baixado 
gratuitamente, integra-se bem a todos os tipos de sistema e agiliza o desenvolvimento.

Os desenvolvedores de software geralmente usam o Python para diferentes tarefas de desenvolvimento e aplicações de software, no caso do nosso projeto criamos as 
seguintes funcionalidades:
- Cronograma de aulas: armazena horários de aulas cadastrados pelo(a) estudante, para facilitar controle e organização de sua agenda;
- Calendário acadêmico: permite cadastro de datas de provas, trabalhos e qualquer ocasião importante para o estudante, com notificações prévias;
- Planos de estudos: a Athena fornece planos de estudos editáveis, de acordo com a meta do estudante;
- Notificações de estudos: alertas lembrando o(a) estudante que chegou a hora de estudar (via pop-up e e-mail);
- Cálculo de médias: permite o(a) estudante conferir de forma fácil como estão indo suas notas no semestre;
- Controle de faltas: para evitar uma reprovação, alerta o(a) estudante sobre quantas faltas ainda podem ser registradas (com contagem regressiva, de acordo com valor previamente cadastrado pelo(a) estudante);
- Dicas: dicas sobre como melhorar a efetividade dos estudos, concentração, absorção de conteúdo e organização;
- Metas de estudos e gráficos de desempenho: planejamento de horas a estudar semanal ou mensal, que auxilia no progresso, juntamente com visualização do desempenho através de gráficos.
</details>

<details><summary>PyAudio e Pydub</summary>
<p align="justify">

>Bem similar ao que temos no nosso celular por exemplo, que ele consegue entender o que falou e fazer uma pesquisa, mas no nosso caso ele vai entender e vai poder printar essa mensagem.

>A biblioteca Pydub, foi criada para manipulação de áudio de forma simples e alto nível. Com ela podemos fazer conversões de formatos, juntar ou dividir arquivos de áudio entre outras atividades.

Utilizamos PyAudio e Pydub junto com a biblioteca SpeechRecognition para a transcrição de voz, você vai poder falar no seu microfone e o código vai fazer o reconhecimento de frases no Python e vai escrever o que falou.
</details>

<details><summary>Tkinter</summary>
<p align="justify">  

>Tkinter é uma biblioteca da linguagem Python que acompanha a instalação padrão e permite desenvolver interfaces gráficas. Isso significa que qualquer computador que tenha o interpretador Python instalado é capaz de criar interfaces gráficas usando o Tkinter, com exceção de algumas distribuições Linux, exigindo que seja feita o download do módulo separadamente.

As interfaces gráficas do usuário (GUI – Graphic User Interface) são bastante populares no uso de softwares em geral, e os programadores devem estar aptos a trabalhar com a criação de interfaces, já que torna o uso mais fácil além de aumentar a produtividade.
  
Utilizamos o Tkinter para montar a interface do usuário, mais especificamente mostrar o gráfico de horas estudadas por matéria.
</details>
  
### Contribuições pessoais

No reconhecimento de voz, implementei a biblioteca SpeechRecognition, para o reconhecimento de voz do usuário/ estudante.
<details><summary>Código</summary>

>A função record_audio é responsável por gravar o áudio do usuário usando o microfone e, em seguida, converter o áudio em texto. Dentro da função, é inicializado um objeto Recognizer da biblioteca SpeechRecognition, que é responsável por reconhecer a fala a partir do áudio gravado. O método listen do objeto Recognizer é usado para gravar o áudio do usuário, e os parâmetros duration e timeout definem, respectivamente, a duração máxima da gravação e o tempo máximo que o método deve esperar antes de retornar uma exceção. O método adjust_for_ambient_noise é usado para ajustar o nível de ruído de fundo antes de iniciar a gravação do áudio. Em seguida, o áudio é convertido em texto usando o serviço de reconhecimento de fala da Google, especificado pelo método recognize_google.
  
```
import speech_recognition as sr

engine = pyttsx3.init()
r = sr.Recognizer()  # inicializa o reconhecedor

# ouve o áudio e converte para texto:
def record_audio(ask=""):
    try:
        with sr.Microphone() as source:
            if ask:
                speak(ask)
            audio = r.listen(source, 5, 5)
            r.adjust_for_ambient_noise(source, duration=1)
            voice_data = ''
            try:
                voice_data = r.recognize_google(audio, language='pt-BR')
            except sr.UnknownValueError:
                time.sleep(10)
                print('Deu erro aquiiiiiii')
                speak(error)
                exit()
            except sr.RequestError:
                speak('Desculpe, serviço indisponível no momento')
            except sr.WaitTimeoutError:
                print('Serviço indisponível no momento, tente novamente !')
                exit()
            print(">>", voice_data.lower())
            return voice_data.lower()
    except TypeError:
        speak('tem alguém aí ?')
        time.sleep(6)
        exit()
    except sr.WaitTimeoutError:
        speak('tem alguém aí ?')
        time.sleep(5)
        exit()

```
</details>

Também fui encarregada de desenvolver a interface, utilizando gráficos, para que o usuário conseguisse observar sua evolução nas metas.

<details><summary>Interface</summary>

>O código define duas listas de strings, horas e horas2, que contêm as legendas e valores das barras do gráfico.  As listas são então passadas para a função plt.bar do Matplotlib, que cria um gráfico de barras com as horas pretendidas e cumpridas. O resultado é um gráfico simples de barras que mostra a quantidade de horas pretendidas e cumpridas de estudo. A barra correspondente às horas pretendidas é exibida em roxo, enquanto a barra correspondente às horas cumpridas é exibida em azul.

```
horas_pretendidas = int(input('Quantas horas você pretende estudar? '))
horas_cumpridas = int(input('Quantas horas você estudou? '))

import numpy as np
import matplotlib.pyplot as plt

horas = ['Horas Pretendidas', 'Horas Cumpridas']
horas2 = [horas_pretendidas, horas_cumpridas]

plt.bar(horas, horas2, color='purple')

plt.xticks(horas) #define as etiquetas do eixo x do gráfico para serem as horas pretendidas e cumpridas
plt.ylabel('HORAS') #rótulo do eixo y do gráfico, que é "HORAS"
plt.xlabel('HORAS DE ESTUDO') #rótulo do eixo x do gráfico, que é "HORAS DE ESTUDO"
plt.title('METAS DE ESTUDO') #título do gráfico como "METAS DE ESTUDO".
plt.show() #exibe o gráfico
```

A imagem abaixo mostra a disposição de informações e resultado do gráfico.
<img src="https://user-images.githubusercontent.com/74321890/234713583-e0115e73-e159-4742-b333-a15939ba2bf2.png">

</details>

### Hard Skills

Neste projeto obtive meu primeiro contato com Python e documentações. Esta experiência me ensinou a buscar informações nas fontes primárias, que são as documentações técnicas geralmente realizadas pelos próprios criadores e responsáveis pelas mais diversas tecnologias. Este projeto foi valioso até hoje em minha trajetória acadêmica e profissional.

Olhar para um problema real e depois inventar uma solução que ainda não existe nesse cenário específico foi um desafio interessante. Isso me ajudou a desenvolver habilidades importantes para quem trabalha com análise e desenvolvimento de software.

Com este desafio, realizei minha primeira decisão de qual tecnologia e tática utilizar em uma solução, e também os detalhes de como implementá-las. Estas decisões são frequentes na carreira de soluções tecnológicas, onde diversas vezes optar pela solução mais eficiente no curto, médio e longo prazo são extremamente necessárias.

Além disso, consegui distinguir a velocidade de profundidade e velocidade em diferentes métodos de pesquisa e estudo. Diversos tutoriais estão disponíveis ensinando a realizar grande partes das etapas de projetos deste tipo, e estes conteúdos possuem sua importância. 

No mais, temos os pontos específicos a seguir:

- Reconhecimento de voz: sei fazer com autonomia.
- Envio de e-mail automático: sei fazer com autonomia.
- Desenvolvimento de scripts em Python: sei fazer com autonomia.

### Soft Skills

Como foi um projeto em grupo que demandou conhecimentos específicos e um grupo com pessoas que conhecia há pouco tempo, desenvolvi muito o **trabalho em equipe** e a **confiança** no trabalho e desenvolvimento de outros integrantes.

# Projeto 2: 2º semestre de 2021

### Parceiro Acadêmico
Necto Systems <br/>
![image](https://user-images.githubusercontent.com/74321890/200952858-ff867019-d4c6-49cf-9c2a-9508546a5ed9.png)

Desenvolvimento estratégico de software para necessidades específicas.

### Visão do Projeto

Este projeto teve como proposta uma aplicação de monitoramento voltada somente à SGBDs, focada na performance e desempenho, através da coleta de dados do SGBD (memória, tempo de consultas, espaço em disco, transações, evolução da memória, caches e registros) que influenciam na saúde e manutenção periódica.

[<img src="https://user-images.githubusercontent.com/74321890/200989611-49f7bac0-fb95-4efd-a935-5c38141a6458.png" width="40%">](https://www.youtube.com/watch?v=zVTsaxL_-l4&list=PLUOBqJKbljZvQtu2OXq071Id11zidSJNS "SGBD Health vídeo Demonstração")

Link do repositório do projeto: https://github.com/DolphinDatabase/SGBD_Health

### Tecnologias adotadas na solução

<details><summary>PostgreSQL</summary>
<p align="justify">  

>PostgreSQL é um sistema gerenciador de banco de dados objeto relacional (SGBD), desenvolvido como projeto de código aberto.

No nosso projeto utilizamos PostgreSQL para realizar a conexão e efetuar a coleta de métricas.
</details>

<details><summary>Java</summary>
<p align="justify">  
  
>Utilizamos a linguagem de programação orientada a objetos conhecida por Java. Para a criação dessa linguagem, utilizaram do C++ como base, mas seu principal objetivo 
era ser uma linguagem de fácil aprendizagem. Seu código é escrito em uma classe onde tudo é objeto, porém números reais e ordinais, valores booleanos e caracteres não 
são considerados objetos já que não participam de classes por questões de funcionamento.  

SGBD Health utilizou Java para:
- Tratamento das métricas (histórico, registro, relatórios, disponibilidade, alertas e valores atingidos durante a operação);
- Tratamento de métricas de forma tabular;
- Salvar consultas em CSV;
- Tabular métricas;
- Coleta periódica de métricas;
- Histórico de métricas;
- Relatórios de métricas;
- Alertas por email;
- Funcionamento do BD (tempo e quantidade de queries e uso de índices).
- Ativar ou Desativar Interface Gráfica;
- Cadastro de dados de conexão dos SGBDs (acesso à estastítica por tabelas).
</details>

### Contribuições pessoais

Como tinha pouco conhecimento com PostgreSQL, na primeira sprint fui encarregada de estudar para que nas próximas pudesse trabalhar com mais autonomia, assim, fiquei responsável e contribui com o desenvolvimento e conexão com o banco de dados.

Desenvolvi em java o código que cria um arquivo csv com as informações sobre o banco.

<details><summary>Código csv</summary>
<p align="justify">  

>O código apresentado é uma implementação em Java para manipulação e exibição de dados em formato CSV. Ele possui uma classe Csv que contém métodos para definir configurações de exibição, adicionar dados e exibir o conteúdo em formato de tabela.
  
```
public class Csv {
	
	  private static final String HORIZONTAL_SEP = "-";
    private String verticalSep;
    private String joinSep;
    private String[] headers;
    private List<String[]> rows = new ArrayList<>();
    private boolean rightAlign;
	static String filepath = "armazenamento.csv";
	static String filepath2 = "query.csv";
	static String filepath3 = "indices.csv";
	static String filepath4 = "transacao.csv";	
[...]

    private void printRow(String[] cells, int[] maxWidths) {
        for (int i = 0; i < cells.length; i++) {
            String s = cells[i];
            String verStrTemp = i == cells.length - 1 ? verticalSep : "";
            if (rightAlign) {
                System.out.printf("%s %" + maxWidths[i] + "s %s", verticalSep, s, verStrTemp);
            } else {
                System.out.printf("%s %-" + maxWidths[i] + "s %s", verticalSep, s, verStrTemp);
            }
        }
        System.out.println();
    }
```
                                         
>O método selecionar que recebe uma consulta SQL, uma conexão com um banco de dados, informações sobre as colunas que devem ser selecionadas, um título para o arquivo CSV a ser salvo, um título para a exibição no console, um caminho para o arquivo CSV, um parâmetro de exibição na console e um parâmetro de salvamento em arquivo.
  
```
if (i == 4 && j == 6) {
	quantidadeColuna[i - 4] = (result.getString(i - 3));
	quantidadeColuna[i - 3] = (result.getString(i - 2).replaceAll("\\r\\n|\\n", "").substring(0, 25)
			+ "...");
	quantidadeColuna[i - 2] = (result.getString(i - 1));
	quantidadeColuna[i - 1] = (result.getString(i));
	st.addRow(quantidadeColuna[i - 4], quantidadeColuna[i - 3], quantidadeColuna[i - 2],
			quantidadeColuna[i - 1]);

} else if (i == 4 && j == 7) {
	quantidadeColuna[i - 4] = (result.getString(i - 3));
	quantidadeColuna[i - 3] = (result.getString(i - 2).replaceAll("\\r\\n|\\n", ""));
	quantidadeColuna[i - 2] = (result.getString(i - 1));
	quantidadeColuna[i - 1] = (result.getString(i));
	st.addRow(quantidadeColuna[i - 4], quantidadeColuna[i - 3], quantidadeColuna[i - 2],
			quantidadeColuna[i - 1]);
				
```
>Esse método executa a consulta SQL e, dependendo dos parâmetros, exibe os resultados no console e salva em um arquivo CSV. Ele utiliza a classe Csv para formatar e exibir os resultados.
  
</details>  

### Hard Skills

Além disso, foi quando coloquei em prática as aulas de banco de dados e utilizei para criar um projeto baseado em situações reais do dia a dia da empresa/ cliente.

- Trabalhar com SGBD: sei fazer com autonomia.
- Criar tabelas, relacionamentos e modelagem: sei fazer com autonomia.
- Desenvolvimento de scripts em Java: sei fazer com autonomia.

### Soft Skills

Este projeto, nosso primeiro contato com clientes reais, aprimorou nossas **habilidades sociais**. Desenvolvemos a capacidade de **trabalhar sob pressão**, melhorar a **comunicação interna e com os clientes**, e fortalecer o **trabalho em equipe** para atender às expectativas e metas do projeto. Isso nos preparou para os projetos futuros.

# Projeto 3: 1º semestre de 2022

## Parceiro Acadêmico
MidAll <br/>
![midall](https://user-images.githubusercontent.com/74321890/191144569-593506c4-b02e-41bf-830d-9f6e88a57278.jpeg)

<p align="justify">
A MidAll é uma empresa que se dedica a ajudar outras empresas a se adaptarem às mudanças do mercado.

### Visão do Projeto
<p align="justify">
Neste projeto propõe-se o desenvolvimento de uma ferramenta para criar promoções de E-commerce, de forma que mecânicas de promoções fossem feitas de forma flexível e de rápida atualização no sistema. As regras de promoções são cadastradas e posteriormente aplicadas no momento em que os itens são adicionados ao carrinho. No desenvolvimento foi implementado e apresentado o cadastro dos produtos em várias promoções no servidor/ banco de dados, utilizando operadores lógicos para criar diferentes mecânicas de promoções, o desconto é aplicado na sacola de compra e possui uma visualização dedicada para conferência e escolha de possíveis promoções. Além disso, há a autonomia fornecida ao usuário para editar, remover, arquivar ou desarquivar seus produtos e para editar, deletar, interromper ou ativar promoções e da visualização prática e intuitiva dos produtos e promoções cadastradas através da listagem que possui um filtro para que seja possível diferenciar quais os status de produtos e promoções.

[<img src="https://github.com/DolphinDatabase/DescontOn/blob/main/Imagens/DescontOn-Youtube.png" width="40%">](https://www.youtube.com/watch?v=n5GK4uJpNkk&list=PLUOBqJKbljZsrdWoo8YF8GLvADBIIRMPV "DescontOn vídeo Demonstração")

Link do repositório do projeto: https://github.com/DolphinDatabase/DescontOn

### Tecnologias adotadas na solução

<details><summary>Spring Boot</summary>
<p align="justify">

>O Spring Boot é um framework Java open source que tem como objetivo facilitar esse processo em aplicações Java. Trazendo mais agilidade para o processo de 
desenvolvimento com uma infinidade de ferramentas surge todos os dias visando justamente acelerar o processo de criação e implantação de soluções nos mais variados 
ambientes.

Utilizamos Spring Boot para desenvolver Java com uma interface gráfica, sendo o primeiro projeto que trabalhamos com desenvolvimento web.
</details>

<details><summary>Oracle</summary>
<p align="justify">
  
>O Banco de dados Oracle (Oracle DB) é um sistema de gerenciamento de banco de dados relacional (RDBMS, Relational Database Management System) da Oracle Corporation. 
Oracle DB é um dos mais utilizados no mercado devido a sua capacidade de orientar aplicativos corporativos no processamento de transações online (OLTP, Online 
Transaction Processing), em data warehouse e na análise de negócios. Equipes de TI também precisam de desempenho sob demanda desses bancos de dados para as 
necessidades de desenvolvimento, teste, análise e continuidade de negócios.

Utilizamos o SGBD Oracle para poder armazenar os dados da aplicação, como cadastro, remoção e edição.

Aqui está um **exemplo** do modelo relacional:

<img src="https://github.com/DolphinDatabase/DescontOn/raw/ebf0051ea024984c038dce84c2d153560b996701/Documenta%C3%A7%C3%A3o/SPRINT3/Imagens/Modelo_Relacional.jpeg">
</details>

<details><summary>HTML</summary>
<p align="justify">
  
>O HTML (HyperText Markup Language) é uma linguagem voltada para a web que foi feita para você montar sua própria estrutura de texto e outros elementos para publicá-
los. Tal linguagem se trabalha em camadas divididas em 3: o próprio HTML, CSS e JavaScript. Estes elementos permitem ao usuário a criação de um website contendo 
diversas variações de textos, imagens, vídeos, botões, entre outros.

Utilizamos o HTML para desenvolver o front-end da aplicação, onde montamos uma interface para que haja a interativadade com o cliente.
</details>

<details><summary>CSS</summary>
<p align="justify">
  
>O CSS (Cascading Style Sheet) é uma folha de estilo que trabalha em conjunto com a linguagem HTML e serve para compor a parte visual do site, deixando-a mais atraente. 
Sua principal função é separar e organizar o site, como exemplo, separar a parte escrita da parte visual. É possível fazer uma comparação com um editor de fotos, já 
que essa style sheet permite a edição, alinhamento, remover, acrescentar ou até mesmo trabalhar com os elementos de uma página web. De acordo com o site WebLink, o CSS 
também permite fazer animações, efeitos visuais, sites dinâmicos e landings pages.

No projeto, utilizamos CSS juntamente com o HTML para dar uma estilização da interface e torná-la mais agradável para o usuário.

</details>

<details><summary>JavaScript</summary>
<p align="justify">
  
>JavaScript é uma linguagem de programação que permite a você implementar itens complexos em páginas web — toda vez que uma página da web faz mais do que simplesmente 
mostrar a você informação estática — mostrando conteúdo que se atualiza em um intervalo de tempo, mapas interativos ou gráficos 2D/3D animados, entre outros, há 
JavaScript envolvido.
  
Utilizamos JavaScript e requisições HTTP, para desenvolver as seguintes funcionalidades no front-end:
- Cadastro de Produtos
- Listar Produtos
- Remover Produtos Cadastrados
- Arquivar e Desarquivar Produtos Cadastrados (para armazenar dados dos produtos que já foram comprados)
- Filtrar a Listagem de Produtos (produtos disponíveis ou arquivados)
- Editar um Produto Cadastrado
- Adicionar Produtos na Sacola
- Alterar a Quantidade de Produtos na Sacola
- Remover Produtos da Sacola
- Finalizar Compra
- Cadastro de Promoções
- Listar Promoções
- Remover Promoções
- Ativar ou Interromper Promoções
- Filtrar a Listagem de Promoções (promoções ativas ou interrompidas)
- Editar uma Promoção
- Aplicar Descontos na Sacola de Compras
- Criar Mecânicas com Modelos Lógicos
- Cadastrar Produtos em (N) Promoções
- Listar desconto por produto na Sacola de Compras
- Visualizar promoções por produto na Sacola de Compras
</details>

### Contribuições pessoais
<p align="justify">
No código, além de trabalhar com o front-end, trabalhei na criação de DTOs (Data Transfer Object), um padrão de projetos bastante usado em Java para o transporte de dados entre diferentes componentes de um sistema, diferentes instâncias ou processos de um sistema distribuído ou diferentes sistemas via serialização.
	
<details><summary>DTO</summary>
<p align="justify">
	
>A ideia consiste basicamente em agrupar um conjunto de atributos numa classe simples de forma a otimizar a comunicação. Além disso, muitas vezes os dados usados na comunicação não refletem exatamente os atributos do seu modelo. Então, um DTO seria uma classe que provê exatamente aquilo que é necessário para um determinado 
processo.
  
Abaixo está um exemplo de ProdutoDTO:

>O código apresenta a classe "ProdutoDTO", que é uma classe de transferência de dados (DTO) usada para representar informações sobre um produto em um sistema. Ela possui cinco campos: "id" (identificador do produto), "nome" (nome do produto), "valor" (valor do produto), "categoria" (categoria do produto) e "status" (status do produto). A classe é anotada com "@Data" para gerar automaticamente métodos básicos, como getters e setters, e "@AllArgsConstructor" para gerar um construtor que aceita todos os parâmetros. Essa classe facilita o transporte e manipulação dos dados do produto em diferentes partes do sistema.
  
  ```
  @Data
  @AllArgsConstructor
  public class ProdutoDTO {
    private Long id;
    private String nome;
    private Double valor;
    private String categoria;
    private Integer status;
  }
  ```
  
Abaixo apresento um exemplo da chamada do DTO dentro de ProdutoController:
	
>Esse trecho de código representa um método que trata uma requisição POST para criar um novo produto. Ele recebe um objeto "Produto" como parâmetro, salva esse objeto no repositório de produtos,"ProdutoDTO" é preenchido com os dados salvos e retorna esse objeto como resposta da requisição. O uso de um DTO permite encapsular e transportar as informações relevantes do produto para a camada de apresentação ou comunicação com outros sistemas, evitando expor diretamente a entidade de domínio "Produto".
	
 ```
  @PostMapping
  public ProdutoDTO create(@RequestBody Produto produto){
    Produto save = produtoRepositorio.save(produto);
    ProdutoDTO res = new ProdutoDTO(save.getId(),save.getNome(),save.getValor(),save.getCategoria(),save.getStatus());
    return res;
  }
 ```
  
</details>

Na parte de usabilidade, desenvolvi os Wireframes no Figma e fiz cada tela prezando pela experiência do usuário (UX - user experience). Utilizei template 
do Bootstrap e trabalhei com HTML/ CSS e JavaScript para o desenvolvimento da aplicação web.
<details><summary>Página inicial</summary>
A imagem abaixo mostra a página inicial da aplicação, a usabilidade das cores (o que transmite para o usuário) e a forma como a barra de navegação é organizada.
<img src="https://user-images.githubusercontent.com/74321890/203669780-f534d9e9-698e-4341-8459-e819e880ea0a.png">

>O código HTML fornecido é a estrutura de uma página web para o DescontOn. A página apresenta um cabeçalho com um menu de navegação, um banner de boas-vindas com uma breve descrição do DescontOn, seções de benefícios e funcionalidades do sistema, e um rodapé com um link para o repositório do projeto no GitHub. O código faz uso de bibliotecas como Bootstrap e Boxicons para estilização e funcionalidades adicionais, além de referenciar arquivos CSS e JavaScript específicos. No geral, o código estrutura de forma organizada as diferentes seções e funcionalidades do DescontOn, fornecendo uma experiência intuitiva para os usuários.

O trecho de código a seguir mostra como montamos o componente de boas-vindas à aplicação.

```
  <!-- ======= Sobre Section ======= -->
  <section id="hero" class="d-flex flex-column justify-content-center align-items-center">
    <div class="container text-center text-md-left" data-aos="fade-up">
      <h1>Bem-Vindo ao&nbsp; <span>DescontOn</span></h1>
      <h2>Ferramenta para criar promoções de E-commerce, onde as mecânicas de promoções são feitas de forma flexível e
        de rápida atualização no sistema.</h2>
      <a href="#saiba-mais" class="btn-get-started scrollto">Saiba Mais</a>
    </div>
  </section>
  <!-- End Sobre -->
```
</details>
	
Atuei como Scrum Master, gerenciando e ajudando com impedimentos do time. Como ferramenta de apoio foi utilizado o Jira para ter mais visualização e controle sobre as tarefas e suas divisões para cada membro da equipe.
<details><summary>Jira - DescontOn</summary>
Para mostrar melhor a usabilidade do Jira e divisão de histórias, abaixo está o roadmap do projeto. 

<img src="https://user-images.githubusercontent.com/74321890/203658630-474dbc4f-a670-470a-836e-d75cd28cf59a.jpeg">
</details>

Documentei o projeto, sendo no Github algumas descrições mais específicas e menos teóricas, já no documento em .pdf falo melhor sobre a teoria das cores, descrição sobre linguagens e frameworks usados e explico trechos de código.
<details><summary>Documentação</summary>
Abaixo está o ínicio da documentação feita no Github, para mais detalhes acesse o nosso github.

<img src="https://user-images.githubusercontent.com/74321890/203660418-1ba84ed7-a534-48b1-9335-eb8598f4ce4e.png">
</details>
	
### Hard Skills
<p align="justify">
  
No desenvolvimento dos serviços do DescontOn, aprendi mais sobre desenvolvimento web. Foi a primeira vez na faculdade em que trabalhei de fato com uma aplicação 
front-end separada dos serviços chamados de back-end.

Por conta desta experiência, fui inserida a um novo nível de exigência para a construção de um sistema web, tendo que me preocupar com o formato e conteúdo específico 
das requisições possíveis de entrada no serviço desenvolvido.

Além disso, foi minha primeira vez atuando no papel de Scrum Master e colocando a metodologia ágil em prática.

- Criação de wireframes, desenvolvimento web e ux: sei fazer com autonomia.
- Utilização da metodologia ágil e atuação como SM: sei fazer com autonomia.
- Utilização de DTO em códigos: sei fazer com autonomia.

### Soft Skills

Ao assumir o papel de Scrum Master em meu primeiro projeto, fui desafiada a aprimorar várias soft skills. A necessidade de compreender e aplicar metodologias ágeis impulsionou uma **atitude positiva e resiliência** para lidar com mudanças e incertezas. A **motivação** tornou-se essencial para inspirar a equipe. A **gestão do tempo e organização** eram necessárias para equilibrar tarefas e responsabilidades. **Comunicação** eficaz era vital para facilitar reuniões e mediar conflitos. Além disso, o papel reforçou meus **princípios éticos**, enfatizando a integridade e a responsabilidade. Essas habilidades contribuíram significativamente para o sucesso do projeto e meu próprio desenvolvimento profissional.

# Projeto 4: 2º semestre de 2022

## Empresa parceira:

Subiter

<img src="https://user-images.githubusercontent.com/74321890/200832569-795e2fa6-0fc6-4b1e-8547-d7b2abf82c0b.jpg" height="300"/>

<p align="justify">
A Subiter é uma empresa de base tecnológica especializada em visão infravermelha.

### Visão do Projeto
<p align="justify">
Este sistema ERP tem como foco principal o gerenciamento eficiente de dados, visando redução de custos, facilitação das tomadas de decisão, otimização do tempo de atendimento a chamados e aprimoramento na resolução desses problemas. Um destaque crucial é o MCS (Sistema de Gerenciamento e Controle), que oferece de maneira fácil e rápida um recurso de extrema importância: o mapeamento gráfico de anomalias nas silhuetas.

O Mapeamento de Anomalias é uma funcionalidade que permite ao suporte, durante ou após uma inspeção, fazer o upload da silhueta e adicionar detalhes específicos sobre as falhas encontradas. Isso é feito de forma visual, atribuindo formas e tamanhos diferentes para uma identificação mais eficaz da posição e do tamanho das anomalias. Essa abordagem facilita não apenas a identificação da quantidade e tipo de falhas, mas também auxilia na escolha dos materiais necessários para solucioná-las, além de possibilitar o cálculo preciso do orçamento. Em resumo, o MCS destaca-se por proporcionar uma ferramenta poderosa de mapeamento de anomalias, contribuindo significativamente para a eficiência no diagnóstico e resolução de problemas.

Sua interface web facilita a gestão de dados e dá autonomia aos usuários dessa aplicação para que possam atuar com desenvoltura dentro das permissões concedidas. 

[<img src="https://github.com/DolphinDatabase/MCS/blob/main/Imagens/MCS_Youtube.png" width="40%">](https://www.youtube.com/watch?v=omSyXxA3AYI&list=PLUOBqJKbljZv85QQ4B3ExV93PQVVf8n2o "MCS vídeo Demonstração")

Link do repositório do projeto: https://github.com/DolphinDatabase/MCS

### Tecnologias adotadas na solução
<p align="justify">
Assim como no projeto anterior, a aplicação teve desenvolvimento web, a única diferença foi utilização o framework VueJS para a construção do front-end da aplicação.
<details><summary>VueJS</summary>
<p align="justify">
	
>Vue.js é um framework JavaScript de código aberto utilizado para construir interfaces de usuário interativas e dinâmicas. Ele é baseado em componentes reutilizáveis e adota uma abordagem de programação reativa, permitindo a criação de aplicativos web de uma única página (SPA) de forma eficiente. O Vue.js combina recursos modernos do JavaScript com uma sintaxe simples e intuitiva, facilitando o desenvolvimento de aplicativos web complexos. Ele é amplamente utilizado na comunidade de desenvolvimento web devido à sua flexibilidade, desempenho e curva de aprendizado suave.

Utilizamos este framework para desenvolver o front-end da aplicação.
</details>

<details><summary>Konva</summary>
<p align="justify">
	
>Konva.js é uma biblioteca JavaScript de código aberto que facilita a criação de gráficos interativos e de alto desempenho em aplicativos da web. Ela é especialmente projetada para trabalhar com elementos gráficos bidimensionais, como desenhos, animações e manipulação de objetos em um ambiente de tela HTML5. Konva.js fornece uma API simples e poderosa que permite criar e gerenciar facilmente elementos gráficos, aplicar transformações, adicionar interatividade, detectar eventos, fazer desenhos vetoriais e muito mais. Com a ajuda do Konva.js, os desenvolvedores podem criar aplicativos visualmente ricos, como editores de imagem, jogos, mapas interativos e ferramentas de desenho.

Utilizamos o Konva para desenhar o mapeamento de anomalias.
</details>
	
Para a programação das rotas HTTP, os serviços e API do back-end foram feitas em Java.
	
Um diferencial do banco de dados, como requisito da FATEC, foi a utilização do OracleCloud.
<details><summary>OracleBD</summary>

 > É o SGBD da Oracle, o mais utilizado em aplicações corporativas, lançado em meados dos anos 70, é multiplataforma e possui licença comercial.

Foi usado para estruturar o modelo de dados relacional da aplicação, além disso foram criadas procedures e triggers no SGBD.
Para acessar a documentação sobre como conectar Autonomous Database da Oracle Cloud com Spring Boot JDBC do clique [aqui.](https://github.com/DolphinDatabase/MCS/blob/main/Documenta%C3%A7%C3%A3o/Como%20conectar%20Autonomous%20Database%20da%20Oracle%20Cloud%20com%20Spring%20Boot%20JDBC.pdf)

</details>

### Contribuições pessoais
<p align="justify">

Neste projeto minha principal responsabilidade no código foi o desenvolvimento das telas no front-end utilizando a biblioteca Element+ para ícones, tabelas, entre outros e konva para o desenho do mapeamento de anomalias. 

No desenvolvimento com VueJS, a organização do código é realizada através da utilização de "views", "components" e outros elementos.

A seguir mostro alguns exemplos do desenvolvimento do **front-end** em VueJS.
<details><summary>Tela - Home</summary>
<p align="justify">

<img src="https://github.com/pdrMottaS/Portifolio/assets/74321890/12f0fd7e-760f-4b28-bac5-a8e88a573b2f">
	
>Nesse trecho de código, mostro como é estruturado a HomeView.vue. Esse template define a estrutura de uma página de login com elementos e conteúdos específicos, usando a sintaxe do Vue.js para criar componentes reutilizáveis e interativos.

```
<template>
  <div id="page">
    <div id="loginBackgorund">
      <div>
        <img src="../assets/Logo.svg">
        <p style="margin-top: auto;">da Subiter.</p>
      </div>
      <div>
        <p>Bem-vindo</p>
        <p>De volta!</p>
      </div>
      <div>
        <p>Alcance o invisível, Subiter</p>
      </div>
    </div>
    <div id="loginMain">
      <div id="loginContent">
        <section id="welcome">
          <h1>Login</h1>
          <div>
            <img src="../assets/Icons/Info.svg" style="width: 12px; margin:1px 7px;"/>
            <span>
              <p>Olá, amigo! Por favor entre no</p>
              <p>Sistema de Gerenciamento de Controle.</p>
            </span>
          </div>
        </section>
        <LoginForm/>
      </div>
    </div>
  </div>
</template>
```

>Esse código também contém a importação de um componente "LoginForm" que conta com a identificação de email, senha e tipo de usuário, onde conseguimos identificar na seção de script:

```
<script> 
import LoginForm from '../components/form/LoginForm.vue'
export default {
  name:"Login",
  components:{
    LoginForm
  }
}
</script>
```

>Para lidar com o design e estilização com CSS, o Vue contém também uma seção onde é possível utilizar com class e ids:
```
<style scoped>

#loginBackgorund {
  background-image: url("../assets/BgLogin.svg");
  width: 50%;
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding: 3rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  color: #fff;
  font-size: 70px;
  font-weight: bold;
}

.loginBackground div:first-child{
  display: flex;
}
</style>
```

>O uso do modificador scoped garante que essas regras de estilo sejam aplicadas somente aos elementos dentro do escopo do componente atual, evitando que sejam afetados por estilos definidos em outros componentes ou estilos globais da aplicação.
</details>

<details><summary>Tela - Desenho de Anomalias</summary>
<p align="justify">
	
 > A cada vez que o usuário clicava dentro da tag canvas uma função era disparada para adicionar as coordenadas do formato desenhado para uma array local e em seguida ser armazenada no banco de dados:
 ```
 draw(evt){
  const stage = evt.target.getStage();
  const pos = stage.getPointerPosition();
  const nl = {
    x:pos.x,
    y:pos.y,
    height: this.tamanho,
    width: (this.forma=="alongado")?(this.tamanho*3):this.tamanho,
    fill:this.color,
    type:this.forma,
    info:{
        w:null,
        h:null,
        d:null
    }
  }
  if(this.forma=="isolado"){
      nl['radius']=this.tamanho/2
  }
  this.layers[this.forma].push(nl)
}
 ```
 > A função "draw" recebe um evento (evt) como parâmetro. Dentro da função, é obtida a referência ao stage a partir do evento. Em seguida, é obtida a posição do ponteiro (pos) no stage. Com base nessa posição, são definidas as propriedades de um novo objeto (nl) que será desenhado. As propriedades incluem as coordenadas x e y, altura e largura, cor de preenchimento, tipo de forma e informações adicionais. Se a forma for "isolado", é definido também o raio com base no tamanho. O novo objeto é então adicionado a uma camada específica (this.layers[this.forma]) para armazenamento.

<img src="https://github.com/DolphinDatabase/MCS/assets/74321890/53243fd2-ffcd-4a47-b175-77c65ae08ff5">
	
</details>

No **back-end**, participei do desenvolvimento das rotas HTTP na linguagem Java.
<details><summary>Rota de Orçamento</summary>
<p align="justify">

<img src="https://github.com/DolphinDatabase/Cloud-In/assets/74321890/37241191-d331-4ae5-81df-281e1e79af07">
	
>Realizei o CRUD de orçamento, porém abaixo mostro o método de uma solicitação GET para listar orçamentos. Ele verifica a permissão do usuário, recupera os resumos de orçamento e retorna uma resposta com o resultado da operação, incluindo mensagens informativas em caso de sucesso ou mensagens de erro em caso de exceção.
```
    @GetMapping
    @PreAuthorize("hasRole('ADM')")
    public ResponseEntity<ResponseSummaryModel> listBudget(){
        ResponseSummaryModel res = new ResponseSummaryModel();
        try{
            List<BudgetSummaryModel> all = bRepository.findAll().stream().map(this::toBudgetSummaryModel).collect(Collectors.toList());
            res.setAll(200, true, "Todos os Orçamentos listados", all);
            logger.info(res.getMessage());
            return ResponseEntity.status(HttpStatus.OK).body(res);
        }catch(Exception err){
            res.setAll(500, false, err.getMessage(), null);
            logger.error(res.getMessage());
            return ResponseEntity.status(HttpStatus.INTERNAL_SERVER_ERROR).body(res);
        }
    }	
```

</details>

Na parte de design, ajudei na criação de wireframes.
<details><summary>Wireframes</summary>
	
Para acessar nossos *Wireframes*, clique [aqui.](https://www.figma.com/file/MM0pLqbdpFde9cqt9upsWx/MCS-Dolphin?node-id=0%3A1).

<img src="https://github.com/DolphinDatabase/Cloud-In/assets/74321890/a2e5f9ff-2b5e-4270-b66e-678b0ecf13e4">

</details>	

Atuando no papel de Scrum Master, fiquei responsável pelo gerenciamento de impedimentos e organização de tarefas.
<details><summary>Jira - MCS</summary>
Para mostrar melhor a usabilidade do Jira e divisão de histórias, abaixo está o roadmap do projeto. 

<img src="https://github.com/pdrMottaS/Portifolio/assets/74321890/bd665fe3-0d36-41cf-8b72-760a2207bd60">
</details>
	
Documentei o projeto no GitHub, desenvolvi documentos sobre o manual do usuário e como está a organização do código e suas funcionalidades.
<details><summary>Documentação</summary>

Para acessar nosso *manual do usuário*, clique [aqui](https://github.com/DolphinDatabase/MCS/blob/main/Manual/MCS_ManualdoUsu%C3%A1rio.pdf)
	
<img src="https://github.com/DolphinDatabase/Cloud-In/assets/74321890/978b4f38-bb0a-466d-bef1-500825c504de">

</details>
	
Minhas áreas de atuação:
- Home: front-end
- CRUD de Usuários: front-end
- CRUD de Equipamentos: front-end 
- CRUD Falhas e Soluções genéricas: front-end
- Orçamento: front-end e back-end
- Mapeamento gráfico: front-end

### Hard Skills
Durante o projeto participei de um Hackathon organizado pela empresa Soluções Sophia, junto com os outros integrantes do grupo Dolphin Database.
Nesse evento, unimos tecnologia e educação onde nosso objetivo foi aperfeiçoar as ideias e implementá-las em um aplicativo feito para professores, pais e alunos. Meu grupo ficou responsável pelo tópico de frequência de alunos, então desenvolvi um protótipo no figma e a aplicação front-end utilizando o VueJS.

Como aluna destaque, fui contratada como estagiária na Soluções Sophia, onde trabalho atualmente com o desenvolvimento web e design.

- Desenvolvimento de serviços CRUD: sei fazer com autonomia.
- Desenvolvimento utilizando VueJS: sei fazer com autonomia.
- Utilização de OracleCloud: sei fazer com autonomia.

### Soft Skills

Neste projeto, atuando novamente como Scrum Master e aplicando experiências anteriores, desenvolvi e aprimorei habilidades para promover agilidade no desenvolvimento.
	
Ganhei um **senso de liderança**, sendo capaz de liderar a equipe na implementação de práticas ágeis. A **resolução de conflitos** se tornou uma competência fundamental para manter um ambiente de trabalho harmonioso. Minha **proatividade** e **comprometimento** impulsionaram o progresso do projeto, enquanto a **motivação** ajudou a manter a equipe focada. A **gestão** eficaz foi crucial para coordenar todas as atividades, resultando em um projeto mais ágil e bem-sucedido. Essas habilidades fortaleceram minha atuação como Scrum Master e como fruto do nosso desenvolvimento fomos chamados para trabalhar na empresa parceira.

# Projeto 5 - 2º semestre de 2023

## Empresa parceira:

MidAll<br/>
![midall](https://user-images.githubusercontent.com/74321890/191144569-593506c4-b02e-41bf-830d-9f6e88a57278.jpeg)

<p align="justify">
A MidAll é uma empresa que se dedica a ajudar outras empresas a se adaptarem às mudanças do mercado.
	
### Visão do Projeto

O software Cloud-In é um aplicativo orquestrador para transferência automática de arquivos entre sistemas de armazenamento online. Através de sua interface minimalista e interativa, o usuário pode cadastrar suas credenciais e configurar as transferências conforme sua necessidade, iniciando a jornada de download e upload entre os storages.

[<img src="https://user-images.githubusercontent.com/74321890/228991716-687c07f9-3b6a-4cea-b855-677b51b2b20a.svg" width="40%">](https://www.youtube.com/watch?v=AGRvBq9Xq4U&list=PLUOBqJKbljZsvHbaHWKrQ3z0l9l2Uo_f0 "Cloud-in vídeo Demonstração")

Link do repositório do projeto: https://github.com/DolphinDatabase/Cloud-In

### Tecnologias adotadas na solução

Para o desenvolvimento web utilizamos o framework VueJS, já citado anteriormente no projeto 4, porém com o framework Tailwind para o CSS.

<details><summary>Tailwind</summary>
<p align="justify">

>Tailwind é um framework CSS que permite há você criar layouts para suas aplicações web utilizando sua estrutura, ou seja, uma ferramenta que fornece componentes para sua estilização.

</details>

O back-end foi feito em Python com Flask.

<details><summary>Flask</summary>
<p align="justify">
	
>Flask é um micro-framework multiplataforma que provê um modelo simples para o desenvolvimento web. Podemos dizer que o micro-framework é uma versão minimalista de frameworks, sendo bastante utilizado para criação de microsserviços, como APIs RESTful.

</details>

E o banco de dados foi armazenado no MySQL.

<details><summary>MySQL</summary>
<p align="justify">

>O MySQL é um sistema gerenciador de banco de dados relacional de código aberto usado na maioria das aplicações gratuitas para gerir suas bases de dados. O MySQL utiliza a linguagem SQL (Structure Query Language – Linguagem de Consulta Estruturada), que é a linguagem mais popular para inserir, acessar e gerenciar o conteúdo armazenado num banco de dados.

</details>

Um diferencial nesse projeto foi a adição de DevOps como critério de aceite por parte da FATEC.

Os processos utilizados foram:

<details><summary>GitFlow</summary>
<p align="justify">

>O método GitFlow funciona a partir de branchs, que são ramificações montadas em um modelo gráfico que parece uma árvore com diversos galhos. Cada fluxo do GitFlow possui cinco ramificações que durante o desenvolvimento do projeto se integram uma à outra constantemente

</details>

<details><summary>Issue Tracking</summary>
<p align="justify">

>Para a ferramenta de gestão optamos por utilizar o Jira, ele está estruturado com Epic/Story/Task. As histórias, no nosso caso, equivalem a questões, onde podemos integrar com o github usando o seu id. Para dar commit, utilizamos o pré-commit onde definimos que todo commit deve começar com a abreviatura padrão para histórias (CLD-) e o número (varia para cada história).

</details>

<details><summary>CI (Continuous Integration)</summary>
<p align="justify">

>Conforme esquema de gitflow do projeto, a branch principal é a de produção, devido a esse processo, existe um fluxo de ações do github que realiza a implantação automática no servidor de produção AWS EC2. A implantação é feita em um container, e ela é criada a partir de uma imagem do [Dockerfile](https://github.com/DolphinDatabase/Cloudin-backend/blob/main/Dockerfile), além disso, toda vez que a implantação é feita, todas as imagens e containers são deletados de acordo com o [deploy flow](https://github.com/DolphinDatabase/Cloudin-backend/blob/main/.github/workflows/deploy.yml).

</details>

<details><summary>Unit Test</summary></summary>
<p align="justify">

>No teste unitário testamos funções e o retorno esperado, há também o teste de banco de dados, onde testamos sua regra de negócio. O teste de unidade ocorre sempre que há uma solicitação pull para o branch dev.

</details>

<details><summary>Integration Test</summary></summary>
<p align="justify">

>O teste de integração testa a conexão com o servidor e, no nosso caso, testa transferências de arquivos, validação de token e autenticação. Este teste é manual.

</details>

<details><summary>Monitoring</summary></summary>
<p align="justify">

>O projeto usa uma instância Amazon Linux EC2 para hospedar a API escrita em Flask. Dentro desta máquina virtual, utilizamos a imagem docker "zabbix/zabbix-agent:latest", que já possui um banco de dados PostgreSQL embarcado, para criar o container "zabbix_server" e utilizar a infraestrutura de monitoramento que a plataforma Zabbix oferece. Este contêiner usa a distribuição Alpine Linux e usamos o gerenciador de pacotes "apk" para instalar o "zabbix-agent". Na interface web do zabbix, criamos o host chamado "Backend" que é referenciado dentro do arquivo de configuração "zabbix-agent".

</details>

<details><summary>CD (Continuous Delivery)</summary></summary>
<p align="justify">

<details id="k3d-p5"><summary>K3D Cluster</summary>

In order to create a k8s environment for testing before using the AKS cluster, the configuration and documentation of the k3d cluster was carried out. K3d is a command line tool designed to simplify the management of Kubernetes clusters locally. It lets you create, deploy, and manage Kubernetes clusters in your development or test environment. With K3d, you can quickly provision lightweight Kubernetes clusters in Docker containers, making it easy to run multiple Kubernetes instances on a single machine. It's a popular choice for developers who want to test and debug applications in a local Kubernetes environment.

    After installing the dependencies, just run the following command:
    ```bash
    k3d cluster create --config k3d-simple-cluster.yaml
    ```

    The complete setup guide is present in the [project repository.](https://github.com/DolphinDatabase/Cloudin-backend#readme)
</details>
<details id="aks-p5"><summary>AKS Cluster</summary>

    Azure Kubernetes Service (AKS) offers the fastest way to get started developing and deploying cloud-native apps in Azure, in datacenters or at the edge with built-in code-to-cloud pipelines and health checkers. Get unified management and governance for on-premises, edge, and multi-cloud Kubernetes clusters. Interoperate with Azure security, identity, cost management and migration services [\[23\]](#references).
</details>

<details id="deployment-p5"><summary>Kubernetes Deployment</summary>

    ```yaml
    apiVersion: apps/v1
    kind: Deployment
    metadata:
    name: cloudin-midall
    labels:
        app: cloudin-midall
    spec:
    replicas: {{ .Values.replicas }}
    selector:
        matchLabels:
        app: cloudin-midall
    template:
        metadata:
        labels:
            app: cloudin-midall
        spec:
        containers:
            - name: backend
            image: {{ include "cloudin-midall.getImage" . }}
            ports:
                - containerPort: {{ .Values.backend.ports.containerPort }}
            env:
            - name: DATABASE_URL
                value: mysql://dbuser:dbuser@cloudin-midall-mysql:3306/cloudin
    {{ include "cloudin-midall.probeAndResources" .Values.backend.ports.containerPort | nindent 10 }}
    ```

    A "Deployment" is used to create and manage application instances in a Kubernetes cluster. It specifies settings for replication, pod selection, pod template, and associated containers. In the case used in the project, the Deployment called "cloudin-midall" is being configured to create a replicaSet with the number of replicas defined by the value defined in values.yaml. The "backend" container is defined with its image and port and environment variable settings.

    A Deployment is suitable for applications that are stateless, that is, do not store persistent data. It manages the deployment of pod replicas in a controlled manner, enabling upgrades, rollback, and automatic scaling. Pods created by a Deployment have no unique identity and do not maintain persistent connections to storage.
</details>
<details id="statefulset-p5"><summary>Kubernetes StatefulSet</summary>

    ```yaml
    apiVersion: apps/v1
    kind: StatefulSet
    metadata:
    name: cloudin-midall-mysql
    labels:
        app: cloudin-midall-mysql
    spec:
    serviceName: cloudin-midall-mysql
    replicas: 1
    selector:
        matchLabels:
        app: cloudin-midall-mysql
    template:
        metadata:
        labels:
            app: cloudin-midall-mysql
        spec:
        containers:
            - name: mysql
            image: mysql:latest
            ports:
                - containerPort: 3306
            env:
                - name: MYSQL_ROOT_PASSWORD
                value: "example"
                - name: MYSQL_DATABASE
                value: "cloudin"
                - name: MYSQL_USER
                value: "dbuser"
                - name: MYSQL_PASSWORD
                value: "dbuser"
            resources:
                limits:
                cpu: 100m
                memory: 512Mi
                requests:
                cpu: 80m
                memory: 128Mi
    ```

A "StatefulSet" has been defined in Kubernetes to run a MySQL database instance. The StatefulSet is named "cloudin-midall-mysql" and has a replica. The service associated with StatefulSet is also called "cloudin-midall-mysql". The pod definition includes a container called "mysql" that uses the latest MySQL image. Port 3306 is exposed for communication. Environment variables are set to define the MySQL root user password, database name, database user name and password. Resource constraints are defined to limit the container's CPU and memory usage.

    A "StatefulSet" is used for applications that have state and require unique identity and persistent storage for their pods. It provides guarantees of order and stability when creating, updating, and deleting pods. Each pod in a StatefulSet is assigned a unique identifier and maintains its own persistent state. This is especially useful for databases and other applications that require persistent storage and state consistency across pods.
</details>
<details id="service-ip-p5"><summary>Kubernetes Service ClusterIP</summary>

    ```yaml
    apiVersion: v1
    kind: Service
    metadata:
    name: cloudin-midall-mysql
    labels:
        app: cloudin-midall-mysql
    spec:
    type: ClusterIP
    ports:
        - port: 3306
        targetPort: 3306
        protocol: TCP
        name: mysql
    selector:
        app: cloudin-midall-mysql
    ```

  Service ClusterIP is a type of service in Kubernetes that exposes a set of pods for internal communication within the cluster. It provides a static internal IP address to the service, allowing other resources within the cluster to connect to it. The "cloudin-midall-mysql" service is defined as a Service ClusterIP. It maps port 3306 to targetPort 3306 in TCP protocol, which is the standard for communication with the MySQL database. The "app: cloudin-midall-mysql" selector ensures that the Service forwards traffic to the pods that have the same label. This type of service is suitable for internal communication and is not accessible from outside the cluster.
</details>
<details id="service-lb-p5"><summary>Kubernetes Service LoadBalancer</summary>

    ```yaml
    apiVersion: v1
    kind: Service
    metadata:
    name: cloudin-midall
    labels:
        app: cloudin-midall
    spec:
    type: LoadBalancer
    ports:
    - port: {{ .Values.backend.ports.containerPort }}
        targetPort: {{ .Values.backend.ports.containerPort }}
        protocol: TCP
        name: http
    selector:
        app: cloudin-midall
    ```

    Service LoadBalancer is a type of service in Kubernetes that exposes a set of pods to external traffic, allowing the application to be accessed from outside the cluster. It automatically provisions an external load balancer, such as a cloud load balancer, that distributes traffic to the Service Pods. The "cloudin-midall" service is defined as a Service LoadBalancer. It maps a given port, defined by the ".Values.backend.ports.containerPort" value, to the corresponding targetPort. The specified protocol is TCP and the service name is "http". The "app: cloudin-midall" selector ensures that the Service forwards traffic to pods with the same tag. This type of service is suitable for exposing an application to external traffic, allowing accessibility from outside the cluster, through the load balancer provided by the Kubernetes runtime, such as a cloud load balancer.
</details>
<details id="hpa-p5"><summary>Kubernetes HorizontalPodAutoscaler</summary>
    
    ```yaml
    apiVersion: autoscaling/v2
    kind: HorizontalPodAutoscaler
    metadata:
    name: cloudin-midall-hpa
    spec:
    scaleTargetRef:
        apiVersion: apps/v1
        kind: Deployment
        name: cloudin-midall
    minReplicas: 1
    maxReplicas: 5
    metrics:
        - type: Resource
        resource:
            name: cpu
            target:
            type: Utilization
            averageUtilization: 80
    ```

    The HorizontalPodAutoscaler (HPA) is a Kubernetes feature that allows automatic scaling of the number of replicas of a Deployment or other horizontally scaling object. The HPA named "cloudin-midall-hpa" is configured to automatically scale the number of replicas of the "cloudin-midall" Deployment. The minimum number of replicas is set to 1 and the maximum number to 5. HPA uses metrics to make sizing decisions. The metric used is the average CPU utilization, where the HPA will try to keep the CPU utilization around 80%. Based on this metric, the HPA will increase or decrease the number of Deployment replicas to meet traffic demands. This allows the Kubernetes cluster to automatically adjust processing power as needed, ensuring efficient scaling of application resources.
</details>
<details id="ingress-p5"><summary>Kubernetes Ingress</summary>
    
    ```yaml
    apiVersion: networking.k8s.io/v1
    kind: Ingress
    metadata:
    name: cloudin-midall
    annotations:
        kubernetes.io/ingress.class: azure/application-gateway
    spec:
    rules:
    - http:
        paths:
        - path: /
            pathType: Prefix
            backend:
            service:
                name: cloudin-midall
                port:
                number: 5000
    ```

   Ingress is a feature in Kubernetes that allows exposing HTTP and HTTPS services externally to the cluster. The Ingress named "cloudin-midall" is defined with the annotation "kubernetes.io/ingress.class" set to "azure/application-gateway", indicating that the Ingress will be managed by Azure Application Gateway. The Ingress specification includes rules for routing traffic. In the example, there is a single rule that forwards all HTTP traffic coming into the root ("/") to the service called "cloudin-midall" on port 5000. The "pathType" field is set to "Prefix", which means that Ingress will match URLs that start with the specified path. Ingress allows flexible configuration of external traffic routing to internal services in Kubernetes, providing a layer of access control and load balancing.
</details>

</details>

### Contribuições pessoais
Neste projeto, minhas principais funções foram o desenvolvimento das telas no front-end e sua prototipação, autenticação utilizando Google, testes unitários e rotas no back-end, além de ser PO, mantendo um contato contínuo com o cliente afim de praticar comunicação.

Abaixo mostro alguns exemplos do desenvolvimento do **front-end** em VueJS.

<details><summary>Tela - Home</summary></summary>
<p align="justify">

Implementamos o login utilizando 2 ferramentas: Google para acessar os arquivos do drive e S3 para acessar os arquivos do bucket.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/3e282808-f684-4e46-917a-92a2a93c4bf6" />

Nessa tela também conseguimos configurar:

- Tempo de pesquisa recorrente;
- Quantidade de banda utilizada;
- Tempo utilizado durante as transferências.

>Esse código faz parte de um formulário que permite configurar o tempo de pesquisa recorrente. Ele exibe campos de entrada de tempo e uma lista suspensa com opções de segundo, minuto e hora, para o usuário selecionar. Os valores escolhidos ou inseridos são vinculados a variáveis para uso no aplicativo.

```
<template>
    <div class="flex flex-col gap-8">
      <div class="rounded-md border-slate-200 border shadow ">
        <div class="grid-container items-center">
          <p>
            Tempo da pesquisa recorrente
          </p>
          <span class="tracinho" />
          <input v-model="config.JOB_TIME" class="bg-transparent border-b-2" type="number">
          <select v-model="selectedTimeSearch" class="bg-transparent border-2 border-slate-200 rounded-md px-4">
            <option value="" disabled>
              Selecione uma opção
            </option>
            <option v-for="time in times" :key="time.id">
              {{ time.tempo }}
            </option>
          </select>
        </div>
      </div>
</template>
```

>Na parte de estilização utilizamos o tailwind que faz isso de forma inline, ou seja, utilizando class e passando seus atributos na própria linha, evitando utilizar o "style" que é nativo do Vue, garante que essas regras de estilo sejam aplicadas somente aos elementos dentro do escopo do componente atual, evitando que sejam afetados por estilos definidos em outros componentes.

```
 setConfig() {
      let tempoPesquisa = 0;
      if (this.selectedTimeSearch == 'segundos') {
        tempoPesquisa = this.config.JOB_TIME
      } else if (this.selectedTimeSearch == 'minutos') {
        tempoPesquisa = this.config.JOB_TIME / 60
      } else if (this.selectedTimeSearch == 'horas') {
        tempoPesquisa = this.config.JOB_TIME / 3600
      }

      let tempoTransfer = 0
      if (this.selectedTimeTransfer == 'segundos') {
        tempoTransfer = this.config.TRANSFER_TIME
      } else if (this.selectedTimeTransfer == 'minutos') {
        tempoTransfer = this.config.TRANSFER_TIME / 60
      } else if (this.selectedTimeTransfer == 'horas') {
        tempoTransfer = this.config.TRANSFER_TIME / 3600
      }

      alert('Configurações aplicadas com sucesso!')

      api.post("/job", { "job": tempoPesquisa, "band": this.config.BAND, "transfer": tempoTransfer })
      localStorage.setItem('selectedTimeSearch', this.selectedTimeSearch)
      localStorage.setItem('selectedTimeTransfer', this.selectedTimeTransfer)
    }
```

>A função acima é usada para configurar e enviar as preferências de tempo de pesquisa e transferência para um servidor, ao mesmo tempo em que as armazena localmente no navegador do usuário para futuras referências. O cálculo dos valores de tempo é baseado nas escolhas feitas pelo usuário e no uso de variáveis de configuração existentes (this.config.JOB_TIME e this.config.TRANSFER_TIME).
</details>

<details><summary>Tela - Transferências</summary></summary>
<p align="justify">

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/67b0da7f-7505-4e37-8378-70977a547047" />

>Essa tela inicial serve para mostrar ao usuário que ele precisa adicionar uma transferência clicando no botão.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/089731e8-244d-48c3-9b7a-95f8e285a3dd" />

>Ao clicar aparece esse collapse onde ele define **de** qual drive ele quer passar os arquivos e **para** qual ele quer passar. Podendo assim escolher os arquivos.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/f9d973c1-93b3-4368-8012-6550085f5002" />

>Na escolha de arquivos, um modal é aberto fazendo com que o usuário tenha ciência das escolhas do drive.

```
<template>
  <div class="flex items-center justify-around mb-8 mt-4">
    <div>
      <p
        class="text-lg"
        :class="{ 'text-green-500 text-lg font-extrabold': step === 0 }"
      >
        {{ origin }}
      </p>
    </div>
    <ChevronRightIcon class="h-5 w-5" />
    <div>
      <p 
        class="text-lg"
        :class="{ 'text-green-500 text-lg font-extrabold': step === 1 }"
    >
        {{ destiny }}
      </p>
    </div>
  </div>
```

>Temos um campo de busca, onde o usuário consegue filtrar os arquivos que ele quer enviar, facilitando a sua procura.

```
<div class="m-3 flex justify-end">
	<div class="relative search-field">
		<MagnifyingGlassIcon class="absolute z-10 w-4 h-4 left-2 top-[10px] text-gray-600" />
		<input
		  v-model="search"
		  type="text"
		  class="border-2 pl-8 py-1 rounded-md"
		  placeholder="Buscar"
		  @input="onSearch()"
		>
	</div>
</div>
```

>Utilizamos uma tabela onde é possível selecionar os arquivos e prosseguir para a próxima página, onde ele consegue escolher para qual pasta ele vai enviar.

```
	<table class="w-[530px] flex flex-col">
	      <thead>
		<tr class="flex border-b-2 border-black">
		  <th class="mr-56">
		    Nome do arquivo
		  </th>
		</tr>
	      </thead>
	      <tbody class="block h-[300px] overflow-auto">
		<tr
		  v-for="d in originData"
		  :key="d.id"
		>
		  <td>
		    <input
		      v-model="selectedOrigin"
		      type="radio"
		      :value="d.id"
		    >
		  </td>
		  <td> {{ d.name }}</td>
		</tr>
	      </tbody>
	</table>
</template>
```

</details>

<details><summary>Tela - Histórico de Transferências</summary></summary>
<p align="justify">

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/6e2b58d3-275e-4031-b840-03e2c17748bc" />

>Assim que as transferências acabam de acontecer, conseguimos ver o status "em andamento", "concluído" e "erro". Além de receber uma notificação referente àquela transferência, como mostro no código e na imagem abaixo.

```
export default async function notify(data) {
    if (!("Notification" in window)) {
        console.warn("Este navegador não suporta notificações do HTML5");
        return;
    }

    var permission = await Notification.requestPermission()
    if (permission === "granted") {
        let icon
        switch (data.icon) {
            case ("Erro"):
                icon = Error
                break;
            case ("Concluido"):
                icon = Complete
                break;
            case ("Em andamento"):
                icon = Warning
        }
        new Notification(data.title, {
            body: data.text,
            icon: icon
        })
    }
}
```

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/ffe27f98-a302-44ff-a10d-75bf8cc6075d" />

>Clicando em ver detalhes, podemos ver informações como nome dos arquivos, tamanho, tempo de transferência, data e hora do início das transferências e se deu erro ou foi concluída com sucesso!

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/853c4059-8cc9-4346-8dc5-175080c90d29" />

>Abaixo encontra-se o trecho que mostra como foi montada a tabela com as informações citadas acima.

```
<table class="min-w-full divide-y divide-gray-200">
	<thead>
	    <tr>
		<th
		    scope="col"
		    class="px-6 py-3 text-left text-xs font-medium text-gray-700 uppercase tracking-wider"
		>
		    Arquivo
		</th>
		<th
		    scope="col"
		    class="px-6 py-3 text-left text-xs font-medium text-gray-700 uppercase tracking-wider"
		>
		    Tamanho
		</th>
		<th
		    scope="col"
		    class="px-6 py-3 text-left text-xs font-medium text-gray-700 uppercase tracking-wider"
		>
		    Tempo
		</th>
	    </tr>
	</thead>
	<tbody class="bg-white divide-y divide-gray-200">
	    <tr v-for="file in this.transaction.file" :key="file">
		<td class="px-6 py-4 whitespace-nowrap">
		    <div class="flex items-center">
			<div class="ml-4">
			    <div class="text-sm font-medium text-gray-900">
				{{ file.name }}
			    </div>
			</div>
		    </div>
		</td>
		<td class="px-6 py-4 whitespace-nowrap">
		    <div class="flex items-center">
			<div class="ml-4">
			    <div class="text-sm font-medium text-gray-900">
				{{ this.convertBytesSizeToHumanReadable(file.size) }}
			    </div>
			</div>
		    </div>
		</td>
		<td class="px-6 py-4 whitespace-nowrap">
		    <div class="flex items-center">
			<div class="ml-4">
			    <div class="text-sm font-medium text-gray-900">
				{{ file.time }}
			    </div>
			</div>
		    </div>
		</td>
	    </tr>
	</tbody>
</table>
```

</details>

A seguir, mostro como foi feita a autenticação com o [Google Drive](https://developers.google.com/drive/api/guides/about-sdk?hl=pt_BR).

<details><summary>Autenticação</summary></summary>
<p align="justify">

<details><summary>Front-end</summary></summary>
<p align="justify">

>Esse código é um componente Vue que exibe um botão com um cartão estilizado e permite aos usuários autenticarem-se com o Google Drive quando o botão é clicado. 

```
<template>
    <button type="button" @click="login()">
        <card-component>
            <img src="@/assets/auth/google.svg" class="w-7 mr-2">
            <p class="cursor-pointer">Autentique com o Google Drive</p>
        </card-component>
    </button>
</template>
```

>A autenticação é realizada usando o SDK do Google e os tokens resultantes são armazenados na store, nesse caso utilizamos o Vuex.

```
methods: {
        login() {
            googleSdkLoaded((google) => {
                google.accounts.oauth2.initCodeClient({
                    client_id: '532089225272-1im33klerc0hmvspgo6mh08aobithavt.apps.googleusercontent.com',
                    scope: 'https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.appdata https://www.googleapis.com/auth/drive.metadata https://www.googleapis.com/auth/drive.photos.readonly',
                    callback: this.initializeToken
                }).requestCode()
            })
        },
        initializeToken(response) {
            var data = {
                code:response.code,
                client_id:"532089225272-1im33klerc0hmvspgo6mh08aobithavt.apps.googleusercontent.com",
                client_secret:"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",
                redirect_uri:"http://localhost:8080",
                grant_type:"authorization_code"
            }
            axios.post("https://oauth2.googleapis.com/token",data)
            .then(res=>{
                this.$store.dispatch("updateGoogleToken",res.data.refresh_token)
                this.$store.dispatch("updateGoogleAccessToken",res.data.access_token)
            })
        }
    }
```
</details>

<details><summary>Back-end</summary></summary>
<p align="justify">

>Nosso back-end conta com funções de download e upload "automático", ou seja, sem interação com o usuário, ele executa essas funções, porém abaixo mostro o código responsável por listar pastas no Google Drive usando a API do Google Drive e retornar os resultados em formato JSON como resposta a uma solicitação HTTP GET. Ele lida com a autenticação usando um token no cabeçalho da solicitação e é projetado para lidar com várias páginas de resultados, se necessário.

```
@drivebp.route("/list/folder", strict_slashes=False)
def list_folders():
    try:
        token = request.headers.get("token")
        url = "https://www.googleapis.com/drive/v3/files"
        headers = {"Authorization": f"Bearer {token}"}
        params = {
            "q": "mimeType='application/vnd.google-apps.folder' and trashed=false",
            "fields": "nextPageToken, files(id, name)",
            "pageSize": 1000,
        }
        folders = []
        next_page_token = True
        while next_page_token:
            response = requests.get(url, headers=headers, params=params)
            json_response = response.json()
            folders.extend(json_response["files"])
            next_page_token = json_response.get("nextPageToken", None)
            params["pageToken"] = next_page_token
        return make_response(jsonify({"result": folders}), 200)
    except Exception as e:
        return make_response(jsonify({"error": f"list folder error:{e}"}, 500))

```
</details>
</details>

<details><summary>Testes unitários</summary></summary>
<p align="justify">

>Fizemos dois tipos de testes unitários, são eles:

<details><summary>Banco de dados</summary></summary>
<p align="justify">

>Esse é um teste unitário escrito usando a biblioteca pytest para testar um modelo chamado File em um aplicativo que usa SQLAlchemy como ORM (Object-Relational Mapping) para interagir com um banco de dados SQLite em memória.

```
@pytest.fixture
def db_session():
    engine = create_engine("sqlite:///:memory:")
    db.metadata.create_all(engine)
    Session = sessionmaker(bind=engine)
    session = Session()
    yield session
    session.rollback()


def test_file_model(db_session):
    # Create a new file
    file = File()
    file.name = "teste"
    file.size = 3.14
    file.time = time(hour=12, minute=12, second=12)

    # Add the file to the session and commit
    db_session.add(file)
    db_session.commit()

    # Query the file from the database
    result = db_session.query(File).filter_by(name="teste").first()

    # Check the result
    assert result is not None
    assert result.id == 1
```

</details>

<details><summary>S3</summary></summary>
<p align="justify">

>Este é um exemplo de teste unitário escrito usando a biblioteca pytest e a funcionalidade de mock do Python. Esses testes são projetados para verificar o comportamento da classe s3Service ao listar arquivos e pastas em um serviço AWS S3 simulado, bem como para garantir que a API responda adequadamente quando solicitada com um token de autenticação válido. Eles são uma parte importante do processo de garantir que o aplicativo funcione corretamente em relação ao AWS S3 e à autenticação.

```
@pytest.fixture(scope="session")
def init_database():
    engine = create_engine("sqlite:///:memory:")
    db.metadata.create_all(engine)
    Session = sessionmaker(bind=engine)
    session = Session()
    yield session
    session.rollback()


def test_files_by_folder():
    boto3_client = MagicMock(name="boto3.client")
    boto3_client.list_objects.return_value = {"Contents": ["folder", "file1", "file2"]}
    with patch("boto3.client", return_value=boto3_client):
        service = s3Service("token token token token")
        result = service.files_by_folder(None)
    assert result == 2

```

>Em resumo, esse teste cria um ambiente isolado de banco de dados em memória, simula a interação com o AWS S3 por meio de um cliente fictício e verifica se a função files_by_folder retorna o resultado esperado quando chamada com esse ambiente simulado. O uso de uma sessão de banco de dados em memória permite que os testes sejam independentes e não afetem um banco de dados de produção.
 
</details>
</details>

### Hard Skills

Neste projeto obtive meu primeiro contato com api do Google e DevOps. Foi muito importante também para o meu desenvolvimento utilizando a linguagem Python, visto que a última e única utilização desta foi no primeiro semestre.

Além disso, utilizar DevOps pela primeira vez foi ótimo, pois permite a colaboração contínua entre desenvolvedores e operadores, acelerando a entrega de software, melhorando a qualidade e a confiabilidade das aplicações, e promovendo uma cultura de automação e feedback constante, que resulta em maior eficiência e satisfação dos clientes.

No mais, temos os pontos específicos abaixo:

- Testes unitários: sei fazer com autonomia.
- Desenvolvimento de componentes, design e demais trabalhos necessários no front-end: sei fazer com autonomia.
- Desenvolvimento de scripts em Python: sei fazer com autonomia.

### Soft Skills

O PO deve ser capaz de **comunicar** de maneira clara e eficaz tanto com a equipe de desenvolvimento quanto com a empresa. Fazendo assim com que **habilidades de negociação** fossem necessárias já que muitas vezes precisa negociar prioridades, recursos e requisitos com a equipe de desenvolvimento e a empresa, garantindo que o produto atenda às necessidades do cliente. A **flexibilidade e adaptação** é essencial à medida que os requisitos e prioridades mudam, e o PO deve ser flexível e capaz de se adaptar às mudanças de forma eficiente. Além da **liderança** como SM em outras sprints, ajudou bastante como PO, pois há o esforço para criar um produto de sucesso, o que requer habilidades de liderança para motivar a equipe e manter todos alinhados com os objetivos.

# Projeto 6: 2º Semestre de 2023

### Parceiro Acadêmico

Visiona

<br/>

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/590f7cea-060d-4216-ad21-c56760dd678c" width=350px/>

A Visiona Tecnologia Espacial é uma joint-venture entre a Embraer Defesa & Segurança e a Telebras, voltada para a integração de sistemas espaciais.

### Visão do Projeto

O POP é uma plataforma de monitoramento das atividades agropecuárias cadastradas no Proagro. Além disso, o sistema possui ferramentas de previsão que visam auxiliar o usuário na tomada de decisão.

[<img src="https://github.com/DolphinDatabase/POP/assets/74321890/1930571b-dd33-4331-8624-17867451e940" width="40%">](https://www.youtube.com/watch?v=-L3xjt2aHUY&list=PLUOBqJKbljZvDd8dOXBFlEHLtTTWCrRLk "pop vídeo Demonstração")

Link do repositório do projeto: https://github.com/DolphinDatabase/POP

### Tecnologias adotadas na solução

O back-end foi feito em Python com Fastapi.

<details><summary>FastAPI</summary>
<p align="justify">

>FastAPI é um framework web rápido (como o nome sugere) e fácil de usar para a criação de APIs em Python. Ele foi projetado para ser fácil de aprender e usar, enquanto fornece alto desempenho e suporte automático para documentação interativa.

No caso do nosso projeto criamos as seguintes funcionalidades:
- Autenticação com JWT;
- CRUD de usuário;
- CRUD de termos;
- GET de informações referente as glebas e suas respectivas localizações;
- GET de informações referentes a predição NDVI.
  
</details>

<details><summary>Pandas</summary>
<p align="justify">

>O pandas é uma biblioteca em Python para manipulação eficiente e análise de dados tabulares, oferecendo estruturas como DataFrames. Amplamente usada em ciência de dados, simplifica tarefas como limpeza, transformação e visualização de dados. Integrando-se facilmente a outras bibliotecas, como NumPy e Matplotlib, o pandas é essencial para análise de dados em Python.

Utilizamos o Pandas para:
- Tratamento de dados do Proagro;
- Atualização de dados no banco.

</details>

<details><summary>Postgis</summary>
<p align="justify">

>O PostGIS é uma extensão geoespacial para o sistema de gerenciamento de banco de dados PostgreSQL. Ele capacita o PostgreSQL a lidar com dados geoespaciais, permitindo armazenar, consultar e analisar informações vinculadas a localizações geográficas. O PostGIS fornece suporte para tipos de dados geométricos e geográficos, além de uma ampla gama de funções espaciais, possibilitando a execução de consultas espaciais complexas. Essa extensão é crucial para projetos que envolvem dados geográficos, como mapeamento, geocodificação e análises espaciais em geral.

Utilizamos o PostGIS, para o armazenamento dos dados do Proagro, visto que contém informações geoespaciais (ex: latitude e longitude), formação de polígonos, entre outros.

</details>

Para o front-end continuamos com o VueJS.

<details><summary>TypeScript</summary>
<p align="justify">

>TypeScript é uma extensão do JavaScript que adiciona tipagem estática opcional, facilitando a detecção de erros durante o desenvolvimento. Funciona como um superset do JavaScript, sendo transpilado para código JavaScript. Suporta recursos do ECMAScript 6 e oferece ferramentas de desenvolvimento avançadas. É popular no desenvolvimento front-end, especialmente com frameworks como Angular.

Nesse projeto demos continuidade na utilização do VueJS para o desenvolvimento do front-end, porém com **composition api**.
A Composition API é uma característica do Vue.js 3 que oferece uma nova abordagem para organizar a lógica de componentes de forma mais modular e reutilizável. Quando combinada com TypeScript, ela proporciona benefícios adicionais devido à tipagem estática.

</details>

<details><summary>Element Plus</summary>
<p align="justify">

Element Plus é uma biblioteca de componentes Vue.js baseada no Element UI. Ambas são bibliotecas de componentes para o framework Vue.js, que facilitam a criação de interfaces de usuário consistentes e atraentes.

</details>

### Contribuições pessoais

No código, criei a autenticação com JWT no FastAPI, abaixo mostro alguns exemplos.
	
<details><summary>Autenticação </summary>
<p align="justify">

<details><summary>Controller</summary>

>Esse código define um endpoint de login (/) que espera receber dados de formulário relacionados ao nome de usuário e senha. Em seguida, ele usa um serviço de autenticação (auth_service) para autenticar o usuário e retorna o resultado dessa autenticação como um objeto do tipo Token.

```
@router.post("/", response_model=Token)
async def login_for_access_token(
    form_data: Annotated[OAuth2PasswordRequestForm, Depends()]
):
    return auth_service.authenticate_user(form_data.username, form_data.password)

```

</details>

<details><summary>Service</summary>

>Essa função é responsável por gerar um token de acesso JWT com base nas informações do usuário fornecido, usando uma chave secreta e um algoritmo específico, e retorna esse token encapsulado em um objeto Token.

```
def create_access_token(usuario: Usuario) -> Token:
    interval_until_expires = timedelta(
        minutes=configuration.OAUTH_ACCESS_TOKEN_EXPIRE_MINUTES
    )
    expire = (datetime.utcnow() + interval_until_expires).timestamp()
    token_data = TokenData(user=usuario.email, expire=expire)

    jwt_token = jwt.encode(
        token_data.model_dump(),
        configuration.OAUTH_SECRET_KEY,
        algorithm=configuration.OAUTH_ALGORITHM,
    )
    return Token(access_token=jwt_token, expire=expire, token_type="bearer", role=usuario.grupo)
```

</details>

</details>

Fiquei responsável pelo front-end da aplicação:

<details><summary>Tela inicial</summary>
	
<img src="https://github.com/beamedeiros/portfolio/assets/74321890/d4a6f580-6534-4e72-b046-51ca4e67362b">

>Utilizando a biblioteca de componentes Element Plus, aqui está um exemplo de como fizemos o carrossel (carousel) de imagens e textos.

```
<template>
  <div>
    <h2>O que nós oferecemos?</h2>
    <el-carousel indicator-position="outside">
      <el-carousel-item>
        <img src="../../assets/carousel/plant.png" alt="" />
        <div class="text-content">
          <h3>Análises detalhadas 🌾</h3>
          <h4>
            Nossa tecnologia avançada de análise de imagens fornece insights detalhados sobre o
            estado de suas plantações, permitindo que você tome medidas proativas para melhorar o
            rendimento.
          </h4>
        </div>
      </el-carousel-item>
    </el-carousel>
  </div>
</template>
```

</details>

<details><summary>Cadastro</summary>

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/82b54868-7299-4c0e-8c20-0240629d9b7f" />

>O código abaixo representa um formulário dinâmico que exibe diferentes campos com base nas escolhas do usuário, especificamente se ele é ou não um proprietário.

```
  <el-form
    :model="cadastroForm"
    :rules="rules"
    class="demo-ruleForm"
    label-width="120px"
    label-position="top"
    status-icon
    ref="cadastroFormRef"
    size="default"
  >
    <div>
      <el-form-item prop="nome">
	<el-input v-model="cadastroForm.nome" placeholder="Nome completo" />
      </el-form-item>
      <el-form-item prop="email">
	<el-input v-model="cadastroForm.email" placeholder="Email" />
      </el-form-item>
      <el-form-item prop="senha">
	<el-input
	  v-model="cadastroForm.senha"
	  placeholder="Senha"
	  type="password"
	  show-password
	/>
      </el-form-item>
      <div class="checks">
	<el-checkbox
	  v-model="cadastroForm.proprietario"
	  label="É proprietário?"
	  size="large"
	  prop="proprietario"
	/>
	<el-form-item v-if="cadastroForm.proprietario" prop="doc">
	  <el-input v-model="cadastroForm.doc" placeholder="CPF" />
	</el-form-item>
      </div>
    </div>
  </el-form>
```

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/d223c18a-d93b-40f3-98d0-93dff4c4fd0c" />

>Ao clicar em continuar, aparecerá os termos. O termo varia dependendo da escolha do tipo de usuário, se ele escolher "proprietário" os termos respectivos à esse grupo.

```
<el-form
    :model="cadastroTerms"
    :rules="rulesTerms"
    class="demo-ruleForm"
    label-width="120px"
    label-position="top"
    status-icon
    ref="cadastroTermsRef"
    size="default"
  >
    <div class="check-terms" v-for="condicao in cadastroTerms.condicoes" :key="condicao.id">
      <el-form-item prop="condicoes">
	<el-checkbox
	  v-model="condicao.aceite"
	  :label="condicao.texto"
	  size="large"
	  :class="cadastroTerms.condicoes.length > 1 ? 'break-text' : 'break-text-only'"
	/>
      </el-form-item>
    </div>
    <div class="check-terms">
      <el-form-item prop="termos">
	<el-checkbox
	  v-model="termos.aceite"
	  label="Li e aceito os Termos de Uso e Política de Privacidade."
	  size="large"
	/>
	<el-icon v-if="!cadastroForm.proprietario" @click="$router.push('/terms')"
	  ><Connection
	/></el-icon>
	<el-icon v-if="cadastroForm.proprietario" @click="$router.push('/terms-owner')"
	  ><Connection
	/></el-icon>
      </el-form-item>
    </div>
</el-form>
```
</details>

<details><summary>Login</summary>

Caso seu cadastro esteja correto. Você será direcionado à página de Login.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/e06a99fd-5fc0-40c1-a14a-7963433a4518" />

```
<el-form :model="login" label-width="120px" label-position="top">
    <el-form-item>
      <el-input v-model="login.username" placeholder="Email" />
    </el-form-item>
    <el-form-item>
      <el-input
	v-model="login.password"
	placeholder="Senha"
	type="password"
	show-password
      />
    </el-form-item>
</el-form>
```

>Esse código cria um formulário simples de login com campos de nome de usuário (email) e senha, utilizando os componentes fornecidos pelo Element Plus. O estado do formulário é gerenciado pelo objeto login no Vue.js.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/adf581aa-ec90-4d0a-9cd4-3e433d964404" />

>Caso o usuário já tenha uma conta e os termos forem atualizados, além de receber um alerta por e-mail, ele também é redirecinado para aceitar os novos termos.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/10bbe18b-56eb-4d1a-96ef-0154a0a1bded" />

</details>

<details><summary>Tela do mapa</summary>

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/4bccd2c3-26d0-4a3a-b773-282f26e00315" />

Utilizamos a api do Google Maps para adicionar o mapa e suas funcionalidades e configurações. Saiba mais [aqui](https://console.cloud.google.com/apis/library/maps-backend.googleapis.com?hl=pt-BR).

>O círculo ao meio do mapa é draggable, sendo utilizado para pesquisar as glebas sem sobrecarregar a aplicação.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/014970e3-d2f4-4ab8-bf6b-ed21d71cedb7" />

```
const circleOptions = {
      strokeColor: '#000000',
      strokeOpacity: 0.8,
      strokeWeight: 2,
      fillOpacity: 0,
      map: map,
      center: currPos.value,
      radius: initialCircleRadius,
      draggable: true,
      zIndex: 0
    }

    const circle = new google.maps.Circle(circleOptions)

    google.maps.event.addListener(circle, 'drag', () => {
      continueLoad.value = false
      map.data.forEach((feature) => {
        map.data.remove(feature)
      })
    })
    google.maps.event.addListener(circle, 'dragend', () => {
      const newCenter = circle.getCenter()
      const newRadius = circle.getRadius()
      continueLoad.value = true

      if (otherPos.value) {
        otherPos.value.lat = newCenter.lat()
        otherPos.value.lng = newCenter.lng()
      }

      get_glebas(newCenter.lat(), newCenter.lng(), newRadius)
    })
```

>O código acima permite ao usuário interagir com um círculo no mapa, ajustando dinamicamente o raio do círculo através de botões de zoom, arrastando o círculo para uma nova posição e atualizando informações no mapa conforme essas interações ocorrem.
	
</details>

<details><summary>Informações da gleba</summary>

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/96d80aa8-f3cf-4370-8770-a5a17c60f54e" />

>As informações específicas sobre o plantio agrícola são mostradas dentro de um drawer. Os detalhes são preenchidos dinamicamente com base em uma consulta na API.

```
<div class="drawer-details" ref="pdfContent">
        <div>
          <h6>Plantio</h6>
          <p>Início plantio: {{ op.inicio_plantio }}</p>
          <p>Fim plantio: {{ op.fim_plantio }}</p>
          <p>Início colheita: {{ op.inicio_colheita }}</p>
          <p>Fim colheita: {{ op.fim_colheita }}</p>
          <p>Estado: {{ op.estado.descricao }}</p>
          <p>Município: {{ op.municipio.descricao }}</p>
        </div>
        <div class="drawer-content">
          <h6>Sistema de produção Agrícola</h6>
          <p>Tipo Solo: {{ op.solo.descricao }}</p>
          <p>Irrigação: {{ op.irrigacao.descricao }}</p>
          <p>Tipo cultivo: {{ op.cultivo.descricao }}</p>
          <p>Grão/Semente: {{ op.grao_semente.descricao }}</p>
          <p>Ciclo do cultivar: {{ op.ciclo.descricao }}</p>
        </div>
        <div>
          <h6>Empreendimento</h6>
          <p>Cesta: {{ op.empreendimento.cesta }}</p>
          <p>Zoneamento: {{ op.empreendimento.zoneamento }}</p>
          <p>Variedade: {{ op.empreendimento.variedade }}</p>
          <p>Produto: {{ op.empreendimento.produto }}</p>
          <p>Modalidade: {{ op.empreendimento.modalidade }}</p>
          <p>Atividade: {{ op.empreendimento.atividade }}</p>
          <p>Finalidade: {{ op.empreendimento.finalidade }}</p>
        </div>
      </div>
```

</details>

<details><summary>Série temporal e Dados de Clima</summary>

O ApexCharts é uma biblioteca de gráficos interativos em JavaScript que permite criar visualizações de dados elegantes e responsivas para páginas da web. Essa biblioteca é construída sobre o popular framework JavaScript chamado Vue.js, mas também oferece suporte a outros frameworks como React, Vue e Angular. Para saber mais [clique aqui](https://apexcharts.com/docs/installation/).

<details><summary>Predição</summary>
	
<img src="https://github.com/beamedeiros/portfolio/assets/74321890/cf7cbc35-702a-4e7c-b185-ee3ba52d8390" />

```
  timeSeriesExist.value = true
  let data: chartData = {}
  let data_predict: chartData = {}

  for (let i in ts.data.data) {
    let d = new Date(parseInt(i, 10))
    let formatted_data = `${d.getFullYear()}-${String(d.getMonth() + 1).padStart(
      2,
      '0'
    )}-${String(d.getDate()).padStart(2, '0')}`
    data_predict[formatted_data] = null
    data[formatted_data] = ts.data.data[i]
  }
  for (let i in ts.data.predict) {
    let d = new Date(parseInt(i, 10))
    let formatted_data = `${d.getFullYear()}-${String(d.getMonth() + 1).padStart(
      2,
      '0'
    )}-${String(d.getDate()).padStart(2, '0')}`
    data_predict[formatted_data] = ts.data.predict[i]
  }
  timeSeriesData.value = Object.values(data)
  timeSeriesPredict.value = Object.values(data_predict)
```

>Este trecho realiza a formatação de dados temporais, organizando os dados existentes e de previsão em objetos específicos e, em seguida, alimentando esses dados em variáveis reativas que provavelmente são usadas para renderizar um gráfico de séries temporais.

```
const predictChartOptions = {
  chart: {
    type: 'area'
  },
  stroke: {
    curve: 'smooth'
  },
  xaxis: {
    categories: []
  }
}
const chartSeries = [
  {
    name: 'NDVI',
    data: timeSeriesData
  },
  {
    name: 'Predição',
    data: timeSeriesPredict 
  }
]
```

>Esse código, portanto, configura um gráfico de área suavizado (smooth area chart) usando ApexCharts. Ele espera receber as categorias ao longo do eixo x dinamicamente e possui duas séries de dados, uma representando o NDVI e outra representando dados de previsão (Predição).
</details>

<details><summary>Open Weather</summary>

A OpenWeatherMap (OpenWeather) é uma empresa que fornece serviços de dados meteorológicos, incluindo previsões do tempo, informações atuais e históricas. Eles oferecem uma API que permite aos desenvolvedores acessar e integrar dados meteorológicos em suas próprias aplicações, sites ou serviços. Para saber mais [clique aqui](https://openweathermap.org/guide).

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/6ce2a672-aeb8-4b17-b722-362614b8937e" />

```
let weather = ts.data.weather
tempSeriesData.value = Object.values(weather.temp)
pressureSeriesData.value = Object.values(weather.pressure)
humiditySeriesData.value = Object.values(weather.humidity)
windSeriesData.value = Object.values(weather.wind_speed)
cloudsSeriesData.value = Object.values(weather.clouds)
weatherChartOptions.xaxis.categories = Object.keys(weather.temp)
```

> Esse trecho organiza dados meteorológicos em diferentes séries (temperatura, pressão, umidade, velocidade do vento, nuvens) e configura as variáveis reativas correspondentes. Além disso, atualiza as categorias ao longo do eixo x nas opções do gráfico, possivelmente para refletir as datas associadas aos dados meteorológicos. Esses dados e configurações são utilizados para renderizar o gráfico meteorológico interativo.

</details>

</details>

<details><summary>Download de Relatório</summary>

Para a construção do relatório utilizamos duas bibliotecas, [jsPDF](https://artskydj.github.io/jsPDF/docs/jsPDF.html) para criar documentos PDF dinamicamente no navegador e [html2canvas](https://html2canvas.hertzen.com/) que permite capturar o conteúdo renderizado de um elemento HTML em um navegador e convertê-lo em uma imagem (canvas). Isso inclui não apenas o texto, mas também gráficos, estilos, imagens e qualquer coisa que esteja sendo exibida na tela.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/f4dbc360-646e-4f1e-b322-c01569290b12" />

```
async function generatePDF(op: any) {
  const pdf = new jsPDF()

  pdf.setFontSize(10)

  pdf.text(`Id operação: ${op_id.value}`, 10, 10)
  pdf.text(`Id da gleba: ${gl_id.value}`, 10, 20)

...
```

>O código acima é o início de um processo de geração de PDF utilizando o jsPDF.

>Já o código abaixo é um processo do uso do html2canvas, onde está capturando o conteúdo de um elemento HTML contendo um gráfico de séries temporais, convertendo-o em uma imagem, e adicionando essa imagem a uma nova página em um documento PDF, juntamente com o texto "Predição".

```
if (timeSeriesExist.value) {
    const el = document.getElementById('chartContainer')

    const options = {
      type: 'dataURL'
    }

    const printCanvas = await html2canvas(el!, options)
    let img = printCanvas.toDataURL('image/png').replace('image/png', 'image/time-series')

    pdf.addPage()

    pdf.text('Predição', 10, 10)

    const imgData = img
    const imgWidth = 100
    const imgHeight = 100

    pdf.addImage(imgData, 'PNG', 10, 20, imgWidth, imgHeight)
  }
```

>Esta última linha do código pdf.save(${gl_id.value}.pdf) está salvando o documento PDF com o nome do id da gleba.

```
  pdf.save(`${gl_id.value}.pdf`)
}
```

</details>

<details><summary>Tela do administrador</summary>
O administrador tem dois grupos para lançar os termos, sendo eles os proprietários ou usuários normais.

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/d2e91b9b-d2d3-4a86-b18a-81e2ef608515" />

>Utilizamos a biblioteca quill para os editores de texto, são comumente usados em aplicações web que requerem a entrada de conteúdo formatado, como blogs, sistemas de gerenciamento de conteúdo (CMS), plataformas de colaboração online e muito mais.

```
quill = new Quill('#editor', {
    theme: 'snow',
    placeholder: 'Digite os termos de uso.'
  })

  quill.on('text-change', () => {
    editorContent.value = quill.root.innerHTML
  })

```

>Esse código configura um editor Quill em uma página web, define um texto de espaço reservado e, sempre que o texto no editor é alterado, atualiza um elemento de conteúdo com o conteúdo formatado do editor Quill. O texto é salvo em tags HTML e assim é possível disponibilizar ele formatado em uma página web.

```
<div class="terms-page" v-html="termo.texto"></div>
```

>Também é possível adicionar parâmetros que os usuários tem opção de aceitar ou não, como por exemplo:

<img src="https://github.com/beamedeiros/portfolio/assets/74321890/15b39d51-6790-4c1a-a42c-df33843d1838" />

```
<p>Adicione parâmetros para os termos do usuário provedor de dados</p>
      <div v-for="(condicao, index) in condicoes" :key="condicao.id">
        <div class="row">
          <div class="col s2">
            <div class="param-label">
              <div>
                <label>Parâmetro {{ index + 1 }}</label>
                <p v-if="condicao.servico == 'envio_email'">Serviço para envio de e-mail</p>
              </div>
              <el-icon v-if="condicao.id != 0" @click="removeTerm(index)"><Close /></el-icon>
            </div>
            <el-input
              v-model="condicao.texto"
              placeholder="Escreva um parâmetro de aceite"
              style="margin-bottom: 16px"
            />
          </div>
        </div>
      </div>
```

>Este código Vue.js representa uma lista de parâmetros para os termos do usuário provedor de dados, permitindo a adição e remoção dinâmica de parâmetros.
</details>

Como PO, também fiquei responsável por estudar os dados do cliente e decidir as regras de LGPD que são coerentes e aplicáveis as regras de negócio do nosso produto.
Sendo elas:
- Backup do banco de dados;
- Aceite de termos da aplicação;
- Edição e exclusão de dados do usuário.

### Hard Skills

Ao longo de minha jornada profissional, obtive uma sólida base de hard skills que moldaram minha capacidade de conceber, desenvolver e aprimorar aplicações web de maneira abrangente. Dentre essas habilidades, destaco meu profundo envolvimento com a API do Google Maps, a implementação de autenticação JWT no framework FastAPI, a criação integral do frontend da aplicação, o estabelecimento de conformidade com as normativas da LGPD (Lei Geral de Proteção de Dados),além da modelagem estética e funcional do design.

Trabalhar com a API do Google Maps envolveu a incorporação de mapas interativos, integração com serviços de geolocalização, e a criação de funcionalidades dinâmicas baseadas em mapas para proporcionar uma experiência de usuário mais rica e envolvente.

No domínio do backend, destaco a implementação bem-sucedida de autenticação utilizando JSON Web Tokens (JWT) em um ambiente FastAPI. Isso contribuiu para garantir a segurança da aplicação, possibilitando a autenticação eficiente e a autorização adequada para os usuários, conforme os requisitos do projeto. 

Assumi a responsabilidade integral pelo desenvolvimento do front-end da aplicação, aplicando tecnologias modernas para criar interfaces intuitivas e visualmente atraentes. A familiaridade com Vue.js foi empregada para garantir uma experiência de usuário suave e responsiva.

Comprometida com a privacidade e segurança dos dados, contribuí ativamente para a conformidade da aplicação com as diretrizes da Lei Geral de Proteção de Dados (LGPD). Isso incluiu a definição e implementação de políticas de privacidade, bem como a adoção de práticas que asseguram a proteção adequada das informações do usuário.

No mais, temos os pontos específicos abaixo:

- Implementação de autenticação JWT no framework FastAPI: sei fazer com autonomia.
- Desenvolvimento de componentes, design e demais trabalhos necessários no front-end: sei fazer com autonomia.
- Connhecimento sobre regras LGPD: sei fazer com autonomia.

### Soft Skills

Em minha trajetória profissional, cultivei um conjunto robusto de soft skills, estas habilidades, fundamentais para um ambiente de trabalho produtivo e inovador, têm sido a base de meu sucesso em equipes multidisciplinares e na entrega de soluções que verdadeiramente atendem às necessidades dos clientes. 

A **colaboração** é o cerne da minha abordagem de trabalho. Reconheço a importância de sinergias produtivas, valorizando as contribuições individuais e acreditando que as melhores soluções emergem da colaboração e da troca de ideias. Estou sempre disposto a compartilhar conhecimento, apoiar colegas e aprender com a diversidade de perspectivas que uma equipe pode oferecer. 

A **empatia** é uma habilidade essencial que tenho cultivado conscientemente. Entender as experiências e desafios dos outros não apenas fortalece os laços dentro da equipe, mas também me capacita a criar soluções mais centradas no usuário.

O **foco no cliente** não é apenas um lema, mas sim um princípio orientador em todas as etapas do meu trabalho. Reconheço que o sucesso de qualquer projeto reside na satisfação do cliente. Isso implica em uma constante busca pela compreensão das necessidades do cliente, antecipando-se às expectativas e garantindo que cada decisão e entrega esteja alinhada com a criação de valor para o usuário final.

Minha habilidade na **tomada de decisões** é fundamentada na análise crítica e na busca pela melhor solução possível. Considero dados objetivos, avalio diferentes perspectivas e levo em conta o impacto de minhas escolhas não apenas no curto prazo, mas também a longo prazo. Isso assegura que minhas decisões estejam alinhadas com os objetivos da equipe e os interesses dos clientes.

Essas soft skills não são apenas características pessoais, mas compromissos vivos que integro diariamente ao meu trabalho, proporcionando não apenas eficiência, mas uma contribuição significativa para a construção de ambientes de trabalho produtivos e produtos que verdadeiramente fazem a diferença para nossos clientes.

## Contatos:

- [LinkedIn;](https://www.linkedin.com/in/bea-medeiros/)
- [GitHub.](https://github.com/beamedeiros) 

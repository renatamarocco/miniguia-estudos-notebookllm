# miniguia-estudos-notebooklm
Aplicando os conhecimentos do Bootcamp da DIO para criação de um guia de estudos para um profissional de Qualidade de Software no notebooklm (RCM - Atualização Teste de SW)
1) Contexto e Objetivos
   Esse guia de estudos é uma orientação para pessoas que querem ingressar na carreira de qualidade, fazer migração de carreira ou se atualizar na área de qualidade. O objetivo desse desafio é capacitar o profissional na teoria da garantia da qualidade e trazer as novas e melhores práticas do mercado para de qualidade como, por exemplo, automação de testes em geral, processo de testes para garantia de qualidade de uma solução que usa IA Generativa, melhor teste a ser empregado em uma fase especifica de testes entre outros.
2) Curadoria da Fontes
   Como fonte de dados para esse guia de estudos usarei fontes confiáveis como materiais para certificação reconhecida mundialmente e também de consultorias/instrutores renomadas: ISTQB, Julio Lima, Udemy (free)
Videos
   https://www.youtube.com/watch?v=XAFfvt0Fej0&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=1
   https://www.youtube.com/watch?v=XAFfvt0Fej0&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=2
   https://www.youtube.com/watch?v=57brkMzlcag&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=3
   https://www.youtube.com/watch?v=57brkMzlcag&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=4
   https://www.youtube.com/watch?v=pVC7SLeZ_4k&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=5
   https://www.youtube.com/watch?v=IbF0zIFeybk&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=6
   https://www.youtube.com/watch?v=_vAlKKVtsgM&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=7
   https://www.youtube.com/watch?v=Ag8m4CTxKm4&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=8
   https://www.youtube.com/watch?v=Lf09zZwewc8&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=9
   https://www.youtube.com/watch?v=bWNV6BW1214&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=10
   https://www.youtube.com/watch?v=8oe6udsdkKc&list=PLf8x7B3nFTl1YHSwrBZPY5ASdDdzOPUXy&index=11
   https://www.youtube.com/watch?v=kXlSsQkg0BM
   https://www.youtube.com/watch?v=G1pGd06BXYo
   https://www.youtube.com/watch?v=Rpr-GRQEX2Y
   https://www.youtube.com/watch?v=Y_j8jHDwNII
   https://www.youtube.com/watch?v=kpqxf1z4Epw
   https://www.youtube.com/watch?v=u3W0Ukg-E4M
   https://malenezi.github.io/malenezi/SE401/Books/114-the-art-of-software-testing-3-edition.pdf
   Além dessas fontes solicitei ao notebookllm uma pesquisa profunda (deep research) de outras fontes relacionadas a CTFL, automação de testes de software e como garantir qualidade de uma aplicação cuja solução utiliza inteligencia artificial generativa

   Prompts:
   1) Como gerente de qualidade preciso fazer o onboarding de alguns estagiários que estarão integrando ao grupo. Quais fundamentos de testes devo apresentar. Poderia fazer uma lista explicando o que é cada um desses fundamentos de forma simples de entender, por favor?
   2) Senti falta da piramide de testes. Poderia incluir esse conteudo, por favor? Lembre-se de explicar de maneira simples.
   3) Qual a responsabilidade de um profissional de QA?
   4) Como posso registar/comunicar um bug?
   5) Falando em bug, tem algo que preciso informar para dizer que o bug encontrado é critico e deve ser priorizado?
   6) Por que devo fazer a prova para certificação?
   7) O que é CT GenAI?
   8) Como testar uma aplicação que tem um chatbot baseado em uma LLM (IA Generativa). Como garantir a cobertura se tem infinitas possibilidades de prompt? Como garantir que o teste foi executado com sucesso se o resultado obtido é de responsabilidade da LLM e podemos ter diversas respostas?
   9) Poderia criar um processo de qualidade com um passo a passo de fases, entradas e saidas para cada uma das fases para garantir a qualidade de uma aplicação que contenha IA Generativa
   10) Entendi. Imagine que um cliente de serviços financeiros me contratou para criar uma solução que sugira o melhor tipo de financiamento para ele. Como ficaria o processo acima? Poderia exemplificar as entradas e saidas de cada fase?
   11) Quais são as principais técnicas de teste de caixa-branca?
   12) Como funciona o papel do relator no registro de bugs?
   13) Quais métricas de qualidade são usadas no monitoramento em produção?
   14) Como funciona a métrica 'LLM-as-a-Judge' na prática?
   15) Quais frameworks podem auxiliar na garantia de qulidade de uma aplicação de IA Generativa?

Link do noteboobklm de QA:
  Link do notebooklm: https://notebooklm.google.com/notebook/3dcee815-a8ce-4425-bbc5-000b9b741c92/preview

  Glossário:
  Aqui está um glossário com os principais fundamentos de teste, baseados nas fontes e princípios de qualidade de software:

### **Conceitos Básicos**
*   **Análise de Valor Limite:** Técnica de **caixa-preta** que foca no teste das bordas das partições de equivalência (ex: se um campo aceita de 1 a 100, testa-se 0, 1, 100 e 101).
*   **Controle de Qualidade (QC):** Abordagem **corretiva** focada no produto final para encontrar defeitos.
*   **Depuração (Debugging):** Atividade de localizar, analisar e **corrigir** a causa raiz de um defeito no código.
*   **Garantia da Qualidade (QA):** Abordagem **preventiva** baseada em processos para evitar que erros aconteçam.
*   **Objeto de Teste:** O artefato (código, documento ou sistema) que está sendo testado.
*   **Particionamento de Equivalência:** Técnica que divide as entradas em grupos (partições) onde se espera que o software se comporte da mesma forma, reduzindo o número de testes necessários.
*   **Rastreabilidade:** Capacidade de conectar requisitos a casos de teste e defeitos, permitindo entender o impacto de mudanças.
*   **Shift-Left:** Prática de **testar o mais cedo possível** no ciclo de vida (SDLC), atuando em requisitos e design antes da escrita do código.
*   **Testware:** Todo produto de trabalho gerado durante o processo de teste, como planos, casos de teste e relatórios.

### **Diferença entre Erro, Defeito e Falha**
*   **Erro:** Um equívoco humano (interpretação errada ou digitação incorreta).
*   **Defeito (Bug):** A imperfeição física no código ou documento resultante de um erro.
*   **Falha:** O comportamento incorreto visível no software em execução (quando o sistema não faz o que deveria).

### **Níveis e Tipos de Teste**
*   **Teste de Unidade (Componente):** Valida a menor parcela do software (métodos ou classes) isoladamente.
*   **Teste de Integração:** Verifica a comunicação entre diferentes módulos ou sistemas.
*   **Teste de Sistema:** Avalia o sistema completo e integrado (front-end, back-end e banco de dados).
*   **Teste de Aceite:** Validação final realizada para garantir que o sistema atende às necessidades de negócio e dos stakeholders.
*   **Teste de Caixa-Branca:** Teste focado na **estrutura interna** e lógica do código (caminhos, instruções e ramificações).
*   **Teste de Caixa-Preta:** Teste focado nos **requisitos funcionais** (entradas e saídas), sem conhecimento do código interno.
*   **Teste de Confirmação:** Realizado para garantir que um defeito específico foi corrigido com sucesso.
*   **Teste de Regressão:** Realizado para garantir que mudanças recentes não quebraram funcionalidades que já estavam funcionando.
*   **Teste Estático:** Análise de documentos ou código **sem execução** (revisões, inspeções).
*   **Teste Dinâmico:** Teste que exige a **execução do software** para validar seu comportamento.

### **Princípios de Teste**
*   **O teste mostra a presença de defeitos**, não a sua ausência (nunca se pode provar que um software é perfeito).
*   **Testes exaustivos são impossíveis**: não se pode testar todas as combinações de dados e caminhos lógicos.
*   **Defeitos se agrupam**: a maioria dos erros costuma estar concentrada em poucas áreas do código (Princípio de Pareto).
*   **Paradoxo do Pesticida**: se os mesmos testes forem repetidos sempre, eles deixarão de encontrar novos defeitos.

### **Testes de IA Generativa (GenAI)**
*   **Alucinação:** Fenômeno onde o modelo de IA gera informações factualmente incorretas com tom de confiança.
*   **Engenharia de Prompt:** Técnica de projetar comandos para extrair os melhores resultados de uma LLM.
*   **LLM-as-a-Judge:** Uso de uma IA superior para avaliar a qualidade e relevância das respostas de outra IA.
*   **Não-Determinismo:** Característica de sistemas onde a mesma entrada pode gerar saídas diferentes a cada execução.
*   **RAG Triad:** Tríade de métricas para avaliar sistemas de recuperação: Relevância do Contexto, Fundamentação e Relevância da Resposta.
*   **Red Teaming:** Teste adversarial onde o testador tenta "quebrar" ou enganar a IA para expor falhas de segurança e ética.

*   Este glossário apresenta os termos e conceitos fundamentais para a automação de testes, abrangendo desde a programação básica até as novas fronteiras da Inteligência Artificial Generativa, conforme as fontes.

### **Conceitos de Programação para Automação**
*   **Classe:** Funciona como um modelo, molde ou **especificação técnica** que descreve o que um objeto poderá fazer. Em Java, define as propriedades e métodos de um elemento de automação.
*   **Objeto:** É a **materialização de uma classe**; quando a definição técnica ganha vida no código e pode executar ações.
*   **Instanciação:** O ato de criar um objeto a partir de uma classe usando o comando `new`. É "tirar o robô do papel" para usá-lo no script.
*   **Método:** Representa as **ações ou habilidades** que um objeto pode realizar (ex: `fazerLogin()`, `clicarBotao()`).
*   **Atributo (Propriedade):** Variável definida dentro de uma classe que armazena informações compartilhadas entre seus diversos métodos.
*   **Construtor:** Comando especial executado automaticamente no momento em que o objeto é criado, sendo útil para definir **pré-requisitos**, como abrir o navegador antes de iniciar qualquer teste.
*   **Modificadores de Acesso (`Public`/`Private`):** Definem a **visibilidade** de classes e métodos. Tornar uma propriedade privada (`private`) impede que outras partes do código a alterem indevidamente, garantindo que apenas a classe dona do objeto possa manipulá-la.
*   **Package (Pacote):** Forma de organizar e agrupar classes semelhantes em diretórios para facilitar a modularização e manutenção do projeto.

### **Infraestrutura e Ferramentas**
*   **Maven (`pom.xml`):** Ferramenta de gerenciamento que automatiza o download e a atualização de **bibliotecas externas** necessárias para o projeto de automação.
*   **WebDriver:** Biblioteca que fornece comandos para **controlar navegadores** web (Chrome, Firefox, etc.), permitindo que o código interaja com campos e botões.
*   **Asserção (Assertion):** Método de comparação que valida se o resultado real obtido pela automação é igual ao resultado esperado, determinando o sucesso ou falha do caso de teste.
*   **CI/CD (Integração Contínua/Entrega Contínua):** Pipelines que automatizam a integração de código e o lançamento de software. A automação de testes é integrada a esse fluxo para fornecer **feedback rápido** a cada mudança de código.
*   **Framework de Automação:** Estrutura base para a criação de testes. Exemplos incluem o **Selenium** (padrão de mercado para múltiplos browsers), **Playwright** (focado em velocidade e paralelismo nativo) e **Cypress** (focado na experiência do desenvolvedor front-end).

### **Estratégias de Automação**
*   **Pirâmide de Testes:** Modelo que recomenda uma base larga de **testes de unidade** (rápidos e baratos), seguidos por testes de API/integração no meio, e uma quantidade menor de testes de UI (mais lentos e caros) no topo.
*   **Shift-Left:** Prática de iniciar a automação e os testes o mais cedo possível no ciclo de desenvolvimento para detectar falhas de lógica antes do deploy.
*   **Teste de Regressão Automatizado:** Execução repetida de scripts de teste para garantir que mudanças recentes ou correções de bugs não quebraram funcionalidades que já estavam funcionando.
*   **Teste E2E (Ponta a Ponta):** Automação que valida o fluxo completo do usuário no sistema, simulando uma interação real do início ao fim.

### **Automação e IA Generativa (GenAI)**
*   **LLM-as-a-Judge:** Uso de uma IA superior para avaliar semânticamente as respostas de outro modelo, verificando dimensões como **relevância e coerência** em vez de comparações binárias exatas.
*   **RAG Triad:** Tríade de métricas (Relevância do Contexto, Fundamentação e Relevância da Resposta) usada para validar se um sistema que consulta documentos internos não está "alucinando".
*   **QA Agêntica:** Uso de agentes de IA capazes de planejar e executar tarefas de teste de forma autônoma, lidando melhor com mudanças na interface do que os scripts fixos tradicionais.
*   **Engenharia de Prompt para Testes:** Uso de técnicas de prompt (como *few-shot* ou *Chain-of-Thought*) para acelerar a criação de scripts e massa de dados em até **50%**.
*   **Self-Healing (Auto-cura):** Capacidade de algumas ferramentas de automação assistidas por IA de se adaptarem sozinhas a pequenas mudanças na interface (como a mudança de um ID de botão), reduzindo o custo de manutenção de scripts.

  
  
   
   

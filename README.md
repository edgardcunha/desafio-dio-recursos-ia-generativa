# DIO Challenge: Explorando IA Generativa com Copilot e Azure OpenAI

Este repositório documenta a conclusão do desafio de projeto da [Digital Innovation One (DIO)](https://web.dio.me/) sobre os Recursos de IA Generativa com Microsoft Copilot e Azure OpenAI. O objetivo foi aplicar os conceitos aprendidos em um exemplo prático e refletir sobre as capacidades e potenciais dessas tecnologias.

## 🚀 Objetivo do Projeto

O desafio consistia em explorar as ferramentas de IA Generativa apresentadas no curso, como o Microsoft Copilot e os serviços do Azure OpenAI. Para demonstrar o aprendizado, foi proposto criar um projeto prático, documentar o processo e compartilhar os resultados e insights em um repositório GitHub bem estruturado.

Neste projeto, optei por realizar uma tarefa de **Reconhecimento Óptico de Caracteres (OCR)** em imagens como exemplo prático, utilizando ferramentas relacionadas ao ecossistema Azure AI.

## 🛠️ Tecnologias Utilizadas

*   **Git & GitHub:** Para versionamento de código e hospedagem do projeto.
*   **Markdown:** Para a criação deste README.
*   **Azure AI Vision (Serviços Cognitivos do Azure):** Utilizado para a tarefa de OCR, extraindo texto das imagens de entrada. <!-- Ou mencione a ferramenta que você usou: Tesseract, Copilot (se analisou imagem), etc. -->
*   **Microsoft Copilot:** Utilizado como assistente durante o desenvolvimento para:
    *   Gerar/sugerir trechos de código (se aplicável, ex: script Python para usar a API).
    *   Explicar conceitos sobre APIs do Azure e IA Generativa.
    *   Auxiliar na redação e estruturação deste README.
*   **Azure OpenAI:** Explorados os conceitos através do conteúdo do curso e da documentação da Microsoft, compreendendo suas capacidades para geração de texto, análise de linguagem, etc. <!-- Mencione se você usou o Playground do Azure OpenAI ou alguma API específica -->

## 📂 Estrutura do Repositório

O projeto está organizado da seguinte forma:

```
├── inputs/             # Contém as imagens originais utilizadas para OCR
│   ├── imagem_exemplo1.png
│   └── imagem_exemplo2.jpg
│
├── outputs/            # Contém os arquivos de texto com os resultados do OCR
│   ├── resultado_imagem1.txt
│   └── resultado_imagem2.txt
│
├── prints/             # (Opcional) Contém screenshots do processo para o README
│   └── azure_vision_ocr.png
│
└── README.md           # Este arquivo com a documentação do projeto
```

## 📝 O Processo: Realizando o OCR

1.  **Seleção das Imagens (`inputs`):** Escolhi algumas imagens contendo texto variado (screenshots de código, fotos de placas, trechos de documentos) e as salvei na pasta `inputs`.
    <!-- Exemplo: ![Exemplo de Imagem de Entrada](prints/input_example.png) -->

2.  **Extração de Texto com Azure AI Vision:** Utilizei o recurso de OCR do serviço [Azure AI Vision](https://azure.microsoft.com/pt-br/products/ai-services/ai-vision/). Enviei as imagens para a API (<!-- Descreva brevemente como: ex: através do Vision Studio no portal Azure, usando um script Python, etc. -->) e obtive os resultados da extração de texto.
    <!-- Exemplo: ![Interface do Azure Vision Studio processando a imagem](prints/azure_vision_ocr.png) -->
    *   **Nota:** A escolha pelo Azure AI Vision se deu pela sua integração com o ecossistema Azure explorado no curso e sua alta precisão em diversas condições de imagem.

3.  **Armazenamento dos Resultados (`outputs`):** O texto extraído de cada imagem foi salvo em um arquivo `.txt` correspondente dentro da pasta `outputs`.

## ✨ Insights e Aprendizados

Durante este desafio e o estudo do conteúdo da DIO, obtive vários insights sobre IA Generativa, Copilot e Azure OpenAI:

*   **Potencial da IA Generativa:** Compreendi que a IA Generativa vai muito além de chatbots. Ela representa uma nova forma de criar conteúdo (texto, imagem, código), resumir informações e automatizar tarefas complexas de maneiras que antes não eram possíveis. A capacidade de modelos como os da família GPT entenderem contexto e gerarem respostas coerentes é impressionante.
*   **Copilot como Ferramenta de Produtividade:** O Microsoft Copilot (<!-- Especifique qual versão usou: GitHub Copilot, Copilot no Windows/Edge, etc. -->) demonstrou ser um "par programador" extremamente útil. Ele não apenas acelera a escrita de código boilerplate, mas também ajuda a encontrar soluções, explicar blocos de código e até mesmo a depurar. É fundamental, no entanto, revisar e entender as sugestões, pois ele é uma ferramenta de auxílio, não um substituto para o raciocínio do desenvolvedor. Usei-o bastante para refinar este README e para pesquisar sintaxes de APIs.
*   **Azure OpenAI e Ecossistema Azure AI:** Explorar o Azure OpenAI mostrou o poder de ter acesso a modelos de larga escala como um serviço gerenciado. A integração com outros serviços do Azure (como o AI Vision usado aqui) cria um ecossistema robusto para construir soluções de IA completas. Os recursos de IA Responsável (filtros de conteúdo, monitoramento) também são um diferencial importante para aplicações em produção.
*   **Desafios e Limitações:** Percebi que a precisão do OCR, embora alta no Azure AI Vision, ainda pode falhar com textos muito estilizados, manuscritos ou em imagens de baixa qualidade. Além disso, a "arte" de criar bons *prompts* para IAs Generativas (engenharia de prompt) é crucial para obter os resultados desejados, seja no Copilot ou no Azure OpenAI.
*   **Importância da Documentação e Estrutura:** O desafio reforçou a importância de organizar projetos (mesmo os pequenos) de forma clara e documentar o processo e os aprendizados, facilitando a compreensão e a colaboração.

## 🚀 Possibilidades Futuras

As tecnologias exploradas abrem um leque enorme de possibilidades:

*   Automatizar a entrada de dados a partir de documentos digitalizados ou fotos.
*   Criar assistentes virtuais mais inteligentes e contextuais.
*   Gerar relatórios, resumos e traduções automaticamente.
*   Integrar IA em ferramentas de desenvolvimento para aumentar ainda mais a produtividade.
*   Analisar grandes volumes de texto (feedback de clientes, artigos científicos) para extrair insights.

## ✅ Como Verificar

1.  Navegue até a pasta `inputs` para ver as imagens originais.
2.  Navegue até a pasta `outputs` para ver os arquivos `.txt` contendo o texto extraído de cada imagem correspondente.
3.  Explore este `README.md` para entender o processo e os aprendizados.

---

*Este projeto foi desenvolvido como parte do bootcamp da [Digital Innovation One](https://web.dio.me/).*\
*Autor: Edgard da Cunha Pontes* 

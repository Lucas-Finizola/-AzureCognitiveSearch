# Azure Cognitive Search

O **Azure Cognitive Search** é um serviço de busca gerenciado e baseado em nuvem, oferecido pela Microsoft Azure, que permite adicionar funcionalidades de pesquisa avançadas a aplicativos, sites ou outros sistemas. Ele é projetado para facilitar a criação de experiências de busca inteligentes, oferecendo suporte a recursos como pesquisa de texto completo, indexação e enriquecimento de dados, e integração com inteligência artificial.

![Azure Cognitive Search](https://github.com/user-attachments/assets/d8e3527d-a58a-42dd-9c40-472032ada11b)

## Principais Características

### Indexação de Dados
- Suporte à importação de dados de diversas fontes, como bancos de dados, arquivos, blobs do Azure e mais.
- Criação automática ou manual de índices personalizados para atender a diferentes necessidades.

### Busca Avançada
- Pesquisa de texto completo com suporte a filtros e facetas.
- Consultas avançadas utilizando operadores booleanos, proximidade e *wildcards*.

### Enriquecimento de Dados com IA
- Uso de modelos pré-treinados de IA para transformar e enriquecer dados antes de indexá-los.
- Recursos como OCR (reconhecimento ótico de caracteres), extração de entidades e análise de sentimento.

### Experiências de Busca Personalizadas
- Implementação de recursos como sugestões de *autocompletar*, sinônimos, correção ortográfica e realce de resultados.
- Suporte multilíngue para atender a uma audiência global.

### Alta Escalabilidade e Disponibilidade
- Dimensionamento para atender a diferentes volumes de dados e cargas de trabalho.
- Oferece replicação e alta disponibilidade com SLAs robustos.

### Segurança e Controle de Acesso
- Integração com Azure Active Directory (AAD) para autenticação e controle de acesso.
- Criptografia de dados em trânsito e em repouso.

### Análise e Monitoramento
- Fornece métricas detalhadas sobre desempenho de consulta e uso do índice.
- Ferramentas para otimizar a relevância dos resultados de busca.

## Casos de Uso

- **E-commerce**: Busca de produtos com filtros e categorização avançados.
- **Aplicativos corporativos**: Busca de documentos e dados internos.
- **Gestão de conhecimento**: Pesquisa em grandes repositórios de informações e bases de conhecimento.
- **Integração com IA**: Análise de dados não estruturados com recursos de aprendizado de máquina.

O Azure Cognitive Search é especialmente útil para desenvolvedores que desejam implementar rapidamente funcionalidades de busca robustas sem precisar gerenciar a complexidade da infraestrutura subjacente.

### Recursos Adicionais
- Um breve tutorial pode ser encontrado neste [link](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#learn-more).

## Configuração Inicial
Inicialmente, o serviço utiliza três componentes principais:
1. **Azure AI Search**
2. **Armazenamento do Azure**
3. **Azure AI Services**

### Configuração Visual
- Etapa 1:
  ![Etapa 1](https://github.com/user-attachments/assets/fbfbf823-764b-4eaa-88db-fa9e735b7218)
- Etapa 2:
  ![Etapa 2](https://github.com/user-attachments/assets/6637e54a-bde1-42fe-a764-a86ede587991)
- Etapa 3:
  ![Etapa 3](https://github.com/user-attachments/assets/080ec556-9091-41a7-ba52-874105ba57db)

Todos os campos devem ser preenchidos conforme o passo a passo apresentado no tutorial.

![Configuração Completa](https://github.com/user-attachments/assets/39656cf6-2e77-4ba8-be9c-9bfeb587735e)

### Envio de Dados
Durante os testes, foi realizado o *upload* de arquivos no armazenamento (*containers*) para que fosse possível associar o banco de dados ao Search.

![Envio de Dados 1](https://github.com/user-attachments/assets/9780b069-95ca-4fe2-8994-9e4a653b7acb)
![Envio de Dados 2](https://github.com/user-attachments/assets/8555e74f-cc52-47f5-8f0f-8a0177419b49)

## Fazendo a Pesquisa

Durante o processo de pesquisa, foi possível filtrar opiniões de diversas formas, como:
- Apenas negativas
- Apenas positivas
- Por localidade (cidades)

Esses filtros são configuráveis conforme o modelo de banco de dados utilizado.

![Pesquisa 1](https://github.com/user-attachments/assets/00b787a1-5791-48e4-809f-689e0646760a)
![Pesquisa 2](https://github.com/user-attachments/assets/27fd7504-cde7-49d5-86cc-a72223559190)


# Portfólio de Projetos Azure - DIO

Este repositório centraliza uma série de projetos desenvolvidos durante o Bootcamp da DIO, demonstrando a aplicação prática dos serviços do Microsoft Azure para engenharia de dados, automação de processos e versionamento de código. Cada projeto destaca uma faceta diferente do ecossistema Azure, desde a orquestração de dados com o Azure Data Factory até o controle de versão com o Azure DevOps e a ciência de dados colaborativa com o Databricks.

## Projetos

### 1. Azure Data Factory para ETL e Gerenciamento de Custos

[cite_start]Este projeto demonstra a criação e o gerenciamento de uma instância do Azure Data Factory para orquestrar fluxos de trabalho de dados[cite: 550]. [cite_start]O objetivo principal foi estabelecer uma abordagem eficiente para gerenciar os custos, garantindo ao mesmo tempo uma infraestrutura organizada e sustentável[cite: 547].

**Principais Funcionalidades:**
* [cite_start]**Infraestrutura como Código (IaC):** Utilizou Templates ARM para automatizar a implantação dos recursos do Azure, garantindo consistência e agilidade[cite: 551].
* [cite_start]**Gerenciamento de Custos:** Implementou alertas para monitorar o consumo, evitando desperdícios e alinhando a implantação de recursos com as necessidades do projeto[cite: 554].
* [cite_start]**Gerenciamento Organizado de Recursos:** Empregou uma estratégia de nomenclatura padronizada para os grupos de recursos para aumentar a clareza e a organização[cite: 549].
* [cite_start]**Dashboards Personalizados:** Criou dashboards personalizados para o monitoramento de métricas, o que auxilia na tomada de decisões[cite: 557].

### 2. Processo de Redundância de Arquivos com Microsoft Azure

[cite_start]Este projeto detalha a implementação de um robusto processo de redundância de arquivos utilizando um conjunto de serviços do Azure[cite: 217]. [cite_start]O foco foi criar uma infraestrutura segura e escalável para automatizar o fluxo de dados e a integração[cite: 223].

**Principais Componentes:**
* [cite_start]**Azure Data Factory:** Usado para automatizar e gerenciar o fluxo de trabalho de redundância de dados[cite: 219, 225].
* [cite_start]**Linked Services:** Configurado para conectar ambientes on-premises ao Azure para transferência de dados[cite: 220, 227].
* [cite_start]**Azure Blob Storage:** Empregado para armazenar arquivos convertidos em diferentes camadas (Raw/Bronze, Silver e Gold)[cite: 221, 233, 234, 235, 236].
* [cite_start]**Azure SQL Database:** Utilizado para estruturar os dados antes de movê-los para o armazenamento de redundância[cite: 222].

[cite_start]O pipeline desenvolvido extrai dados de um SQL Server local, converte-os em arquivos `.xls` e os move para o Azure Data Lake, garantindo alta disponibilidade[cite: 230, 231, 232].

### 3. Versionamento e Backups com GitHub e Azure DevOps

[cite_start]Este projeto demonstra a integração do GitHub e do Azure DevOps para o versionamento e backup eficazes de artefatos de desenvolvimento[cite: 339]. [cite_start]Essa abordagem garante um fluxo de trabalho estruturado, seguro e escalável[cite: 340].

**Práticas Essenciais:**
* [cite_start]**Configuração do Repositório Git:** Estabeleceu um ambiente controlado para documentar todas as versões de código e artefatos[cite: 342, 343].
* [cite_start]**Backups Automatizados:** Criou pipelines de backup automatizados no Azure DevOps para eliminar processos manuais e garantir a recuperabilidade[cite: 345, 347].
* [cite_start]**Melhores Práticas de Versionamento:** Adotou commits frequentes e detalhados, juntamente com tags e releases para marcar versões estáveis[cite: 349, 350].
* [cite_start]**Integração CI/CD:** Implementou pipelines de CI/CD para automatizar testes, validação e implantação, tornando o fluxo de desenvolvimento mais ágil[cite: 352, 353].

### 4. Controle e Versionamento de Código em Notebooks do Azure Databricks

[cite_start]Este projeto explora o uso do Azure Databricks para o versionamento e organização de notebooks em ambientes com uso intensivo de dados[cite: 425]. [cite_start]A integração com o Azure DevOps foi um aprendizado fundamental, destacando a importância de um histórico de versões para evitar a perda de dados e facilitar a colaboração em equipe[cite: 433, 434].

**Destaques:**
* [cite_start]**Processamento Distribuído:** Configurou um cluster Databricks para execução de tarefas em paralelo, melhorando a velocidade da análise[cite: 427, 428].
* [cite_start]**Desenvolvimento Assistido por IA:** Aproveitou a IA integrada ao Databricks para gerar automaticamente código Python e Spark, acelerando o fluxo de trabalho[cite: 430, 431, 436].
* [cite_start]**Notebooks Organizados:** Estruturou notebooks com filtros, sumarizações e visualizações interativas para melhorar a interpretação dos dados[cite: 432].
* [cite_start]**Integração com Azure DevOps:** Utilizou o Azure DevOps para o controle de versão dos notebooks, garantindo um processo de desenvolvimento seguro e gerenciável[cite: 433, 440].

## Conclusão

Coletivamente, esses projetos ressaltam a importância do planejamento estratégico na infraestrutura em nuvem, desde a configuração inicial de recursos e gerenciamento de custos até a implementação de uma redundância de dados robusta e a adoção das melhores práticas para o controle de versão. A experiência prática com o Azure Data Factory, Azure DevOps e Azure Databricks forneceu insights valiosos sobre a construção de soluções de dados escaláveis, eficientes e seguras.

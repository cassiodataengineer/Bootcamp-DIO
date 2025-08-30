# Portfólio de Projetos Azure - DIO 🚀  

Este repositório consolida **projetos práticos desenvolvidos durante o Bootcamp da DIO**, com foco em **engenharia de dados, automação de processos, versionamento de código e boas práticas de governança em nuvem**.  

Através do uso do **Microsoft Azure**, os projetos abordam desde a **orquestração e integração de dados (Azure Data Factory)** até o **versionamento seguro em pipelines CI/CD (Azure DevOps)** e o **processamento distribuído para ciência de dados (Databricks)**.  

O objetivo é **demonstrar na prática** como aplicar serviços de nuvem de forma **eficiente, escalável e sustentável**, respeitando aspectos de **custos, segurança, governança e boas práticas de engenharia de dados**.  

---

## 📂 Projetos

### 1. Azure Data Factory para ETL e Gerenciamento de Custos  
Este projeto demonstra a criação e gerenciamento de uma instância do **Azure Data Factory** para **orquestrar fluxos de trabalho de dados** e **controlar custos** de forma estratégica.  

**Principais Funcionalidades:**  
- **Infraestrutura como Código (IaC):** Automação da implantação via Templates ARM, garantindo padronização e consistência.  
- **Gerenciamento de Custos:** Configuração de alertas de consumo para evitar desperdícios.  
- **Organização de Recursos:** Estratégia de nomenclatura padronizada para aumentar clareza e rastreabilidade.  
- **Dashboards Personalizados:** Monitoramento em tempo real para apoiar a tomada de decisão.  

---

### 2. Processo de Redundância de Arquivos com Microsoft Azure  
Implementação de um processo de **redundância de dados seguro, escalável e automatizado**, utilizando serviços integrados do Azure.  

**Principais Componentes:**  
- **Azure Data Factory:** Automação do fluxo de redundância.  
- **Linked Services:** Conexão de ambientes on-premises ao Azure.  
- **Azure Blob Storage:** Estrutura em camadas (Raw/Bronze, Silver, Gold) para governança dos dados.  
- **Azure SQL Database:** Organização e estruturação dos dados antes da redundância.  

🔄 O pipeline desenvolvido extrai dados de um **SQL Server local**, converte-os em `.xls` e os move para o **Azure Data Lake**, garantindo **alta disponibilidade e resiliência**.  

---

### 3. Versionamento e Backups com GitHub e Azure DevOps  
Projeto focado em **versionamento de código, automação de backups e práticas de CI/CD**.  

**Práticas Essenciais:**  
- **Configuração de Repositórios Git:** Controle centralizado e organizado de versões de código.  
- **Backups Automatizados:** Pipelines no Azure DevOps eliminando processos manuais.  
- **Versionamento Profissional:** Uso de commits frequentes, tags e releases para rastreabilidade.  
- **Integração CI/CD:** Automação de testes, validação e implantação contínua.  

---

### 4. Controle e Versionamento de Código em Notebooks do Azure Databricks  
Uso do **Azure Databricks** para **processamento distribuído de dados** e **versionamento de notebooks** em ambiente colaborativo.  

**Destaques:**  
- **Processamento Distribuído:** Clusters configurados para execução paralela.  
- **Desenvolvimento Assistido por IA:** Geração de código automatizado em Python e Spark.  
- **Organização de Notebooks:** Filtros, sumarizações e visualizações para análise eficiente.  
- **Integração com Azure DevOps:** Controle de versão e colaboração em equipe.  

---

## 📊 Conclusão  

Esses projetos demonstram a **integração estratégica entre engenharia de dados, governança e automação em nuvem**, trazendo benefícios como:  

✔ **Eficiência Operacional:** pipelines automatizados e versionados.  
✔ **Escalabilidade:** soluções que suportam grandes volumes de dados.  
✔ **Segurança & Governança:** gestão de custos e rastreabilidade de recursos.  
✔ **Colaboração:** ambientes integrados e controlados para times de dados.  

Com experiência prática em **Azure Data Factory, Azure Blob Storage, Azure SQL Database, Azure DevOps e Databricks**, este portfólio evidencia como aplicar **boas práticas de engenharia de dados em ambientes corporativos**.  

---

## 🛠️ Tecnologias e Serviços Utilizados  

- **Azure Data Factory**  
- **Azure Blob Storage / Data Lake**  
- **Azure SQL Database**  
- **Azure DevOps (Repos, Pipelines, Backups, CI/CD)**  
- **Azure Databricks**  
- **GitHub (versionamento e integração)**  
- **ARM Templates (Infraestrutura como Código)**  

---

## 📌 Próximos Passos  

📍 Expandir os pipelines para integrações com **Power BI**.  
📍 Implementar **monitoramento com Azure Monitor e Log Analytics**.  
📍 Adicionar **Docker e Kubernetes** para orquestração de workloads de dados.  

---

👨‍💻 **Autor:** Cássio Campos  
🔗 GitHub: [cassiodataengineer](https://github.com/cassiodataengineer)  

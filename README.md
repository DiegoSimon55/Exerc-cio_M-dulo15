### **Descrição do Projeto**

O projeto consiste em uma análise exploratória dos dados com foco na **variável Churn**, utilizando as bibliotecas Python **Pandas** e **Plotly**. A análise busca identificar padrões e variáveis que influenciam na taxa de churn de clientes de um serviço, com o objetivo de gerar insights acionáveis para reduzir essa taxa.

#### **Bibliotecas Utilizadas**
- **Pandas**: Para manipulação e agrupamento de dados.
- **Plotly**: Para visualização de dados, especialmente gráficos interativos.

#### **Principais Análises**
1. **Análise Bivariada entre `Tipo_Contrato` e `Churn`**:
   - Descobriu-se que o tipo de contrato **"Month-to-Month"** apresenta a maior taxa de churn (42%), enquanto contratos anuais ou bienais apresentam taxas significativamente menores.
   - Sugestões estratégicas foram apresentadas, como incentivar clientes com contratos mensais a migrarem para contratos anuais com descontos ou benefícios adicionais.

2. **Identificação de Variáveis Relevantes para o Churn**:
   - As variáveis `Tipo_Contrato` e `Tempo_como_Cliente` foram identificadas como as mais impactantes na taxa de churn.
   - Combinando essas variáveis, é possível traçar estratégias mais assertivas para retenção de clientes.

---

### **README para o Projeto**

#### **Título do Projeto**
Análise de Churn: Explorando Padrões em Tipos de Contrato e Retenção de Clientes

#### **Descrição**
Este projeto utiliza dados de clientes para realizar uma análise detalhada da variável **Churn** e identificar padrões que podem levar ao cancelamento de serviços. O objetivo é gerar insights acionáveis para melhorar a retenção de clientes e reduzir a taxa de churn.

#### **Funcionalidades**
- Análise exploratória de dados.
- Visualização de padrões em churn utilizando gráficos interativos (Plotly).
- Geração de insights para estratégias de retenção de clientes.

#### **Pré-Requisitos**
Antes de executar o projeto, instale as bibliotecas necessárias:
```bash
pip install pandas plotly
```

#### **Como Executar**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Abra o arquivo no Jupyter Notebook:
   ```bash
   jupyter notebook Profissao_Cientista_de_Dados_M15_Pratique.ipynb
   ```

#### **Insights Principais**
1. **Churn por Tipo de Contrato**:
   - Contratos mensais ("Month-to-Month") apresentam **42% de churn**.
   - Contratos anuais ("One year") têm **11% de churn**.
   - Contratos bienais ("Two year") têm menos de **2% de churn**.

2. **Recomendações**:
   - Incentivar a migração de clientes mensais para contratos anuais por meio de **descontos ou benefícios adicionais**.
   - Demonstrar os benefícios de contratos mais longos na comunicação com os clientes.

#### **Estrutura do Projeto**
- **`Profissao_Cientista_de_Dados_M15_Pratique.ipynb`**: Notebook com todo o código, análises e visualizações.
- **`README.md`**: Documento explicativo sobre o projeto.

#### **Tecnologias Utilizadas**
- **Linguagem**: Python
- **Bibliotecas**:
  - **Pandas**: Manipulação e análise de dados.
  - **Plotly**: Criação de gráficos interativos.

#### **Autor**
Diego
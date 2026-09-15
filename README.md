# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Ferramenta prática desenvolvida em Microsoft Excel para simulação de acúmulo de patrimônio, projeção de renda passiva e análise do efeito dos juros compostos (*Efeito Bola de Neve*) em investimentos imobiliários.

---

## 🎯 Objetivo do Projeto
Auxiliar investidores a tomarem decisões informadas sobre aportes em FIIs, automatizando cálculos de projeção patrimonial, reinvestimento de dividendos e acompanhamento de métricas financeiras ao longo dos anos.

---

## 🛠️ Funcionalidades e Estrutura da Planilha

### 1. Painel de Premissas (Entradas do Usuário)
* **Aporte Inicial e Mensal:** Definição do capital investido.
* **Preço Médio e Dividend Yield:** Parâmetros operacionais do fundo.
* **Taxa de Valorização da Cota:** Estimativa de valorização dos ativos.
* **Reinvestimento Automático:** Alternador dinâmico (*SIM/NÃO*) via Validação de Dados.

### 2. Dashboard de Resultados e KPIs
* **Total Aportado:** Capital diretamente investido.
* **Patrimônio Total Final:** Valor final considerando cotas acumuladas e valorização.
* **Total em Dividendos Recebidos:** Soma de todo o provento gerado no período.
* **Status Magic Number:** Indicador inteligente que alerta quando os dividendos mensais já compram +1 cota sem novos aportes.

### 3. Tabela de Projeção Mês a Mês
* Modelagem detalhada cobrindo até **120 meses (10 anos)**.
* Cálculo automático de arredondamento de cotas (`INT`).
* Atualização de preço por valorização anual proporcional.

---

## 📈 Recursos Visuais
* **Gráfico de Linha Integrado:** Acompanhamento visual da evolução patrimonial versus total investido.
* **Design Profissional:** Layout com paleta *Dark Navy & Teal*, dados formatados e congelamento de painéis para facilitar a navegação.

---

## 📁 Arquivos no Repositório
* `Simulador_Investimento_FII.xlsx`: Planilha automatizada do Excel pronta para uso.
* `README.md`: Documentação técnica do projeto.

---

## 💻 Tecnologias Utilizadas
* **Microsoft Excel** (Fórmulas financeiras, validação de dados e gráficos)
* **Markdown** (Documentação no GitHub)

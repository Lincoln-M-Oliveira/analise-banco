# Análise de Campanha de Marketing Bancário

Este projeto analisa dados de uma campanha de marketing de um banco, com o objetivo de identificar padrões e insights que ajudem a aumentar a taxa de conversão de clientes.

O trabalho foi feito utilizando **Python** e **SQL** integrados, com visualização de dados para facilitar a interpretação dos resultados.

---

## Objetivos

- Explorar os dados da campanha e entender o perfil dos clientes.
- Analisar fatores que influenciam a aceitação da oferta do produto.
- Demonstrar habilidades práticas em Python, SQL e análise de dados.

---

## Ferramentas utilizadas

- **Python**: Pandas, Matplotlib, Seaborn
- **SQL**: Consultas diretas em banco SQLite
- **Jupyter Notebook** para organização e execução do projeto

---

## Estrutura do Projeto

- `analise_campanha.ipynb` → Notebook com todo o código, consultas SQL e gráficos.
- `bank_marketing.db` → Banco de dados gerado a partir do dataset original.
- `README.md` → Documentação do projeto.

---

## Principais Análises

1. **Distribuição por profissão**  
   Identificação de quais profissões têm mais clientes no banco.

2. **Saldo médio por estado civil**  
   Comparação do saldo médio entre solteiros, casados e divorciados.

3. **Taxa de sucesso por profissão**  
   Profissões com maior percentual de conversão na campanha.

4. **Taxa de sucesso por faixa etária**  
   Idades mais propensas a aceitar o produto.

---

## Principais Insights

- Profissões como **aposentados** e **estudantes** apresentaram taxas de conversão acima da média.
- Clientes entre **26 e 35 anos** tiveram desempenho melhor que outras faixas etárias.
- Estado civil "solteiro" tende a ter maior saldo médio no banco.

Essas descobertas podem ser usadas para otimizar campanhas futuras, reduzindo custos e aumentando conversões.

---

## Exemplos de Gráficos

![Distribuição por Profissão](imagens/distribuicao_profissao.png)
![Taxa de Sucesso por Faixa Etária](imagens/sucesso_idade.png)

---

## Como Executar

1. **Clonar o repositório**
   ```bash
   git clone git clone https://github.com/Lincoln-M-Oliveira/analise-banco.git
   cd analise-banco
2. **Instalar dependências**
   ```bash
   pip install pandas matplotlib seaborn
3. **Abrir o notebook**

### Dataset original disponível em:
   https://archive.ics.uci.edu/ml/datasets/bank+marketing

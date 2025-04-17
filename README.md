# README - Praticando Spark

## 📌 Visão Geral
Repositório dedicado ao aprendizado e prática de Apache Spark, contendo scripts e análises de dados utilizando PySpark. O foco principal é explorar as capacidades do Spark para processamento distribuído de grandes volumes de dados.

## 🚀 Principais Recursos
- Scripts de análise de dados com PySpark
- Exemplos práticos de transformações e ações no Spark
- Análise do dataset Titanic como estudo de caso
- Códigos para cálculo de métricas estatísticas

## 🔍 Conteúdo Destacado
- [`titanic_analysis.py`](titanic_analysis.py): Script que calcula a média de idade dos passageiros que não sobreviveram no naufrágio do Titanic
- Exemplos de operações básicas com DataFrames
- Demonstrações de funções de agregação

## ⚙️ Pré-requisitos
- Python 3.8+
- Apache Spark 3.3.2
- Java 8 ou 11 instalado
- Bibliotecas Python: pyspark, pandas (para alguns exemplos)

## 🛠️ Configuração
1. Clone o repositório:
   ```bash
   git clone https://github.com/josimarfilho/Praticando_Spark.git
   cd Praticando_Spark
   ```

2. Crie um ambiente virtual (recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install pyspark pandas
   ```

## 🏃 Como Executar
Para rodar o script de análise do Titanic:
```bash
spark-submit titanic_analysis.py
```

## 📊 Dataset Titanic
O dataset utilizado contém informações sobre os passageiros do Titanic, incluindo:
- Sobrevivência (Survived)
- Classe (Pclass)
- Nome, Sexo, Idade
- Número de parentes a bordo
- Tarifa paga
- Local de embarque

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para:
- Abrir issues para reportar bugs ou sugerir melhorias
- Enviar pull requests com novas funcionalidades
- Adicionar mais exemplos e estudos de caso

## 📜 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

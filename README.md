📊 Análise Criminal de Chicago (2001-2025 + Projeção até 2030)

Projeto Final do curso de Análise de Dados da EBAC — Desenvolvido por Diogo Centeno.

Este projeto realiza uma análise estatística e visual de dados criminais da cidade de Chicago, abrangendo o período de 2001 a 2025, com projeções até 2030.

📁 Estrutura do Projeto

📂 Analise_Criminal_Chicago/
├── 📊 Gráficos (.png)
├── 📈 Projeções (.xlsx)
├── 📘 Relatório final (.pdf)
├── 📄 Dados consolidados (.xlsx)
├── 📜 Script principal (.py)
└── 📚 README.md

![distribuicao_ano](https://github.com/user-attachments/assets/ca308d76-cba5-4843-be06-479b93cfb664)

⚙️ Tecnologias Utilizadas
Python 3.x

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn (Linear Regression)

OpenPyXL, FPDF

Tqdm, Logging, Tabulate

📌 Objetivos
Consolidar dados criminais de diferentes fontes.

Realizar análise estatística descritiva.

Produzir visualizações úteis para a tomada de decisão.

Gerar relatórios executivos e arquivos formatados.

Projetar a criminalidade futura até 2030 com base em regressão linear.

📥 Fontes de Dados
Kaggle – Crimes in Chicago

Chicago Data Portal

🔎 Principais Funcionalidades
✅ Carregamento automático e validação de datasets

✅ Cruzamento e enriquecimento de dados

✅ Análises estatísticas (Top crimes, locais, eficiência policial)

✅ Projeção de criminalidade até 2030
![projecao_crimes](https://github.com/user-attachments/assets/d23b9148-de3e-4c80-aabf-b9a5c54ec342)

✅ Geração de gráficos:
![tendencia_top_crimes](https://github.com/user-attachments/assets/d0564cd3-6302-444f-bdea-97538516b11c)

Linha temporal

Distribuição anual

Heatmap por local
![heatmap_distribuicao](https://github.com/user-attachments/assets/1e95902e-f782-4f79-b322-7e734fbba332)

Boxplot
![boxplot](https://github.com/user-attachments/assets/9737ef5e-993f-4eb8-b9ad-42aae32d8f57)

✅ Exportação consolidada em Excel com formatação

✅ Geração de relatório completo em PDF


📊 Exemplos de Visualizações
Tipo de Visualização	Exemplo
Linha temporal dos principais crimes	
Distribuição anual	
Heatmap por local	
Projeção até 2030

🧪 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/analise-criminal-chicago.git
Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Certifique-se de colocar os arquivos de entrada .xlsx no diretório correto (ou ajuste os caminhos no código):

Crimes_po_ano_tipo.xlsx

Crimes_por_bairro.xlsx

Local_dos_crimes.xlsx

Execute o script:

bash
Copiar
Editar
python analise_criminal_chicago.py
![Fluxograma](https://github.com/user-attachments/assets/dc2ab612-b0ce-4215-a4f2-37583cc89146)


📂 Resultados Gerados
Após a execução, os seguintes arquivos serão salvos na pasta ~/Desktop/Analise_Criminal_Resultados/:

Dados_Consolidados.xlsx — planilha com todos os dados integrados e análises.

Relatorio_Completo.pdf — relatório final com gráficos e tabelas.

Imagens dos gráficos gerados.

Crimes_Unificados.xlsx — base integrada com colunas como "CRIME_GRAVE" e "CRIMES_POR_1000_HAB".

✍️ DASH
![Captura de tela 2025-05-26 132848](https://github.com/user-attachments/assets/50fd134f-f85e-46da-9c3a-6f0e72787d71)



✍️ Autor
Diogo Centeno
Projeto desenvolvido como Trabalho Final para o curso de Análise de Dados da EBAC.

📝 Licença
Este projeto está licenciado sob os termos da MIT License.

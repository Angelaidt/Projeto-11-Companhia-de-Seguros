# Sprint 11 - Projeto 11/17 BootCamp TripleTen de Ciências de Dados
<p align="center">
<img src="https://github.com/Angelaidt/Projeto-11-Companhia-de-Seguros/blob/main/imagem%20-%20proteja%20o%20seu%20amanha.png"
</p>

🛡️ Machine Learning para Seguros: Proteja Seu Amanhã

Este projeto desenvolve uma série de soluções baseadas em Aprendizado de Máquina para otimizar os processos da seguradora. O objetivo principal é fornecer ferramentas analíticas para marketing, predição de sinistros e garantir a segurança das informações dos clientes.

🎯 Objetivos do Projeto: 
O projeto foi dividido em quatro frentes de trabalho essenciais:

Segmentação de Clientes: Implementação de algoritmos para encontrar perfis semelhantes, auxiliando a equipe de marketing em campanhas direcionadas.

Predição de Sinistros (Classificação): Desenvolvimento de um modelo para prever se um novo cliente receberá um pagamento de seguro, comparando o desempenho contra um modelo dummy.

Estimativa de Pagamentos (Regressão): Utilização de Regressão Linear para prever a quantidade de pagamentos de seguro que um cliente pode vir a receber.

Privacidade e Proteção de Dados: Implementação de um método de ofuscação de dados (mascaramento) que protege as informações sensíveis dos clientes sem comprometer a acurácia dos modelos de predição.

🔒 Proteção de Dados: Para cumprir as diretrizes de privacidade, foi desenvolvido um algoritmo de transformação de dados baseado em álgebra linear. 
O processo garante que:
                           A x P = B

Onde A são os dados originais, P é uma matriz invertível aleatória (chave) e B são os dados ofuscados. Isso torna os dados ilegíveis para terceiros, mantendo a relação matemática necessária para as predições.


# Estrutura do Repositório
Veja os dados utilizados : 

![Dados Sprint 11 - arquivo  CSV](https://github.com/Angelaidt/Projeto-11-Companhia-de-Seguros/blob/main/insurance_us.csv)


# 🚀 Tecnologias: 

PythonBibliotecas: Pandas, NumPy, Scikit-learn, Matplotlib/SeabornConceitos: Regressão Linear, Classificação, K-Nearest Neighbors (KNN), Métricas de Erro (RMSE, $R^2$), e Ofuscação de Matrizes.



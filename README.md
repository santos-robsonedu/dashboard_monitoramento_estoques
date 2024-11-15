## 📊 Dashboard para Monitoramento de Estoques - E-commerce Varejista

![layout_inicial](https://github.com/user-attachments/assets/0b442d20-d862-45c7-9aa7-0d67e84f772a)


Este dashboard foi criado para simplificar o acompanhamento dos estoques por parte da equipe de compras, auxiliando-os na tomada de decisões semanais sobre ajustes necessários para manter os níveis de estoque saudáveis e alinhados com as metas da empresa.

## 🎯 Objetivo
O dashboard visa fornecer uma visão objetiva da situação do estoque, de forma a:

- Avaliar a situação atual dos níveis de estoque.
- Identificar se os estoques estão em condições ideais para alcançar as metas de vendas.
- Contribuir diretamente com o planejamento e as estratégias da equipe de compras.

Para um e-commerce varejista que opera exclusivamente com vendas a partir do estoque disponível, o controle do estoque é fundamental para uma operação saudável, impactando diretamente as vendas, margens e conversões. Todas as outras métricas são diretamente dependentes dos níveis de estoque.

## 🏷️ Dados Sintéticos
Os dados apresentados neste dashboard foram substituídos por valores sintéticos para proteger a confidencialidade das informações da empresa, sem prejudicar a análise.

## 🛠️ Obtenção e Tratamento dos Dados

- **Fonte dos Dados:** As informações de estoque são obtidas automaticamente toda segunda-feira via API do Bling ERP.
- **Processamento:** Um script em Python trata os dados, gera novas métricas (como o potencial de vendas) e adiciona informações relevantes sobre a capacidade de armazenamento.
- **Base de Dados:** Após o processamento, os dados são utilizados como base para visualização no Power BI.

## 🧩 Estrutura do Dashboard
O dashboard é organizado em três seções principais:

## 1️⃣ Indicadores Atuais
![image](https://github.com/user-attachments/assets/91fc9261-ec6d-4b12-b795-83e85b2deb93)

Esta seção exibe os indicadores mais relevantes, incluindo:

- **Potencial de Vendas:** Um valor essencial que orienta a gestão de estoques. É calculado com base no custo médio do metro cúbico dos produtos em estoque. Esse valor médio é reavaliado constantemente, mas em resumo, cada R$ 1 em estoque tem o potencial de se transformar em média em R$ 1,8 na hora da venda.
- **Valor Total do Estoque (CMV), SKUs em Estoque e SKUs Sem Estoque.**

## 2️⃣ Análise de Capacidade de Vendas
![image](https://github.com/user-attachments/assets/16e1300d-79a0-4244-8203-dec68bcfe563)

Nesta seção, é possível visualizar:

- **Meta de Vendas da Empresa.**
- **Capacidade em Estoque:** O valor potencial de receita dos produtos em estoque. Os valores de venda atuais não são informados aqui para não interferir na análise dos compradores, pois é possível bater metas de venda mesmo com um estoque problemático, o que poderia diminuir a importância dada aos ajustes necessários.
- **Capacidade do Espaço:** O valor potencial de receita de acordo com o espaço total do armazém e se a meta de vendas cabe dentro da capacidade atual de armazenamento.

## 3️⃣ Distribuição dos Estoques
![image](https://github.com/user-attachments/assets/37007716-f355-4efd-b01e-78a3a8f60e11)

Esta seção traz insights sobre:

- **Níveis de Estoque:** Exibe a distribuição percentual entre estoque ideal, acima do ideal, abaixo do ideal e zerado, permitindo uma rápida identificação de pontos críticos, assim como o espaço ocupado no armazém.
- **Top Produtos em Estoque:** Produtos com maior valor total em estoque, ajudando a identificar itens de alto impacto.
- **Top Categorias:** Visualiza as categorias de maior volume em estoque, contribuindo para o equilíbrio do portfólio.

## 🚀 Uso e Análises Relevantes
Para instruções detalhadas de uso e insights, consulte a pasta Instruções de Uso onde estão descritos os procedimentos e as análises sugeridas para cada seção do dashboard. Essas orientações ajudarão a equipe de compras a interpretar os dados e a tomar decisões assertivas.

## 🧩 Estrutura do Dashboard

Este dashboard é atualizado automaticamente toda segunda-feira, oferecendo aos compradores uma visão clara e objetiva da situação dos estoques. Seu principal objetivo é orientar decisões estratégicas para a otimização desse recurso essencial no varejo.

O dashboard é organizado em três seções principais:

## 1️⃣ Indicadores Atuais
![image](https://github.com/user-attachments/assets/91fc9261-ec6d-4b12-b795-83e85b2deb93)

Esta seção exibe os indicadores mais relevantes, incluindo:

- **Potencial de Vendas:** A partir de dados históricos, identificou-se que cada R$ 1 de custo do metro cúbico dos produtos armazenados pode gerar em média R$ 1,80 de receita, representando um potencial de 1,8x na geração de receita.
Esse indicador é fundamental, pois é usado para calcular uma estimativa da receita que pode ser gerada com os estoques atuais e da capacidade máxima de receita com base no espaço disponível no armazém.
- **Valor Total do Estoque:** Custo total dos produtos em estoque (CMV).
- **SKUs em Estoque**: Variedade de produtos disponíveis para venda.
- **SKUs sem Estoque**: Variedade de produtos com ruptura.

## Insights:

De imediato, é possível observar um número significativo de SKUs sem estoque. Esses itens devem ser analisados para determinar se estão zerados devido a uma decisão estratégica (como a escolha de não reposição) ou por rupturas de estoque, onde há perda de vendas devido à falta de produtos disponíveis.
<br><br>

## 2️⃣ Análise de Capacidade de Vendas
![image](https://github.com/user-attachments/assets/16e1300d-79a0-4244-8203-dec68bcfe563)

Nesta seção, é possível visualizar:

- **Meta de Vendas da Empresa.**
- **Capacidade em Estoque:** O valor potencial de receita dos produtos em estoque. Os valores de venda atuais não são informados aqui para não interferir na análise dos compradores, pois é possível bater metas de venda mesmo com um estoque problemático, o que poderia diminuir a importância dada aos ajustes necessários.
- **Capacidade do Espaço:** O valor potencial de receita de acordo com o espaço total do armazém, também é possível avaliar se a meta de vendas cabe dentro da capacidade atual de armazenamento.

O cálculo do custo por metro cúbico envolve calcular o volume de cada produto a partir das suas dimensões e, em seguida, dividir o preço de custo pelo volume em metros cúbicos. Isso permite entender o custo de ocupar um metro cúbico no estoque para cada produto. Foi escolhida a mediana dos custos como valor de referencia para todo o estoque.
O potencial de vendas é apurado multiplicando a mediana do custo por metro cúbico pela área total disponível ou ocupada no estoque, multiplicado pelo indicador de potencial de vendas.

![image](https://github.com/user-attachments/assets/77732def-b972-41dc-82ab-817a0dc90ca5)


## Insights:

Atualmente, podemos observar que o estoque disponível não é suficiente para atingir a meta de vendas estabelecida. No entanto, é evidente que o espaço atual do armazém oferece capacidade para aumentar os estoques.
<br><br>

## 3️⃣ Distribuição dos Estoques
![image](https://github.com/user-attachments/assets/37007716-f355-4efd-b01e-78a3a8f60e11)

Esta seção traz insights sobre:

- **Espaço Ocupado:** Quanto da área útil do armazém está sendo ocupada pelos produtos em estoque.
- **Níveis de Estoque:** Exibe a distribuição percentual entre estoque ideal, acima do ideal, abaixo do ideal e zerado, permitindo uma rápida identificação de pontos críticos.
- **Top Produtos em Estoque:** Produtos com maior valor total em estoque, ajudando a identificar itens de alto impacto.
- **Top Categorias:** Visualiza as categorias de maior volume em estoque, contribuindo para o equilíbrio do portfólio.

Cada produto em estoque tem seus níveis de estoque calculados de acordo com o histórico de vendas dos últimos 30 dias, atualizados semanalmente. O 'Limite mínimo' deve atender pelo menos 20 dias de venda e o 'Limite máximo' deve atender até 45 dias de vendas. O ideal é que a quantidade em estoque fique entre os limites mínimos e máximos.

## Insights:

Embora haja espaço disponível no armazém para aumentar os estoques, a distribuição atual não está otimizada. Apenas 16% dos SKUs estão dentro dos limites ideais. Além disso, 54% dos SKUs ultrapassam o limite máximo, o que indica que esses recursos podem ser realocados para outros SKUs à medida que as unidades forem vendidas, visando uma alocação mais eficiente dos recursos.
<br><br>

## 🚀 Outras Análises Relevantes:



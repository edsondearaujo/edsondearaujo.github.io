## Como testar a aplicação no Google Colab

Este notebook foi dividido em várias células para facilitar a execução e compreensão das etapas do código. Aqui está um passo a passo para testar o projeto no Google Colab:

### Passo 1: Executando as células
Depois de abrir o notebook no Colab, siga os seguintes passos para rodar o código:

1. **Selecione a célula** com o código que deseja executar clicando nela.
2. **Pressione `Shift + Enter`** ou clique no botão de "Play" no topo da interface do Colab.
   - Isso executará o código da célula e avançará automaticamente para a próxima célula.
3. Para executar todas as células de uma vez, vá ao menu **"Runtime"** e clique em **"Run all"**.

### Passo 2: Estrutura do notebook
Este notebook está organizado em várias etapas. Aqui está uma visão geral de cada uma:

1. **Instalação das dependências**:
   - A primeira célula instala todas as bibliotecas necessárias para rodar o notebook, como `pandas`, `matplotlib` `seaborn`, e `google.colab`.
   - Execute esta célula primeiro para garantir que todas as dependências estejam instaladas corretamente.

2. **Imports**:
   - A segunda célula contém os imports de todas as bibliotecas que serão utilizadas no código.
   - Execute esta célula após a instalação das dependências.

3. **Módulos de processamento**:
   - As próximas células contêm as funções responsáveis por carregar, processar, e visualizar os dados em gráficos.
   - Cada célula tem uma função específica e pode ser executada individualmente ou como parte do fluxo completo do código.

4. **Main**:
   - A célula final contém a função `main()`, que orquestra a execução de todo o fluxo de trabalho, desde o carregamento dos dados até a visualização dos gráficos.
   - Execute esta célula por último para ver os resultados completos.

### Passo 4: Visualizando os gráficos
Após rodar a função `main()` e processar os dados, o notebook irá gerar gráficos que ajudam a visualizar a correlação entre diferentes métricas da sua planilha.

Você pode visualizar esses gráficos diretamente no Google Colab.

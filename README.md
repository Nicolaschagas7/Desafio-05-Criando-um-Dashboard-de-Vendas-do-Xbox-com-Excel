# Desafio 05 - Criando um Dashboard de Vendas do Xbox com Excel

## Sobre o Desafio

Este projeto faz parte de um **Desafio de Projeto** do **Bootcamp Heineken - Inteligencia artificial aplicada a dados**, promovido pela **DIO (Digital Innovation One)**. 

O desafio foi proposto pelo instrutor **Felipe** e tem como objetivo transformar dados brutos em **informações visuais** por meio da construção de um **dashboard interativo no Excel**, com foco em vendas e comportamento dos usuários.

## Arquivos Fornecidos

A pasta de trabalho entregue pelo instrutor continha as seguintes planilhas:

- **assets**: com imagens, símbolos e códigos de cores que auxiliam na construção visual do dashboard.
- **base**: com os dados brutos de vendas, clientes, planos adicionais e uso de cupons.
- **cálculos**: inicialmente vazia, usada para centralizar as fórmulas e tabelas dinâmicas.
- **dashboard**: inicialmente vazia, usada para armazenar a dashboard.

## O que foi feito

### Planilha **base**

- Adicionada uma nova coluna: `Total Planos Adicionais`.
  - Soma os valores das colunas de planos **EA Sports** e **Minecraft** para facilitar a visualização no dashboard.

### Planilha **cálculos**

- Foram criadas **tabelas dinâmicas** e **fórmulas** essenciais para alimentar o dashboard.
- Cada elemento contém um **título explicativo** acima, detalhando sua função.
- Todos os cálculos e estruturas estão bem organizados e separados por categorias, garantindo fácil manutenção e compreensão.

### Planilha **dashboard**

Um dashboard completo e funcional foi criado, com elementos interativos e que permitem várias análises. Ele contém:

- **6 botões de segmentação** que filtram os dados e atualizam automaticamente todos os gráficos e indicadores.

#### Indicadores na parte superior:

1. **Total de Inscrições**: número total de registros de clientes inscritos.
2. **Valor Total**: soma dos valores pagos nas inscrições.
3. **Total de Cupons Utilizados**: número de vezes em que cupons foram aplicados.
4. **Soma dos Planos Adicionais (EA Sports + Minecraft)**: mostra quantas pessoas adicionaram extras ao plano.

#### Gráficos interativos:

- **Gráfico de barras verticais**: mostra a quantidade de inscrições por mês.
- **Gráfico de pizza (Cupom/Total)**: exibe a proporção de usuários que utilizaram cupom versus os que não usaram.
- **Gráfico de rosquinha (Autorrenovação)**: mostra o percentual de usuários que ativaram ou não a renovação automática.
- **Gráfico de pizza (Planos adicionais)**: compara quem adicionou extras com quem não adicionou.
- **Gráfico de barras horizontais (Tipo de inscrição)**: exibe a distribuição dos tipos de planos contratados.

## Como Usar

1. Abra o arquivo Excel.
2. Acesse a planilha **dashboard**.
3. Use os **segmentadores** para aplicar filtros e explorar os dados.
4. Consulte a aba **cálculos** para entender a lógica aplicada e os dados utilizados para alimentar os gráficos.

## O que contém neste repositório

- Arquivo `Xbox_finalizado.xlsx` com todas as planilhas e o dashboard totalmente funcional.
- Imagem de visualização do dashboard para referência rápida.

## Considerações Finais

Este desafio mostrou como é possível construir um dashboard completo e interativo apenas com os recursos do Excel, reforçando a importância de organização de dados e domínio das ferramentas da própria planilha. A experiência foi útil tanto para revisar fórmulas como para treinar a criação de visualizações de dados com propósito analítico.

## Contribuições

Caso tenha sugestões de melhorias, novos gráficos ou ideias para filtros adicionais, sinta-se à vontade para contribuir com este repositório por meio de **pull requests** ou **issues**. Toda colaboração é bem-vinda!

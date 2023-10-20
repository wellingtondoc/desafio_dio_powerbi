# DIO - Santader BootCamp 2023 Projeto Power BI

Este é um projeto de análise de dados usando o Microsoft Power BI e conexão com banco de dados MySql instalado na azure.

## Descrição

Este projeto foi criado para realizar análises de dados utilizando a ferramenta Power BI e criar uma instância na azure com banco de dados MySql. Ele oferece visualizações interativas e relatórios com base nos dados fornecidos.

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter instalado o Microsoft Power BI Desktop em sua máquina. Você pode baixá-lo gratuitamente no site oficial da Microsoft.

## Como Usar

1. Clone ou faça o download deste repositório em sua máquina local.

2. Abra o arquivo `.pbix` no Microsoft Power BI Desktop.

3. Conecte o arquivo `.pbix` aos seus próprios dados ou fontes de dados.

4. Personalize as visualizações e relatórios de acordo com suas necessidades.

5. Salve o projeto e exporte relatórios, se necessário.

6. Publique seu projeto no Power BI Service, se desejar compartilhar com outros.

## Como foi desenvolvidos

1. Criação de uma instância na Azure para MySQL

2. Criar o Banco de dados com base disponível no github (https://github.com/julianazanelatto/power_bi_analyst)

3. Integração do Power BI com MySQL no Azure

4. Feito a conexão power BI com banco MySql

5. Transformação dos dados conforme foi pedido no desafio

6. Foi necessário Mesclar tabelas, importante ressaltar o uso da mesclagem e não uso da combinação:

Mesclar (Merge):

A mesclagem no Power Query é usada principalmente para combinar duas ou mais tabelas com base em uma ou mais colunas-chave.
Você define as colunas-chave nas tabelas que servirão como critério de união.
A mesclagem é semelhante ao conceito de JOIN em SQL e é útil quando você deseja combinar dados de várias fontes com base em chaves correspondentes.

Combinar (Append):

A combinação no Power Query é usada para adicionar linhas de uma tabela a outra.
Isso é útil quando você tem tabelas com a mesma estrutura de coluna e deseja simplesmente empilhar uma tabela em cima da outra, criando uma única tabela maior.
Diferentemente da mesclagem, que combina colunas de várias tabelas, a combinação só adiciona linhas de uma tabela a outra.

7. Tratamento dos dados nulos

8. Removidos as colunas desnecessárias

9. Criado um relatório para básico para mostrar os dados.

## Contribuindo

Se você quiser contribuir para este projeto, siga estas etapas:

1. Fork este repositório.

2. Crie uma branch para a sua feature (`git checkout -b feature/nova-feature`).

3. Faça commit das mudanças (`git commit -m 'Adicionar nova feature'`).

4. Push para a branch (`git push origin feature/nova-feature`).

5. Crie um novo Pull Request.

## Contato

- Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para [criar uma issue](https://github.com/wellingtondoc/desafio_dio_powerbi/issues) neste repositório.

- Para entrar em contato diretamente, você pode enviar um e-mail para [wellington59122@gmail.com].

---

**Aproveite o seu projeto Power BI!** 📊💡
# Projeto Churrasco

Este projeto é uma aplicação web para gerenciar churrascos. Ele permite criar, editar e excluir eventos de churrasco, além de calcular a quantidade necessária de carne, pão de alho, carvão, refrigerante e cerveja com base no número de homens, mulheres e crianças que participarão do evento.

<img src="/tela.jpg" style="width: 300px;"> <img src="/tela2.jpg" style="width: 300px;">

## Funcionalidades

1. **Página inicial**: Exibe uma tabela com os detalhes dos churrascos (Data, Quantidade de Pessoas, Carne, Pão de alho, Carvão, Refrigerante, Cerveja e Ações). As ações incluem botões para editar e excluir um churrasco.

2. **Página de criação de churrasco**: Contém campos para indicar a quantidade de homens, mulheres e crianças. Ao clicar no botão "Criar", a aplicação calcula a quantidade necessária de itens para o churrasco e salva as informações no servidor.

3. **Página de edição de churrasco**: Similar à página de criação, mas permite editar um churrasco existente. Ao clicar no botão "Salvar", a aplicação recalcula a quantidade de itens e atualiza as informações no servidor.

## Critérios

- A calculadora deve funcionar corretamente e atender aos requisitos especificados.
- O código deve fazer uso de seletores e métodos para manipulação do DOM.
- O código deve fazer uso de adição e remoção de classes e estilização através do Javascript.
- O código deve fazer uso de eventos ligados aos elementos da página.
- O código deve fazer uso da API JSON (json-server).
- O código deve fazer uso de chamadas assíncronas e seus derivados.

## Grupo

<a href="https://github.com/ananeres">Ana Patrícia</a>

<a href="https://github.com/VictorCallegari">Victor Callegari</a>

<a href="https://github.com/HaralanS">Haralan Santana</a>

<a href="https://github.com/AndersonS7">Anderson Queiroz</a>

<a href="https://github.com/elizacso">Eliza</a>

<a href="https://github.com/juninho-Oliveira">Damião Junior</a>


## Dependências

Este projeto faz uso do pacote json-server para simular uma API RESTful. Para iniciar, execute o seguinte comando:

```bash
npx json-server db.json   



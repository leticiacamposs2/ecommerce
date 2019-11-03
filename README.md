# Trabalho Final - Etapa 1
Nesta etapa os alunos devem entregar os seguintes artefatos:

* [Diagrama de use-cases (ao menos 3 atores e 5 casos de uso)](#diagrama-de-use-cases) 
* [Regras de negócios](#regras-de-negocios)
* [Requisitos funcionais](#requisitos-funcionais)
* [Requisitos não funcionais](#requisitos-nao-funcionais)
* Descritivo dos casos de uso
* [Protótipo de tela de baixa fidelidade (ao menos 5 telas)](#prototipo-de-tela-de-baixa-fidelidade)

## <a name=“diagrama-de-use-cases”><a/>
## Diagrama de use cases

![](casodeuso.jpg)

## <a name=“regras-de-negocios”><a/>
## Regras de negocios

##### RN01
Quando o cliente visualizar os produtos (carrinho) o sistema deve permitir alteração de quantidade de itens.

##### RN02
Quando o cliente visualizar os produtos (carrinho) o sistema deve permitir exclusão de itens

##### RN03
Quando o cliente finalizar o pedido o sistema deve identificar o cliente

##### RN04
Quando o cliente finalizar o pedido e o cliente não for cadastrado o sistema deve permitir cadastrar cliente

##### RN05
Quando o cliente finalizar o pedido o sistema deve cadastrar endereço de entrega

##### RN06
Quando o cliente finalizar o pedido deve permitir selecionar tipo de pagamento

## <a name=“requisitos-funcionais”><a/>
## Requisitos funcionais

##### RF1
O sistema deve buscar produto

##### RF2
O sistema deve adicionar produto (itens do carrinho)

##### RF3
O sistema deve visualizar produtos (vitrine e itens do carrinho)

##### RF4
O sistema deve excluir produto (itens do carrinho)

##### RF5
O sistema deve alterar quantidade produto (itens do carrinho)

##### RF6
O sistema deve finalizar pedido (fechar carrinho)

##### RF7
O sistema deve identificar cliente

##### RF8
O sistema deve cadastrar cliente

##### RF9
O sistema deve cadastrar endereco de entrega

##### RF10
O sistema deve permitir ao cliente selecionar opção de pagamento

##### R11
O sistema deve confirmar a compra

## <a name=“requisitos-nao-funcionais”><a/>
## Requisitos nao funcionais

##### 1. Confiabilidade
* O sistema deve garantir que a atualização de dados será feita de forma atômica e imediata.

##### 2. Eficiência
* O sistema deve responder a qualquer pesquisa, inclusão, alteração e exclusão.

##### 3. Portabilidade
* O sistema deve ser executado em microcomputadores com acesso a internet com velocidade mínima de 3 Mbps (megabits por segundo).

##### 4. Usabilidade
* O sistema deve seguir as diretrizes de interface humana do projeto GNOME: http://developer.gnome.org/projects/gup/hig/

## <a name=“prototipo-de-tela-de-baixa-fidelidade”><a/>
## Prototipo de tela de baixa fidelidade

#### Cadastro de cliente
![](cadastrodecliente.png)

#### Cadastro de produto
![](cadastrodeproduto.png)

#### Vitrine da loja
![](vitrinedaloja.png)

#### Pagamento
![](pagamento.png)

#### Relatório
![](relatoriodevenda.png)

##### Link do projeto
https://leticialojavirtual.azurewebsites.net/ecommerce

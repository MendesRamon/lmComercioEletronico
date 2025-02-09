## Projeto - Comércio Eletrônico 

 <img align="center" alt="html5" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

### Objetivo:

Este trabalho tem como objetivo responder a pergunta de negócio usando machine learning e consolidar conceitos aprendidos sobre os **algorítimo de Regressão Linear** no Python e usar a técnica KDD para o desenvolvimento do projeto.

____


### Método KDD

Para a analise, serpa utilizado o método KDD (Knowladge Discovery in Databases), é um processo estruturado para análise e descoberta de dados.


[Fonte: Wikipedia]("https://pt.wikipedia.org/wiki/Extra%C3%A7%C3%A3o_de_conhecimento")
___


### Problema de Negócio:

Parabéns! Você conseguiu um contrato de trabalho com uma empresa de comércio eletrônico com sede na cidade de Nova York que vende roupas online, mas também tem sessões de consultoria em estilo e vestuário na loja. Os clientes entram na loja, têm sessões / reuniões com um estilista pessoal, então podem ir para casa e encomendarem em um aplicativo mobile ou site para a roupa que desejam.

*A empresa está tentando decidir se deve concentrar seus esforços em aplicativos móveis ou em seu site*. Eles contrataram você para ajudá-los a descobrir isso! Vamos começar!

___

### Conclusão
**Interpretando os coeficientes:**

  | Coefficient            | Value      |
|------------------------|-----------|
| Avg. Session Length   | 25.981550  |
| Time on App           | 38.590159  |
| Time on Website       | 0.190405   |
| Length of Membership  | 61.279097  |

__

Para uma boa interpretação, aplicarei o conceito de _Ceteris Paribus_.

**Ceteris Paribus** é uma expressão em Latim, usado na economia, "tudo o mais constante" ou "mantendo-se as demais variáveis inalteradas". Ou seja, quando avaliamos um coeficiente aplicado a resposta do negócio, considera-se as demais variáveis inalteradas.


**Mantendo todos as outras variáveis constantes**, um aumento de 1 unidade na média de tempo de uso está associado a um aumento de 25,98 dólares totais gastos.

**Mantendo todos as outras variáveis constantes**, um aumento de 1 unidade no tempo gasto no App está associado a um aumento de 38,59 dólares totais gastos.

**Mantendo todos as outras variáveis constantes**, um aumento de 1 unidade no tempo no site está associado a um aumento de 0,19 dólares em dólares.

**Mantendo todos as outras variáveis constantes**, um aumento de 1 unidade no tempo de Associação está associado a um aumento de 61,27 dólares em dólares.


A principal questão: **A empresa deve se concentrar mais no aplicativo ou site?**

O **APP** trás um maior retorno em comparação ao **site**. Porém, não podemos descartar que, o **Tempo de Associação** está com maior influência nos gastos dos usuários. Ou seja, indico fidelizar o cliente mantendo o maior tempo com a empresa.

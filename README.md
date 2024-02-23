
Calc no CSS

A função calc() no CSS é uma ferramenta poderosa que permite realizar cálculos matemáticos para determinar valores de propriedades CSS. Isso pode ser útil em várias situações, como definir larguras de elementos responsivos, ajustar margens e preencher espaços de forma dinâmica.



Sintaxe básica

A função calc() segue uma sintaxe simples:.
width: calc(100% - 20px);

width: calc(100% - 20px);


Exemplos de uso

Largura responsiva

.container {
    width: calc(50% - 10px);
}

Neste caso, a largura do elemento será metade da largura do contêiner menos 10 pixels de espaço.


Altura dinâmica

.item {
    height: calc(100vh - 80px);
}

A altura do elemento será igual à altura da janela do navegador menos 80 pixels, criando um espaço vertical dinâmico.


Margens automáticas

.element {
    margin: calc(10px + 5%) auto;
}

A margem superior e inferior do elemento será de 10 pixels mais 5% da largura do contêiner, e as margens laterais serão automáticas.


Considerações finais

A função calc() é uma ferramenta poderosa para criar layouts flexíveis e responsivos no CSS. No entanto, é importante usá-la com cuidado e garantir a compatibilidade com navegadores mais antigos, se necessário, fornecendo um valor de fallback adequado.
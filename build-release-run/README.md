# Build, Release, Run

Separe estritamente os estágios de construção e execução

```
- O estágio de construção é uma transformação que converte um repositório de código em um pacote executável conhecido como construção. Usando uma versão do código de um commit especificado pelo processo de desenvolvimento, o estágio de construção obtém e fornece dependências e compila binários e ativos.

- O estágio de lançamento pega a construção produzida pelo estágio de construção e a combina com a atual configuração do deploy. O lançamento resultante contém tanto a construção quanto a configuração e está pronta para execução imediata no ambiente de execução.

- O estágio de execução roda o app no ambiente de execução, através do início de alguns dos processos do app com um determinado lançamento
```

É extremamente recomendável separar todo o processo de deploy em três etapas, facilitando assim o rollback de uma release que esteja apresentando bug.

# Sistema de Estoque — Tarefa 4

Projeto em linguagem C organizado em `main.c`, `produto.c/.h`, `categoria.c/.h`, `util.c/.h` e `arquivo.c/.h`.

## Compilar e executar

No Dev-C++, crie um projeto **Console Application / C**, adicione todos os arquivos `.c` e `.h` desta pasta e use **Execute → Compile & Run**.

Com GCC no terminal:

```sh
gcc -std=c11 -Wall -Wextra -pedantic main.c produto.c categoria.c util.c arquivo.c -o estoque
./estoque
```

No Windows, execute `estoque.exe` após compilar. Os arquivos `categorias.txt` e `produtos.txt` são criados na pasta de execução ao escolher **5 - Sair**. Na primeira execução, listas vazias são carregadas normalmente. O separador `|` é reservado para o formato dos arquivos e não é aceito em nomes.

## Operações

1. Em **Categorias**, cadastre ao menos uma categoria e liste as categorias.
2. Cadastre produtos usando o código de uma categoria existente.
3. Liste os produtos e pesquise por código ou pelo nome exato.
4. Saia para salvar os dois arquivos. Execute novamente para confirmar a persistência.

Capacidades: 20 categorias e 50 produtos. Códigos repetidos são rejeitados, e cada produto exibe o nome da categoria relacionada.

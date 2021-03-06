### Simulador de Cache
Projeto da disciplina de Introdução a Organização e Arquitetura de Computadores do Instituto Metrópole Digital (IMD).
## Documentação
A documentação está dentro da pasta `docs` e pode ser visualizada clicando [Aqui](https://pabloufrn.github.io/simulador_de_cache).
### Compilando o projeto
- Usando CMake:  
  Use o comando `cmake CMakeLists` para gerar o arquivo MakeFile, depois use `make` para compilar.
- Usando g++: 
  Use o comando `g++ -Wall -std=c++11 -Iinclude src/* -o sim_cache` para copilar.
### Executando o projeto
Use o comando `./sim_cache` para executar, o programa não requer argumentos.  
Obs.: Tem que existir um arquivo chamado `config.txt` na pasta `data` com as 7 configurações.

### Arquivo de Configuração
O arquivo de configuração `config.txt` dever estar dentro da pasta `data` e as linhas obedecem a seguinte ordem:

| Configuração            |||                                                                 |
| ----------------------- | ---------------- | --------------- | ---------------------------- |
| Número de palavras      | Exemplo: 4       |
| Número de linhas        | Exemplo: 4       |
| Número de blocos        | Exemplo: 6       |
| Política de Mapeamento  | 1 - Direto       | 2 - Associativo | 3 - Associativo por conjunto |
| Número de Conjuntos     | Exemplo: 2       |
| Política de escrita     | Exemplo: 1       |

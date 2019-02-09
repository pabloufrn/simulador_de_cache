
# Simulador de Cache
Esse projeto tem como objetivo simular o comportamento da memória cache de um processador baseados nas diretivas de 
mapeamento e escrita mais básicas.  
O programa é executado em terminal, onde você pode usar os comandos disponíveis.

# Desafios
No começo eu não sabia como inicia a modulagem e, como o projeto era em dupla, eu tinha que fazer com que ficasse 
o mais claro possível. Sendo assim a abordagem para realizar o projeto foi diferente do tudo que eu já tinha feito, 
o objetivo foi deixa o código com poucos linhas e bem separado. O nome da váriaveis e das funções está extendido - 
sem nome pequenos que não revelam o próposito de seu uso. O visual de saída foi feito com base no que foi dado. Em 
geral, não foi um projeto complexo, mas foi bom de se fazer.

# Documentação
Veja a documentação clicando [Aqui](https://pabloufrn.github.io/simulador_de_cache).

# Como usar
Depois de compilado ou baixado, execute com o comando `./sim_cache`. O programa vai ler o arquivo e configuração e 
você poderá utilizar os seguintes comandos.
- write <endereco> <valor>: para gravar um valor no <endereço> um <valor> inteiro não negativo.
- show: para ver o estado da cache e da mémoria principal.
- read: para ler um bloco da mémoria principal.  
Com isso você poderá como vai ficando a cache quando você carrega (read) valores da mémoria.  
obs.: é importante você rola a página um pouco para cima quando usar o show, para que você veja tudo.

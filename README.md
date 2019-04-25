# comando-do-terminal-linux
Comando do Terminal Linux
Aluna: Maria Eduarda Pereira

1.       Utilize o comando echo para imprimir seu nome no terminal
            	echo Maria Eduarda
 
2.        Utilize o comando echo para salvar seu nome em um arquivo chamado cliente01.txt. Confira o resultado com o comando less.
echo “Maria Eduarda” > cliente01.txt
less cliente01.txt
 
3.        Utilize o comando echo para salvar o nome da cidade em que vocˆe nasceu no final do arquivo cliente01.txt.
echo “Joinville” > cliente01.txt
4.        Crie um novo diret´orio chamado clientes com o comando mkdir. Confira o resultado com o comando ls
mkdir clientes
ls
5.        Mova o arquivo cliente 01.txt para o diret´orio clientes. Confira o resultado com os comandos ls e cd.
mv cliente_01.txt clientes
cd cliente
Ls
 
6.        Crie uma c´opia do arquivo cliente 01.txt com o comando cp chamado cliente01.txt.bkp. Confira o resultado.
cp cliente_01.txt cliente01.txt.bkp
ls
7.       Remova o arquivo cliente 01.txt com o comando rm. Confira o resultado.
rm cliente_01.txt
ls
 
8.        Crie um arquivo chamado de cliente.script com todos os comandos utilizados acima, na mesma ordem de execução.
echo "" > client.script
 
9.        Modifique o arquivo cliente.script com o comando chmod para se tornar um arquivo execut´avel. Execute o arquivo e confira o resultado. Para executar utilize o comando ./cliente.script. Obs: exclua a pasta clientes antes de executar o script para garantir que está funcionando corretamente.
chmod +x client.script
rmdir clientes
./client.script
 
10.    Execute o comando cal. Observe o resultado. Execute o comando echo|cal > hoje.txt. Utilize o comandos ls e less para conferir o resultado. O que ocorreu? Qual a fun¸c˜ao do operador — ?
O que ocorreu é que o echo cal > hoje.txt salvou so o comando cal no arquivo. O operador serve para subtração.
 
11.   roblema Utilize o comando wget para baixar o arquivo cidades sc.txt no endere¸co https: //gist.githubusercontent.com/leandersonandre/c8cba982f42262591be628e5397d1c3f/ raw/bd13a3e13823708e477f99f9285f845b292714c6/cidades_sc.txt.
wget  https:
//gist.githubusercontent.com/leandersonandre/c8cba982f42262591be628e5397d1c3f/
raw/bd13a3e13823708e477f99f9285f845b292714c6/cidades_sc.txt -o cidades_sc.txt
 
12.    Execute o comando grep Balneario cidades sc.txt. Qual ´e o resultado?
Ele procura a string balneario no arquivo encontrando alguns resultados ai
13.    Execute o comando grep balneario cidades sc.txt. Qual ´e o resultado?
Ele procura a string balneario no arquivo noa encontrando arquivos
14.    Execute o comando grep ”do Sul”cidades sc.txt. Qual ´e o resultado?
Ele procura a string do Sul encontrando vários resultados
15.   Utilize os comandos cat e grep para filtrar as cidades que come¸cam com o nome Balneario.
cat cidades_sc.txt | grep "Balneario"
16.   Crie um arquivo chamado balneario.txt com o conte´udo filtrado no problema 15.
cat cidades_sc.txt | grep "Balneario" > test.txt
 
17.   Problema Compacte o arquivo balneario.txt, nomeando de compactado.tar com o comando tar.
tar – zcf compactado.tar balneário.txt
18.   Problema Descompacte o arquivo compactado.tar com o comando tar.
tar – xvf compactado.tar.balneario.txt 

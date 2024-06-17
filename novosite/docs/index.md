# Atividade Avaliativa

Instituto Federal de Ciência e tecnologia do Maranhão (IFMA)<br>
Aluna: Sara Sandres de Souza Ferreira<br>
5° periodo de Ciência da Computação


## Introdução:

A atividade consistiu em 3 partes:
## 
* 1 instalação do GLPI (deu muito trabalho)
* 2 configurar o GLPI
* 3 documentar no sistema MKDOCS
##
para a instalação do GLPI no sistema windows foi recomendado a instalação de uma maquina virtual, a criação direto no sistema ubuntu no proprio windows ou pelo XAMPP. Ao tentar fazer primeiramente pela maquina virtual enfrentei problemas que não consegui resolver e parti para a segunda opção, porem ao final resolvi que melhor seria pelo XAMPP e foi por ele que fiz a atividade proposta.



## Instalação

Para instalar o GLPI com o XAMPP usei o video <a>https://youtu.be/7-CqrK9pxz4?si=S7fro4MetcrCU7At</a> Nele temos o passo a passo para a instalação. primeiro baixei o XAMPP e o GLPI (na versão stable) pelo google, depois extrai o glpi nos arquivos. o proximo passo é instalar o programa XAMPP. agora iremos abrir o arquivo glpi e dentro dele tera outro arquivo que sera movido para a pasta htdocs do XAMPP no disco local.<img src="Captura de tela 2024-06-17 170228.png"> <br> no XAMPP ja aberto sera necessario ativar o apache e o MySQL nesse momento tive um problema com a porta que o MySQL estava usando pois antes em outras tentativas de instalação eu ocupei a mesma, apos resolver esse problema liberando a porta necessaria pude dar continuidade, a partir dai NÃO SE PODE MAIS FECHAR XAMPP durante o seu uso. agora abriremos o navegador e digitaremos localhost/glpi onde abrira a pagina do GLPI e escolheremos o idioma e aceiraremos os termos, e instalaremos o GLPI. Dois erros criticos foram apresentados nesse momento e para resolver entramos novamente o XAMPP e na parte config. do apache abriremos o php.ini <img src="Captura de tela 2024-06-17 174744.png"><br>e no bloco de notas editaremos a parte ";extencion=gd" e ";extencion=intl" tirando o ; das duas e salvaremos o arquivo e reiniciamos o apache e o MySQL isso sera suficiente para o processo continuar. A partir desse momento sera feito conforme o video do professor no classrom. ao final da configaração teremos telas especificas para cada ususario alem das configurações comforme direcionamento do professor, no meu caso foram essas:<img src="Captura de tela 2024-06-17 124244.png"><br><br>
<img src="Captura de tela 2024-06-17 124351.png"><br><br>
<img src="Captura de tela 2024-06-17 124436.png"><br><br>
<img src="Captura de tela 2024-06-17 124705.png"><br><br>
<img src="Captura de tela 2024-06-17 124824.png"><br>
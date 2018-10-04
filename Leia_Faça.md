# Fliper
Fliperama produzido no FabLab do Instituto Mauá de Tecnologia juntamente com os conhecimentos adquiridos na matéria de micro-controladores

   A ideia do projeto foi criar uma bancada que simulase os antigos fliperamas , para isso utilizamos a router presente no FabLab com a finalidade de cortar as peças individuais que unidas formaran a bancada, essas peças podem ser encontradas nos arquivos nas extanções .DXF e .DWG , ápos a finalização do corte realizamos a montagen, você pode ver as imagens da montagem na pasta Imagens presente aqui no repositorio.
   
   Quando finalizada a montagem realizamos a colacação dos botoes e a postorior configuração dos mesmos para tal usamos o guia do GPIO, vale salientar que deve-se utilizar como referancia os números dos pinos do GPIO uma vez que a cor de seus cabos pode diferir da utilizada por nós. Feito esse precedimento iniciamos a preparação de nosso Raspberry Pi 3, primeiramente formatamos o cartão de memoria,recomendamos o formato FAT32, para a instalação do RecalBox uma vez baixado o recalbox , link para download: https://archive.recalbox.com/, utilizamos a ferramenta Etcher, https://etcher.io/, para gravar a iso do sitema no cartão.
   
   Feito isso tivemos que acessar o sistema do recalbox atravez da rede, para isso conectamos ele na mesma rede que nosso computador, no menu de rede do propio recalbox pegamos o ip do mesmo, uma vez com ip acessamos ele atrvez do explorador de arquivos do windows , para isso basta digitar \\IPdoRecalBox, uma vez acessando o recalbox fomos em system nesta pasta acessamos o arquivo recalbox.conf e nele encontramos controller.gpio.enabled = 0, para podermos usar os botoes ligados no GPIO temos que alterar de 0 para 1.
   
   Para finalizar jogamos umas partidas de de Street Fighter. 

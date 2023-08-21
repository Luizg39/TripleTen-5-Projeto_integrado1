# TripleTen-5-Projeto_integrado1


## Projeto Integrado


A atividade consiste em analisar os dados coletados de 2016 de uma loja de online. A loja online Ice, vende videogames no mundo todo, os dados a serem analisados são os dados históricos sobre vendas de jogos. O objetivo é identificar possíveis sucessos para planejar uma campanha publicitária para 2017.


## Conclusão Geral

Em primeiro lugar, foi feita uma observação inicial dos dados do dataframe, para identificar problemas que possam afetar a análise. Os problemas encontrados foram:

    Necessidade de colocar os nomes das colunas em letra minúscula;
    Uma colunas estava com o tipo incorreto;
    Seis colunas possuiam valores ausentes.

Os nomes das colunas e o tipo da coluna foram corrigidos. Os valores ausentes das colunas critic_score, user_score e rating não foram preenchidos por não haver valores na tabela que estajam ligados a eles. Dessa forma, também não foi possível identificar a razão deles estarem ausentes. Não foram deletados pois essas colunas serão necessarios para a análise. As outras colunas com valores ausentes as linhas que possuiam foram deletadas por não representarem mais que 1% do dataframe. Para aprimorar a análise foi criada a coluna total_sales.

Através da análise foi idenficado:

    Houve uma tendência de alta para o lançamento de jogos a cada ano, com o pico sendo 2008, seguido de uma tendência de queda até 2016.

    O tempo de vida de uma plataforma é de aproximadamente 10 anos.

    Os dados utilizados para a análise serão de 2014 a 2016.

    As plataformas que estão liderando as vendas em 2016 são o PS4 com 69 milhões, XOne com 26 milhões e o 3DS com quase 15 milhões de vendas de jogos para a plataforma.Entre 2015 e 2016 todas as plataformas estão em tedência de queda.

    As plataformas possuem determinados jogos de representam a maior parte das vendas dessa plataformas.

    As avaliações de usuários não afetam as vendas totais dos jogos. As avaliações de profissionais possui uma relação positiva com as vendas totais.

    O jogo mais vendido do período de 2014 a 2016 foi o "Call of Duty: Black Ops 3", a maior parte das vendas foram no PS4 e no XOne, a distribuição da venda está relativa a distribuição das vendas totais por plataforma.

    Os gêneros mais lucrativos são "Shooter", "Action" e "Role-Playing". Os principais gêneros também são os que possuem os maiores outliners, sendo que esses outlines os jogos mais vendidos do período.

Foram criados perfis de usuários para cada região, para identificar se existem diferentes tedências, as regiões são América do Norte, Japão e Europa. O perfil de usuário da região da América do Norte e da Europa são bem parecidos, com o console PS4 liderando o mercado, na América do Norte o XOne tem vendas proximas do PS4, isso não é visto na Europa. Os principais gêneros sendo "Shooter" e "Action", a posição está invertida na Europa. O perfil do Japão é diferente, com o principal console sendo o 3DS. Os principais gêneros sendo "Role-Playing" e "Action", e a classificação mais comum sendo "T". O usuário japonês consome jogos de RPG jogando no consele 3DS.

Foram feitos dois testes de hipóteses em relação as classificações médias dos usuários entre plataforma e gênero. Os testes demonstraram que as classificações médias dos usuários das plataformas Xbox One e PC são as mesmas e que as classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes.

Em conclusão, a partir da análise uma boa campanha publicitária deveria focar na plataforma PS4 para jogos do tipo "Shooter" e "Action", com classificação "M", nas regiões da América do Norte e Europa.


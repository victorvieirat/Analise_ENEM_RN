**Esta análise trata-se do projeto realizado durante a semana da Imersão Dados Alura, apenas com finalidade de praticar o que se foi estudado.**

# Análise do Rio Grande do Norte

A partir dos dados do Exame Nacional do Ensino Médio (ENEM) 2019 no estado do Rio Grande do Norte, vamos dimensionar quantos estudantes vão ser afetados e de quais municípios eles são pensando em quais locais o Estado poderia priorizar nos recursos para educação. Para isso vamos considerar que os estudantes do ano passado serão os mesmos desse ano, analisaremos critérios como acesso à internet, quantidade de computadores e celulares na residência.

Por **Victor Vieira**

## Acesso à internet

Visto que a previsão da [volta às aulas da rede pública está prevista para depois do ENEM 2020](https://g1.globo.com/rn/rio-grande-do-norte/noticia/2020/10/22/governo-do-rn-preve-retomada-de-aulas-na-rede-estadual-com-ensino-hibrido-a-partir-de-1o-de-fevereiro-de-2021.ghtml) enquanto a [rede particular retornou apenas esse mês](https://g1.globo.com/rn/rio-grande-do-norte/noticia/2020/09/03/governo-do-rn-anuncia-retorno-das-aulas-presenciais-a-partir-de-5-de-outubro.ghtml) (outubro). É notável que uma conexão à internet em casa é crucial para a preparação da prova, já que os estudantes tiveram que passar a maior tempo do ano em casa sem poder sair para estudar em outros locais. O gráfico abaixo mostra a distribuição de alunos com internet em casa.

{% include acesso_internet.html %}

Percebe-se que uma parcela muito significativa dos inscritos do ENEM não possuem meios de estudar online em casa.

## Equipamento para estudar online
Apesar do grande número de jovens sem acesso à internet em casa que estão sendo diretamente afetados pela medidas sanitárias de distanciamento, mesmo os que tenham meios de estudar online podem sofrer dificuldades nos estudos. Ter um celular ou computador à disposição é de grande importância para o aprendizado nesse momento. O gráfico abaixo mostra quantos a quantidade de computadores na resisdência dos alunos.

### Computador

{% include computador.html %}

### Celular
É possível observar que uma boa parte dos incritos com acesso à internet em casa não possuiu nenhum computador para poder estudar, ou seja, estão totalmente dependentes de um celular para se preparar para a prova. Contudo, o celular é um equipamento de uso pessoal e muito mais constante, então é necessário analisar a quantidade pessoas por celular nas casas de quem possui internet mas não computador. O gráfico abaixo mostra a distribuições dessa relação.

{% include pessoa_celular.html %}

Para melhor visualização recomendo selecionar a área de interesse. Uma relação maior que duas pessoas por celular significa que o estudante tem terá que dividir o uso com celular com no mínimo uma pessoa, o que é muito prejudicial nos momentos de estudos.

## Conclusão
Agora vamos reunir todos os incritos prejudicados a partir dos critérios já discutidos (acesso à internet, não possuiu computador, muitas pessoas por celulare na casa) e descobrir o que eles possuem em comum.

{% include mapa.html %}

A partir do apresentado é possível concluir que os alunos da região intermediária de natal (agreste e parte litoral norte e litoral oriental) são os que estão sendo mais afetados pelas consequências do COVID no seu ano de ENEM. Logo, estas regiões merecem um esforço maior atenção e esforço do Gorveno do Estado do Rio Grande do Norte para garantir uma educação digna à quem mais precisa.

# Referências
A [Imersão dados Alura](https://www.alura.com.br/), onde aprendi e pude me aprofundar um pouco nesse mundo da análise de dados;

O canal [Peixe Babel](https://www.youtube.com/user/CanalPeixeBabel), onde aprendi mais sobre o potencial do Plotly;

O canal [Programação Dinâmica](https://www.youtube.com/channel/UC70mr11REaCqgKke7DPJoLg), onde aprendi a fazer encontrar as cordenadas a partir do código do município;

O repositório de [Kelvin S. do Prado](https://github.com/kelvins/Municipios-Brasileiros), onde tirei os dados das coordenadas.

<b>Documentação</b> <i>Botcamp CSS</i>

Formas de inclusão do css: Inline, Interno e Externo, sendo a forma externa a mais indicada para a inclusão do css.

<b>Seletores CSS</b>

Usamos os seletores # para atribuir elementos em ID

. para atribuir elementos em class

Somente a tag para atribuição de valores simples em tags

(*) Usado para seletores universais, ou seja para pegar todos os elementos do html 

<b>Seletores de Atribuição</b>

Os seletores por atribuição é um pouco mais complexo:

Usamos o comando [] para colocar a propriedade do qual queremos atribuir o estilo e também usamos alguns elementos para determinar alterações específicas:

~ (elemento tio) = Usado quando queremos especificar uma palavra em meio de outros elementos ou uma palavra completa.

^(Sufixo) = Usado quando queremos especificar uma palavra no início do elemento.

$(Sifrão) = Usado quando queremos especificar uma palavra no final da propriedade

(*) = Asterísco dentro do seletor atribuição busca a palavra em qualquer posicionamento que ela possa estar no elemento.



<b> Imagens</b>

Propriedade objetc-fit: É usado para dimensionar a imagem para que possa ser ajustada de forma adequada dentro do elemento que é chamado de container.

fill: dimensiona a imagem para caber em toda a estrutura ao redor do container, isso pode fazer com que a imagem fique distorcida se as medidas definidas no container não seja igual as medidas da imagem escolhida.

Contain: Adequa perfeitamente a imagem para dentro do container, com isso não há distorção da imagem mas pode ter a adequação de tamanho como altura e largura.

 Cover: Adequa a imagem sem distorção em todo o conteúdo dentro do container porém ele corta a imagem.

None: Não respeita os tamanhos do elemento pai e preenche com o seu tamanho original sendo assim o valor acaba ultrapassando ainda mais o seu tamanho dentro da container

scale-down - Adequa a imagem dentro do container escolhendo qual é a configuração menor

<u>*Object-position*</u> - Ela é utilizada juntamente com a propriedade objetc fit, especifica como o elemento deve se posicionar tanto verticalmente quanto horizontalmente, pode ser definido tanto com porcentagem quanto com pixel e texto (left, right) e o primeiro valor sempre é o horizontal e o segundo vertical


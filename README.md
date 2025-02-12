# introducaoHTML

HTML (Hypertext Markup Language ou na tradução para o português Linguagem de Marcação de Hipertexto) é uma linguagem utilizada para construção de páginas de Internet. HTML define um conjunto de regras que permite a formatação de páginas. Um documento HTML consiste em um arquivo de texto que será lido e interpretado como uma página por browsers (navegadores), como por exemplo, Chrome, Firefox, Opera, Edge ou Safari.

Construir páginas em HTML é o principal método para divulgação de conteúdo na Internet. Apesar de haver diversos editores que permitem a construção de páginas sem a necessidade de alterar o código-fonte, compreender a sintaxe dessa linguagem é de grande importância. Dominar a linguagem HTML é essencial para dominar a Web.

# História

HTML surgiu no princípio da década de 1990, após Tim Berners-Lee e colaboradores implementarem a comunicação entre máquinas usando o protocolo HTTP. A linguagem HTML foi inspirada na metalinguagem SGML, criada na década 1960 pela IBM. HTML herdou algumas características do SGML para estruturação de texto, como por exemplo o uso de tags.

Anos mais tarde, um grupo informal de pesquisadores lançou novas versões do HTML. A partir de 1996, a linguagem HTML passou a ser mantida pela W3C (World Wide Web Consortium). A partir da versão 3.5 do HTML, o grupo de pesquisadores passou a trabalhar numa versão do HTML mais simples de ser processada, baseada em XML. Em 1999, surge a versão 4.01, a última especificação lançada pela W3C antes da versão 5.

# HTML5
HTML5 é a mais recente versão da linguagem HTML. Trouxe novas funcionalidades e perspectivas em relação ao papel exercido pelo HTML na Web. HTML traz novas tags, como "<"header">" para cabeçalhos, <nav> para menus, "<"video">" e "<audio>" para respectivos elementos, além de apresentar uma sintaxe mais simples como por exemplo para declaração do DOCTYPE.

# Sintaxe
Antes de se aprender como programar alguma coisa específica, aprender o que faz cada parâmetro no código, ou mesmo o que são estes elementos, é necessário saber como redigí-lo, de forma que o computador entenda o que estamos lhe solicitando através do programa que escrevemos. Ao contrário das linguas e linguagens verbais, onde um erro de concordância, ou uma palavra falada errada, não impede outra pessoa de compreender a mensagem que tentamos transmitir, o código computacional precisa ser absolutamente impecável, sem nenhum erro sequer, pois sua interpretação é literal, e feita por uma máquina incapaz de assumir o que queremos dizer.
A primeira etapa do aprendizado de qualquer linguagem de programação é entender sua sintaxe, isto é, as regras de como o código precisa ser escrito, mesmo quando ainda não sabemos exatamente está escrito por desconhecermos o que fazem as instruções ali presentes.
![image](https://github.com/user-attachments/assets/6ac04dbc-e3dd-43c6-befd-8475d39550c4)

Toda tag é identificada pela presença dos < >. Quase todas as tags são finalizadas por uma marcação </ >, logo, a tag <a> é finalizada pela marcação </a>. Quase todas as tags aceitam atributos, que modificam de alguma forma seu comportamento ou atuação. Nos exemplos acima, os parâmetros href="./arquivo.html", href="doc.html", id="palavra1", id="bloco2", class="forte" e class="link" definem valores para os atributos href, class e id das diversas tags em que são colocados como propriedades. O conteúdo, isto é, aquilo que está entre a declaração da tag, e sua finalização (nos exemplo acima, "texto", "Primeiro parágrafo", "Segundo parágrafo", etc.), é o valor que pertence à tag, isto é, o valor/dado que este nó guarda no ponto final de sua estrutura; Qualquer tipo de conteúdo pode ser colocado "dentro" de uma tag, inclusive outras tags.

As tags HTML possuem propriedades gerais, que modificam suas atribuições de forma igual para toda e qualquer tag, e propriedades/atributos específicos, que precisam ser conhecidos e entendidos caso-a-caso, tag por tag.

Uma característica importante na sintaxe do código HTML é que espaços em branco ou linhas sendo puladas (↵) ao longo dele não interferem em nada sobre sua interpretação. O navegador, ambiente onde o código é interpretado, ignora espaços e linhas puladas, e junta todo seu conteúdo como se ele estivesse escrito linearmente; letras minúsculas ou maiúsculas nas tags e propriedades também não são diferenciadas.

A estrutura do código HTML é entendida pelo navegador como um conjunto de nós; uma árvore formada por diversas ramificações, do tronco à cada pequena folha. Este formato é chamado de Document Object Model (modelo dos elementos que formam o documento), onde cada ramificação possui seus próprios nós filhos, e cada nó filho torna-se pai de outros nós filhos.

O que não pode acontecer neste código em forma de árvore de dados, que quebra toda a lógica de como o HTML se estrutura

Todo nó precisa terminar dentro dos limites de seu nó pai. No exemplo acima, a tag <div> permanece aberta dentro do seu nó pai, a tag <a>, e seu fechamento acontece depois que sua própria tag-pai já esta fechada. Isto configura uma estrutura sintática que o navegador dificilmente conseguirá interpretar e resolver, e consequentemente, não conseguirá apresentar nada corretamente na tela do usuário.
Este mecanismo de como o código HTML é estruturado é um formato bastante simples e, devido a isso e a sua flexibilidade, o código final de um documento tende a ficar bastante complexo, intrincado e possivelmente confuso. É recomendável que se utilize identação (este espaçamento para cada nível hierárquico do código que você vê nos exemplos) para torná-lo um pouco mais fácil de ser lido.
# Comentários
Toda linguagem de programação possui uma forma do programador registrar comentários e anotações ao longo de seu código. No HTML, os comentários são colocados dentro da marcação <!-- e -->. Quaisquer informações colocadas entro destas marcações, código ou texto, serão sumariamente ignoradas pelo navegador.

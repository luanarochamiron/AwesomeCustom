# Awesome Custom Radio Buttons

Um componente de seleção de opções (Radio Buttons Customizados) moderno, limpo e totalmente responsivo desenvolvido exclusivamente com HTML5 e CSS3. O projeto substitui os botões de rádio nativos do navegador por uma interface modular em estilo de lista de cartões (pílulas), oferecendo uma experiência de seleção muito mais fluida, elegante e visualmente intuitiva.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica do formulário, cabeçalho do card e uso de elementos nativos de seleção única (`<input type="radio">`) vinculados a tags `<label>`.
* CSS3: Estilização completa, uso de cantos arredondados estilo pílula, gerenciamento de estados visuais (hover, focus e active) e sombras projetadas.
* Flexbox: Organização vertical dos blocos de opção e centralização absoluta do card principal na tela.

## Funcionalidades e Técnicas Aplicadas

* Customização Completa de Radio Buttons: Ocultação acessível dos inputs circulares padrão do navegador utilizando propriedades CSS, reconstruindo os marcadores visuais do zero para total controle de design.
* Cabeçalho de Bloco Sólido: O topo do contêiner apresenta uma faixa preta sólida contrastante com o título em branco ("Select your option"), criando uma hierarquia visual limpa e bem delimitada.
* Design Estilo Pílula (Pill-shaped Design): Cada opção individual (Gamer, YouTuber, Student, Developer) é encapsulada em um bloco com bordas finas cinzas e cantos perfeitamente arredondados por meio de `border-radius: 50px`.
* Microinterações de Seleção Dinâmica: Uso avançado da pseudo-classe `:checked` combinada com seletores de irmãos para modificar a cor da borda, do plano de fundo e do marcador circular interno de forma responsiva ao clique do utilizador.
* Centralização Absoluta com Flexbox: Alinhamento perfeito do card branco e sua respectiva sombra suave (`box-shadow`) no centro x/y da viewport clara.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 

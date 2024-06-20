# Alura Midi

O Alura Midi é um projeto que apresenta um instrumento musical de interface digital, onde cada botão reproduz o som de um instrumento quando clicado.

# 🔨 Funcionalidade
O MIDI tem um teclado funcional com 9 botões, que ao ser pressionado, reproduzirá um som diferente. O HTML carregará os arquivos de mídia com o som dos instrumentos através do elemento `<audio>`, e com o MIDI vamos controlar a reprodução destes arquivos de mídia através do clique, em seus elementos.

# 📍 Técnicas e tecnologias usadas

- `Html` : O HTML foi utilizado para a inserção dos elementos <audio>, que irão prover para o JavaScript os controles de reprodução da mídia carregada. 
- `CSS` : O CSS foi usado para dar formato e indicar a interação do usuário com a interface gráfica, então além de deixar um visual mais atrativo, ele também indica quando os botões são pressionados pelo mouse ou teclado.
- `JavaScript` : O JavaScript nós proporciona a programação da dinâmica de controle de reprodução de um som, que inicialmente está sendo realizada pelo elemento `<audio>`, e passa este controle para os elementos `<button>`, com todo cuidada para ser um código inteligente, sem repetição, e que cuida dos aspectos visuais.

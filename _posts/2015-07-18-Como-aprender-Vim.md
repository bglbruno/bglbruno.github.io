---
published: true
layout: post
---


Olá pessoal! 

Hoje vou falar sobre o editor de texto [Vim](http://www.vim.org/ "Vim"). Mais especificamente, vou dar orientações sobre como você pode aprender a usá-lo. 

Se você já teve algum contato com Vim, sabe que existe uma infinidade de comandos, e isso inicialmente pode parecer uma confusão enorme, e talvez isso entre outros motivos, te desencoraje a usar o Vim no seu dia a dia. 

Pois bem, vou mostrar alguns caminhos que facilitarão sua jornada no aprendizado. Que inclusive, foram de grande importância quando busquei materiais de apoio para aprender também.

Esses caminhos dos quais falarei aqui, são:
* [Vimtutor](http://linuxcommand.org/man_pages/vimtutor1.html "Vimtutor")
* [vimgolf](http://www.vimgolf.com/ "Vim Golf")
* [OpenVim](http://www.openvim.com/ "OpenVim")

### Vimtutor 

[Vimtutor](http://linuxcommand.org/man_pages/vimtutor1.html "Vimtutor"){:target="_blank"} é um tutorial via terminal, usando de fato o _Vim_. Para instalar o vimtutor, digite no terminal:

```
# apt-get install vimtutor
# vimtutor
```

Uma tela será aberta, com uma tela de boas vindas ao vimtutor, com uma explicação do que é, juntamente com algumas outras informações. Que nada mais é do que o editor _Vim_ com um texto e instruções para seguir, dividido em 7 lições, cada uma com suas seções. 

O tutorial é básico porém, após finalizá-lo, você estará pronto pra usar o _Vim_ com maior facilidade, isso é certeza!

### Open Vim 

[OpenVim](http://www.openvim.com/ "OpenVim") é um tutorial passo a passo também, parecido com o _vimtutor_, porém um pouco mais interativo. O seu uso é bem intuitivo, basta entrar no site e seguir as instruções.

### Vim Golf 

[VimGolf](http://www.vimgolf.com/ "Vim Golf") é um jogo baseado no _Vim_. Nele você faz pontos de acordo o número mínimo de passos que teve de executar para chegar num resultado final, como manda o desafio que você estiver.

Para usá-lo, é necessário ter uma conta no _Twitter_

```
$ gem install vimgolf
```

Depois de instalar a gem, faça login no site com sua conta do _twitter_ e execute o seguinte comando no terminal:

```
$ vimgolf setup
```

Esse comando irá pedir a sua _VimGolf Key_, que é fornecida a você após fazer o login.

Feito isso, irá aparecer a mensagem > Saved. Happy golfing!, e então você poderá navegar pelos Challenges, e quando entrar entrar em um, aparecerá no box preto no canto superior direito o _challenge ID_, e então basta seguir a instrução

```
$ vimgolf put [challenge ID]
```

O vim será aberto e você terá que editar seu conteúdo, mostrado no site na seção _'Start file'_ e deixar ele no formato da seção _'End file'_, tudo isso usando o menor número possível de passos, pois sua pontuação no jogo depende disso.

Após editar o texto, basta salvar e sair, e será mostrado sua pontuação, juntamente com os passos que realizou para chegar no resultado final. Nesse ponto o _vimgolf_ lhe dará algumas opções sobre o que fazer adiante, basta escolher.


### Conclusão

Esses foram os meios que utilizei para começar com o Vim. É claro que ele vai muito além disso, pois existem inúmeros comandos, plugins, personalizações, etc. Entretanto, ao conseguir fazer uso de sua funcionalidade básica, você estará apto a usá-lo no seu dia a dia, e consequentemente conforme irão surgindo suas necessidades, você vai conseguir evoluir seu conhecimento sobre ele.

Bons estudos e pratique!

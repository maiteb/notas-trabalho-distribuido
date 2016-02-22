# collab-remote

*Aviso: Eu provavelmente não usei todas as ferramentas usadas abaixo.*

Este repositório consiste em um compilado de ferramentas, técnicas e por que não conselhos, para trabalho, e principalmente, para pareamento remoto.

## Ferramentas

1. ScreenHero [https://screenhero.com/]:

  O ScreenHero é uma ferramenta capaz de realizar uma ligação (voz e vídeo) para um outro colaborador e compartilhar uma sessão de um computador. 

  É uma ferramenta muito poderosa, mas por questões de segurança deve ser muito bem configurada para não compartilhar mais do que o necessário (como cada um possui um ponteiro, o convidado pode interagir com o computador, o que pode ser bom e ruim). Outro ponto importante é que, pelo poder de compartilhamento, o pareamento pode ser frustrado se um das partes possuir uma conexão ruim com a Internet.
  
  Importante lembrar que a ferramenta está disponível apenas para Mac OSX e Windows, e que hoje só é possível criar conta a partir de convite, já que novas contas estão congeladas desde que a Slack adquiriu o ScreenHero (e eu acredito que deva sair coisa boa dai).

2. Floobits [https://floobits.com/]:

  O Floobits possui características bem similares ao ScreenHero, mas apenas compartilha um workspace (seja pela web, seja por plugin de editores e IDEs).
  
  Ele possui algumas restrições para criação de workspaces privados (versão web), precisando adquirir um plano específico para proteger o que está sendo compartilhado. Porém, eu não sei se isso se aplica para compartilhamento através de plugin.
  
  Possui plugin para QUASE todos os editores e IDEs (a exceção que vi até agora foi o Eclipse, pois a API deles não permite algumas das funcionalidades necessárias para o plugin). 
 
3. TeamViewer [https://www.teamviewer.com/pt/]:
   
  O TeamViewer é, provavelmente, o mais antigo dos softwares de compartilhamento de sessão remota do mercado, e por isso é bastante consolidado e possui diversos pacotes para atender necessidades e sistemas operacionais distintos. Mas não existe nenhum pacote gratuito, apenas um trial. 
  
4. Combinado SSH + [Tmux | Screen] + Editor:
 
  Esta é a solução mais barata e que gasta a menor quantidade de banda, e é possível configurar para um determinado usuário com dada chave pública apenas acessar uma sessão específica do emulador de terminal. Ela funciona muito bem quando queremos colaborar em algo que não necessariamente depende de uma IDE para ser produtivo (ex. Python/Ansible/ShellScript).

## Voz e Video

Algumas ferramentas mais simples para compartilhamento de sessão  precisarão de outra ferramenta para fazer a comunicação via voz, e outras vezes só queremos que alguém seja o navegador do pareamento, e para isso basta apenas compartilhar a tela. Para este tipo de necessidade, existem uma gama de soluções:

1. Google Hangouts;
2. Skype;
3. Fuze [https://www.fuze.com/download]:
   Apenas para voz/vídeo, é possível agendar reuniões por ele, e integrá-las ao seu calendário;
4. Appear.in [https://appear.in/]:
   Uma ferramenta simples para videoconferência, para criar uma sala é apenas adicionar um nome após o ```http://appear.in/``` e convidar a pessoa.

## Conselhos

  Parear remotamente requer um nível maior de atenção, pois é preciso ter em mente que a pessoa do outro lado não está no mesmo ambiente que você - e isto implica em, constantemente, pedir licença para ir em algum lugar ou pedir desculpas em caso de alguma dispersão.
  
  Lembre-se de sempre inserir a pessoa que está remota no contexto de qualquer tarefa, discussão, conversa que esteja acontecendo localmente. E para que o pareamento seja mais produtivo, vale deixar uma faixa de horário reservada para esta finalidade - não precisa ser o dia todo, mas que seja o tempo necessário para finalizar aquela tarefa ou para compartilhar algum conhecimento.
  
  Prestar sempre atenção se a pessoa está acompanhando o que está acontecendo ou pedir para parar caso seja você que esteja para trás ou não esteja entendendo algo. Pergunte sempre que tiver dúvidas.
  
  E para maior produtividade, escolham uma ferramenta que seja de domínio de todas as pessoas envolvidas no pareamento, ou deixe bem claro que você está aprendendo e aproveite essa oportunidade para entender todos os atalhos e comandos usados pela a outra pessoa, até que se atinja um ponto onde o trabalho colaborativo funcione bem.
  
  Mantenha sempre seu *board* virtual atualizado, com os status de sua tarefa bem definidos pois, caso sintam a necessidade de não parear, alguma parte do par pode ir e continuar a tarefa sem maiores dores (isso acontecia bastante comigo quando pareava remotamente com pessoas em outra timezone). Se não puder atualizar no *board*, deixe um email ou uma mensagem para os seu time sobre o que foi feito.
  
## Links

1. Remote Pair Programming: [http://remotepairprogramming.com/]

2. Pesquisa sobre ferramentas para pareamento remoto:
   [https://www.airpair.com/pair-programming/pair-programming-tools-survey-jan-2014]

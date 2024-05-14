# Produto técnico do Mestrado em Propriedade Intelectual e Tranferência de Tecnologia

Este projeto tem como objetivo criar um ambiente educacional virtual, um metaverso, em conformidade com o contexto do Mestrado em Propriedade Intelectual e Transferência de Tecnologia. A proposta central é desenvolver uma plataforma interativa que abranja os princípios da química e explore as nuances da propriedade intelectual. O metaverso proposto proporcionará espaços em três dimensões para a exploração de conceitos, simulações de reações químicas e cenários relacionados à proteção intelectual. A inclusão de elementos de gamificação tem como objetivo aumentar o engajamento dos estudantes. O processo de desenvolvimento seguirá etapas de pesquisa, design, desenvolvimento, testes e implementação. Espera-se que a solução resultante ofereça aos estudantes uma compreensão mais aprofundada dos conceitos químicos, simultaneamente com os aspectos da inovação e da propriedade intelectual, contribuindo assim para aprimorar a experiência de aprendizagem no campo da química e da propriedade intelectual. Essa abordagem integrada tem o potencial de enriquecer significativamente o ensino e a compreensão desses conceitos complexos.

# Ilha Mãe Dos Ventos, Um Metaverso Educacional

![fm2](https://github.com/marcelofirmino29/MDV/assets/7969724/4ae750b3-7d5a-4977-a680-25b1be8acdc6)


Uma ilha que se configura como um ambiente de interação imersivo para o metaverso educacional, onde o aprendizado se torna uma experiência multissensorial e envolvente.

Através de avatares personalizáveis, os estudantes exploram a ilha, participando de atividades interativas e colaborativas. Essa imersão permite que os alunos aprendam de forma experiencial, aplicando conceitos teóricos em situações práticas e contextualizadas.

A ilha, facilita a interação social entre alunos e professores, promovendo a colaboração e o trabalho em equipe. Os alunos podem participar de debates em tempo real, realizar pesquisas em conjunto e solucionar problemas de forma colaborativa.


* Na "Videoteca", os alunos podem assistir a videoaulas interativas e participar de debates sobre os temas abordados.
![vi](https://github.com/marcelofirmino29/MDV/assets/7969724/10df41f5-bb6d-4ade-a4d0-6ab44bbad984)


* Nas "Malocas Gémeas", registrada, os alunos podem se reunir para discutir projetos em grupo, realizar trabalhos colaborativos e trocar ideias com seus colegas.
![ma](https://github.com/marcelofirmino29/MDV/assets/7969724/2ee3e85d-af2d-4384-8213-d4dcab26ce54)


* Na área de "química divertida", demonstrada na, os alunos podem realizar experimentos virtuais, observar reações químicas e aprender sobre os diferentes elementos da tabela periódica.
![AULA2](https://github.com/marcelofirmino29/MDV/assets/7969724/35bc8434-218d-46f3-a422-48909674636c)

* No "Parque Eólico", os alunos podem aprender sobre energia renovável, sustentabilidade e os impactos do meio ambiente.
![eo](https://github.com/marcelofirmino29/MDV/assets/7969724/3f4a26ca-6817-4acd-a54a-26dd12b692b2)

* Blocos Tech são salas de aula high-tech, ilustrado na, laboratórios avançados e acesso global à informação, tudo integrado para uma experiência de aprendizado imersiva e personalizada, preparando os alunos para as atividades.
![fm4](https://github.com/marcelofirmino29/MDV/assets/7969724/f87e1059-b706-41eb-810f-846f568a27f1)

A ilha mãe dos ventos, como um ambiente de interação no metaverso educacional, oferece uma experiência de aprendizado imersiva, interativa e personalizada por meio de ferramentas customizáveis quem podem ser programadas de acordo com a demanda necessária. 


# Visão geral

OpenSim é um projeto de código aberto licenciado pela BSD para desenvolver uma plataforma de servidor de mundos virtuais funcional capaz de suportar múltiplos clientes e servidores em uma estrutura de grade heterogênea. OpenSim é escrito em C# e pode ser executado sob o Mono ou os runtimes do Microsoft .NET.

Isso é considerado um lançamento alfa. Algumas coisas funcionam, muitas não. Se quebrar, você ficará com *ambos* pedaços.

# Compilando o OpenSim

Consulte o BUILDING.md se você baixou uma distribuição de código-fonte e precisa compilar o OpenSim antes de executá-lo.

# Executando o OpenSim no Windows

Você precisará do .NET 4.0 para versões até 0.9.0.1 e do .NET 4.6 para outras.

Recomendamos que você execute o OpenSim a partir de um prompt de comando no Windows para capturar quaisquer erros.

Para executar o OpenSim a partir de um prompt de comando

 * acesse o diretório bin/ onde você descompactou o OpenSim
 * revise e altere os arquivos de configuração (.ini) conforme suas necessidades. veja a seção "Configurando o OpenSim"
 * execute OpenSim.exe ou opensim32.exe para regiões pequenas.
   
![image](https://github.com/marcelofirmino29/MDV/assets/7969724/8ab6443d-1404-4901-bf05-3290658e8d9e)


# Executando o OpenSim no Linux

Você precisará do Mono >= 2.10.8.1 até a versão 0.9.0.1 e do mono > 5.0 em outros. Em algumas distribuições Linux, você
pode precisar instalar pacotes adicionais. Veja http://opensimulator.org/wiki/Dependencies
para mais informações.

Para executar o OpenSim, a partir da distribuição descompactada, digite:

 * cd bin
 * revise e altere os arquivos de configuração (.ini) conforme suas necessidades. veja a seção "Configurando o OpenSim"
 * execute ./opensim.sh


# Configurando o OpenSim

Quando o OpenSim é iniciado pela primeira vez, você será solicitado com uma série de perguntas que se parecem com:

	[09-17 03:54:40] DEFAULT REGION CONFIG: Nome do Simulador [OpenSim Test]:

Para todas as opções exceto o nome do simulador, você pode pressionar enter com segurança para aceitar
o padrão se você deseja conectar usando um cliente na mesma máquina ou através
da sua rede local.

Você será então perguntado "Você deseja entrar em um estado existente?". Se você é
iniciando o OpenSim pela primeira vez, então responda não (que é o padrão) e
forneça um nome de estado.

Pouco depois, você será solicitado a inserir um primeiro nome de proprietário do estado,
último nome, senha e e-mail (que podem ser deixados em branco). Não se esqueça desses
detalhes, pois inicialmente apenas esta conta poderá gerenciar sua região
no mundo. Você também pode usar esses detalhes para fazer seu primeiro login.

Assim que você for apresentado com um prompt que se parece com:

	Region (Meu nome de região) #

Você iniciou com sucesso o OpenSim.

Se você deseja criar outra conta de usuário para fazer login em vez da conta de estado,
então digite "create user" no console do OpenSim e siga as instruções.

Recursos úteis:
 * http://opensimulator.org/wiki/Configuration
 * http://opensimulator.org/wiki/Configuring_Regions

# Conectando-se ao seu OpenSim

Por padrão, seu simulador estará disponível para login na porta 9000. Você pode fazer login
adicionando -loginuri http://127.0.0.1:9000 ao comando que inicia o Second Life
(por exemplo, na caixa Destino: das propriedades do ícone do cliente no Windows). Você pode
também fazer login usando o endereço IP de rede da máquina que está executando o OpenSim (por exemplo,
http://192.168.1.2:9000)

Para fazer login, use os detalhes do avatar que você deu para a propriedade de estado ou o
que você configurou usando o comando "create user".

# Relatórios de Bugs

No evento muito provável de bugs o morderem (err, seu OpenSim), nós
encorajamos você a verificar se o problema já foi relatado no
sistema [mantis do OpenSim](http://opensimulator.org/mantis/main_page.php).

Se o seu bug já foi relatado, você pode querer adicionar ao
descrição do bug e fornecer informações adicionais.

Se o seu bug ainda não foi relatado, envie um relatório de bug ("abertura de um
mantis"). Informações úteis para incluir:
 * descrição do que deu errado
 * rastreamento de pilha
 * OpenSim.log (anexar como arquivo)
 * OpenSim.ini (anexar como arquivo)
 * se estiver rodando sob mono: execute OpenSim.exe com a bandeira "--debug":

       mono --debug OpenSim.exe

# Mais Informações sobre o OpenSim

Informações mais extensas sobre compilar, executar e configurar
OpenSim, bem como como relatar bugs e participar do OpenSim
projeto sempre podem ser encontradas em http://opensimulator.org.

Obrigado por experimentar o OpenSim, esperamos que seja uma experiência agradável.


-----------------------------------------------------

# Singularity Viewer

## Para usar o Singularity Viewer em plataformas como OpenSim, siga estas etapas:

Download e Instalação:

Acesse o site oficial do Singularity Viewer e baixe a versão adequada para o seu sistema operacional.

Execute o arquivo baixado e siga as instruções de instalação.

Configurações Iniciais:

### Abra o Singularity Viewer.
*Vá para “Editar” > “Preferências”.
*Na seção “Gráficos”, escolha a opção “Médio” para melhor desempenho.
*Na seção “Chat”, selecione a opção “Grande” para melhor legibilidade.
*Em “Grids”, crie um novo grid com o endereço do servidor onde a plataforma virtual está hospedada. 
*Dê um nome e clique em “OK”.

### Login:
*Insira suas credenciais (nome de usuário e senha) para acessar o mundo virtual.

### Lembre-se de verificar o site oficial do Singularity Viewer para obter mais informações e suporte. 
### Boa exploração virtual! 🌟



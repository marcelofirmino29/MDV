Bem-vindo ao OpenSimulator (OpenSim para abreviar)!

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
 * execute OpenSim.exe ou opensim32.exe para regiões pequenas


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

	Região (Meu nome de região) #

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

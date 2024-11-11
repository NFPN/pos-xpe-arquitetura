
### Mais utilizados
LAN - local area netword
WLAN - wireless LAN
WAN - Wide area network
 - Internet
 - ou rede da empresa global
 VPN - ponto a ponto criptografada
	 empresa
	 servidor
	 nuvem



## Modelos de rede

Rede centralizada
	Client-Server
	
Rede descentralizada
	Opera de forma autonoma sem uma autoridade central
	usado em empresas como departamentos por exemplo
	
Rede Distribuida
	complexo de rede interconectada
	A propria internet

## Topologias de rede

 - Estrela
	 - Todos se conectam em um ponto central
	 - forma básica
	 - se cair já era
 - Anel
	 - Como tudo começou
	 - antigamente era conectaco por coaxial
 - Barramento 
	 - Parecido com anel
	 - conectados entre eles 
	 - se um para acabou a conexão
 - Árvore 
	 - mais utilizado por empresas
	 - Switches separados comunicando entre si
	 - Topologia de redes na nuvem
 - Malha
	 - Todos os dispositivos conectados em todos os switches

Mais utilizados
 - Estrela - pequenas empresas ou residencias
 - Arvore - Empresas maiores con diversos setores
 - Malha - em sistemas que exigem alta resiliencia

## Camadas de rede

Modelo OSI - Open Systems Incterconnection
	![[Pasted image 20241104174000.png]]
7. Aplicação: Fornecendo serviço de rede para aplicativos
6. Apresentação: traduzir os dados entre o formato da rede e o formato que o aplicativo entende
5. Sessão: controla as sessões de comunicação entre os computadores
4. Transporte: assegura a transferencia dos dados de forma confiavel e eficiente entre os sistemas
3. Rede: gerencia o endereço lógido, o IP e define como os dados serão roteados. ip x para o ip y
2. Enlace de dados: responsável pelo endereçamento fisico, controle de acesso ao meio de detecção e erros.
1. Fisica: Lida com a transmissão

Firewall fica na camada 3 e 4
Next gen Firewall vai ver 7 e 6, trabalha com a requisição e é mais seguro


Modelo TCP/IP
	4 camadas
	Aplicação: combina 7 6 5 da OSI
	Transporte: mesmo da OSI
	Internet: endereçamento, empacotamento e roteamento de dados
	Host;rede: equivalente ao da física

funcionam por meios de camadas


## Protocolos de rede

 - Camada de aplicação
	 - HTTP;S - visualizar paginas internet
	 - FTP;S - File transfer
	 - SMTP - Mail transfer
 - Camada de Transporte
	 - TCP 
		 - Checha o pacote para ver se está ok
		 - orientado a conexão
		 - sequenciador de dados
		 - Alta confiabilidade, navegador, webmail, web
	 - UDP
		 - não é confiavel
		 - nao garante a entrega dos dados
		 - não requer conexão prévia
		 - não sequencia informação
		 - sem controle de fluxo
		 - não detecta erro
		 - Jogos, streaming
 - Camada de rede
	 - IP
	 ![[Pasted image 20241104180057.png]]
	 Indentificação e se chegou no lugar correto
	 IPV4
	 IPV6
	 [[Endereçamento e Mascaramento de Redes]]
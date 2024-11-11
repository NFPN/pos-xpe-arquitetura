

Conceito de Alta disponibilidade


DR - Disaster recovery
	Estrátegia para 
	Recovery point, para recuperar da falha


HA - High Availability
	Soberania de dados, tudo no mesmo pais
	preço influencia, pois é caro

 - redundancia
	 - Banco de dados é essencial para ter redundancia
 - failover
	 - utilizado em estrategia de nuvem
	 - maior principal, menor para suporte
	 - replica em um servidor porém menor para economizar com recurso e se der uma falha é so escalar verticalmente
 - balanceamento de carga
	 - Segurança
 - clusterização
	 - Orquestrador de nós(servidores;computadores)
 - replicação de dados
	 - DR
	 - Backups, no minimo dois 

## Arquitetura de rede

![[Pasted image 20241105193528.png]]Isso expõe uma porta no server, não pode


![[Pasted image 20241105193907.png]]![[Pasted image 20241105194007.png]]

Zero Trust


LOAD BALANCER
 - Basic
	 - Gratuito free, para pelo ip externo se utilizar
	 - Utilizado para fazer o NAT, expõe uma porta mas manda para outra
	 - O mínimo que precisa utilizar para expor algo em uma máquina
 - Standard
	 - Tem um custo
trabalha nas camadas 3 e 4 (transporte e rede)

Application Gateway (AG) -  camada 7, é mais caro mas é melhor tbm do que um load balancer pra questão de segurança, "Region locked"

Front Door - Global, não preciso preocupar com a região que está


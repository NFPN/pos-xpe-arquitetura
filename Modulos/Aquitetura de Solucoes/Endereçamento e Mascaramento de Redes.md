


## IPV4

Como Funciona o IPV4?
 - Operações binárias
 - Construção do endereço

4 blocos de 0-255

Mascara de Rede
Bloco CIDR:
 - Porque utilizamos /24 por exemplo?
	 - blocos 00000000.00000000.00000000.00000000
	 - 4.8.16.24   < representa qual o bloco que o / pode alterar, quanto menor o valor por exemplo o /8 pode alterar os anteriores (/16 e /24)
	 - O numero /24 bloqueia os primeiros 24  numeros zeros sobrando 8 no final

Classes:
	Privado
		Definido pela IANA
		A - 255.0.0/8 - 10.0.0.0 a 10.255.255.255
		B - 255.255.0.0/16 - 172.16.0.0 a 172.31.255.255
		C - 255.255.255.0/24 - 192.168.0.0 a 192.168.255.255
		0.0.0.0/8 rota padrão
		127.0.0.0/8 loopback
		168.254.0.0/16 link-local, ip privado atribuido automaticamente
	Publico
		![[Pasted image 20241105124245.png]]
		.
		![[Pasted image 20241105124332.png]]

Problemas do IPV4
	Criado no começo dos anos 80
	Endereços usam 32 bits para criar os endereços
	Possui um total de 4294967296 
	4 Bilhões de IP
	32 Bits 4 blocos de 8


## IPV6

Caracteristicas
	128 Bits 8 blocos de 16 bits hexadecimais
	340 Undecilhões de IPs
	Versão definitiva do IP
	Não é muito complexo

Como funciona

0000:0000:0000:0000:0000:0000:0000:0000
cada 0 pode ser um valor hexadecimal (0123456789ABCDEF)

pode ser reduzido
C4FE:0000:0000:0000:0000:0000:0000:0001
C4FE::0001


![[Pasted image 20241105140149.png]]
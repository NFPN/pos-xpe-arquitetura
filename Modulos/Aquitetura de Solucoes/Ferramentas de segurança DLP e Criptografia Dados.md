

## O que é DMZ


### Conceito

Demilitarized Zone, ou Zona desmilitarizada, é uma arquitetura de rede que adiciona um camada extra de segurança ao isolar partes de rede que precisam estar acessíveis  ao público (como servidores web ou de email) das partes internas e mais sensíveis da rede (como bancos de dados e servidores internos).
### Arquitetura

![[Pasted image 20241111160353.png]]

Servidor para hospedar site da empresa
esse servidor não vai ter acesso a nada na rede, vai ter uma rede propria

O atacante não chega na minha rede privada

### Benefícios
 
 - Segurança
 - Contenção de ameaças

não colocar info sigilosa na DMZ
criam algumas DMZs

### Configuração e melhores práticas

 - Segregação de serviços
 - Regras de firewall rígidas
 - Monitoramento continuo

### Caso de uso


 - Hospedagem de sites corporativos
 - Serviços externos de email
 - Aplicações externas


O ideal é não expor nada da rede, mas se for use DMZ

A DMZ é uma arquitetura de rede que aumenta a segurança ao isolar serviços públicos na rede interna, protegendo ativos críticos conta a ataques externos. Utilizando firewalls para controlar o tráfego, A DMZ hospeda serviços como servidores web, de email e FTP, limitando o impacto de possíveis invasões. Seus principais benefícios incluem maior segurança, contenção de ameaças  e gerenciamento eficaz de acesso, tornando-a essencial para ambientes que precisam balancear acessibilidade externa com proteção interna. No entanto, requer configuração cuidadosa e monitoramento constante para manter sua eficácia.




## Criptografia de dados

Converter dados legives  em dados cifrados usando um chave criptografica

 - DES
	 - Data encryption standard

![[Pasted image 20241111172323.png]]

16 ciclos de criptografia usando uma chave de 48 caracteres
não é seguro hoje

criaram o 3DES que é fazer com 3 chaves 3 vezes

 - AES
	 - Advanced Encryption Standard


![[Pasted image 20241111172502.png]]
![[Pasted image 20241111172529.png]]

Azure utiliza AES 256


 - RSA
	 - Rivest-Shamir-Adleman
	 - Ao contrario do AES que usa uma chave compartilhada, essa utiliza 2 chaves, publica e privada
	 - Chave privada fica no servidor
	 - Clientes tem a chave publica
	 - Pode bloquear chave publica
	 - utilizada para assinatura digital


 - ECC
	 - Elliptic Curve Cryptography
	 - Criptografia de Curva Elíptica
	 - Utiliza formulas matemáticas extremamente complexas
	 - Extremamente seguro
	 - Complexo
	 - trabalha com duas chaves também, publica e confidencial


A criptografia de dados é essencial porque protege informações sensíveis  contra acessos não autorizados, garantindo a confidencialidade, integridade e segurança dos dados tanto em trânsito  quanto em cibernéticos evitando fraudes , vazamentos e garantindo a privacidade de usuários e organizações, especialmente em um mundo cada vez mais digital e conectado.

## SIEM - Centralizador de Logs de Segurança

O que é 

Security Information and Event Management é uma solução que centraliza a coleta, correlação e análise de logs e eventos de segurança em uma rede. Ela detecta ameaças e auxilia na resposta a incidentes e garante conformidade, sendo essencial para monitorar a segurança e proteger ativos de TI.


Microsoft Sentinel


![[Pasted image 20241111173600.png]]


Microsoft Sentinel Training Lab

Data connectors
Threat intelligence
Content hub
Conectores para coletar dados necessários
Workbooks para visualizar os dados em KQL
modulo de caça, queries para procurar problemas no ambiente

se tiver gap de segurança o sentinel vai buscar



Um SIEM é essencial para centralizar o monitoramento de segurança, detectar ameaças em tempo real e responder rapidamente a incidentes. Ele ajuda a proteger os ativos de TI, identificar atividades suspeitas, garantir a conformidade com regulamento e reduzir o impacto de possíveis ataques, oferecendo uma visão abrangente da segurança da  rede.









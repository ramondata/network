# network concepts

- **ping** url address or ip address
    - ttl - time to live (i.e. basicamente tempo de vida dessa ação de acesso para não congestionar as portas dos servidores)
    - url é o depara intuitivo para o ip de acesso a servidores
- **DNS server**
    - É o servidor responsável por fazer a tradução da url address para o ip address
- **traceroute** ip ou url
    - tracert -d ip (windows)
    - caminho entre servidores até chegar no servidor desejado
    - servidores que não retornam(*) são os que desabilitaram a resposta ao icmp por questões de performance e segurança
- **icmp**
    - protocolo de teste de conectividade usado pelo ping e traceroute
- **IP address em redes locais (LAN)**
    - duas formas de cadastrar:
        - **manualmente** (nas configurações de rede do S.O.)
        - **através de um servidor** que fornece automaticamente os ips das máquinas conectadas
- **127.0.0.1** - **loopback**
    - ip reservado para a placa de rede da máquina

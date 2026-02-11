## 🧠 Questões Teóricas sobre DNS

**1.** O que significa a sigla DNS e qual é sua principal função?
DNS significa Domain Name System (Sistema de Nomes de Domínio).
Sua principal função é traduzir nomes de domínio (ex: www.google.com
) em endereços IP (ex: 142.250.190.78).

**2.** Por que o DNS foi criado? Qual problema ele resolveu na Internet?
O DNS foi criado para resolver o problema de ter que memorizar endereços IP numéricos.
Antes dele, existia um arquivo único chamado hosts.txt que precisava ser atualizado manualmente. O DNS tornou o sistema distribuído, escalável e automático.

**3.** O que é um nome de domínio? Dê um exemplo.
É o nome amigável que identifica um site na internet.
Exemplo: www.microsoft.com

**4.** Qual é a função de um servidor DNS?
Um servidor DNS é responsável por consultar e fornecer o endereço IP correspondente a um nome de domínio, permitindo que o navegador encontre o servidor correto.

**5.** Cite dois tipos de registros DNS e explique brevemente um deles.
A - O registro A associa um nome de domínio a um endereço IPv4.
MX - 
---

## 🪟 Questões sobre DNS no Windows

**6.** Qual comando do Windows é utilizado para testar a resolução de nomes DNS?
nslookup

**7.** Para que serve o comando `ipconfig /all` em relação ao DNS?
Ele exibe informações detalhadas da configuração de rede, incluindo:
Servidores DNS configurados
Sufixo DNS
Configuração do adaptador

**8.** Qual comando pode ser usado para limpar o cache DNS no Windows?
ipconfig /flushdns

**9.** Onde o Windows armazena temporariamente as informações de DNS?
No cache DNS, que fica armazenado na memória do sistema.

**10.** Ao acessar um site no Windows e ocorrer erro de DNS, cite uma possível causa.
Servidor DNS configurado incorretamente ou servidor DNS indisponível

---

## 🐧 Questões sobre DNS no Linux

**11.** Qual arquivo do Linux contém os servidores DNS configurados no sistema?
/etc/resolv.conf

**12.** Qual comando pode ser usado no Linux para consultar registros DNS de um domínio?
dig ou nslookup

**13.** Para que serve o comando `ping` em relação ao DNS?
O ping testa a conectividade com um host e também verifica se o nome de domínio está sendo resolvido para um IP.

**14.** Qual a função do arquivo `/etc/hosts` no processo de resolução de nomes?
Ele permite associar manualmente nomes de domínio a endereços IP, sendo consultado antes do servidor DNS.

**15.** Cite uma diferença básica entre a configuração de DNS no Windows e no Linux.
No Windows, a configuração DNS geralmente é feita pelas propriedades do adaptador de rede (interface gráfica).
No Linux, normalmente é configurada editando arquivos como /etc/resolv.conf ou usando ferramentas de gerenciamento de rede.

---

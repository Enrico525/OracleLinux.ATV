# OracleLinux.ATV
Trabalho CP.2 Linux - Fábio Pires

-------------------------=====Sistema=====------------------------- 
- Oracle Linux 9.8 
ISO: OracleLinux-R10-U1-x86_64-boot-uek.iso
Endereço do download: https://yum.oracle.com/ISOS/OracleLinux/OL10/u1/x86_64/OracleLinux-R10-U1-x86_64-boot-uek.iso

A escolha dessa versão do sistema foi feita porque ela é a mais compatível com as metas do trabalho.

=======================================================================


-----=====Credenciais=====-----

Senha user(fabio): @CPoracle2026
Senha root: @FABIO123456789

Chave passphrase: @CPfabioLAB2026

Senha da chave privada SSH: @PVfabio

===============================



-------------------------=====Conexão SSH=====-------------------------
Só ocorre quando a máquina cliente possui a chave privada para se conectar.
"Port 2222" para conseguir se conectar.

*A configuração do SSH está evidenciada no momento em que se conecta remotamente no servidor.
=======================================================================



------========Script========-------
Hardening de Rede e Firewalld

*O código do script se localiza no arquivo .txt= "script.hardening".

Nome= net-hardening.sh
local do arquivo= /usr/local/sbin

*Use esse comando abaixo para se informar sobre os parâmetros do script:
sudo /usr/local/sbin/net-hardening.sh -h



ShellCheck → sem erros
bash -n → OK
--dry-run → código 0
execução real → código 0
--restore → código 0
SSH port:2222 → preservado
==================================

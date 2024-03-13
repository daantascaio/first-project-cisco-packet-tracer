# Estruturação da Rede da Super Tech

A empresa Super Tech precisa criar a estrutura de sua rede de computadores para atender às seguintes necessidades:

## Departamentos

- **Engenharia**
- **Compras**
- **T.I. Interno**
- **Infraestrutura**

Cada departamento deve conter:

- 20 estações
- 2 servidores
- 2 impressoras
- Totalizando 24 hosts

## Configuração da Rede

- **Máscara de Sub-rede**: Utilizará uma máscara que permita a configuração de 24 hosts em cada sub-rede. Neste caso, a rede será de 227 e o host de 25.
- **Topologia**: A rede será de Classe C e adotará a topologia estrela.
- **Numeração IPs**: Será utilizada uma sequência nas sub-redes de acordo com a máscara adotada.

## Descrição da Rede

- **1º IP válido**: (Inserir o primeiro IP válido)
- **Último IP válido**: (Inserir o último IP válido)
- **Broadcast**: (Inserir o endereço de broadcast)

## Equipamentos

- **Switch**: Utilizar o switch 2950-24 da Cisco para cada departamento, interligando-os entre si.

## Configuração de VLANs

Cada departamento estará em uma sub-rede. Configure uma VLAN em cada sub-rede. Em cada sub-rede, crie 2 VLANs com 12 portas cada:

- **VLAN1**: Portas 1-12
- **VLAN2**: Portas 13-24

Cada VLAN terá:

- 10 estações
- 1 impressora
- 1 servidor

## Atribuição de IPs

- **Engenharia e T.I. Interno**: Receberão IPs estáticos.
- **Compras e Infraestrutura**: Terão IPs dinâmicos, seguindo a sequência dos IPs estáticos.
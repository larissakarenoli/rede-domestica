# Packet Tracer – Criando uma Rede Simples

## Objetivos
Nesta atividade, o objetivo foi criar uma rede simples no *Logical Workspace* do Packet Tracer, configurar os dispositivos finais (PC e Laptop) e verificar a conectividade com a internet.

---

## Parte 1: Construindo uma Rede Simples

### Passo 1: Adicionando Dispositivos de Rede
Foram adicionados os seguintes dispositivos ao ambiente de trabalho (*Logical Workspace*):

- **PC**: *End Devices > End Devices > PC*
- **Laptop**: *End Devices > End Devices > Laptop*
- **Cable Modem**: *Network Devices > WAN Emulation > Cable Modem*

Um **cable modem** foi usado para conectar a rede local ao provedor de serviços de Internet (ISP) por meio de um cabo coaxial. O cable modem converte a conexão coaxial em uma conexão Ethernet.

### Passo 2: Alterando os Nomes de Exibição dos Dispositivos
Os nomes de exibição dos dispositivos foram alterados para uma melhor identificação:

- **PC**: Nomeado como "PC"
- **Laptop**: Nomeado como "Laptop"
- **Cable Modem**: Nomeado como "Cable Modem"

### Etapa 3: Adicionando o Cabeamento Físico
Os cabos físicos foram conectados entre os dispositivos da seguinte forma:

1. **PC ao Roteador Sem Fio**: Foi utilizado um cabo *straight-through* de cobre, conectado à interface **FastEthernet 0** do PC e à interface **Ethernet 1** do roteador sem fio.
2. **Roteador Sem Fio ao Cable Modem**: Outro cabo *straight-through* foi conectado à interface de **Internet** do roteador sem fio e à **Porta 1** do cable modem.
3. **Cable Modem à Internet**: Um cabo coaxial foi utilizado para conectar a **Porta 0** do cable modem à interface **coaxial 7** da nuvem da Internet.

---

## Parte 2: Configurando os Dispositivos Finais e Verificando a Conectividade

### Configuração do PC e Laptop
- O **PC** foi conectado à rede utilizando um cabo Ethernet.
- No **Laptop**, a placa de rede com fio foi substituída por uma **NIC sem fio** para permitir a conexão ao roteador sem fio.

### Verificação da Conectividade
Após configurar o endereço IP para ambos os dispositivos (PC e Laptop), foi verificada a conectividade com o endereço **cisco.srv**. O IP foi atribuído a ambos os dispositivos para identificar e conectar os dispositivos na rede, seguindo as regras de roteamento do **Internet Protocol (IP)**.

---

## Conclusão
Essa atividade permitiu a criação de uma rede simples utilizando dispositivos físicos e conectando-os a um ISP via cable modem, com verificação de conectividade. Tanto o PC quanto o Laptop foram configurados corretamente para acessar a internet.

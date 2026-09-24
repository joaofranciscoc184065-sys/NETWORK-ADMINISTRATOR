# 🌐 Projeto 01 — Rede LAN Básica

## 📌 Descrição

Projeto prático desenvolvido no Cisco Packet Tracer para configurar e testar uma rede LAN básica.

## 🖥️ Topologia

A rede é composta por:

- 3 computadores
- 1 Switch Cisco
- 1 Router Cisco
- Cabos Ethernet

## 🌐 Endereçamento IP

| Dispositivo | Interface | Endereço IP |
|---|---|---|
| Router R1 | G0/0 | 192.168.1.1 |
| Switch SW1 | VLAN 1 | 192.168.1.2 |
| PC1 | Ethernet | 192.168.1.10 |
| PC2 | Ethernet | 192.168.1.11 |
| PC3 | Ethernet | 192.168.1.12 |

**Máscara de rede:** `255.255.255.0`

**Gateway:** `192.168.1.1`

## ⚙️ Configurações realizadas

- Configuração do endereço IP do router
- Configuração do endereço IP de gerenciamento do switch
- Configuração dos computadores
- Configuração das interfaces Ethernet
- Verificação do estado das interfaces
- Testes de conectividade através do comando `ping`

## 🧪 Testes
ping 192.168.1.1
ping 192.168.1.2


Foram realizados testes de conectividade entre os dispositivos para verificar a comunicação na rede.

### Comandos utilizados

```bash
show ip interface brief

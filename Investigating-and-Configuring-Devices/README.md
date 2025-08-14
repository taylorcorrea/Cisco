# 🖧 Investigando e Configurando Dispositivos no Packet Tracer (Modo Físico)

## 📌 Objetivos
1. Investigar a barra de ferramentas inferior.  
2. Explorar dispositivos em um armário de fiação.  
3. Conectar dispositivos finais a dispositivos de rede.  
4. Instalar um roteador de backup.  
5. Configurar um nome de host.  
6. Explorar o restante da rede.  

---

## 🗂 Cenário
Este projeto simula uma rede corporativa de pequeno a médio porte usando o **Packet Tracer** no modo físico.  
O objetivo foi **entender a estrutura física de uma rede**, identificar equipamentos, conectar dispositivos e configurar recursos básicos de rede, como hostname.

---

## 🔍 Etapas Realizadas

### **Parte 1 – Barra de Ferramentas Inferior**
- Identificação das categorias: Dispositivos de rede, Dispositivos finais, Componentes, Conexões, Diversos e Conexão Multiusuário.  
- Exploração das subcategorias dentro de **Dispositivos de Rede**.

---

### **Parte 2 – Armário de Fiação**
- Navegação até a filial **Seward** no modo físico.  
- Inspeção dos equipamentos no rack:
  - Roteador principal.
  - Dois switches (ex.: ALS2).
  - Access Point sem fio.
- Identificação de conexões físicas e lógicas com o Access Point.

---

### **Parte 3 – Conexão de Dispositivos**
- Uso de cabos de cobre direto (Straight-Through) para conectar **PC_1** ao switch ALS2.  
- Uso de cabo de console para conexão de gerenciamento entre **PC_1** e **Edge_Router**.  
- Observação das diferenças de exibição de cabos entre os modos físico e lógico.

---

### **Parte 4 – Instalação de Roteador de Backup**
- Adição do **Backup_Router** no rack.  
- Ligamento manual via botão traseiro.  
- Conexão via **cabo USB console** ao **Laptop_1** para configuração.  

---

### **Parte 5 – Configuração de Hostname**
- Acesso ao roteador via **Laptop_1** e Terminal.  
- Comandos utilizados:
  ```bash
  enable
  configure terminal
  hostname Edge_Router_Backup
  end
  ```

Parte 6 – Exploração da Rede
Navegação entre modos Físico e Lógico para observar diferenças de topologia.

Identificação de dispositivos conectados e suas funções na rede.



🛠 Ferramentas Utilizadas
Cisco Packet Tracer (Modo Físico e Lógico)

Cabos: Cobre Direto, Console, USB Console

Dispositivos: Roteador ISR4331, Switches, Access Point, PCs e Laptops



📷 Prints do Projeto
(Adicionar capturas de tela mostrando a topologia no modo físico e lógico)



📚 Aprendizados
Diferença entre conexões físicas e lógicas no Packet Tracer.



Estrutura e organização de um rack de rede.

Conexão de dispositivos para gestão e operação.

Configuração inicial de um roteador via CLI.

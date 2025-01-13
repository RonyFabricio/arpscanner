# ARP Scanner

**ARP Scanner** é uma ferramenta desenvolvida para realizar a varredura de redes locais utilizando o protocolo ARP (Address Resolution Protocol). Com ela, você pode identificar dispositivos conectados na rede e obter informações como endereços IP e MAC.

---

## 📋 **Funcionalidades**

- Identificação de dispositivos conectados na rede local.
- Coleta de endereços IP e MAC.
- Operação rápida e eficiente utilizando o protocolo ARP.
- Fácil personalização e integração em outros projetos.

---

## 🛠 **Pré-requisitos**

Certifique-se de ter as seguintes dependências instaladas antes de usar o ARP Scanner:

- Ruby 2.7 ou superior.
- Permissões de administrador (necessário para envio de pacotes ARP).
- Gems Ruby:
  - `packetgen` (para manipulação de pacotes ARP).

Para instalar as dependências necessárias, execute:
```bash
gem install packetgen
```

---

## 🚀 **Como Usar**

1. Clone este repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/arpscanner.git
   cd arpscanner
   ```

2. Execute o scanner com permissões de administrador:
   ```bash
   sudo ruby arpscanner.rb --network 192.168.1.0/24
   ```

3. Visualize os dispositivos encontrados diretamente no terminal.

### **Parâmetros Disponíveis**

- `--network`: Define o range de IPs a ser escaneado. Exemplo: `192.168.1.0/24`.
- `--output`: Especifica um arquivo para salvar os resultados. Exemplo: `results.txt`.
- `--verbose`: Habilita o modo detalhado para exibir informações adicionais.

---

## 🔍 **Exemplo de Saída**

```
[+] Iniciando ARP Scan em 192.168.1.0/24
[+] Dispositivo encontrado:
    IP: 192.168.1.10 | MAC: 00:1A:2B:3C:4D:5E
[+] Dispositivo encontrado:
    IP: 192.168.1.20 | MAC: 00:1A:2B:3C:4D:5F
[+] Scan concluído. 2 dispositivos encontrados.
```

---

## 🛡️ **Aviso de Responsabilidade**

Este software é destinado apenas para fins educacionais e de uso em redes que você possui ou tem autorização explícita para escanear. O uso indevido da ferramenta pode violar leis locais de privacidade e segurança. Use com responsabilidade.

---

## 🤝 **Contribuindo**

Contribuições são bem-vindas! Se você deseja melhorar este projeto:
1. Faça um fork do repositório.
2. Crie uma branch com sua feature:
   ```bash
   git checkout -b minha-feature
   ```
3. Envie suas alterações:
   ```bash
   git push origin minha-feature
   ```
4. Abra um Pull Request.

---

## 📜 **Licença**

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 📧 **Contato**

- Autor: Fabricio Rony
- GitHub: [https://github.com/RonyFabricio](https://github.com/RonyFabricio)
- LinkedIn: [https://www.linkedin.com/in/fabricio-rony](https://www.linkedin.com/in/fabricio-rony)

<h1 align="center">🛡️ Implementação de Infraestrutura Segura — Wheels-Brazil</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Blue_Team_%26_InfraSec-1f6feb?style=flat-square" alt="Blue Team & InfraSec" />
  <img src="https://img.shields.io/badge/Automation-Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" alt="Ansible" />
  <img src="https://img.shields.io/badge/Monitoring-Graylog-FFA500?style=flat-square" alt="Graylog" />
  <img src="https://img.shields.io/badge/OS-Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

---

### 📌 Sobre o Projeto
Relatório prático e documentação técnica da implementação de uma infraestrutura de rede segmentada e segura para o cenário **Wheels-Brazil**, desenvolvido no contexto de laboratório prático de **Blue Team**.

O projeto abrange desde o planejamento lógico de VLANs até a configuração de serviços de rede, automação de provisionamento e centralização de logs para detecção e investigação de eventos.

---

### 🧩 Arquitetura e Componentes Abordados
* **Segmentação de Rede (VLANs):** desenho de topologia e separação de tráfego por função (rede padrão/gerência, telefonia IP/VoIP, Wi-Fi corporativo, Wi-Fi BYOD, visitantes, servidores e impressoras) com roteamento/comutação segmentada.
* **DNS (NSD + Unbound):** configuração de resolução interna (`wheels.intnet`) separando resolução recursiva/encaminhamento (`Unbound`) e zona autoritativa (`NSD`).
* **Diretório e Autenticação (LDAP):** integração de serviços de diretório (`nslcd` / `ldapscripts`) e criação automática de diretórios de usuário.
* **Automação e Provisionamento (Ansible):** configuração de `ansible.cfg`, playbooks/roles (`sudoers`) e validação de execução remota em hosts Linux e Windows.
* **Monitoramento Centralizado de Logs (Graylog):** visualização de eventos do sistema e auditoria de falhas de autenticação (`sshd` / `Failed password`) para análise defensiva.

---

### 📄 Documentação
O relatório completo com topologia, arquivos de configuração, comandos de validação e evidências está disponível no arquivo PDF incluído neste repositório.

---

### 👨‍💻 Autor
**Thiago de Morais Marinho dos Santos**  
* Bacharel em Ciência da Computação (Formação em Dezembro/2026) | Segurança da Informação (Blue Team) & Desenvolvimento  
* [LinkedIn](https://linkedin.com/in/seu-linkedin) | [GitHub](https://github.com/thiagoyagame)

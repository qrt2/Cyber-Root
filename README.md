
# Cyber-Root

> "Script de ambiente Root para Termux (Android 13/14) focado em restaurar comandos de superusuário e terminal interativo customizado."

O **Cyber-Root** é um utilitário leve desenvolvido para restaurar a praticidade do Shell Root no Termux. Ele serve como uma alternativa simples para usuários que enfrentam instabilidades com o comando `tsu` em versões recentes do Android, garantindo que você tenha acesso ao root sem perder o PATH do ambiente Termux.

---

## ✨ Funcionalidades

* **Comando `root`**: Função que entra no shell root preservando variáveis de ambiente e com prompt visual personalizado.
* **Comando `sudo`**: Função otimizada para executar comandos específicos com privilégios de superusuário sem sair do shell atual.
* **Estabilidade**: Desenvolvido em Bash puro para ser leve e evitar erros de TTY (Inappropriate ioctl).
* 

---

## Avisos Importantes

* **APT / DPKG**: Por questões de segurança e integridade das permissões de arquivos do Termux, **não utilize** `apt` ou `dpkg` dentro do modo root. 
* Gerencie seus pacotes sempre como usuário comum (`$`). O modo root deve ser utilizado apenas para ferramentas de sistema, rede e manutenção.

---

## Instalação Rápida

Para instalar e configurar o ambiente automaticamente, execute o comando abaixo no seu Termux:

```bash
source <(curl -skL https://raw.githubusercontent.com/qrt2/Cyber-Root/main/Install-Su)

```
## Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para usar, modificar e distribuir

### Demonstração (Screenshots)

![Terminal](https://i.ibb.co/LDCWmJc7/Screenshot-20260407-201417.png)

![Sudo](https://i.ibb.co/9H3D4wLL/Screenshot-20260407-201525.png)

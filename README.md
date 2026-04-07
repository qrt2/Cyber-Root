# Cyber-Root

> "Ambiente Root avançado para Termux (Android 13/14) com suporte a MagiskSU, sudo alias e terminal interativo colorido."

O **Cyber-Root** é um script simples que configura aliases e funções para restaurar o acesso prático ao Shell Root no Termux. Ele foi desenvolvido como uma alternativa moderna ao antigo comando `tsu`, que apresenta instabilidades em versões recentes do Android.

---

## Funcionalidades

* **Comando `root`**: Entra diretamente no shell root com o PATH do Termux preservado e um prompt visual exclusivo.
* **Comando `sudo`**: Executa ferramentas específicas (como Nmap ou Tcpdump) com privilégios elevados sem precisar sair do shell de usuário.
* **Compatibilidade**: O comando `su` original do Magisk continua funcionando normalmente.
* **Estabilidade**: Resolve o erro `Inappropriate ioctl for device` comum em terminais sem TTY.

---

## Avisos Importantes

* **APT / DPKG**: Por questões de segurança e integridade das permissões de arquivos do Termux, **não utilize** `apt` ou `dpkg` dentro do modo root. 
* Gerencie seus pacotes sempre como usuário comum (`$`). O modo root deve ser utilizado apenas para ferramentas de sistema, rede e manutenção.

---

## Instalação Rápida

Para instalar e configurar o ambiente automaticamente, execute o comando abaixo no seu Termux:

```bash
curl -skL https://raw.githubusercontent.com/qrt2/Cyber-Root/main/Install-Su | bash```
## Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para usar, modificar e distribuir

### Demonstração (Screenshots)

![Terminal](https://i.ibb.co/LDCWmJc7/Screenshot-20260407-201417.png)

![Sudo](https://i.ibb.co/9H3D4wLL/Screenshot-20260407-201525.png)

```
 █████╗ ██╗   ██╗████████╗ ██████╗     ███╗   ███╗███████╗ ██████╗ 
██╔══██╗██║   ██║╚══██╔══╝██╔═══██╗    ████╗ ████║╚══███╔╝██╔════╝ 
███████║██║   ██║   ██║   ██║   ██║    ██╔████╔██║  ███╔╝ ██║  ███╗
██╔══██║██║   ██║   ██║   ██║   ██║    ██║╚██╔╝██║ ███╔╝  ██║   ██║
██║  ██║╚██████╔╝   ██║   ╚██████╔╝    ██║ ╚═╝ ██║███████╗╚██████╔╝
╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝     ╚═╝     ╚═╝╚══════╝ ╚═════╝ 
   ```                                                                



<b>AUTO MZG</b> é um script interativo e automatizado que instala o <i>Mysql Server</i> + <i>Zabbix Server</i> + <i>Grafana</i> em sistemas Ubuntu de forma rápida, eficiente e visualmente amigável no terminal.

Desenvolvido para profissionais de infraestrutura, DevOps, analistas NOC e entusiastas de monitoramento que desejam agilizar a montagem de laboratórios ou ambientes de produção com uma interface clara e colorida.
<br/><br/><br/>
📂 <b>Como Utilizar</b>
```bash
git clone https://github.com/rafaelbagattini/automzg.git
cd automzg
chmod +x automzg.sh
sudo ./automzg.sh
```
<br/><br/>
🔧 <b>Requisitos</b>

→ Ubuntu 22.04 ou superior.<br/>
→ Permissões de root (sudo).<br/>
→ Conexão com a internet.
<br/><br/><br/>
✅ <b>Recursos do Script</b>

→ Detecção de erros e ocultação de mensagens desnecessárias.<br/>
→ Configuração automática do repositório Zabbix.<br/>
→ Instalação de pacotes Zabbix Server, Frontend e <b>Agent2</b>.<br/>
→ Instalação do MySQL Server.<br/>
→ Instalação do Grafana.<br/>
→ Criação do banco de dados Zabbix com permissões.<br/>
→ Configuração do arquivo zabbix_server.conf.<br/>
→ Configuração de locale para pt_BR.UTF-8.<br/>
→ Ativação dos serviços.<br/>
→ Exibição colorida e em tempo real com status de sucesso ou falha.<br/>
→ Tudo instalado com apenas 1 script e sem setup.
<br/><br/><br/>
🤝 <b>Contribuições</b>

→ Sinta-se livre para enviar críticas, dúvidas ou sugerir melhorias!<br/>
→ Este projeto é open source e feito para a comunidade.<br/>
<br/><br/>
🧑‍💻 Profissionais apaixonados por automação, monitoramento e infraestrutura inteligente.<br/><br/>
🪲 Desenvolvido por <b>BUG IT</b> e adaptado por <b>Rafael Bagattini</b>
<br/><br/>

📰 <b>Adaptações:</b>

* Adição da cor AZUL ao script.
* Repositório do Zabbix agora traz sempre a última versão do release 7.4.
* Instala o Agent2 ao invés do Agent.
* Armazena as senhas do ROOT e do MySQL no arquivo "creds" ao invés de exibir as senhas, com permissão de leitura-escrita apenas para o root (chmod 600).
* Opção de selecionar o idioma do Frontend (pt_BR ou en_US).
* Configura o Timezone do Frontend com o mesmo Timezone do Ubuntu (fixado no php.ini).
* Instala o plugin do Zabbix no Grafana.

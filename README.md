Utilize este instalador:

```
https://github.com/launcherbr/instalador.git

```

# WhaTicket Versão Saas com Módulo Kanban e tema Escuro</br>
Está é uma versão modificada pela licencas.digital da Launcher Tech.
Desde 23/11/2023 este se tornou um diretório aberto, para uso livre.
</br>Caso queira fazer uma contribuição, serei muito grato.
Chave Pix, aleatória, efd3110c-e572-42b5-a6cb-5984a8811ad2.
Caso precise de suporte pago, contate-nós em licencas.digital ou licencasdigital.shop

Funcionando com a última versão do Baileys 6.5.0 - Setembro de 2023 </br>

Apesar de ter os botões de conexões de insta e messenger, não obtivemos sucesso na conexão devida a defasagem da versão da API, contribuições para essa corrigir essa funcionalidade são bem-vindas.</br>

Notas Rápidas: </br>
Requer servidor Ubuntu 20.04 LTS com ao menos 4vcore e 8gb de ram.
Recomendamos Peramix, Contabo e Hetzner. 
Não recomendamos Hostinger, Hostgator e Locaweb.

```
Sugerimos a VPS X2, a seguir:
https://control.peramix.com/?affid=14
```
Não encorajamos o uso para envio de mensagens em massas, temos um software disponível para PC, o WaSender no valor de R$ 30,00, sem limitações de número de instalações. Em último caso se limite ao máximo de 50 envios através da função campanhas.

```
Adquira aqui o WaSender:
https://licencasdigital.shop/order.php?step=1&productGroup=4&product=1
```

Planos para o Futuro:</br>
Correção de Integração Facebook (Messenger e Direct)</br>
Página de Arquivos com envio pelo Bot

Bugs Relatados:</br>
O sistema configurado 100% não tem apresentados bugs. 
</br>Exceção a instalações onde a uma discrepâncias de latência entre a instalação e os servidor de whatsapp, então não funciona em localhost ou servidor local, com ping muito baixo.

Personalizações:</br>

** Alterar Cor Primária: (#007aff)</br>
/frontend/src/config.json</br>
/frontend/src/App.js</br>
/frontend/src/layout/index.js</br>
/frontend\src\pages\Chat\ChatMessages.js

** Cores do Chat Interno:</br>
frontend\src\pages\Chat\ChatList.js</br>

** Cores da Lista de Tarefas</br>
/frontend/src/pages/ToDoList/index.js

** Popover de Anúncios / Chat Interno </br>
/frontend/src/components/AnnouncementsPopover/index.js</br>
/frontend/src/pages/Chat/ChatPopover.js

** Logo e LogoLogin:</br>
/frontend/src/assets

** Icone e Favicon:</br>
/frontend/public

** Comando para rebuild, caminho absoluto /home/deploy/"nome"/
Sempre que fizer alguma alteração nos arquivos é necessário rebuildar a aplicação.
  
cd /frontend
npm run build

URL WEBHOOK META:

```bash
https://api.seudominio.com.br/webhook/fb
```

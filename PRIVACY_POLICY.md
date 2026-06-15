Política de Privacidade — FAPP Monitor & E-mail (Dynamics)
Última atualização: 14 de junho de 2026

Esta extensão foi criada para apoiar o atendimento ao cliente (CX) na gestão e comunicação de ocorrências do Microsoft Dynamics 365. Esta política explica de forma clara e transparente quais dados a extensão acessa, como são tratados e reforça que nenhum dado sensível sai do seu navegador.

1. Princípio Geral de Privacidade
A extensão opera inteiramente dentro do seu navegador e da sua sessão já autenticada no Dynamics 365. Ela não coleta, não rastreia, não exibe anúncios e não envia nenhum dado para servidores externos, terceiros ou para o desenvolvedor.

2. Quais dados a extensão acessa
Utilizando a sua própria credencial de acesso, a extensão consulta via API oficial do Dynamics 365 apenas as informações necessárias para a sua rotina operacional:

Ocorrências (casos) abertas atribuídas a você: número do ticket, assunto, prazo de SLA, número do pedido e valor.

Dados de contato: Nome e e-mail do cliente vinculados à ocorrência, exclusivamente para preencher o destinatário das mensagens.

Comunicações: E-mails recebidos vinculados à ocorrência (assunto e snippet/resumo) para disparar notificações de novas mensagens.

Filas de envio: Acesso à fila configurada (ex: Suporte FAPP) para despachar o e-mail em seu nome.

Esses dados são buscados em tempo real e exibidos na interface da extensão. Eles não são transmitidos para fora do ecossistema do seu navegador e do Dynamics.

3. O que é armazenado localmente
Para garantir o funcionamento, a extensão salva dados apenas no armazenamento local do seu dispositivo (chrome.storage.local). Os únicos itens guardados são:

Suas configurações de interface (fila padrão, campos mapeados, templates de e-mail, logo e assinatura).

Os IDs das ocorrências que você fixou como prioridade (apenas o código identificador).

Suas observações pessoais ("notas") sobre cada caso.

Marcações de data/hora de "e-mail já visto" para controle do alerta sonoro e visual.

Nenhum endereço de e-mail completo ou conteúdo de mensagem do cliente é armazenado. Os dados são transitórios e descartados da memória ao fechar o painel.

4. Permissões Solicitadas e Justificativas
activeTab / scripting: Necessários para ler o contexto da ocorrência aberta e injetar o script que realiza o envio do e-mail diretamente da página do Dynamics.

storage: Necessário para salvar suas preferências e templates localmente.

alarms / notifications: Utilizados em conjunto para verificar periodicamente atualizações nos e-mails e emitir alertas (badge e push).

optional_host_permissions: Concedida sob demanda para domínios do Dynamics, permitindo o monitoramento em segundo plano sem que a extensão precise estar aberta.

5. Conformidade com a LGPD
A extensão foi arquitetada no modelo Privacy by Design. Todo o processamento de dados pessoais ocorre localmente e sob a base legal do acesso que o operador já possui no Dynamics 365. Para adicionar uma camada extra de proteção, a extensão dispõe de uma funcionalidade nativa para ocultar parcialmente o e-mail do cliente na tela.

6. Retenção e Exclusão de Dados
Os dados de configuração permanecem no seu navegador até que você decida removê-los. É possível apagar todas as informações instantaneamente através do botão "Restaurar padrão" na página de Configurações, ou simplesmente desinstalando a extensão.

7. Contato
Em caso de dúvidas sobre esta política de privacidade, tratamento de dados ou funcionamento da extensão, entre em contato:

Desenvolvedor: Alisson Rozendo Dos Santos

E-mail: alisson.rozendo1998@gmail.com

 # Connecta-Pinhais, Leandro Prado e Luiz Mariano
Atualizações do projeto: 
Atualmente o projeto é um protótipo funcional, e obteve uma mudança na intenção do programa
O mesmo deixou de ser o software connecta senior, e se tornou connecta pinhais, pois agora nossa missão não é somente integrar o pessoal com idade avançada, e sim a população de pinhais em geral
O sistema agora realiza separação de temas, tipos de letras e diferenças por faixa etária
Integrações de mapas, calendário, botões e agendamento funcionam totalmente, banco de dados simplificado local na web
Demais funções da versão web são funcionais, porém atualmente ainda não obtemos da prefeitura em si os dados, apenas conseguimos informar e mostrar prévias que inserimos manualmente 
A intenção do sistema ainda permanece como híbrida, sendo o programa instalado a partir do navegador,atualmente a única versão que funciona corretamente é a WEB
--------------------------------------------
Mocks e o que funciona:

*   **Interface Base**: Telas de Home, Atividades, Saúde, Chat e Perfil. OK
*   **Sistema de Notificações**: Gerenciador local de lembretes OK, porém somente com o site em aberto
*   **Geolocalização**: Estrutura preparada para exibição de mapas e rotas de atividades OK
** Tela de confirmação de consentimento de coleta de dados respeitando lgpd, simulando o que ocorreria junto a integração real com a prefeitura de pinhais
**Versão apk instalável via navegador ainda em desenvolvimento, não funciona corretamente, apresenta muitos erros de build e no momento foi removida do site funcional
** Separação por faixas etárias OK
** Diferenciação de temas tamanhos de fontes e contraste de acordo com a idade OK
** Sistema valida dados como CPF email e senha OK
** Sistema atualmente é seguro, apenas utiliza interface web do navegador para funcionar e mostrar informações postadas pelo pessoal da prefeitura de Pinhais, eventos parceiros dedicados também aparecem 
---



Ainda há funcionalidades importantes para serem finalizadas ou refinadas:

*   **Autenticação**: 
*   **Persistência de Dados**: Backend é simples e fica na máquina cliente, junto aos cookies
*   **Refinamento de UX**:
Sistema atualmente funciona com repositórios grátis encontrados na internet, para mapas e calendário, pode ocorrer alguns erros, mas a idéia é que mais a frente sejam adquiridas ferramentas mais precisas, assim como a aquisição de servidor para banco de dados e integrações e licenças para integração a autenticadores

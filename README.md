Flappy Pig

Protótipo Android em Kotlin e Jetpack Compose para um jogo inspirado em Flappy Bird.

## Organização

- `navigation/`: coordenação e destino das telas (MVVM-C).
- `features/game/domain/model/`: estado, fases e configuração do jogo.
- `features/game/domain/service/`: regras de movimento, pontuação e colisão.
- `features/game/presentation/`: ViewModel e tela Compose do jogo.
- `ui/theme/`: tema visual do aplicativo.

Cada tela nova deve ganhar sua própria pasta dentro de `features/`, com as camadas necessárias para aquela funcionalidade.

## Primeiro protótipo

Ao abrir, uma contagem regressiva de 3 segundos leva à tela pronta. Cada toque aplica um impulso para cima; entre os toques, a gravidade leva o personagem para baixo. Depois do primeiro toque, os policiais se deslocam da direita para a esquerda, com uma nota em posição aleatória no vão. A pontuação aumenta somente ao tocar na nota. Colidir com um policial ou chegar ao limite inferior encerra a partida; o botão de fim de jogo reinicia.

## Política de Privacidade

**Última atualização: 20 de outubro de 2026**

Esta política descreve como o aplicativo **Flappy Pig** trata informações durante o uso. O jogo é um projeto para Android e exibe um anúncio em banner na tela de fim de partida.

### Informações usadas pelo jogo

Os comandos, a pontuação e o estado da partida são processados no próprio dispositivo para permitir o funcionamento do jogo. O aplicativo não exige cadastro e não solicita diretamente nome, endereço de e-mail, telefone, contatos ou localização precisa. A pontuação da partida não é vinculada a um perfil e não é mantida pelo jogo depois que a sessão termina.

### Anúncios e serviços do Google

O aplicativo integra o SDK Google Mobile Ads para exibir anúncios. Esse SDK pode coletar e transmitir automaticamente informações necessárias à exibição, medição e personalização de anúncios, à análise de desempenho e à prevenção de fraude. Conforme a configuração do SDK e do dispositivo, essas informações podem incluir endereço IP (que pode ser usado para estimar localização aproximada), identificadores de publicidade ou do aplicativo/dispositivo, interações com o aplicativo e anúncios (como inicializações, toques e visualizações) e dados de diagnóstico e desempenho.

Essas informações são tratadas pelo Google de acordo com as políticas e configurações dos serviços de publicidade do Google. O tráfego do SDK é protegido por criptografia durante a transmissão, conforme a documentação do Google. Para mais detalhes, consulte a [Política de Privacidade do Google](https://policies.google.com/privacy) e a [divulgação de dados do Google Mobile Ads SDK](https://developers.google.com/admob/android/privacy/play-data-disclosure?hl=pt-br).

No código atual do projeto, estão configurados os identificadores de teste oficiais do Google para o aplicativo e o banner. Antes de uma publicação com anúncios reais, os identificadores, as configurações de consentimento e as declarações de segurança de dados da loja devem ser revisados para refletir a configuração efetivamente distribuída.

### Armazenamento e compartilhamento

O jogo não mantém um cadastro ou histórico de pontuação em um servidor próprio. Os dados técnicos relacionados à publicidade podem ser transmitidos ao Google pelo SDK, conforme descrito acima. Esta versão do aplicativo não possui outros serviços próprios de conta ou armazenamento remoto identificados.

### Suas opções e direitos

As opções disponíveis para limitar ou redefinir o identificador de publicidade dependem da versão do Android e podem ser encontradas nas configurações de privacidade ou anúncios do dispositivo. Você também pode consultar as opções e os canais de privacidade do Google nos links acima. Solicitações relacionadas a dados tratados diretamente pelo Google devem ser encaminhadas ao Google; para dúvidas sobre o aplicativo, use o contato informado ao final desta política.

Os direitos aplicáveis podem variar conforme o local onde você mora. Para exercer direitos ou esclarecer dúvidas sobre o tratamento relacionado ao aplicativo, entre em contato com o responsável indicado abaixo.

### Crianças

O aplicativo não solicita idade nem cria perfis de usuários. Se uma versão for direcionada a crianças ou distribuída como conteúdo para famílias, o responsável deverá revisar e ajustar as configurações de anúncios, consentimento e classificação etária antes da publicação.

### Alterações nesta política

Esta política pode ser atualizada quando o aplicativo, seus recursos ou os serviços integrados mudarem. A versão vigente será publicada neste README com a data da última atualização.

### Responsável e contato

- **Responsável pelo aplicativo:** Filipe Souza
- **Contato para assuntos de privacidade:** contatohabapps@gmail.com

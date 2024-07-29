# ⏰ Scrumdinger App
## ✨ Sobre
Scrumdinger é um aplicativo iOS que ajuda equipes a gerenciar as reuniões diárias. Para ajudar a manter os scrums curtos e focados, o Scrumdinger usa sinais visuais e sonoros para indicar quando e por quanto tempo cada participante deve falar. O aplicativo também exibe uma tela de progresso que mostra o tempo restante na reunião e cria uma transcrição que os usuários podem consultar posteriormente.

Com Scrumdinger você pode:

- Ver a lista de reuniões agendadas na tela principal;
- Criar novas reuniões: adicione todos os participantes a uma lista, configure a data e hora da reunião, escolha um tema para a reunião e veja o histórico da reunião;
- Editar a reunião: altere o título, duração, tema e participantes.

## ✨ Telas

| Meetings screen | Add a meeting screen |  Meeting details screen |
|:---------:|:---------:|:---------:|
| ![IMG_7924](https://github.com/user-attachments/assets/0cfc53b7-f6ce-4621-b510-2b7de87baa0d) | ![IMG_7934](https://github.com/user-attachments/assets/081ed4d9-7186-4762-b7ad-2173c26399b8) | ![IMG_7925](https://github.com/user-attachments/assets/d0b544f9-0a77-4e9a-862c-145c8fa8faf1) |

| Edit a meeting screen | Themes | Meeting screen |
|:---------:|:---------:|:---------:|
| ![IMG_7926](https://github.com/user-attachments/assets/e692c25e-fd86-4b8b-832e-4f256aa0b576) | ![IMG_7927](https://github.com/user-attachments/assets/2895ccf3-aef7-42a3-97d9-5f77d5e840fe) | ![IMG_7929](https://github.com/user-attachments/assets/9759e1bd-2d75-4f32-980f-6199e9ef1355) |


Aqui estão as principais telas da aplicação:

**Tela Principal (Meetings Screen)**: Nessa tela, você pode ver todas as reuniões programadas, incluindo detalhes como nome da reunião, número de participantes e o tempo programado, que será dividido igualmente entre todos os participantes.

**Tela de Adicionar Reunião**: Nessa tela, é possível adicionar uma nova reunião à lista de reuniões programadas.

**Tela de Detalhes da Reunião**: Mostra informações detalhadas sobre a reunião, incluindo participantes (attendees) e histórico da reunião.

**Tela de Edição de Reunião**: Permite a edição das informações da reunião e dos participantes.

**Temas**: Escolha entre 16 cores diferentes para representar visualmente sua reunião.

**Tela da Reunião**: Exibe a reunião em andamento, com um cronômetro e sinais sonoros.

## ✨ Funcionalidades
Sinais Visuais e Sonoros
Indicadores Visuais: O aplicativo exibe sinais visuais que indicam quem deve falar e por quanto tempo.
Alertas Sonoros: Alertas sonoros são usados para sinalizar a troca de oradores e para lembrar os participantes sobre o tempo restante.

Tela de Progresso
A tela de progresso mostra o tempo total restante da reunião e o tempo alocado para cada participante.
Facilita a visualização do andamento da reunião, ajudando a manter o foco e a pontualidade.

Transcrição
O aplicativo gera uma transcrição da reunião que pode ser consultada posteriormente.
As transcrições ajudam a registrar decisões, acompanhar ações e fornecer uma referência para futuras reuniões.

## ✨ Estrutura do Projeto
Para implementar o Scrumdinger, podemos seguir uma estrutura de projeto que inclui os seguintes componentes principais:

### Modelos
Scrum: Representa um scrum diário, contendo detalhes como título, participantes e duração.
Participant: Representa cada participante do scrum, incluindo nome e tempo de fala alocado.

### Visualizações
ProgressView: Exibe o tempo restante da reunião e o tempo de cada participante.
TranscriptionView: Exibe a transcrição da reunião.

### Controladores
ScrumViewController: Controla a lógica do scrum, gerenciando o tempo de fala e alternando entre os participantes.
ProgressViewController: Controla a atualização da tela de progresso.
TranscriptionViewController: Gerencia a exibição e o armazenamento da transcrição.

### Sinais Visuais e Sonoros
Visual Cues: Implementados como animações ou alterações de UI para indicar o orador atual.
Audio Cues: Implementados usando AVFoundation para tocar sons de alerta.

# SecretVideo

**Um player dedicado para assistir a vídeos de vários sites — e salvá-los quando você precisar.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, prevalece a [versão em coreano](README.ko.md).

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/secretvideo?lang=pt)

![Captura de tela do SecretVideo](images/secretvideo-en.webp)

## Visão geral

O SecretVideo é um player em estilo de navegador feito para sites de vídeo. Escolha um site na tela inicial e ele abre na hora; ao colocar um vídeo em tela cheia, ele vira uma pequena **janela PIP** para você continuar assistindo enquanto faz outra coisa.

Quando o vídeo que você está assistindo pode ser salvo, um **botão de download** aparece ao lado da barra de endereços. Um clique salva no formato e na qualidade que você escolheu — original, MP4 ou MP3. Sites que exigem login também funcionam: entre uma vez dentro do SecretVideo e a sessão é mantida.

O bloqueio de anúncios vem ligado, e `Ctrl+P` salva a página inteira que você está vendo como imagem.

## Recursos

- **Tela inicial de sites** — YouTube, Twitch, TikTok, CHZZK, Netflix, TVING, Wavve, Watcha, Coupang Play e outros em um só lugar. Adicione ou edite a lista como quiser.
- **Tela cheia → PIP automaticamente** — colocar um vídeo em tela cheia o transforma em uma pequena janela sempre no topo. Arraste para onde quiser e redimensione pelas bordas.
- **Botão de download que aparece só quando funciona** — ele desliza para a tela quando há um vídeo pronto para salvar. Não aparece em anúncios nem em transmissões ao vivo.
- **Formato e qualidade à sua escolha** — Original / MP4 / MP3, 720p / 1080p / Melhor qualidade.
- **Janela de lista de downloads** — miniaturas e progresso em um relance, com notificação do Windows ao concluir.
- **Amplo suporte a sites** — traz embutido um mecanismo de download muito usado (yt-dlp); em sites que ele não conhece, o SecretVideo encontra sozinho o arquivo em reprodução e o salva.
- **Continue logado** — faça login em um site dentro do SecretVideo e vídeos exclusivos para membros também podem ser assistidos e salvos.
- **Bloqueio de anúncios** — o uBlock Origin Lite vem embutido e pode ser ligado ou desligado pelo menu.
- **Captura de página inteira** — `Ctrl+P` salva a página completa, incluindo tudo abaixo da dobra, como PNG.
- **Lembra suas janelas** — posição/tamanho/estado maximizado da janela principal, posição e tamanho da janela PIP, posição da lista de downloads.

## Download / Instalação

| Pacote | Link |
|---|---|
| Instalador | [Baixar](https://down.kilho.net/secretvideo?lang=pt) |
| Portátil (ZIP) | [Baixar](https://down.kilho.net/secretvideo?lang=pt&nosetup) |

O SecretVideo pode ser usado como aplicativo portátil: descompacte em qualquer lugar e execute `SecretVideo.exe`.

**Na primeira execução** ele baixa os componentes necessários para salvar vídeos (mecanismo de download, conversor, bloqueador de anúncios). Aguarde a janela de progresso terminar. Isso acontece uma única vez; depois, só baixa de novo quando um componente mudou.

## Como usar

### Primeiros passos

1. Abra o SecretVideo. A **tela inicial de sites** aparece. Clique no site desejado.
2. Navegue pelo site e reproduza um vídeo como em qualquer navegador.
3. Se o vídeo puder ser salvo, um **botão de download** (↓) aparece à direita da barra de endereços. Clique nele e o salvamento começa na hora.
4. A janela **Lista de downloads** abre automaticamente e mostra o progresso. Ao terminar, aparece uma notificação do Windows; clique nela para abrir a pasta de destino.

A pasta de destino padrão é a pasta **Downloads** do seu PC. Altere em menu (⋮) → **Configurações de pasta**, ou abra com **Abrir pasta**.

### A janela

| Controle | O que faz |
|---|---|
| ◀ ▶ | Voltar / Avançar |
| ⟳ / ✕ | Recarregar (Parar enquanto uma página carrega) |
| Barra de endereços | Digite um endereço para ir até ele, ou palavras para pesquisar |
| ↓ | Botão de download — aparece só quando há um vídeo pronto para salvar |
| ⋮ | Menu |

O título da janela acompanha o título da página. Se um site tentar abrir uma nova janela, o SecretVideo a abre na janela atual.

### Como…

**Salvar um vídeo do YouTube como MP3**
Menu → **Configurações de formato → MP3** e clique no botão de download na página do vídeo. Só o áudio é baixado e convertido para MP3. A configuração de qualidade não afeta o MP3.

**Obter um arquivo que toque na TV ou em outros dispositivos**
Escolha **Configurações de formato → MP4**. Na mesma resolução, o SecretVideo prefere o formato H.264, amplamente compatível, então é menos provável que o arquivo não abra em um player básico ou na TV. **Original** salva o que o site fornece como está (unido em MP4 quando necessário).

**Economizar espaço, ou obter a melhor qualidade**
Em **Qualidade do download** escolha **720p**, **1080p** (padrão) ou **Melhor qualidade**. 720p e 1080p significam "até essa resolução": se ela não estiver disponível, usa-se a imediatamente abaixo.

**Downloads falham ou travam com frequência**
Experimente **Velocidade do download → Estável**. Ele baixa uma parte por vez, o que aguenta bem uma conexão instável. Se a sua conexão é rápida, **Rápido** (várias partes ao mesmo tempo) é bem mais veloz. O padrão é **Normal**.

**Vídeos exclusivos para membros que exigem login**
Faça login no site dentro do SecretVideo como faria normalmente. O login é mantido, então a partir daí os vídeos de membros tocam direto, e o botão de download aparece sempre que um vídeo puder ser salvo.

**Baixar uma playlist inteira**
Em uma página de playlist do YouTube, clique no botão de download para baixar a lista inteira, um vídeo após o outro. As listas **Mix / Rádio** geradas automaticamente são a exceção: só o vídeo que você está assistindo é baixado.

**Sites em que você rola de vídeo em vídeo (TikTok e similares)**
O SecretVideo percebe qual vídeo está tocando mesmo quando o endereço da página não muda, então basta rolar até o que você gosta e clicar no botão de download.

**Sites de streaming como CHZZK e Twitch**
VODs e clipes podem ser salvos. **Transmissões ao vivo não podem ser salvas**, e o botão de download não aparece nelas.

**Continuar assistindo enquanto trabalha (PIP)**
Coloque um vídeo em **tela cheia** e o SecretVideo vira automaticamente uma pequena janela PIP sempre no topo.
- **Arraste** a janela para movê-la.
- Segure uma **borda** para redimensionar.
- Menu do **botão direito**: Voltar à janela normal / Sempre no topo ligado ou desligado / Sair.
- Quando o site sai da tela cheia, a janela volta ao tamanho e à posição anteriores.
- A posição e o tamanho da janela PIP são lembrados para a próxima vez.
- Se não quiser isso, desligue Menu → **Ativar PIP ao entrar em tela cheia**. A tela cheia então usa o monitor inteiro, como em um navegador comum.

**Guardar uma página inteira como imagem**
Pressione `Ctrl+P`. A **página inteira** — não só a parte visível, mas tudo abaixo da dobra — é salva na pasta de destino como `SecretVideo-001.png` e uma notificação aparece. Útil para guardar postagens, comentários ou telas com legendas.

**Anúncios atrapalham / um site falha por causa do bloqueio de anúncios**
O bloqueio de anúncios (uBlock Origin Lite) vem ligado. Se um site específico não funcionar direito, desligue-o por um tempo em Menu → **Extensões**.

**Gerenciar arquivos baixados (janela Lista de downloads)**
Abra a qualquer momento em Menu → **Lista de downloads**. Cada linha mostra miniatura, título, origem e status (Ocioso → Análise → Recebendo → Convertendo → Concluído), e o fundo da linha mostra o progresso.
- **Clique duplo**: abrir o arquivo baixado
- **Tecla Delete**: remover da lista
- **Botão direito**: Ir à origem / Abrir pasta / Ver log / Excluir
- Fechar a janela ou pressionar `ESC` apenas a oculta; os downloads continuam.

**Baixar o mesmo vídeo duas vezes**
Se já existir um arquivo com o mesmo nome, ele não é sobrescrito; um número como `(1)`, `(2)` é adicionado.

**Editar a tela inicial de sites**
Use **Edit** na tela inicial para adicionar ou remover sites, e **Reset** para restaurar a lista padrão. Manter só os sites que você realmente usa deixa o início mais rápido.

### Aviso sobre direitos autorais

O SecretVideo é uma ferramenta para assistir e guardar, para uso pessoal, vídeos que você tem o direito de usar. Respeite os termos de serviço e os direitos autorais de cada site.

## Configuração

Não há uma janela de configurações separada; tudo é alterado pelo menu (⋮) e salvo automaticamente.

| Menu | O que define | Padrão |
|---|---|---|
| Configurações de pasta / Abrir pasta | Onde os arquivos são salvos | Pasta Downloads |
| Configurações de formato | Original / MP4 / MP3 | Original |
| Velocidade do download | Estável / Normal / Rápido | Normal |
| Qualidade do download | 720p / 1080p / Melhor qualidade | 1080p |
| Lista de downloads | Mostrar ou ocultar a janela da lista | Abre sozinha ao iniciar um download |
| Ativar PIP ao entrar em tela cheia | Transformar a tela cheia em janela PIP | Ligado |
| Extensões | Bloqueio de anúncios ligado ou desligado | Ligado |

O idioma da interface segue o idioma de exibição do Windows (coreano → coreano, qualquer outro → inglês).

## Requisitos

- Windows 10 ou Windows 11, **64 bits**
- Microsoft Edge WebView2 Runtime (já presente no Windows 11 e no Windows 10 recente; o instalador o adiciona se estiver faltando)
- Conexão com a Internet (download de componentes na primeira execução, assistir e salvar vídeos)

## Atualizações

O SecretVideo **não** se atualiza sozinho. Novas versões são publicadas manualmente após verificação interna e anunciadas na [página do SecretVideo](https://kilho.net/secretvideo). Veja o [aviso sobre a política de atualizações](https://en.kilho.net/archives/notice/2940).

## Licença

O SecretVideo é **Freeware**.

Você pode usá-lo em qualquer lugar — em casa, no escritório, em escolas e em órgãos públicos — e redistribuí-lo livremente em sua forma não modificada.

## Links

- Site: <https://kilho.net/secretvideo>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET

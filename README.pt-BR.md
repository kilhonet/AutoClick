# AutoClick

**Um clicador automático gratuito para Windows que clica por você no ponto e no intervalo que você escolher — e que pode memorizar uma sequência de pontos para clicar um após o outro.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/autoclick?lang=pt)

![Tela do AutoClick](images/autoclick-en.webp)

> A interface do programa não tem tradução para português; ela é exibida em inglês. Os nomes de botões e opções abaixo aparecem como na tela.

## Visão geral

Algumas tarefas exigem clicar no mesmo botão dezenas ou centenas de vezes. O AutoClick faz esses cliques por você.

Escolha o botão a pressionar (esquerdo, direito ou roda), se o clique é simples ou duplo e com que frequência clicar, e pressione o atalho (**F3** por padrão) para começar. Pressione o mesmo atalho de novo para parar. O atalho funciona mesmo quando você está olhando outro programa, então a janela do AutoClick não precisa ficar na frente.

Se for preciso clicar em vários pontos, um de cada vez, e não em um só, use o **Record**. Coloque o mouse sobre um ponto e pressione o atalho (**F4** por padrão): essa posição entra na lista, uma linha por vez. Marque **Use Record** e execute, e o AutoClick clica nos pontos na ordem da lista.

## Principais recursos

- **Cliques automáticos** — pressiona repetidamente o botão esquerdo, o direito ou a roda, com clique simples ou duplo.
- **Faixa de intervalo** — clique em intervalo fixo, como a cada segundo, ou em um intervalo diferente a cada vez, por exemplo entre 1 e 3 segundos. Ajuste em centésimos de segundo.
- **Atalhos globais** — inicie e pare com uma tecla, mesmo com outro programa na frente. Troque as teclas pela combinação que preferir.
- **Record** — monte um padrão que clica em várias posições em ordem, com botão, tipo de clique e intervalo próprios para cada uma.
- **Salvar padrões** — salve a lista em um arquivo e abra quando precisar. A última lista volta como estava na próxima vez que o programa for aberto.
- **Número de repetições** — para sozinho depois de um número definido de cliques. Deixe o campo vazio para continuar clicando até você parar.
- **Manter o cursor** — depois de clicar no ponto escolhido, devolve o cursor do mouse para onde estava.
- **Avisos** — uma notificação do Windows avisa quando os cliques começam e param. O aviso de início também mostra o atalho para parar.
- **Modo escuro** — segue o modo de aplicativo do Windows (claro ou escuro).
- **8 idiomas** — coreano · inglês · japonês · chinês · russo · italiano · francês · espanhol.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Baixar](https://down.kilho.net/autoclick?lang=pt) |
| Portátil (ZIP) | [Baixar](https://down.kilho.net/autoclick?lang=pt&nosetup) |

O instalador abre o AutoClick assim que a instalação termina. Na versão portátil, descompacte o ZIP e execute `AutoClick.exe`. As duas versões têm os mesmos recursos.

## Como usar

### Primeiros passos

1. Abra o AutoClick.
2. Em **Mouse settings**, escolha o botão a pressionar (**Mouse**), se o clique é simples ou duplo (**Click**) e o intervalo entre cliques (**Delay**). No início, ele está ajustado para pressionar o botão esquerdo uma vez por segundo.
3. Coloque o cursor do mouse sobre o ponto a clicar.
4. Pressione **F3**. A barra de status embaixo muda para **Running** e o AutoClick começa a clicar nesse ponto no intervalo definido.
5. Quando terminar, pressione **F3** de novo. A barra de status volta para **Waiting**.

### Organização da tela

| Elemento | Função |
|---|---|
| **Home** · **Test** · **Donate** | Menu superior. **Test** abre uma página de teste do mouse para experimentar os cliques |
| Logotipo KILHO.net | Abre a página do AutoClick |
| **Mouse settings** | **Mouse** (Left · Right · Wheel) · **Click** (Single · Double) · **Delay** (intervalo entre cliques; os dois campos formam uma faixa) |
| **Hotkey settings** | **Run/Stop** (F3 por padrão) · **Add Record** (F4 por padrão) |
| **Other setting** | **Repeat** · **Position** (Hold · Modify) · **Use notice** (On · Off) |
| Lista **Record** | As posições a clicar, em ordem. Colunas: **Position** · **Mouse** · **Click** · **Delay** |
| **Use Record** | Marcado, a execução clica na lista em ordem |
| **Clear** · **Open** · **Save** | Limpa toda a lista / abre uma lista salva / salva a lista em um arquivo |
| Barra de status | **Waiting** ou **Running** |

### O que fazer quando…

**Clicar sempre no mesmo ponto**
Coloque o cursor no ponto e pressione **F3**: o AutoClick clica sem parar no ponto onde o cursor estava ao começar. Com **Position** em **Hold**, ele devolve o cursor para onde estava depois de cada clique, então você pode mover o mouse para outro lugar enquanto isso e o ponto clicado não muda.

**Clicar onde o cursor estiver**
Coloque **Position** em **Modify** e o AutoClick clica onde o cursor estiver no momento de cada clique, e não no ponto em que começou. É prático quando você quer mover o mouse durante a execução para mudar o que é clicado.

**Variar um pouco o intervalo a cada vez**
Digite uma faixa nos dois campos de **Delay**. Por exemplo, `00:01.00` e `00:03.00` clicam com um intervalo diferente entre 1 e 3 segundos a cada vez. Se os dois campos forem iguais, o intervalo é sempre o mesmo. Os campos têm a forma `minutos:segundos.centésimos`, então basta digitar os números em ordem para que caiam no lugar certo; o valor mais longo é 99 minutos e 59,99 segundos.

**Preciso preencher os dois campos?**
Ao mudar o primeiro campo e passar para outro, o segundo acompanha o primeiro. Depois que você mesmo edita o segundo campo, o AutoClick mantém esse valor; para definir uma faixa, preencha primeiro o primeiro campo e depois o segundo. Se o segundo for menor que o primeiro, ele sobe até igualar o primeiro.

**Clicar um número fixo de vezes e parar**
Digite um número em **Repeat**. O AutoClick para sozinho depois desse número de cliques e, se **Use notice** estiver ligado, mostra o aviso "The run finished after the repeat count was reached." enquanto o AutoClick pisca na barra de tarefas. Deixe o campo vazio (com **none** em cinza) para continuar clicando até você parar. Um clique duplo conta como um.

**Clicar em vários pontos, um de cada vez (Record)**
1. Escolha o botão, o clique e o delay em **Mouse settings**.
2. Coloque o cursor no primeiro ponto e pressione **F4**. Uma linha com essa posição e o botão, clique e delay escolhidos entra na lista **Record**.
3. Pressione **F4** do mesmo jeito em cada ponto seguinte. Para usar outro botão ou delay em uma linha, mude **Mouse settings** antes de pressionar **F4**.
4. Marque **Use Record** e pressione **F3**. O AutoClick clica da primeira linha para baixo e, depois da última, volta para a primeira. A linha sendo clicada fica destacada na lista.

O **Delay** de cada linha é o tempo que o AutoClick espera depois de clicar naquele ponto antes de passar para a linha seguinte.

**Reordenar linhas ou apagar só uma**
Clique com o botão direito em uma linha da lista para ver **Move Up** · **Move Down** · **Delete**. Para limpar a lista inteira, clique em **Clear** e depois em **Sim** na confirmação. A lista não pode ser alterada durante a execução; pare primeiro.

**Ter vários padrões e escolher um**
Use **Save** para guardar a lista atual em um arquivo e **Open** para carregá-la quando precisar. Um arquivo por tarefa é prático. Mesmo sem salvar, a lista que estava aberta ao fechar o AutoClick volta na próxima vez. Arquivos de registro salvos por versões anteriores abrem como estão.

**Ler os delays da lista**
Um intervalo único aparece como `00:01.00` e uma faixa como `01:01.00~05:03.00`, na mesma forma dos campos de entrada. Se uma faixa longa parecer cortada, passe o mouse sobre ela ou arraste a divisa entre os títulos das colunas para alargar a coluna.

**Trocar um atalho**
Clique em um campo de **Hotkey settings** e ele muda para "Press a key". Pressione a tecla desejada, ou uma combinação com **Ctrl** · **Alt** · **Shift** (por exemplo **Ctrl+Shift+F3**), e ela é trocada e salva na hora. Pressione **Esc** no campo para deixar esse atalho vazio (**None**). Escolha uma tecla que seus jogos ou outros programas não usem.

**Quando um atalho coincide com o de outro programa**
Se outro programa já usa a mesma tecla, o AutoClick avisa. Troque de tecla ou feche aquele programa; depois que ele for fechado, abrir o AutoClick de novo reativa a sua tecla original. Se você colocar a mesma tecla nos dois atalhos, o AutoClick avisa que ela já é usada pela outra função e não a aceita.

**Se você não precisa dos avisos**
Coloque **Use notice** em **Off** e o AutoClick não mostra avisos de início, parada ou de repetições concluídas. Ligado, o aviso de início lembra como parar, por exemplo "Press the same shortcut again to stop (F3)" — útil se você esquecer o atalho.

**Pressionar o botão da roda**
Escolher **Wheel** em **Mouse** pressiona o botão da roda (botão do meio) em vez de rolar. Use onde o botão do meio tem alguma ação, como abrir um link em uma nova aba do navegador.

**Testar antes de começar**
Clique em **Test** no alto para abrir no navegador uma página de teste do mouse que conta os cliques e cliques duplos dos botões esquerdo, roda e direito. Assim você pode mudar o botão, o clique e o delay e conferir antes se os cliques saem como quer.

**Mudar as configurações durante a execução**
Durante a execução, os campos ficam bloqueados para nada mudar por engano. Pare com **F3**, faça as mudanças e pressione **F3** de novo.

**Abrir de novo quando já está aberto**
Só uma cópia do AutoClick roda por vez. Abrir de novo não cria outra: a janela que já está aberta vem para a frente. O título da janela mostra a versão atual.

## Configuração

Não há uma janela de configurações separada. Os atalhos, **Position** e **Use notice** são lembrados assim que você os muda, e a lista é salva ao fechar o AutoClick e volta na próxima vez. O AutoClick segue sozinho o seguinte:

| Item | Segue |
|---|---|
| Idioma | As configurações regionais do Windows (inglês se o idioma não for suportado) |
| Cores | O modo de aplicativo do Windows (claro ou escuro) — a mudança vale na hora com o AutoClick aberto |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Não precisa de permissão de administrador.
- Nenhum outro componente precisa ser instalado.
- A conexão com a internet é usada só para avisos de nova versão. Todos os recursos funcionam sem conexão.

## Atualizações

O AutoClick **não** se atualiza sozinho. Ao iniciar, ele verifica se há uma nova versão e mostra um aviso; clicar em **[Sim]** abre a página de download e fecha o programa. Novas versões são lançadas manualmente após verificação interna e anunciadas na [página do AutoClick](https://kilho.net/autoclick). Consulte o [aviso sobre a política de atualizações](https://en.kilho.net/archives/notice/2940).

## Licença

O AutoClick é **freeware**. Use de graça e sem restrições em qualquer lugar — no trabalho, em casa, em órgãos públicos ou na escola — e redistribua livremente.

## Links

- Site: <https://kilho.net/autoclick>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET

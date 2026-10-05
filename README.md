<div align="center">

<p><img src="oracle-logo-combinada.svg" alt="Logo do Oracle" width="320" /></p>

**Pesquise, abra e resolva tarefas do Windows em uma única janela.**

Launcher para Windows com busca rápida, ferramentas do dia a dia e recursos para League of Legends.

[⬇️ Baixar a versão mais recente](https://github.com/mathwegner/Oracle/releases) · [Ver todas as versões](https://github.com/mathwegner/Oracle/releases)

![Windows 10 e 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows&logoColor=white)
[![Versão e canal](https://img.shields.io/github/v/release/mathwegner/Oracle?include_prereleases&label=vers%C3%A3o%20%2F%20canal)](https://github.com/mathwegner/Oracle/releases)

</div>

---

## O que é o Oracle?

O Oracle é um launcher inteligente para Windows. Abra a pesquisa, digite o que precisa e acesse aplicativos, cálculos, conversões, traduções, respostas de IA e ferramentas de League of Legends sem navegar por vários menus.

O canal de lançamento aparece junto da versão acima: tags com `-beta` indicam uma versão de pré-lançamento; sem esse sufixo, indicam uma versão estável. Recursos e integrações online podem mudar conforme os serviços externos atualizam seus sites e dados.

## Recursos

### Pesquisa e produtividade

- Encontre e abra aplicativos instalados, com busca por nomes, iniciais e pequenos erros de digitação.
- Faça cálculos com números ou expressões escritas em palavras.
- Converta moedas tradicionais e criptomoedas.
- Traduza palavras e frases e escolha o idioma de destino.
- Consulte a web quando precisar de informações atuais.
- Digite `clima Biguaçu` para ver temperatura atual, previsão de oito dias e gráficos por hora, sem escrever `web`. Use também cidade e estado, como `clima Santa Maria RS` ou `clima Santa Maria, Rio Grande do Sul`.
- Digite `yt` e pressione Enter para abrir o YouTube no navegador padrão.
- Ajuste tema, idioma, transparência, atalhos e posição da janela.
- A janela se ajusta ao conteúdo; ao redimensioná-la manualmente, o Oracle respeita o espaço escolhido.

### Chat IA local

- Converse com um assistente local para perguntas gerais, planejamento e ajuda com programação e projetos.
- Envie anexos compatíveis, incluindo imagens, vídeos e arquivos de texto.
- Use Enter para enviar ou o botão de envio; Shift+Enter cria uma nova linha.
- Continue uma resposta inicial em uma conversa com histórico, mensagens em cartões e emojis coloridos disponíveis offline.
- O Oracle usa o Ollama e um modelo local. Na configuração inicial, pode ser necessário baixar componentes e o modelo; essa etapa requer internet e espaço em disco.
- As respostas são geradas pelo modelo instalado no computador. A qualidade, a velocidade e os formatos que ele consegue analisar dependem do modelo e do hardware disponíveis.

### League of Legends

- **Duo Bot:** combina o catálogo do projeto com dados de sinergia da OP.GG, mostra tiers e estatísticas e permite percorrer a lista sem pesquisar cada dupla. Os dados da OP.GG têm uma amostra mínima; combinações incluídas no catálogo do projeto são preservadas.
- **Counter Pick:** consulta confrontos por rota, inclusive quando há poucas partidas na amostra.
- **Runas:** abre as recomendações do campeão e da rota no League of Graphs.
- **Perfil do jogador:** aceita Riot ID com `#` e busca nomes compatíveis quando você informa somente o nick.
- Retratos dos campeões atuais ficam incluídos no aplicativo; fontes online ajudam a atualizar dados e imagens.
- As sugestões de LoL aparecem por padrão quando uma instalação do jogo é detectada. Mesmo sem o jogo, você pode ativá-las em **Opções**; suas escolhas ficam salvas.

### Windows

- Escolha o alinhamento centralizado ou à esquerda para os ícones da barra de tarefas, conforme o suporte da versão do Windows.
- Acesse atalhos para desligar, reiniciar e abrir as Configurações do Windows.
- Configure a tecla Windows para abrir ou ocultar o Oracle, mantendo combinações como `Win + R` e `Win + E` disponíveis.
- Ajuste opções compatíveis da barra de tarefas. Algumas delas dependem da versão do Windows e de componentes externos como Windhawk ou TaskbarX.
- Capture a tela pelas opções do Oracle.
- Ao iniciar com o Windows, o Oracle fica em segundo plano na área de notificação. Clique no ícone para abrir a janela; a posição em Ícones ocultos segue sua preferência no Windows.
- Use **Restaurar barra de tarefas padrão** para desfazer as ocultações do Oracle e recuperar o alinhamento anterior preservado do Windows.

## Instalação

1. Abra a página de [releases](https://github.com/mathwegner/Oracle/releases).
2. Baixe **Oracle.exe**, o executável para Windows x64 anexado à versão mais recente.
3. Abra o arquivo baixado para iniciar o Oracle.

O Oracle é distribuído como um executável independente. A IA local e algumas consultas online podem baixar dados adicionais na primeira utilização.

## Atualizações

Use **Verificar atualizações** na seção **Sobre** do Oracle. O aplicativo consulta as releases deste repositório e pode baixar e aplicar uma versão mais recente.

As atualizações passam a manter o nome **Oracle.exe** e a ajustar os atalhos correspondentes da área de trabalho para **Oracle**, preservando suas preferências.

Também é possível baixar manualmente a versão atual pela página de [releases](https://github.com/mathwegner/Oracle/releases).

## Novidades da versão 0.1.60-beta

- **Clima com estado:** informe a sigla ou o nome do estado para distinguir cidades com o mesmo nome, como `clima Santa Maria RS`.
- **Atualização com nome fixo:** o executável e os atalhos correspondentes passam a usar Oracle, sem a versão no nome.
- **Início discreto:** com a inicialização automática ativada, o aplicativo permanece em segundo plano, sem abrir a janela.
- Consulte [todas as melhorias e correções desta versão](https://github.com/mathwegner/Oracle/releases/tag/v0.1.60-beta).

## Exemplos de pesquisa

Digite estes comandos na busca do Oracle:

| Para fazer | Exemplo |
|---|---|
| Abrir um aplicativo | `chrome` |
| Calcular | `30 + 2` ou `trinta mais dois` |
| Consultar duos | `duo bot` ou `duo bot tier S` |
| Ver confronto por rota | `counter pick Ahri meio` |
| Ver runas | `runas Yasuo` |
| Buscar um perfil | `lol perfil Nome#TAG` ou `lol perfil Nome` |
| Conversar com a IA | `chat como faço para organizar meu projeto?` |
| Pesquisar na web | `web notícias de tecnologia` |
| Consultar o clima | `clima Biguaçu SC`, `clima Santa Maria RS` ou `clima Santa Maria, Rio Grande do Sul` |
| Abrir o YouTube | `yt` + Enter |
| Traduzir | `traduzir good morning para português` |

Os nomes dos comandos podem variar conforme o idioma selecionado e a versão do aplicativo.

## Dados e serviços externos

O Oracle usa serviços externos para recursos online. Entre as fontes utilizadas estão OP.GG, League of Graphs, Riot Data Dragon e [Open-Meteo](https://open-meteo.com/), com geocodificação baseada no GeoNames. A disponibilidade e a atualização dos dados dependem desses serviços. O Chat IA local usa o Ollama e o modelo instalado no computador; consultas explicitamente feitas à web podem enviar o texto de pesquisa ao serviço de busca correspondente.

League of Legends e os nomes, ícones e recursos relacionados são marcas e propriedades de seus respectivos titulares. O Oracle é um projeto independente e não é afiliado à Riot Games.

Emojis coloridos: [Twemoji](https://github.com/jdecked/twemoji), de Twitter e colaboradores, sob a licença [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). As imagens ficam incluídas no aplicativo para uso offline.

## Ajuda e contato

Encontrou um erro ou quer sugerir uma melhoria? Abra uma [issue](https://github.com/mathwegner/Oracle/issues) informando a versão do Oracle, sua versão do Windows e os passos para reproduzir o problema. Se possível, anexe uma captura de tela sem dados pessoais.

## Apoie o projeto

Se o Oracle é útil para você, sua contribuição ajuda a manter o projeto e dar continuidade ao desenvolvimento.

Leia o QR Code abaixo com o aplicativo do seu banco para fazer uma doação via Pix:

<p align="center"><img src="pix-donation-qr.png" alt="QR Code Pix para apoiar o projeto Oracle" width="280" /></p>





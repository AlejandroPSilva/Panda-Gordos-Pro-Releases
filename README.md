<div align="center">

  <img src="assets/pandas-gordos-pro-panda.png" width="180" alt="Panda do Pandas Gordos PRO segurando uma picareta">

  # Pandas Gordos PRO

  **Seu mundo Minecraft, organizado em um único aplicativo.**

  Um espaço criado para explorar mundos, planejar construções, organizar mods e reunir ferramentas úteis para Minecraft Java e Bedrock.

  [![Plataforma](https://img.shields.io/badge/plataforma-Windows-111111?style=for-the-badge)](#disponibilidade)
  [![Estado](https://img.shields.io/badge/estado-em%20desenvolvimento-218a43?style=for-the-badge)](#disponibilidade)
  [![Criador](https://img.shields.io/badge/criador-AlejandroPSilva-111111?style=for-the-badge)](https://github.com/AlejandroPSilva)

</div>

---

## Conheça o aplicativo

O **Pandas Gordos PRO** é uma bancada de ferramentas para Minecraft. A proposta é reduzir a quantidade de páginas, arquivos e utilitários separados necessários durante uma aventura ou projeto, mantendo tudo em uma experiência visual consistente.

### PandaMap

Explore seeds, biomas e estruturas em um mapa interativo. Navegue entre Overworld, Nether e The End, use coordenadas, filtros, waypoints e ferramentas de planejamento para conhecer melhor cada mundo.

O mapa oferece navegação contínua, cache progressivo, perfis de desempenho e carregamento automático ao trocar de dimensão. O The End diferencia ilhas e void e destaca a arena central; no Nether, fortalezas, portais e variantes reais de bastiões recebem marcadores próprios, incluindo sala do tesouro, ponte, estábulos e unidades habitacionais.

### PandaSync

Analise uma pasta de mods, identifique versões, loaders e dependências e acompanhe atualizações compatíveis. O fluxo foi pensado para deixar cada alteração clara antes de substituir um arquivo.

Há suporte para Fabric, Forge, NeoForge e Quilt, comparação por versão do Minecraft, acompanhamento da pasta, vínculos manuais para projetos não reconhecidos, backups e restauração de atualizações.

### Panda AI

Um assistente contextual para dúvidas, planejamento, comandos, construções e análise de informações do Minecraft. Cada usuário conecta sua própria chave compatível quando desejar utilizar o recurso.

O assistente aceita conversas com streaming, imagens e arquivos de diagnóstico higienizados, possui modos especializados e prepara ações para outras ferramentas do aplicativo antes de qualquer alteração confirmada pelo usuário.

### Ferramentas da bancada

| Área | O que oferece |
|---|---|
| **Projetos** | Materiais, etapas, comandos e planejamento de construções. |
| **Calculadoras** | Coordenadas, dimensões, stacks, ticks, experiência e recursos. |
| **Comandos** | Criação, visualização e organização de comandos Minecraft. |
| **Geometria** | Formas, medidas, camadas e visualização de construções bloco a bloco. |
| **Waypoints** | Bases, portais, farms e outros locais importantes. |
| **Servidores** | Consulta organizada de servidores Java e Bedrock. |

## Experiência atual

- interface responsiva com modo claro e escuro;
- densidade e escala ajustáveis para diferentes telas;
- navegação lateral fixa ou flutuante;
- transições reduzidas quando o sistema solicita menos movimento;
- integração opcional com Discord Rich Presence;
- atualização do aplicativo preparada para publicações oficiais futuras;
- armazenamento protegido para credenciais configuradas pelo usuário.

## Tecnologia

O aplicativo combina uma interface moderna com recursos nativos de desktop:

- **Tauri 2** e **Rust** para a aplicação desktop e operações locais;
- **React 18** e **TypeScript** para a interface;
- **Vite** para desenvolvimento e empacotamento;
- **CSS responsivo** com identidade visual própria, temas claro e escuro;
- **Cubiomes** integrado ao backend nativo para geração Java utilizada pelo PandaMap;
- integração com serviços públicos utilizados pelas ferramentas, quando habilitados pelo usuário.

## Disponibilidade

> **Os downloads ainda não foram publicados.**

Este repositório está sendo preparado como o canal oficial de distribuição. Quando uma versão pública estiver pronta, ela aparecerá na página **[Releases](https://github.com/AlejandroPSilva/Panda-Gordos-Pro-Releases/releases)** com instalador, notas da versão e informações de integridade.

Nenhum instalador publicado fora deste repositório deve ser considerado uma distribuição oficial.

## Segurança das futuras versões

As publicações poderão incluir:

- instalador oficial para Windows;
- notas com as mudanças da versão;
- checksum SHA-256 para conferência;
- assinatura usada pelo atualizador do aplicativo;
- arquivo de atualização compatível com o Tauri.

Credenciais, chaves privadas, configurações pessoais e código interno não fazem parte deste repositório de distribuição.

## Criador

Criado e desenvolvido por **[AlejandroPSilva](https://github.com/AlejandroPSilva)**.

O Pandas Gordos PRO nasceu como uma bancada pessoal para Minecraft e está evoluindo para uma experiência completa, acessível e fácil de usar.

---

<div align="center">
  <strong>Pandas Gordos PRO</strong><br>
  Planeje. Explore. Construa.
</div>

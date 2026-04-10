

<p align="center">
  <strong>Lumma Overlay de filtros e controle de monitor dentro de jogos — sem precisar alt-tab.</strong>
</p>
            <div align="center" style="display:flex; justify-content:center; gap:10px; flex-wrap:wrap;">
  <img src="https://github.com/user-attachments/assets/5f57cb66-32b0-4db0-a4d1-6be7aa724dc9" width="280"/>
  <img src="https://github.com/user-attachments/assets/30301845-d516-43aa-8270-2ed6b931ff66" width="280"/>
  <img src="https://github.com/user-attachments/assets/6b606d5c-145b-4bab-9e80-4684fdd994ae" width="280"/>
  <img src="https://github.com/user-attachments/assets/701c2019-1a92-49e6-b923-34863f0b6004" width="280"/>
</div>

<p align="center">
  <a href="https://github.com/Bob3111/lumma-overlay/releases/latest">
    <img src="https://img.shields.io/github/v/release/Bob3111/lumma-overlay?label=versao&color=00D4FF" alt="Versao">
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey" alt="Plataforma">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white" alt="Windows">
</p>

<p align="center">
  <strong>Controle brilho, contraste, gama, temperatura de cor e mais — direto de dentro de qualquer jogo.</strong>
</p>

---

## O que é o Lumma Overlay?

O Lumma Overlay é uma sobreposição leve e transparente que fica por cima dos seus jogos e permite ajustar as configurações do monitor em tempo real — **sem nunca sair do jogo**.

Feito para gamers que querem ajustar a tela na hora, seja escurecendo uma cena de terror, aumentando o contraste em jogos competitivos ou ajustando a temperatura de cor para sessões noturnas.

---

## Recursos

| Recurso | Descrição |
|---------|-----------|
| Controle do Monitor em Tempo Real | Ajuste brilho, contraste, gama, temperatura de cor, saturação e mais via DDC/CI |
| Detecção Automática de Jogos | Detecta automaticamente quando você entra/sai de jogos em tela cheia |
| Contador de FPS | FPS em tempo real usando Intel PresentMon via ETW |
| Perfis por Jogo | Salve configurações por jogo e carregue automaticamente |
| Suporte a Controle Xbox | Navegação completa pelo D-Pad — sem teclado |
| Presets Rápidos | Presets de brilho/contraste com um clique para cenários comuns |
| Modo Compacto | Overlay minimal que não atrapalha a jogatina |
| Início com o Windows | Inicia automaticamente junto com o sistema |
| Menu na Bandeja | Controle total pelo ícone na área de notificação |
| Verificador de Atualizações | Verifica automaticamente por novas versões |

---

## Controles pelo Teclado

| Atalho | Ação |
|--------|------|
| `Ctrl + Shift + O` | Mostrar/esconder overlay |
| `Ctrl + Shift + Cima` | Brilho +5% |
| `Ctrl + Shift + Baixo` | Brilho -5% |
| `Ctrl + Shift + Direita` | Contraste +5% |
| `Ctrl + Shift + Esquerda` | Contraste -5% |
| `Ctrl + Shift + R` | Restaurar padrão |
| `Ctrl + Shift + P` | Trocar perfil |

---

## Controle Xbox

| Botão | Ação |
|-------|------|
| **View + Select** (segurar) | Abrir/fechar modo controle |
| **D-Pad Cima** | Mover seleção para cima |
| **D-Pad Baixo** | Mover seleção para baixo |
| **D-Pad Esquerda** | Diminuir valor selecionado |
| **D-Pad Direita** | Aumentar valor selecionado |

> O overlay detecta automaticamente quando você está em um jogo e muda para o modo controle sem interrupção.

---

## Instalação

1. **Baixe** o instalador mais recente na página de [Releases](https://github.com/Bob3111/lumma-overlay/releases/latest)
2. **Execute** `Lumma_Overlay_Setup_1.1.0.exe` como Administrador
3. **Siga** o assistente de instalação
4. **Abra** pelo atalho na Área de Trabalho ou Menu Iniciar

> O app precisa de privilégios de Administrador para se comunicar com monitores via DDC/CI e capturar dados de FPS.

---

## Configurações e Opções

### Opções de Interface
- **Modo Compacto** — Reduz o tamanho do overlay para cobertura mínima na tela
- **Mostrar Presets Rápidos** — Ativa/desativa a barra de presets
- **Mostrar Seção de Perfis** — Ativa/desativa o seletor de perfis
- **Transparência** — Ajuste a opacidade do overlay de 35% a 100%

### Perfis
- Crie perfis personalizados para diferentes jogos ou cenários
- Carregamento automático quando um jogo específico é detectado
- Exporte e compartilhe perfis com outros usuários

### Seleção de Monitor
- Selecione qual monitor controlar (suporte a múltiplos monitores)
- Aplique configurações globalmente ou por monitor

### Início com o Windows
- Ative/desative "Iniciar com o Windows" pelo menu na bandeja ou Configurações > Sobre
- Roda silenciosamente em segundo plano, pronto quando você precisar

---

## Requisitos

| Requisito | Detalhes |
|-----------|----------|
| **SO** | Windows 10 ou Windows 11 |
| **Monitor** | Compatível com DDC/CI (a maioria dos monitores modernos) |
| **Modo do Jogo** | Janela sem borda recomendado para visibilidade do overlay |
| **Permissões** | Administrador (necessário para DDC/CI e monitoramento de FPS) |

> O DDC/CI precisa estar ativado nas configurações OSD do seu monitor. A maioria dos monitores já vem com isso ativado por padrão.

---

## Changelog

🚀 v1.1.1 — Estabilidade e Distribuição (Windows)
✨ Melhorias
Ícone corrigido no instalador e no aplicativo (.ico padrão)
Backend identificado corretamente como Lumma Overlay Service
Adicionado versionamento ao executável
🛠️ Build & Distribuição
Processo de build mais robusto
Geração automática de ícone durante o build
Sistema de fallback caso o PyArmor esteja sem licença
🎮 Input & Controle
Teclado otimizado:
Diferenciação entre toque e segurar
Correção do bug de loop ao abrir/fechar overlay
🎉 v1.1.0 — Primeiro Lançamento
🔧 Funcionalidades principais
Controle completo via DDC/CI:
Brilho
Contraste
Gama
Temperatura de cor
Saturação
Detecção automática de jogos
Perfis individuais por jogo
Contador de FPS via PresentMon
🎮 Controle & Interface
Suporte a controle Xbox (navegação via D-Pad)
Sistema de presets rápidos
Modo compacto
Controle completo pela bandeja do sistema
⚙️ Sistema & Automação
Inicialização automática com o Windows
Verificador de atualizações
Sistema de perfis:
Salvar
Carregar
Exportar


<p align="center">
  Feito com ❤️ por <strong><a href="https://www.youtube.com/@Doug_tech">@Doug_tech</a></strong>
</p>

<p align="center">
  <a href="https://github.com/Bob3111/lumma-overlay/releases/latest">Baixar Última Versão</a>
</p>



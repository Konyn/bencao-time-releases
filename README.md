# ⏳ BlessTime (Bênção Time)

> **Desktop Time Tracker moderno, leve e focado em produtividade.**

O **BlessTime** é um aplicativo desktop desenvolvido para simplificar o rastreamento de tempo em tarefas do dia a dia. Com interface minimalista, execução em segundo plano e ferramentas visuais de métricas, ele ajuda você e seu time a manter o foco no trabalho sem atritos operacionais.

---

## 🎯 Objetivo

O objetivo do BlessTime é eliminar a fricção do registro diário de horas:
- **Transparência de Tempo**: visualize claramente para onde vão suas horas de trabalho diárias e semanais.
- **Foco sem Interrupções**: registre suas atividades através de um widget flutuante compacto e discreto sem precisar alternar para abas de navegador ou ferramentas pesadas.
- **Acompanhamento de Metas**: acompanhe o ritmo de entregas com gráficos dinâmicos de sprints e metas diárias de horas trabalhadas.
- **Confiabilidade**: mantenha timers em execução contínua com suporte offline e sincronização resiliente.

---

## 🚀 Como Funciona

### 1. 🪟 Mini Timer Flutuante
- Janela flutuante compacta que pode ser fixada no topo (*Always-on-Top*).
- Permite iniciar, pausar, reiniciar tarefas e acompanhar o tempo decorrido em tempo real.
- Arraste para qualquer canto da tela ou acesse a janela principal com apenas um clique.

### 2. 🍔 Integração com a Bandeja do Sistema (Tray)
- O aplicativo continua rodando de forma silenciosa e eficiente na barra de tarefas / bandeja.
- Exibe o tempo ativo diretamente no ícone ou tooltip.
- Menu de contexto com ações rápidas para iniciar, pausar, retomar ou alternar tarefas com facilidade.

### 3. 📊 Painel de Histórico e Gráficos
- **Visualização Diária**: distribuição e detalhamento do tempo gasto por dia.
- **Visualização Semanal**: acompanhamento do total de horas acumuladas na semana.
- **Visualização por Sprint**: acompanhamento de ciclos de sprint (iniciando em segundas-feiras) com linha de tendência e comparação com a meta de horas úteis.

### 4. ⚡ Desempenho e Leveza
- Construído com tecnologia de ponta (Tauri + Rust + Vue), consumindo o mínimo de memória RAM e recursos da sua máquina.
- Compatibilidade nativa com **Windows**, **macOS** e **Linux**.

### 5. 🔄 Atualizações Automáticas
- O aplicativo conta com mecanismo integrado de verificação de atualizações.
- Notificações dentro do app informam quando uma nova versão estiver disponível, permitindo atualizar de forma simples e segura.

---

## 📥 Download e Instalação

Você pode baixar a versão mais recente diretamente na página de [Releases](https://github.com/Konyn/bencao-time-releases/releases/latest).

| Sistema Operacional | Formato | Como Instalar |
| :--- | :--- | :--- |
| **Windows** | `.exe` (NSIS) | Baixe o instalador `.exe` e siga o assistente de instalação. |
| **macOS** | `.dmg` | Baixe o arquivo `.dmg`, abra-o e arraste o BlessTime para a pasta **Aplicativos**. |
| **Linux (Ubuntu / Debian)** | `.deb` | Baixe o pacote `.deb` e instale com `sudo dpkg -i <arquivo>.deb` ou pela central de programas. |
| **Linux (Universal)** | `.AppImage` | Baixe o `.AppImage`, conceda permissão de execução (`chmod +x`) e execute. |

---

## 🔒 Privacidade e Segurança

- Os binários são compilados diretamente via integração contínua (CI/CD) no GitHub Actions e contam com assinaturas criptográficas para validação de integridade.
- Todos os dados locais de cache e configurações permanecem salvos unicamente no armazenamento seguro da sua máquina.

---

## 📦 Repositório de Releases

Este repositório é dedicado exclusivamente à distribuição pública de executáveis, pacotes de instalação e artefatos de atualização do BlessTime.

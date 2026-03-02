# Code Reviewer — Funcionalidades do App Desktop

> **"Diga adeus ao Code Review custoso"**

O **Code Reviewer** é um assistente de revisão de código alimentado por IA, disponível para **macOS**, **Windows** e **Linux**. Automatize análises, publique comentários diretamente nos Pull Requests e reduza o tempo de review em até 80%.

---

## 🤖 Análise Inteligente com IA

- **Múltiplos provedores de IA**: Google Gemini e OpenAI (ChatGPT)
- **Modelos dinâmicos**: escolha entre diversos modelos (ex.: `gemini-1.5-flash`, `gpt-4o-mini`, `gpt-4o`) conforme sua necessidade
- **Níveis de criticidade ajustáveis**:
    - **HIGH** — rigoroso (ideal para times júnior)
    - **MEDIUM** — moderado (pleno)
    - **LOW** — básico (sênior)
    - **NONE** — padrão
- **Detecção automática** de bugs, vulnerabilidades e sugestões de melhoria
- **Resumo do diff** gerado pela IA para visão geral rápida
- **Contexto enriquecido**: anexe arquivos (drag & drop ou file picker) para enriquecer o prompt da análise
- **Histórico de conversas** (ChatSession) mantido para contexto contínuo entre análises

---

## 🔗 Integração com VCS

| Provedor | Suporte | URLs suportadas |
|----------|---------|-----------------|
| **Azure DevOps** | ✅ | `dev.azure.com/{org}/{proj}/_git/{repo}/pullrequest/{id}` |
| **GitHub** | ✅ | `github.com/{owner}/{repo}/pull/{id}` |
| **GitLab** | ✅ | `gitlab.*/.../merge_requests/{id}` |

- **Cole a URL do PR** e o app carrega automaticamente o diff e metadados
- **Múltiplos PATs** por provedor — escolha qual conta usar em cada aba
- **Verificação de permissões** (GitHub repo, GitLab role) antes de postar
- **Imagens autenticadas** no Azure DevOps via interceptor dedicado

---

## 💬 Comentários e Colaboração

- **Publicação direta** de comentários no Pull Request (Azure DevOps, GitHub, GitLab)
- **Severidades**: CRITICAL, HIGH, MEDIUM, LOW, UNKNOWN
- **Draft comments**: crie e edite comentários localmente antes de publicar
- **Threads remotos** com cards específicos por provedor
- **Resolução de discussões** no GitLab (resolve/reopen)
- **Status de threads** no Azure DevOps
- **Voto de revisão** no Azure DevOps: Approve, Reject, Wait

---

## 📂 Visualização de Diff

- **Diff lado a lado** (side-by-side) para comparação clara
- **Lista de arquivos** com navegação rápida
- **Busca no diff** (Cmd/Ctrl + F)
- **Filtro de produção**: ignore arquivos de teste na análise
- **Renderização de Markdown** em comentários e blocos de código
- **Tipografia configurável** para diff, comentários e UI

---

## 🛠️ Stack de Tecnologia Customizável

- **TechStack**: Android, iOS, Flutter, KMP, React Native, Outro
- **TechCategory**: Mobile, Web, Backend, Desktop, DevOps/Cloud, Outro
- **Technologies customizadas**: adicione tecnologias por categoria para análises mais precisas
- **Tecnologias built-in** para cenários comuns

---

## 📑 Produtividade

- **Até 5 abas simultâneas** — revise múltiplos PRs ao mesmo tempo
- **Atalhos de teclado** em toda a aplicação:
    - `Cmd/Ctrl + ,` — Configurações
    - `Cmd/Ctrl + T` — Nova aba
    - `Cmd/Ctrl + W` — Fechar aba
    - `Ctrl + Tab` / `Ctrl + Shift + Tab` — Navegar entre abas
    - `Cmd/Ctrl + =` / `Cmd/Ctrl + -` / `Cmd/Ctrl + 0` — Ajustar fonte
    - `Cmd/Ctrl + S` — Salvar alterações
    - `Cmd/Ctrl + F` — Busca
    - `Cmd/Ctrl + Shift + /` — Diálogo de atalhos
- **Som opcional** ao concluir a análise
- **Atualização automática** via manifest ou GitHub Releases

---

## 🎨 Interface e Acessibilidade

- **Tema claro e escuro** (Light/Dark)
- **Tamanhos de fonte configuráveis** para diff, comentários e UI
- **Material Design 3** — interface moderna e consistente
- **Tooltips** contextuais
- **Drag & drop** de arquivos para contexto adicional
- **Layout responsivo** com escala de tipografia adaptável

---

## ⚙️ Configurações

- **Chaves de API**: Gemini e OpenAI (múltiplas chaves suportadas)
- **PATs**: Azure DevOps, GitHub, GitLab
- **Tecnologias**: lista customizada por categoria
- **Tema**: Light / Dark
- **Fontes**: Diff, Comentários, UI
- **Som ao concluir**: ativar/desativar

---

## 📦 Plataformas e Distribuição

| Plataforma | Formato | Arquiteturas |
|------------|---------|--------------|
| **macOS** | DMG | Intel (x64), Apple Silicon (arm64) |
| **Windows** | MSI | x64 |
| **Linux** | DEB | amd64, arm64 |

- **Atualização automática** integrada (macOS, Windows, Linux)
- **Monitoramento de erros** com Sentry

---

## 🚀 Por que usar o Code Reviewer?

1. **Economize tempo** — reduza o tempo de review em até 80%
2. **Multi-VCS** — um único app para Azure DevOps, GitHub e GitLab
3. **Multi-IA** — escolha entre Gemini e OpenAI conforme preferir
4. **Contexto personalizado** — anexe arquivos e defina tecnologias para análises mais precisas
5. **Publicação direta** — publique comentários no PR sem sair do app
6. **Multi-plataforma** — macOS, Windows e Linux com a mesma experiência
7. **Atualização automática** — mantenha-se sempre na versão mais recente

---

*Desenvolvido por [Probox Studio](https://proboxstudio.com.br)*

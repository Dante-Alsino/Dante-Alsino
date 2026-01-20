# Dante Alsino — Desenvolvedor · Automação · IA 🚀

[![Profile Views](https://komarev.com/ghpvc/?username=Dante-Alsino&color=0e75b6)](https://github.com/Dante-Alsino)

Sou desenvolvedor com foco em automação desktop, prototipagem em Python e aplicações web leves. Trabalho com soluções práticas e confiáveis que reduzem trabalho repetitivo e aceleram entregas. Este perfil destaca projetos, capacidades técnicas e o principal produto: AutoClicker (v1.0.0) — uma ferramenta madura para automação no Windows.

---

## Índice
- ⭐ Destaque: AutoClicker (v1.0.0)
- 📦 Portfólio de repositórios
- 🧩 Arquitetura & detalhes técnicos do AutoClicker
- 🛠️ Tech Stack
- 📦 Como instalar e executar (usuário e desenvolvedor)
- 🚀 Roadmap & contribuição
- 📊 Estatísticas do GitHub
- 📬 Contato

---

## ⭐ DESTAQUE PRINCIPAL — AutoClicker (v1.0.0) 🎯
[AutoClicker](https://github.com/Dante-Alsino/AutoClicker) — v1.0.0 (estável)

AutoClicker é a estrela do meu portfólio: uma ferramenta de automação desktop robusta, desenvolvida para aumentar produtividade em tarefas repetitivas.

Principais características
- 🐍 Desenvolvido em Python com interface moderna usando CustomTkinter (UI responsiva e agradável)
- 🧩 Arquitetura modular (módulos separados para UI, core, hotkeys, scripts e logs)
- 📋 Sistema de logs configurável (nivéis: DEBUG / INFO / WARN / ERROR) para auditoria e troubleshooting
- 🛠 Instalador em Inno Setup (experiência de instalação Windows com atalho no menu Iniciar)
- ⌨️ Captura de hotkeys global e suporte a perfis de scripts/atalhos
- 🔁 Execução de scripts personalizáveis (JSON/YAML) para sequências de cliques/teclas
- ✅ Versão v1.0.0 — focada em estabilidade, usabilidade e manutenção

Por que é relevante
- Economiza horas ao automatizar fluxos repetitivos
- Fácil para usuários finais: instalador dedicado e UI intuitiva
- Preparado para extensões: novos módulos de ação podem ser adicionados sem reescrever o core

Exemplo rápido (uso):
- Baixe o instalador → Instale → Abra o AutoClicker → Carregue um perfil de script → Ative via hotkey.

---

## 📁 Portfólio — Repositórios públicos (resumo organizado)
| Repositório | Linguagem principal | Propósito (1 frase) |
|---|---:|---|
| [AutoClicker](https://github.com/Dante-Alsino/AutoClicker) | Python (96.8%) + Inno Setup | Automação de cliques/teclado para Windows com scripts, logs e instalador — projeto desktop modular e estável (v1.0.0). |
| [Postlygram](https://github.com/Dante-Alsino/Postlygram) | Python (100%) | Projeto Python para automação/experimentação relacionada a postagem ou prototipagem de processos. |
| [FormularioCompass](https://github.com/Dante-Alsino/FormularioCompass) | JavaScript (78.8%) / HTML / CSS | Atividades do estágio na Compass: formulários, front-end e interação com usuário. |
| [Api-Mini-Banco-Central](https://github.com/Dante-Alsino/Api-Mini-Banco-Central) | JavaScript (100%) | API exemplo para consumo/integração de dados financeiros (mini-projeto de backend). |
| [dio-lab-open-source](https://github.com/Dante-Alsino/dio-lab-open-source) | Jupyter Notebook (100%) | Notebooks educacionais do laboratório "Contribuindo em um Projeto Open Source". |
| [lab-natty-or-not](https://github.com/Dante-Alsino/lab-natty-or-not) | N/D | Estudos e conteúdo sobre "IA e o Futuro do Trabalho". |
| [Compass](https://github.com/Dante-Alsino/Compass) | N/D | Repositório relacionado a atividades/projetos da empresa/estágio (conteúdo variado). |
| [Dante-Alsino (profile repo)](https://github.com/Dante-Alsino/Dante-Alsino) | N/D | Repositório de perfil com README e apresentação pessoal. |

Observação: "N/D" indica que a linguagem principal não estava disponível nas informações fornecidas.

---

## 🧩 Arquitetura & visão técnica do AutoClicker
Visão de alto nível (componentes):
- core/: regras de execução, scheduler de ações, parser de scripts
- ui/: telas e diálogos construídos com CustomTkinter
- hotkeys/: captura global de teclas e mapeamento de ações
- scripts/: exemplos de scripts em JSON/YAML e templates
- logs/: configuração e handlers de logs (arquivo + console)
- installer/: script Inno Setup usado para gerar o instalador Windows

Boas práticas aplicadas:
- Separação clara entre UI e lógica de negócio
- Logging configurável e tratamento de exceções para evitar falhas silenciosas
- Perfis exportáveis/importáveis para compartilhamento de automações

Segurança e confiabilidade:
- Confirmação de ações críticas antes de execução em massa
- Níveis de logs e modo "dry-run" para validar scripts sem executar cliques reais

---

## 🛠️ Tech Stack (visual & direto)
Com base nos repositórios públicos, minhas tecnologias e ferramentas comuns:
- 🐍 Python (CustomTkinter, automação, scripts)
- 🧾 Jupyter Notebook (prototipagem e estudos)
- 🌐 JavaScript (APIs e front-end)
- 🧩 HTML / CSS (interfaces web)
- 🪟 Inno Setup (criador de instaladores Windows)
- 🔧 Git & GitHub (controle de versão, releases)
- 🧰 Logging / Arquitetura modular / Testes básicos

---

## 📦 Como instalar e executar

Para usuários finais (instalador):
1. Acesse Releases: https://github.com/Dante-Alsino/AutoClicker/releases
2. Baixe o instalador `.exe`
3. Execute o instalador e siga os passos
4. Abra o AutoClicker pelo menu Iniciar e carregue um perfil

Para desenvolvedores (rodar local):
```bash
# clone
git clone https://github.com/Dante-Alsino/AutoClicker.git
cd AutoClicker

# criar venv
python -m venv .venv
# windows
.venv\Scripts\activate
# linux/mac
source .venv/bin/activate

# instalar dependências
pip install -r requirements.txt

# rodar (exemplo)
python -m app.main
```
Dicas: use o modo `--dry-run` (se disponível) para validar scripts sem executar ações reais; consulte `scripts/` para modelos de automação.

---

## 🚀 Roadmap & Como contribuir
Prioridades (curto a médio prazo)
- [ ] Melhor integração com perfil de scripts via UI
- [ ] Suporte a formatos adicionais de script (YAML, ZIP de perfis)
- [ ] Testes automatizados para core e hotkeys
- [ ] Internacionalização (i18n) da interface

Como contribuir
1. Abra uma Issue descrevendo a proposta ou bug
2. Faça um fork e abra uma branch com nome `feat/…` ou `fix/…`
3. Submeta um Pull Request com descrição clara e caso de uso
4. Para mudanças grandes, abra uma Issue/Discussão antes

Bug reports, pedidos de feature e testes serão muito bem-vindos — colaboração é a forma mais rápida de evoluir.

---

## 📊 Estatísticas dinâmicas do GitHub
Use estas imagens do github-readme-stats no seu README para exibir estatísticas atualizadas:

- Stats gerais (tema radical):
  - https://github-readme-stats.vercel.app/api?username=Dante-Alsino&show_icons=true&theme=radical&count_private=true

- Linguagens principais (compact) (tema radical):
  - https://github-readme-stats.vercel.app/api/top-langs/?username=Dante-Alsino&layout=compact&theme=radical

Se preferir dark:
- altere `theme=radical` para `theme=dark` nas URLs acima.

Exemplo de inclusão:
```md
![Dante's GitHub stats](https://github-readme-stats.vercel.app/api?username=Dante-Alsino&show_icons=true&theme=radical)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Dante-Alsino&layout=compact&theme=radical)
```

---

## ���� Contato
- GitHub: https://github.com/Dante-Alsino
- Melhor forma de contato: abrir Issue no repositório relevante ou enviar PR com sugestões/ajustes

---

Tom de voz: profissional, técnico e orientado a solução — sempre buscando clareza, eficiência e impacto real no dia a dia.  
Se quiser que eu gere um README em inglês, com badges customizados, imagens/screenshots prontas ou um arquivo CHANGELOG e LICENSE (MIT), eu posso preparar tudo pronto para adicionar ao repositório. 🚀

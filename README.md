# AGN Search - Projeto de Busca de Núcleos Galácticos Ativos

## Descrição do Projeto

Este repositório contém o código e documentação para o projeto de busca e análise de Núcleos Galácticos Ativos (AGN - Active Galactic Nuclei). O projeto foi desenvolvido como parte dos estudos acadêmicos na área de astronomia e astrofísica.

## Pré-requisitos

Antes de começar, certifique-se de ter instalado em seu sistema:

- Git (versão 2.0 ou superior)
- Python 3.8 ou superior
- Pip (gerenciador de pacotes Python)
- Editor de código (recomendamos Visual Studio Code)

## Como Clonar o Repositório

### 1. Clonagem via HTTPS
```bash
git clone https://github.com/seu-usuario/AGN_search.git
cd AGN_search
```

### 2. Clonagem via SSH (recomendado se você tem chaves SSH configuradas)
```bash
git clone git@github.com:seu-usuario/AGN_search.git
cd AGN_search
```

## Configuração do Ambiente de Desenvolvimento

### 1. Criar um Ambiente Virtual (Recomendado)
```bash
python3 -m venv venv
source venv/bin/activate  # No Linux/Mac
# ou
venv\Scripts\activate     # No Windows
```

### 2. Instalar Dependências
```bash
pip install -r requirements.txt
```

## Estrutura do Projeto

```
AGN_search/
├── src/                 # Código fonte principal
├── data/               # Dados de entrada e processados
├── notebooks/          # Jupyter notebooks para análise
├── tests/              # Testes unitários
├── docs/               # Documentação adicional
├── requirements.txt    # Dependências do projeto
└── README.md          # Este arquivo
```

## Comandos Git Essenciais para Estudantes

### Configuração Inicial (apenas uma vez)
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu.email@exemplo.com"
```

### Fluxo de Trabalho Básico
```bash
# 1. Verificar status do repositório
git status

# 2. Adicionar arquivos modificados
git add .                    # Adiciona todos os arquivos
git add arquivo_especifico   # Adiciona arquivo específico

# 3. Fazer commit das alterações
git commit -m "Descrição clara das mudanças"

# 4. Enviar para o repositório remoto
git push origin main
```

### Comandos Úteis para Colaboração
```bash
# Atualizar repositório local com mudanças remotas
git pull origin main

# Criar uma nova branch
git checkout -b nome-da-nova-branch

# Mudar entre branches
git checkout nome-da-branch

# Ver histórico de commits
git log --oneline

# Verificar diferenças
git diff
```

## Boas Práticas para Estudantes

### 1. Mensagens de Commit
- Use mensagens claras e descritivas
- Exemplos:
  - ✅ "Adiciona função de processamento de dados espectrais"
  - ✅ "Corrige bug na visualização de gráficos"
  - ❌ "update"
  - ❌ "fix"

### 2. Organização do Código
- Mantenha o código organizado e comentado
- Use nomes de variáveis descritivos
- Separe funcionalidades em módulos distintos

### 3. Versionamento
- Faça commits frequentes com pequenas alterações
- Teste o código antes de fazer push
- Use branches para funcionalidades experimentais

## Executando o Projeto

### 1. Executar Scripts Principais
```bash
python src/main.py
```

### 2. Executar Jupyter Notebooks
```bash
jupyter notebook notebooks/
```

### 3. Executar Testes
```bash
python -m pytest tests/
```

## Recursos de Aprendizado

### Git e GitHub
- [Pro Git Book](https://git-scm.com/book) - Documentação oficial completa
- [GitHub Learning Lab](https://lab.github.com/) - Tutoriais interativos
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials) - Guias práticos

### Python para Astronomia
- [AstroPy](https://www.astropy.org/) - Biblioteca Python para astronomia
- [Python for Astronomers](https://python4astronomers.github.io/) - Tutoriais específicos

## Solução de Problemas Comuns

### Erro de Autenticação
Se você receber erros de autenticação:
```bash
git config --global credential.helper store
```

### Conflitos de Merge
Para resolver conflitos:
```bash
git status                    # Ver arquivos em conflito
# Edite os arquivos manualmente
git add arquivo_resolvido
git commit -m "Resolve conflito de merge"
```

## Contribuindo para o Projeto

1. Faça um fork do repositório
2. Crie uma branch para sua funcionalidade (`git checkout -b nova-funcionalidade`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça push para a branch (`git push origin nova-funcionalidade`)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo `LICENSE` para detalhes.

## Contato

Para dúvidas sobre o projeto, entre em contato através de:
- Email: [seu.email@universidade.edu]
- Issues do GitHub: [Link para issues](https://github.com/seu-usuario/AGN_search/issues)

---

**Nota para Estudantes:** Este README serve como guia inicial. À medida que você aprende e contribui para o projeto, sinta-se à vontade para sugerir melhorias na
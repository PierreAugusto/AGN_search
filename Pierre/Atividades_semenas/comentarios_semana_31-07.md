# Atividade da Semana
**Objetivo:**  
Clonar o repositório `AGN_search` no GitHub, configurar no VS Code, criar estrutura de pastas, desenvolver códigos `.ipynb`, criar branches, realizar commits, push/pull e manter o projeto sincronizado.

---

## 1. Acesse o repositório no GitHub

- Verifique se o repositório `AGN_search` está disponível na sua conta do GitHub (como colaborador/editor).
- Ele deve aparecer na lista de repositórios do seu perfil.

---

## 2. Clone localmente usando o VS Code

1. Abra o VS Code.
2. Faça login com sua conta GitHub (ícone de contas no canto inferior esquerdo).
3. Pressione `Ctrl + Shift + P` e digite **Git: Clone** ou clique em **Clone repository** em Source Control.
4. Escolha **Clone from GitHub** e selecione `PierreAugusto/AGN_search` ou cole a URL do repositório.
5. Selecione uma pasta no seu computador para clonar o repositório.  
  > Uma subpasta `AGN_search` será criada, contendo a pasta oculta `.git`.
6. Após o clone, abra a pasta no VS Code.  
  > A extensão Source Control mostrará que o repositório está ativo.

---

## 3. Estruture o projeto no computador

- Na pasta do projeto, organize subpastas dentro da sua pasta pessoal:
  - `dados/` — para arquivos `.fits` (ex: `AGN_sample.fits`)
  - `notebooks/` — para arquivos `.ipynb`
  - `imagens/` — para imagens ou scripts
  - Outros conforme necessidade

> Edite e salve seus arquivos dentro dessa estrutura para manter tudo organizado.

---

## 4. Crie uma branch para suas alterações

1. No VS Code, clique no indicador de branch na barra inferior e escolha **Create Branch**.
2. Use um nome descritivo, ex: `projeto_agn_branco`.
3. Suas mudanças ficarão isoladas da branch principal (`main` ou `master`).

---

## 5. Adicione, commit e push das alterações

1. No painel **Source Control**, selecione os arquivos modificados e clique em **Stage Changes** (ou no ícone `+`).
2. Digite uma mensagem de commit clara, ex: `"Adiciona download de AGN_sample.fits"`.
3. Pressione `Ctrl + Enter` para commitar.
4. Para enviar ao GitHub, clique em **Publish Branch** ou use o ícone de **Push** na barra de status.

---

## 6. Sincronize com atualizações do repositório original

- Sempre que houver atualizações no GitHub, faça **Git → Pull** para obter as novas versões no seu clone local.
- No VS Code, use o botão **Synchronize Changes** ou `Ctrl + Shift + P → Git: Pull`.

---

## 7. Baixe e utilize sua biblioteca auxiliar

- Acesse o repositório da biblioteca em: [PierreAugusto/astronomia-auxiliar-pessoal](https://github.com/PierreAugusto/astronomia-auxiliar-pessoal).
- Leia o arquivo `README.md` para instruções detalhadas de instalação e uso.

- Verifique se existe um arquivo `requirements.txt` na raiz do repositório.
- No terminal do VS Code, navegue até a pasta do projeto e execute:

```bash
pip install -r requirements.txt
```

- Isso instalará todas as dependências necessárias para rodar os notebooks e scripts do projeto.
- Caso surjam erros, confira se o Python está instalado corretamente e se o ambiente virtual está ativado.
- Consulte o `requirements.txt` para entender quais bibliotecas estão sendo utilizadas.

- Importe os módulos da biblioteca nos seus notebooks para facilitar tarefas comuns de astronomia.
- Consulte exemplos e documentação no próprio repositório para aproveitar todas as funcionalidades.

Após instalar a biblioteca no seu ambiente, importe no Python com:

```python
from auxiliar_astro.constants import *
from auxiliar_astro.data_processing import *
from auxiliar_astro.image_utils import *
```
---

## 8. Instale os requisitos do projeto


# 🤝 Guia de Contribuição - Ciência da Computação Unoesc Maravilha

Ficamos muito felizes com o seu interesse em contribuir! Este espaço foi feito por e para estudantes. Seja subindo um trabalho de faculdade, corrigindo um exemplo ou melhorando a documentação, sua ajuda é fundamental.

Siga os passos abaixo para garantir uma colaboração organizada e eficiente.

---

## 🔑 1. Como Obter Acesso à Organização

Antes de começar a enviar seus códigos, você precisa fazer parte da organização no GitHub:

1. Acesse a página principal da organização: `://github.com`
2. Caso veja o botão **"Request to join"** (Solicitar acesso) no cabeçalho da organização, clique nele para enviar seu pedido direto.
3. Se o botão não estiver visível, abra uma **Issues**, Informe que deseja acesso a organização e informe o ```Semestre/Fase```.

Assim que o seu acesso for aprovado, você poderá criar branches e enviar códigos diretamente!

---

## 📂 2. Como Contribuir na Prática

### Passo 1: Localize o Repositório Correto
Navegue pela organização e encontre a pasta ou repositório correspondente à disciplina e ao ano vigente.
* *Exemplo:* Se você quer subir uma lista de exercícios de Estrutura de Dados, procure pelo repositório `Fase03-EstruturaDeDados-2026`.

### Passo 2: Crie uma Branch para a sua Contribuição
Evite fazer commits diretamente na branch principal (`main`/`master`). Sempre crie uma branch nova:
```bash
git checkout -b minha-fase-meu-nome
# Exemplo: git checkout -b fase03-lucas-silva
```

### Passo 3: Organize a sua Pasta
Para não misturar seus arquivos com os de outros colegas, crie uma pasta própria dentro do repositório seguindo o padrão:
`[NomeDoAluno]-[Matricula_Ou_Fase]`
* *Exemplo de estrutura:* `Fase03-EstruturaDeDados-2026/Lucas-Silva/Lista-01/`

### Passo 4: Faça o Commit Seguindo os Padrões
Suas mensagens de commit devem utilizar os prefixos corretos definidos no nosso padrão de commits:
```bash
git commit -m "[ESTRUTURA_DADOS] feat: adiciona resolucao da lista de exercicios 01"
```

### Passo 5: Envie o Código e Abra um Pull Request (PR)
Suba a sua branch para o GitHub:
```bash
git push origin fase03-lucas-silva
```
Vá até a página do repositório no GitHub e clique em **"Compare & pull request"**. Descreva brevemente o que foi adicionado e aguarde a revisão dos colegas.

---

## ⚠️ 3. Regras Importantes (Não Esqueça!)

* **Atenção ao `.gitignore`:** Nunca suba arquivos executáveis gerados por compilação (como `.exe`, `.out`, `.class`), pastas de dependências locais (como `node_modules`, `venv`) ou arquivos de configuração de IDEs (como `.vscode`, `.idea`).
* **Segurança em Primeiro Lugar:** **NUNCA** faça commit de chaves de API, senhas, tokens de acesso ou credenciais de bancos de dados. Se o seu projeto usa variáveis de ambiente, utilize um arquivo `.env.example` sem os dados reais.
* **Respeito ao Código Alheio:** Não altere ou apague pastas de outros colegas de turma a menos que seja um projeto em grupo e haja um acordo mútuo.

---
Se tiver dúvidas sobre o processo, abra uma **Issue** no repositório principal ou chame um colega no grupo da turma! 🚀

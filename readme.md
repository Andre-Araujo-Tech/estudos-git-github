# Repositório para estudos [Git e Github]

## 🚀 Inicialização de Repositório

**`git init`**  
➜ Inicia um novo repositório Git local.

**`git clone URL`**  
➜ Clona um repositório remoto para a máquina local.

---

## 📝 Controle de Alterações

**`git status`**  
➜ Exibe o estado atual do repositório.

**`git add .`**  
➜ Adiciona todas as alterações à staging area.

**`git commit -m "mensagem"`**  
➜ Cria um commit com mensagem clara e descritiva.

**`git diff`**  
➜ Mostra as diferenças entre arquivos modificados e a última versão commitada.

---

## 🕒 Histórico de Commits

**`git log`**  
➜ Exibe o histórico completo de commits.

**`git log --oneline`**  
➜ Exibe o histórico de commits de forma resumida.

---

## 🌱 Branches (Ramificações)

**`git branch`**  
➜ Lista todas as branches locais.

**`git branch nome-da-branch`**  
➜ Cria uma nova branch.

**`git checkout nome-da-branch`**  
➜ Troca para uma branch existente.

**`git checkout -b nome-da-branch`**  
➜ Cria e troca para uma nova branch.

**`git merge nome-da-branch`**  
➜ Mescla outra branch na branch atual.

---

## 🌐 Repositório Remoto (GitHub)

**`git remote -v`**  
➜ Lista repositórios remotos configurados.

**`git remote add origin URL`**  
➜ Adiciona um repositório remoto.

**`git pull`**  
➜ Atualiza o repositório local com o remoto.

**`git fetch`**  
➜ Busca alterações sem aplicá-las automaticamente.

**`git push origin main`**  
➜ Envia commits para o GitHub.

**`git push -u origin main`**  
➜ Define a branch padrão (upstream).

---

## 🏷️ Tags e Versionamento

As tags são utilizadas para marcar versões importantes do projeto, como releases estáveis.

**`git tag`**  
➜ Lista todas as tags do repositório.

**`git tag v1.0.0`**  
➜ Cria uma nova tag local.

**`git push origin v1.0.0`**  
➜ Envia uma tag específica para o GitHub.

**`git push origin --tags`**  
➜ Envia todas as tags para o repositório remoto.

**Versionamento semântico:**  
`vMAJOR.MINOR.PATCH`

---

## ♻️ Desfazer Alterações

**`git reset arquivo`**  
➜ Remove o arquivo da staging area sem apagar alterações locais.

**`git rm arquivo`**  
➜ Remove um arquivo do repositório e do histórico.

---

## ✅ Boas Práticas Utilizadas
```
- Commits pequenos e objetivos  
- Mensagens de commit claras e descritivas  
- Uso de branch principal (`main`)  
- Organização e documentação do repositório  
- Histórico limpo e fácil de entender  
``` 
---

## 📚 Glossário Git & GitHub

**->Commit**  
Registro permanente de uma alteração no repositório. Cada commit representa um ponto específico da evolução do projeto, contendo autor, data e mensagem descritiva.

**->Branch**  
Linha de desenvolvimento independente dentro do repositório. Permite criar, testar e evoluir funcionalidades sem impactar diretamente o código principal.

**->Merge**  
Processo de integrar alterações de uma branch em outra, normalmente trazendo uma funcionalidade finalizada para a branch principal (`main`).

**->Fork**  
Cópia completa de um repositório para outra conta no GitHub. Muito usado em projetos open source para contribuir sem alterar diretamente o repositório original.

**->Pull Request (PR)**  
Solicitação formal para que alterações feitas em uma branch ou fork sejam revisadas, discutidas e integradas ao projeto principal.

**->Tag**  
Marcador aplicado a um commit específico, geralmente usado para identificar versões estáveis do projeto (ex: `v1.0.0`).

**->Gist**  
Pequeno repositório do GitHub usado para compartilhar trechos de código, scripts ou anotações de forma rápida.

**->Release**  
Versão oficial do projeto no GitHub, normalmente associada a uma tag, contendo descrição das mudanças e arquivos para download.

**->Issue**  
Registro de problemas, bugs, melhorias ou tarefas. Serve como ferramenta de organização e comunicação dentro do projeto.

**->Wiki**  
Área dedicada à documentação do repositório, ideal para guias, tutoriais, padrões e informações técnicas detalhadas.

---

## 🔐 Autenticação e Segurança

### Métodos de Autenticação

- **Usuário e senha** *(obsoleto para Git via HTTPS)*  
  Método antigo de autenticação. O GitHub não permite mais o uso direto de senha para operações Git via HTTPS.

- **Token de Acesso Pessoal (PAT – Personal Access Token)**  
  Substitui a senha em conexões HTTPS. Possui permissões configuráveis e maior controle de segurança.

- **SSH (Secure Shell)**  
  Método mais utilizado em ambientes profissionais. Usa par de chaves criptográficas para autenticação segura, sem necessidade de digitar senha a cada operação.

- **Autenticação em Dois Fatores (2FA)**  
  Camada adicional de segurança que exige um segundo fator (app autenticador, SMS ou chave física), protegendo a conta mesmo em caso de vazamento de credenciais.

---

### 🔑 Chaves e Modelos de Implementação de Segurança

- **SSO (Single Sign-On)**  
  Permite que o usuário acesse múltiplos sistemas com uma única autenticação. Muito usado em empresas para integrar GitHub a provedores corporativos (ex: Google, Azure AD).

- **SAML (Security Assertion Markup Language)**  
  Protocolo de autenticação utilizado em conjunto com SSO. Permite autenticação centralizada e controle de acesso em organizações.

- **LDAP (Lightweight Directory Access Protocol)**  
  Protocolo usado para autenticação e gerenciamento de usuários em diretórios corporativos. Pode ser integrado a plataformas internas para controle de permissões.

---
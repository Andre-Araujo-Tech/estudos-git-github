# Repositório para estudos [Git e Github] teste

## Inicialização
**git init**  
*➜ Inicia um novo repositório Git.*

**git clone URL**  
*➜ Clona um repositório remoto.*

---

## Controle de Alterações
**git status**  
*➜ Mostra o estado atual do repositório.*

**git add .**  
*➜ Adiciona todas as alterações à staging area.*

**git commit -m "mensagem"**  
*➜ Cria um commit com mensagem descritiva.*

**git diff**  
*➜ Mostra diferenças entre arquivos modificados e a última versão commitada.*

---

## Histórico
**git log**  
*➜ Exibe o histórico de commits.*

**git log --oneline**  
*➜ Histórico resumido dos commits.*

---

## Branches
**git branch**  
*➜ Lista branches locais.*

**git branch nome-branch**  
*➜ Cria uma nova branch.*

**git checkout nome-branch**  
*➜ Troca para uma branch existente.*

**git checkout -b nome-branch**  
*➜ Cria e troca para uma nova branch.*

**git merge nome-branch**  
*➜ Mescla outra branch na branch atual.*

---

## Repositório Remoto (GitHub)
**git remote -v**  
*➜ Lista repositórios remotos configurados.*

**git remote add origin URL**  
*➜ Adiciona um repositório remoto.*

**git pull**  
*➜ Atualiza o repositório local com o remoto.*

**git fetch**  
*➜ Busca alterações sem aplicá-las automaticamente.*

**git push origin main**  
*➜ Envia commits para o GitHub.*

**git push -u origin main**  
*➜ Define a branch padrão (upstream).*

---

## Desfazer Alterações
**git reset arquivo**  
*➜ Remove o arquivo da staging area.*

**git rm arquivo**  
*➜ Remove um arquivo do repositório.*

---
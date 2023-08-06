# Comando Basicos do Git
---
## Inicializar um Repositorio
    git init
## Setar usuário globalmente
	git config --global user.name "Nome usuario"
## Setar email globalmente
	git config --global user.email "email.usuario"
---
# Estado dos arquivos
* Não rastreado (Untraked)
* Não modificado (Unmodified)
* Modificado (Modified)
* Preparado (Staged)

## Verificar estado dos arquivos
	git status
---
## Adicionar arquivo a área de preparo

### Adicionar um arquivo em específico
	git add nome_arquivo
### Adicionar todos os arquivos
	git add . 
---
## Remover arquivo
	git rm nome_arquivo
---
## Exibir histórico
	git log
## Exibir histórico de maneira resumida em uma linha
    git log --oneline
---

## Commitar arquivos com uma mensagem
    git commit -m "Mensagem desejada"
---
## Enviar arquivos para o repositório remoto
    git push

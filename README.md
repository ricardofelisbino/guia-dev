# Algumas dicas para Dev que estejam iniciando


## Ferramentas/Programas

### Download GIT
https://git-scm.com/download

### Download IntelliJ IDEA
https://www.jetbrains.com/pt-br/idea/download/

### Download Notepad++ 
https://notepad-plus-plus.org/downloads/ 



## Dicas Git

#### Definir Usuário Padrão do Commit
```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

#### Comandos mais Usados Git
```
git clone {{url_repositorio}}  - para clonar/baixar um repositório
git status - verificar situação branch do git e ver arquivos modificados
git add {{nome_arquivo}}  - para selecionar um arquivo para commit
git add *  - para selecionar todos os arquivos para commit
git rm {{nome_arquivo}}  - para remover a seleção de arquivo do commit
git commit -m "Descrição do Commit" - realizar o commit (preparar os arquivos para envio)
git push - realiza o publicação/envio dos arquivos para repositório
git pull - realiza o atualização/baixar atualização do repositório
```

Ver mais: https://comandosgit.github.io/ 


## Dicas IntelliJ Idea

#### Ajustes linhas (formatador)
```
Ctrl + Y: Apaga a linha inteira
Ctrl + D: Duplicar linha atual
Alt + Shift + Setas: Mover linha atual
Ctrl + Shift + Setas: Mover linha atual mantendo contexto
```

#### Buscar
```
Shift & Shift: Busca tudo
Ctrl + N: Busca rápida de classes
Ctrl + Shift + N: Busca rápida de arquivos
Ctrl + F: Busca no arquivo por conteúdo de arquivo
Ctrl + Shift + F: Busca global por conteúdo de arquivo
Ctrl + R: Busca no arquivo por conteúdo de arquivo com replace
Ctrl + Shift + R: Busca global por conteúdo de arquivo com replace
```

#### Organizar
```
Shift + F6: Renomeia classe, variável, método, etc
Ctrl + / ou Ctrl + Shift + /: Comentar código
Ctrl + Alt + L: Reformatar código
Ctrl + Alt + M: Extrair método - transforma código selecionado em método
Ctrl + Alt + O: Reajustar imports da classe (remove imports não utilizados)
```

Ver Mais: http://www.basef.com.br/index.php/Atalhos_do_IntelliJ_Idea

# Guia Básico do Git

# COMANDOS

# Navegação via Command line interface (CLI)
    Windows:
    - dir (listar as pastas)
    - cd / (navegar nas pastas)
    - cd .. (retroceder um nível na navegação)
    - cls (limpar a tela)
    - mkdir (criar uma pasta)
    - del (deleta arquivos)
    - rmdir /S /Q (deleta tudo por completo)

    Git
    - ls (listar as pastas)
    - cd / (navegar nas pastas)
    - cd .. (retroceder um nível na navegação)
    - clear (limpar a tela)
    - mkdir (criar uma pasta)

# Configurando o Git
- git config: Seguido de -- podemos configurar de forma global ou local no repositório. Deve ser seguido dos atributos a serem configurados. ex: user.email "" / user.name ""

# Criando projetos

    - git init: Comando único utilizado criar um novo repositório.

    - git clone: Comando que clona um repositório com git clone [url].

# Básico

    - git add: Comando que adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados. Oferecendo diferentes possibilidades de sintaxe.

    - git add * : Esse comando irá adicionar todos os arquivos novos e/ou modificados ao repositório.

    - git status: Comando lhe mostra em qual branch você se encontra.

    - git commit:
        
        É fundamental saber a diferença entre git add e git commi_.
	    
        1. git add adiciona seus arquivos modificados à fila para serem submetidos a um commit posteriormente.
	    
        2. git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log.
    
            É possível combinar as duas ações em um único comando: git commit -a. Também é possível adicionar uma mensagem para execução de um commit: git commit -m "sua mensagem".

# Compartilhar e Atualizar Projetos

    - git remote add origin (linkgithub): Comando para upar os repositórios.

    - git push: Comando para enviar arquivos novos ao repositório, leva as alterações ao repositório local para o remoto.

    - git pull: Usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.
    
    
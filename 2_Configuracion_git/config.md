# CONFIG
    git config --global

### configuracion a nivel global
    git config --global user.name "sopteccjscgmailcom"
    git config --global user.email "sopteccjsc@gmail.com"

### configuracion a nivel de repositorio
    git config user.email "sopteccjsc@gmail.com"

### creamos comandos personalizados con alias - tambien podemos editarlo en gitconfig
    git config --global alias.tree "log -graph --decorate --all --oneline"

### ver el nombre de usuario configurado
    git config --get user.name
    git config --get user.email

### Mostrar la información de configuración del usuario que está siendo utilizado por Git
    git config --get-regexp user.*

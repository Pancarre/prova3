# Git - work with Remotes
* i repository sono versioni del tuo progetto che sono ospitate su internet
* la collaborazione con altri programmatori implica la gesione di questi repository remote e il push e il pulldi dati

fondametale è saper **sincronnizzare il nostro lavoro locale con un repository remoto**

*comandi principali*
git remote -v --> visualizza iserver remoti collegati asl nostri repository

## Aggiungere o rimuovere un repository remoto
git remoto add <nome> <url>

## Caricare il lavoro locale al repository remoto
git push <remote> <ramo-locale>

## Aggiornare la copia locale di repository, allineandola con la versione remota
git pull <nome> <url>

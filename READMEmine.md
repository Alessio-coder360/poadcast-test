XML Tools scarica estensione per formattare file xml 

consigli : 

Fai sempre un backup prima di sovrascrivere

cp podcast.xml podcast.backup.xml

comandi utili :


# 1) Verifica le remotes attuali (sei nel tuo Codespace)
git remote -v

# 2) Aggiungi la remote del tutorial come 'upstream'
git remote add upstream https://github.com/planetoftheweb/podcast-test.git

# 3) Scarica tutti i rami dell’upstream
git fetch upstream

# 4) Vedi rami remoti disponibili
git branch -a
# Dovresti vedere:
# remotes/upstream/01_04e
# remotes/upstream/02_01b
# remotes/upstream/02_01e
# ecc.

# 5) Checkout di un ramo del tutorial creando un ramo locale che lo traccia
git switch -c 01_04e --track upstream/01_04e
# Ora lavori sul ramo locale '01_04e' con i contenuti del tutorial

# 6) Se vuoi tornare al tuo main
git

## Funzione generazione

All'interno del file potete trovare la funzione per creare i certificati HTTPS da utilizzare con NGINX

Inserire la funzione all'interno di zshrc

Da terminale eseguire questo comando:

generate_self_signed_cert "cert_name" "example.com,www.example.com" "pass"\n

!! I certificati verranno creati all'interno della cartella attuale, quindi entrate nella cartella dove desiderate salvare i certificati
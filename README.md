# NOZE

Penser à modifier le fichier host en faisant pointer quelque chose finissant par .si.fr.intraorange vers localhost

Docker run
```bash
docker run -dit --name noze -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4
```

Puis y accéder via navigateur. Je passe les détails, vous devez être des experts archi confirmés :D

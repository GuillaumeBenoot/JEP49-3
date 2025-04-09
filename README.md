## Dans PowerShell

# Générer

docker container run --rm -v C:\Users\g.benoot\IdeaProjects\JEP-49-3\slides:/documents -w /documents asciidoctor/docker-asciidoctor:1.80.0 asciidoctor-revealjs -r asciidoctor-diagram index.adoc


# Lancer

docker container run --name prez --rm -d -p 8080:80 -v C:\Users\g.benoot\IdeaProjects\JEP-49-3\slides:/usr/share/nginx/html nginx
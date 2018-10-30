# scm-prointer

** Prointer I ** Esse site faz parte do Projeto Interdisciplinar Aplicado aos Cursos Superiores de Tecnologia I (PROINTER I) 

Como iniciar o projeto?
* Tenha um servidor linux
* Instale o docker com o seguinte comando: curl https://raw.githubusercontent.com/rancher/install-docker/master/17.03.2.sh | sh
* Habilite o servco: systemctl enable docker && systemctl restart docker
* Instale o docker-compose: sudo curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose ; sudo chmod +x /usr/local/bin/docker-compose
* Realize git clone do repositorio 
* Caso seja necessario altere o docker-compose.yml apontando o volume do container para onde voce fez o git clone
* Execute docker-compose up -d

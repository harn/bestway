# README #

O aplicativo deve prover a melhor rota entre dois pontos. Esse problema é conhecido como "Problema do caminho mínimo"


Foi escolhido utilizar o Neo4J pois ele é classificado como banco de dados de grafos sendo um banco otimizado para se trabalhar com essa estrutura de dados, assim a aplicação não fica responsável pela implementação dos algorítimos ligados a grafos, estando mais preparado para se trabalhar com sistemas mais escaláveis.

A ferramenta Chef e Vagrant foram escolhidas para fazer o provisionamento da maquina de desenvolvimento, mantendo uma VM padrão para o desenvolvimento.

O manual da API foi descrito utilizando a GEM Apipie. é acessível por meio do link http://localhost:3000/apipie

### Quais tecnologia esse aplicativa utiliza? ###

* Ruby on Rails 4.2
* Neo4j
* Chef

### Como configurar? ###

* Instalar o Vagrant com os plugins
* ** vagrant plugin install vagrant-librarian-chef-nochef
* ** vagrant plugin install vagrant-omnibus
* logar na maquina virtual "vagrant up; vagrant ssh"
* bundle 
* configurar as senhas do Neo4J no secret.yml
* rake db:seed
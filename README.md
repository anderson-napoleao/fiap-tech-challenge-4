Criamos esse repositório para agregar os projetos e facilitar o uso do docker compose

Passos para rodar o projeto:

clonar o repositório:
git clone https://github.com/anderson-napoleao/fiap-tech-challenge-4.git

navegar para o diretorio criado:
cd fiap-tech-challenge-4

atualizar a branch de cada submódulo, como configurado no arquivo .gitmodules:
git submodule update --init --remote

Para subir no docker:
Abrir o docker na maquina.

rodar o comando par dar build e subir os serviços no modo detached:
docker compose up --build -d

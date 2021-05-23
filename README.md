# appollo
git clone https://github.com/apolloauto/apollo-a
docker --version
cd apollo
sudo bash docker/scripts/install_docker.sh
cd apollo
sudo bash docker/scripts/dev_start.sh
sudo bash docker/scripts/dev_into.sh
bash apollo.sh build
bash scripts/bootstrap.sh

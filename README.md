# anguler_crud

## install anguler
### install nodejs
### readme: https://github.com/nodesource/distributions/blob/master/README.md#rpm

```bash
sudo yum install gcc-c++ make
curl -fsSL https://rpm.nodesource.com/setup_17.x | sudo bash -
sudo yum install -y nodejs
```

## install angular

```bash
sudo npm install -g @angular/cli
```

## start anguler

```bash
ng serve --host 0.0.0.0 --port 4000
```

## install goenv

```bash
git clone https://github.com/syndbg/goenv.git ~/.goenv
echo 'export GOENV_ROOT="$HOME/.goenv"' >> ~/.bash_profile
echo 'export PATH="$GOENV_ROOT/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(goenv init -)"' >> ~/.bash_profile
echo 'export PATH="$GOROOT/bin:$PATH"' >> ~/.bash_profile
echo 'export PATH="$PATH:$GOPATH/bin"' >> ~/.bash_profile
exec $SHELL
goenv install 1.13.5
```

## install echo
```
mkdir backend; cd backend
go mod init github.com/geliefan/anguler_crud/backend
go get github.com/labstack/echo/v4
```
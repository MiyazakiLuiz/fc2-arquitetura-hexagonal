### Comandos Uteis

```
go mod init <module name>

go mod init github.com/codeedu/go-hexagonal
```
Toda vez que utilizar um pacote externo o go mod vai adiciona-lo automaticamente no arquivo go.mod


```
mockgen -destination=application/mocks/application.go -source=application/product.go application
```
Cria mocks da aplicacao para utilizar nos testes unitarios

```
touch sqlite.db
sqlite3 sqlite.db
```
Cria o arquivo de configuracao do sqlite e acessa o mesmo

```
cobra init --pkg-name=github.com/codeedu/go-hexagonal
```
Inicializa o Cobra para realizar comandos cmd


```
go mod tidy
```
Instala pacotes que precisarao ser utilizados
# Go Estudos  
<img src="https://go.dev/blog/gopher/header.jpg" width="400">

------------------------
### Execução no Go

```
go run .
```
-------------------
### Criação de diretório

```
mkdir hello // "hello" é o nome do diretório
cd hello //  Entrar no diretório

```
---------------
### Inicialização um módulo (passo importante antes de qualquer coisa!)
```
go mod init exemplo/olá
go: criando novo go.mod: módulo exemplo/hello

```
-----------------
```
go mod init exemplo/olá
go: criando novo go.mod: módulo exemplo/hello

```
------------------
### Atualização de dependências
```
go mod tidy
```
----------------
### Declaração de variável e impressão
```
var nome = "Maria"
var idade = 20
fmt.Println("O nome é: ", nome, "e a idade é ", idade)  // lembre-se de importar o package "fmt" no início

```
Outra possibilidadae de declarar uma variável
```
nome := "Maria"
idade := 20
fmt.Println("O nome é: ", nome, "e a idade é ", idade)   // lembre-se de importar o package "fmt" no início

```

### if e else
----------------

### For
----------------

### Switch
-------------

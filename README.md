#Criando o primeiro commit.

Antes de criar nosso primeiro commit, deveremos seguir uma série de passos.  
Passos para nosso primeiro commit
* Criação de repositório
* Criar arquivo
* Adicionar e confirmar

##Ciração de repositório

A criação de um novo repositório é algo extremamente simples, onde basta criar uma pasta onde será o diretório e rodar um comando.
```
# criando a pasta que irá conter o repositório
mkdir repositorio
# navegue até o repositorio
cd repositorio
# crie o repositorio
git init
```

Com esses simples passos seu repositório já estara pronto para uso.

## Criar arquivo
A criação de arquivo não requer explicações, mas em nosso tutorial criaremos um arquivo chamado "README.md" para exemplificar.
```
touch README.md
```

##Adicionar e confirmar
Para adicionar os arquivos utilize o comando abaixo.
```
git add <arquivo>
```

Caso fosse adicionar mais arquivos, poderia ser utilizado outro comando.
```
git add *
```

Após adicionar os arquivos, será possivel partir para o proximo passo e realmente confirmar a adição dos arquivos.
```
git commit -m "comentários das alterações"
```


##Guias e referencias
* Utilização do git
  * http://rogerdudler.github.io/git-guide/index.pt_BR.html
* Utilização do markdown
  * https://guides.github.com/features/mastering-markdown/
  * https://help.github.com/articles/github-flavored-markdown/ 

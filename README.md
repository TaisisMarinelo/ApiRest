# Gama Academy e Banco Pan

## Turma 1

#### Desenvolvedor Aluna Taisis



### Dias 27/10/2021 , 28/10/2021 e 29/10/2021

### Projeto de ensino do Profº Jonathan, e exercício em grupo.

### Projeto usando Spring, Maven, Toncat e BDH2.

### Desenvolvimento de uma aplicação com uso de BDH2. 



## api/scr/main/java:



## Pacote api:

ApiApplication.java

Classe principal da aplicação, onde instanciamos o  BD. 

Exporta de UsuarioRepository e ProdutoRepository. E Implementa de CommandLineRunner (que e uma implementação Java).

E passa as informações para salvar nos arrays nos banco. 



## Pacote api.controllers:

UsuarioController.java e ProdutoController.java

UsuarioController.java (path= "/usuarios")

Produto.Controller.java (path= "/produtos")

Classe que implementa os métodos CRUD de serviço criado nas classes UsuarioService.java e ProdutoService.Java.



## Pacote api.model:

Usuario.java e Produto.java

Classe de declaração dos atributos, dos getters e setters,  do constructors e do equals e hashcode.



## Pacote api.repositories:

UsuarioRepository.java e ProdutoRepository.java

Interface que está estendendo de JpaRepository (que e uma implementação Java), e também serve como repositório da aplicação. 



## Pacote api.service:

UsuarioService.java e ProdutoService.java

Classe que implementa os serviços de busca do objeto, update, create e delete.

A mesma implementa de UsuarioRepository.java para Usuário e de ProdutoService.java para Produto. 



### api/scr/main/resources

application.properties

Arquivo de configuração do BD H2.





## Treinamento Java e AWS Cloud!

### #GoGama #OPanEhTech
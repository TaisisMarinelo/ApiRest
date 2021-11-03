# Gama Academy e Banco Pan

## Turma 1

#### Desenvolvedor Aluna Taisis



### Dias 27/10/2021 e 28/10/2021

### Projeto de ensino do Profº Jonathan.

### Projeto usando Spring, Maven, Toncat e BDH2.

### Desenvolvimento de uma aplicação com uso de BDH2. 



## api/scr/main/java:



## Pacote api:

ApiApplication.java

Classe principal da aplicação, onde instanciamos o  BD. 

Implementa de UsuarioRepository e CommandLineRunner (que e uma implementação Java).



## Pacote api.controllers:

UsuarioController.java

Classe que implementa os métodos CRUD de serviço criado na classe UsuarioService.java



## Pacote api.model:

Usuario.java

Classe de declaração dos atributos, dos getters e setters,  do constructors e do equals e hashcode.



## Pacote api.repositories:

UsuarioRepository.java

Interface que está estendendo de JpaRepository (que e uma implementação Java), e também serve como repositório da aplicação. 



## Pacote api.service:

UsuarioService.java

Classe que implementa os serviços de busca do objeto, update, create e delete.

A mesma implementa de UsuarioRepository.java.



### api/scr/main/resources

application.properties

Arquivo de configuração do BD H2.





## Treinamento Java e AWS Cloud!

### #GoGama #OPanEhTech
#   springdocs


### Annotations

### @Component:

>   é uma anotação que permite ao Spring detectar automaticamente nossos beans customizados.
  sem ter que escrever nenhum código explícito, o Spring irá: Escanear nosso aplicativo em busca de
  classes anotadas com @Component. Instancie-os e injete quaisquer dependências especificadas neles.
  Injete-os sempre que necessário.
### @Autowired:

>   é usado para injetar dependências automáticas.
    A estrutura Spring é construída sobre injeção de dependência e injetamos 
    as dependências de classe por meio do arquivo de configuração do bean spring.
    
##

### springBootApplication 
    
>   é usada para marcar uma classe de configuração que declara um ou mais métodos
    @Bean e também aciona a configuração automática e a varredura de componentes

### spring Boot Dev Tools

>   O objetivo é tentar melhorar o tempo de desenvolvimento
    ao trabalhar com o Spring Boot.

### @RestController

>   é uma anotação de conveniência para criar controladores Restful.
É uma especialização de @Component e é autodetectada por meio da 
varredura de caminho de classe. Ele adiciona as anotações @Controller 
e @ResponseBody. Ele converte a resposta em JSON ou XML.

### ResquestMapping

>   Ele é usado para mapear solicitações da Web em classes 
de manipulador específicas e/ou métodos de manipulador.
@RequestMapping pode ser aplicado à classe do controlador, 
bem como aos métodos.

### @RequiredArgsConstructor

> Gera um construtor com argumentos necessários.

### @GetMapping 

> é uma anotação composta que atua como um atalho para
@RequestMapping(method = RequestMethod. GET) .

### @Postmapping
> @PostMapping faz parte de um grupo predefinido de 
> anotações compostas que internamente usam @RequestMapping.
> Essas anotações funcionam como atalhos que servem para simplificar o mapeamento dos métodos HTTP e expressar de forma
> mais concisa os métodos de manipulação. 

### @DeleteMapping 
> @DeleteMapping is a composed annotation that acts as a 
> shortcut for @RequestMapping(method = RequestMethod. DELETE)
> Anotação para mapear solicitações HTTP DELETE em métodos 
> de manipulador específicos.

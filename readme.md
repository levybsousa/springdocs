#   Spring docs

**spring @Autowired**:

    é usado para iserir dependências automáticas.
    A estrutura Spring é construída sobre injeção de dependência e injetamos 
    as dependências de classe por meio do arquivo de configuração do bean spring.
    
**spring @Component**:

    é uma anotação que permite ao Spring detectar automaticamente nossos beans customizados.
    sem ter que escrever nenhum código explícito, o Spring irá: Escanear nosso aplicativo em busca de 
    classes anotadas com @Component. Instancie-os e injete quaisquer dependências especificadas neles.
    Injete-os sempre que necessário.

**springBootApplication**
    
    é usada para marcar uma classe de configuração que declara um ou mais métodos
    @Bean e também aciona a configuração automática e a varredura de componentes
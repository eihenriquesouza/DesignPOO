# Técnicas de POO

- Este repositório aborda três técnicas da Programação Orientada a Objetos (POO): Herança, Composição/Associação e Injeção de Dependência.
Abaixo explico, de forma resumida, o que entendi sobre cada uma delas.

# Herança

- A herança permite que uma classe aproveite atributos e métodos de outra. Isso ajuda a evitar repetições de código e cria uma hierarquia mais organizada.
Porém, quando usada em excesso, pode deixar o sistema rígido e difícil de adaptar, além de forçar relações que nem sempre fazem sentido. Muitas vezes é preciso criar classes intermediárias para dar conta de variações, o que complica a estrutura.

# Composição / Associação

- Na composição, uma classe utiliza outras classes em vez de herdar delas. Isso torna o código mais flexível e próximo de situações reais (ex.: um carro tem um motor).
Apesar disso, se não for bem aplicado, pode gerar dependências fortes e dificultar a manutenção, já que qualquer mudança em um comportamento pode impactar várias partes do sistema.

# Injeção de Dependência

- A injeção de dependência é uma forma de desacoplar ainda mais as classes. Em vez de criar diretamente os objetos de que precisa, uma classe os recebe prontos, normalmente através do construtor.
Isso facilita testes e manutenção, pois é possível trocar implementações sem alterar toda a estrutura. Em sistemas maiores é muito útil, mas em projetos pequenos pode ser complexo demais.

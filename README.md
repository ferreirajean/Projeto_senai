# O que é um sistema de controle de versões (VCS)?

É a pratica de rastrear e gerenciar alterações em um código de software. São ferramentas que ajudam as equipes de software a gerenciar as alterações no código-fonte ao longo do tempo. O controle de versão permite uma colaboração rápida e eficiente entre desenvolvedores, mantendo a integridade do código e permitindo que as equipes de desenvolvimento de software trabalhem sem medo de conflitos de código também permite que façam backup e arquivem o código-fonte de seus projetos. Isso torna mais fácil revisar e fazer edições no repositório ou restaurar versões anteriores no caso de um erro. O VCS também oferece suporte à capacidade de criar ramificações onde os desenvolvedores podem trabalhar independentes e em fluxos separados. O sistema permite mesclar todas as alterações e edições em um repositório centralizado.

## Cite 5 vantagens em utilizar um VCS




•	Histórico de alterações, 

•	Trabalho colaborativo, 

•	Backup, 

•	Segurança,

•	Registro de Autoria e Auditoria.

## Cite 3 exemplos de VCS

•	GIT

•	SVN(Subversion) 

•	Mercurial



## Desafio 2

POO é um paradigma de linguagem de programação. Assim como em outras áreas, no desenvolvimento de software também existem várias formas de resolver um problema. Uma dessas formas é a Programação Orientada a Objetos (POO). A diferença é que ela é a mais usada entre os programadores, porque funciona com várias linguagens e também ajuda em análises, não só na programação. O objeto é uma união de estados (como ele está) e ações (o que ele faz). Ele representa algo do mundo real ou de uma ideia, dentro do problema que está sendo estudado. Esse jeito de pensar aproxima a realidade do que é feito no computador. Para criar objetos, foi necessário definir as classes. A classe é um grupo de objetos que têm características parecidas. Ela diz como o objeto se comporta, usando ações (chamadas de métodos) e características (chamadas de atributos). Por isso, os conceitos principais da Programação Orientada a Objetos (POO) são objetos e classes.

### Seus pilares são: Herança, Polimorfismo, Encapsulamento e Abstração

#### A abstração é um conceito da POO que permite esconder detalhes complexos e mostrar apenas o que é essencial. Isso facilita o entendimento e a organização do código.

Cenário: Sistema de Cadastro de Funcionários 
Imagine que estamos criando um sistema para gerenciar funcionários de uma empresa.

•	No mundo real, um funcionário tem várias informações, como nome, CPF, salário, cargo, endereço, telefone, entre outras.

•	No entanto, nem todas essas informações são necessárias para todas as partes do sistema.

•	Se estivermos lidando apenas com folha de pagamento, precisamos do nome, cargo e salário do funcionário, mas não do endereço ou telefone.

•	Se for um módulo de comunicação interna, o mais importante pode ser o nome, telefone e e-mail, mas não o salário.

#### O encapsulamento é um conceito da POO que restringe o acesso direto aos dados de um objeto, permitindo que sejam modificados apenas por meio de métodos específicos. Isso protege as informações e garante que os dados sejam manipulados corretamente.

Cenário: Conta Bancária 
Imagine que estamos desenvolvendo um sistema bancário.

•	Uma conta bancária tem informações sensíveis, como o saldo.

•	Não queremos que qualquer parte do sistema possa alterar o saldo diretamente, pois isso pode causar erros ou fraudes.

•	O correto é permitir que o saldo seja alterado apenas por meio de métodos controlados, como depositar e sacar.

#### A herança é um conceito da POO que permite que uma classe herde atributos e métodos de outra classe. Isso evita a repetição de código e facilita a manutenção do sistema.

Cenário: Sistema de Funcionários de uma Empresa

•	Imagine que estamos criando um sistema para gerenciar funcionários de uma empresa. Existem diferentes tipos de funcionários, como Gerentes e Desenvolvedores.

•	Todos os funcionários têm algumas informações em comum, como nome, salário e cargo.

•	No entanto, cada tipo de funcionário pode ter características específicas.

•	Um Gerente pode ter um bônus no salário.

•	Um Desenvolvedor pode ter uma linguagem de programação associada.

•	Em vez de repetir esses atributos e métodos em várias classes, podemos criar uma classe base (superclasse) chamada Funcionário e fazer com que Gerente e Desenvolvedor herdem dela.

#### O polimorfismo é um conceito da POO que permite que diferentes classes usem um mesmo método, mas cada uma com seu próprio comportamento. Isso torna o código mais flexível e facilita sua expansão.

Cenário: Diferentes Tipos de Funcionários em uma Empresa

•	Imagine um sistema de gestão de funcionários onde diferentes cargos têm maneiras diferentes de calcular o salário final.

•	Todos os funcionários têm um salário base.

•	No entanto, cada tipo de funcionário pode ter regras específicas para o cálculo do pagamento.

•	Um Gerente recebe um bônus além do salário.

•	Um Desenvolvedor pode receber um bônus por projeto concluído.

•	Um Estagiário recebe apenas o salário base, sem adicionais.

•	Podemos usar polimorfismo para que todas essas classes tenham um método calcular pagamento(), mas cada uma implemente esse método de forma diferente.

## 5 vantagens da POO

Reutilização de Código
A herança permite reaproveitar atributos e métodos de uma classe existente, evitando a repetição de código. Isso torna o desenvolvimento mais rápido e reduz erros.

Facilidade na Manutenção
O código fica mais organizado, pois cada objeto representa uma parte específica do sistema. Alterações podem ser feitas em uma classe sem afetar outras partes do programa.

Segurança e Controle de Acesso
O encapsulamento protege os dados sensíveis e evita que sejam modificados indevidamente. Os atributos podem ser privados (private), permitindo acesso apenas por métodos específicos.

Flexibilidade e Extensibilidade
Com polimorfismo, diferentes classes podem ter métodos com o mesmo nome, mas com implementações diferentes. Isso permite adicionar novas funcionalidades sem modificar o código já existente.

Melhor Modelagem do Mundo Real
Objetos representam entidades do mundo real, tornando o código mais intuitivo e fácil de entender.


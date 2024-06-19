# Trabalho de Sistemas Computacionais
Descrição do Funcionamento dos Métodos
O servidor implementa uma classe Calculadora com métodos expostos via Pyro4 para realizar operações matemáticas básicas.

Os resultados de cada operação são impressos no console.

Usabilidade do RPC (Remote Procedure Call)
RPC (Remote Procedure Call) permite que programas executem procedimentos (funções ou métodos) em uma máquina remota como se fossem chamadas locais. Aqui estão algumas características e vantagens da usabilidade do RPC:

Transparência de Localização:
Os métodos remotos são chamados da mesma forma que os métodos locais, ocultando a complexidade da comunicação de rede do programador.

Modularidade:
Permite que a lógica de negócios seja separada e distribuída entre diferentes servidores, facilitando a manutenção e a escalabilidade.

Facilidade de Uso:
Ferramentas como Pyro4 simplificam a implementação de RPC em Python, fornecendo mecanismos fáceis para expor métodos e registrar objetos no servidor.

Desempenho:
Embora haja uma sobrecarga de comunicação de rede, o RPC é eficiente para operações que não requerem grande quantidade de dados entre cliente e servidor.

Flexibilidade:
Permite a implementação de serviços distribuídos e pode ser utilizado em diversas aplicações, desde sistemas corporativos até jogos online.

Exemplo de Uso:
Imagine um sistema de cálculo distribuído onde várias máquinas clientes realizam operações matemáticas intensivas. Com RPC, um servidor central pode fornecer serviços de cálculo, e os clientes podem delegar essas operações ao servidor. Isso não só distribui a carga de processamento como também centraliza a lógica de cálculo, facilitando atualizações e manutenções.

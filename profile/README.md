<div align="center">
  <h1>RISC-V Pipeline Processor</h1>
</div>

<div align="center">
<h2>Desenvolvido na matéria de Arquitetura de Computadores (Developed in the Computer Architecture course)</h2>
</div>

<div align="center">
<h2>Antonio da Ressurreição Filho and Matheus Gastal Magalhaes, students in the third semester of Computer Science at the Federal University of Paraná (UFPR).</h2>
</div>


## Professor: [Dr. Paulo Ricardo Lisboa de Almeida.](https://prlalmeida.com.br/)

## Bibliography: Patterson, Hennessy. Computer Organization and Design RISC-V Edition: The Hardware Software Interface. 2020

<div align="center">
  <img src="Assets/circuito.png" alt="Processor" width="800px" />
</div>

# Português:

O trabalho foi desenvolvido na disciplina de Arquitetura de Computadores e consistiu na montagem de um processador Pipeline com tratamento de hazards (de dados e de controle) da arquitetura RISC-V no 
[Logisim](https://github.com/logisim-evolution/logisim-evolution). Cada um dos membros contribuiu significativamente, sendo que a divisão das funcionalidades ficou muito próxima de 50% para cada um. 

O processador implementa as seguintes instruções: ADD, SUB, OR, AND, ADDI, SLLI, LW, SW e BEQ. Essas instruções seguem fielmente a bibliografia utilizada (Patterson, Hennessy. Computer Organization 
and Design RISC-V Edition: The Hardware Software Interface. 2020), a qual explica o funcionamento do processador RISC-V Pipeline e apresenta formas de tratar os hazards.

Após a apresentação do projeto ao professor [Dr. Paulo Ricardo Lisboa de Almeida.](https://prlalmeida.com.br/), foi atribuída a nota máxima a ambos os membros do grupo. 


<h3>Arquivos contidos no repositório:</h3>


- "Processador_Arquitetura.circ": Arquivo do processador, o qual pode ser aberto através do Logisim.
- "RISCV_CARD.pdf": Informações do RISC-V, como Opcodes de instruções e informações de registradores, as quais foram utilizadas para o processador se parecer ao máximo à arquitetura RISC-V.
- "Códigos_Assembly&Hex.pdf": Códigos em Assembly e em Hexadecimal usados para testar o programa de todas as formas possíveis.
- "Assets": Diretório dedicado às imagens que contribuíram para a realização do projeto e imagens do próprio projeto.

# English:

The project was developed for the Computer Architecture course and consisted of building a RISC-V Pipeline processor with hazard handling (both data and control hazards) using
[Logisim](https://github.com/logisim-evolution/logisim-evolution). Each member contributed significantly, with the division of responsibilities being almost evenly split at around 50% each.

The processor implements the following instructions: ADD, SUB, OR, AND, ADDI, SLLI, LW, SW, and BEQ. These instructions strictly follow the reference book used: Patterson, Hennessy. Computer 
Organization and Design RISC-V Edition: The Hardware Software Interface. 2020, which explains the RISC-V Pipeline architecture and presents ways to handle hazards.

After the presentation of the project to [Dr. Paulo Ricardo Lisboa de Almeida.](https://prlalmeida.com.br/), he highest grade was awarded to both group members.

<h3>Files contained in the repository:</h3>

- "Processador_Arquitetura.circ": The processor file, which can be opened using Logisim.
- "RISCV_CARD.pdf": Contains RISC-V information, such as instruction opcodes and register details, which were used to make the processor closely resemble the RISC-V architecture.
- "Códigos_Assembly&Hex.pdf": Assembly and hexadecimal codes used to test the processor in every possible way.
- "Assets": Directory dedicated to images that contributed to the development of the project, including images of the processor itself.






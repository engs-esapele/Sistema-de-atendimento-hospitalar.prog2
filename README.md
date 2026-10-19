# .✦ ݁˖ Sistema de atendimento-hospitalar ⋆˚࿔
## ⋆˙⟡ ───── 𝑨𝒍𝒖𝒏𝒂𝒔 ───── ⋆˙⟡ 
###  𓂃۶ৎ Marya Eduarda dos Santos Mota
### 𓂃۶ৎ Emily Caroline Sequinel 
### 𓂃۶ৎ Isabely Gislaine dos Santos

## ⋆˙⟡ ───── 𝑰𝒏𝒇𝒐𝒓𝒎𝒂𝒄̧𝒐̃𝒆𝒔 ───── ⋆˙⟡

#### ✧  Disciplina: Programação e Sistemas Computacionais II

#### ✧ Professor: Giovane Galvão

#### ✧ Instituição: Centro Universitário Campo Real (Engenharia de Software)

## ⋆˙⟡ ───── 𝑺𝒐𝒃𝒓𝒆 𝒐 𝑷𝒓𝒐𝒋𝒆𝒕𝒐 ───── ⋆˙⟡

##### O sistema simula a Triagem e Atendimento Digital do Hospital Campo Real utilizando estruturas de dados lineares encadeadas construídas manualmente em C++, sem o uso de bibliotecas da STL (vector, queue, stack, list).

####  ✦ R1 · Fila de Pacientes (FIFO): Entrada e remoção na fila por ordem de chegada e prioridade.

#### ✦ R2 · Histórico (LIFO): Pilha que armazena os atendimentos efetuados durante o dia.

#### ✦ R3 · Lista de Médicos (Lista Encadeada): Lista circular de plantão. O médico atende e retorna ao final da fila de disponibilidade.

#### ✦ R4 · Relatório Final: Impressão de todo o histórico do topo à base utilizando uma pilha auxiliar para preservar os dados.

## ⋆˙⟡ ───── 𝑹𝒆𝒈𝒓𝒂𝒔 𝑻𝒆́𝒄𝒏𝒊𝒄𝒂𝒔 ───── ⋆˙⟡

#### 𓂃۶ৎ Proibido usar STL: Estruturas criadas manualmente.

#### 𓂃۶ৎ Gestão de Memória: Todo new possui seu respectivo delete (sem memory leak).

#### 𓂃۶ৎ Compilação Limpa: Compilado com -Wall sem warnings.

#### 𓂃۶ৎ Estrutura Base: Utilização exclusiva da struct No fornecida.

## ˙⟡ ───── 𝑪𝒐𝒎𝒐 𝑬𝒙𝒆𝒄𝒖𝒕𝒂𝒓 ───── ⋆˙⟡

### ˚➶ Compilação sem warnings (C++17):

#### g++ -std=c++17 -Wall -o atendimento atendimento_template.cpp


### ˚➶ Execução do programa:

#### Linux / macOS:

 ./atendimento


 #### Windows (PowerShell / Terminal):

.\atendimento.exe


## ⋆˙⟡ ───── 𝑬𝒙𝒆𝒎𝒑𝒍𝒐 𝒅𝒆 𝑺𝒂𝒊́𝒅𝒂 ───── ⋆˙⟡

###  ╔═══════════════════════════════════════════════════╗
###       ⋆˙⟡♡₊˚⊹.   .⊹˚₊♡⟡˙⋆ Sistema de Atendimento — Triagem Digital ⋆˙⟡♡₊˚⊹.   .⊹˚₊♡⟡˙⋆       
###  ╚═══════════════════════════════════════════════════╝

 #### Médicos disponíveis: Dra. Ana Lima ⤿ Dr. Bruno Costa ⤿ Dra. Carla Ramos

 #### Pacientes chegando:
 #### Próximo a ser atendido: Eduardo (urgencia=3)
 #### Total na fila: 4

 ### Simulação de atendimentos:
   #### [1] Dra. Ana Lima atende Eduardo (urgencia=3)
   #### [2] Dr. Bruno Costa atende Fernanda (urgencia=1)
   #### [3] Dra. Carla Ramos atende Gabriel (urgencia=2)
   #### [4] Dra. Ana Lima atende Helena (urgencia=1)

 #### Último atendimento registrado (peek): Dra. Ana Lima → Helena (urgencia=1)

 ### ✩࿐࿔  Relatório de Atendimentos ⋆˚𝜗𝜚˚⋆
  ####  1. Dra. Ana Lima → Helena (urgencia=1)
   #### 2. Dra. Carla Ramos → Gabriel (urgencia=2)
   #### 3. Dr. Bruno Costa → Fernanda (urgencia=1)
   #### 4. Dra. Ana Lima → Eduardo (urgencia=3)




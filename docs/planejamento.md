# 🖥️ PLANO DE ESTUDOS SISTEMAS OPERACIONAIS: 60 DIAS

**👤 Perfil:** Iniciante em Sistemas Operacionais (conhecimento básico de programação)  
**⏱️ Dedicação:** Flexível - aprenda no seu ritmo  
**📅 Início:** [Sua Data]  
**🎯 Conclusão:** [60 dias depois]  
**🎓 Meta:** Dominar Sistemas Operacionais do zero usando analogias, histórias e design instrucional

---

## 📑 ÍNDICE NAVEGÁVEL

**[FASE 1: Fundamentos de SO](#fase-1)** → Dias 1-14  
**[FASE 2: Gerenciamento de Processos](#fase-2)** → Dias 15-28  
**[FASE 3: Gerenciamento de Memória](#fase-3)** → Dias 29-42  
**[FASE 4: Sistemas de Arquivos e I/O](#fase-4)** → Dias 43-52  
**[FASE 5: Projeto Final](#fase-5)** → Dias 53-60

---

<a name="fase-1"></a>
# 🌟 FASE 1: FUNDAMENTOS DE SO (Dias 1-14)

**Objetivo:** Compreender a arquitetura e funções básicas de um sistema operacional

---

## 📅 DIA 1 - Introdução aos SO: O Maestro da Orquestra Digital

**📚 Recursos:**
- [Operating Systems: Three Easy Pieces - Introdução](http://pages.cs.wisc.edu/~remzi/OSTEP/)
- [Tanenbaum - Modern Operating Systems - Cap 1](https://www.pearson.com/en-us/subject-catalog/p/modern-operating-systems/P200000003295)
- [Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)
- [OSDev Wiki](https://wiki.osdev.org/)

**🎯 Tópicos:**
- O que é um Sistema Operacional
- História e evolução dos SO
- Componentes principais (kernel, shell, drivers)
- Tipos de SO (batch, tempo compartilhado, tempo real)
- Arquitetura em camadas
- System calls e API do SO

**💻 Exercício Prático:**
- Explorar comandos básicos do terminal
- Identificar processos em execução
- Visualizar estrutura de diretórios do sistema

**✅ Checkpoint:**
- [ ] Compreende o papel do SO
- [ ] Identifica componentes principais
- [ ] Navega pelo terminal com confiança

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais, tenho conhecimento básico de programação. Estou começando a aprender SO do zero, no meu primeiro dia de estudos.

Crie um material de estudo completo usando DESIGN INSTRUCIONAL e técnicas de aprendizagem efetiva sobre:

CONTEÚDO TÉCNICO:
1. Definição e propósito de um Sistema Operacional
2. História: DOS, Unix, Linux, Windows, MacOS
3. Componentes principais: kernel, shell, drivers, filesystem
4. Tipos de SO: batch, time-sharing, real-time, distributed
5. Arquitetura em camadas (hardware → kernel → API → aplicações)
6. System calls: interface entre aplicação e SO

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- Liste 3-5 objetivos claros, mensuráveis e específicos do dia
- Use verbos de ação (identificar, explicar, distinguir, demonstrar)

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Perguntas para conectar com experiências do aluno
- Analogia central: SO como "Maestro de uma Orquestra Digital"
- História introdutória envolvente (2-3 parágrafos)

📚 APRESENTAÇÃO DO CONTEÚDO:
- Informação em blocos pequenos (chunking)
- Linha do tempo visual da evolução dos SO
- DIAGRAMAS MERMAID/UML OBRIGATÓRIOS:
  * Diagrama de arquitetura em camadas do SO
  * Fluxograma de interação: aplicação → system call → kernel → hardware
  * Mapa mental dos componentes principais
  * Comparação visual entre tipos de SO
- Anatomia de um system call
- Glossário de termos técnicos

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo prático de system call
- Demonstração de comandos de terminal
- Visualização de processos do sistema

🎯 PRÁTICA GUIADA (APENAS 1 EXERCÍCIO COMPLETO):
- Exercício principal: Explorador do Sistema Operacional
  * Contexto e motivação do exercício
  * Objetivo claro do que será explorado
  * Especificação detalhada
  * Comandos para executar (Windows e Linux)
  * Dicas progressivas
  * Interpretação dos resultados
  * Variações opcionais para explorar
  * Conexão com mundo real

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de verificação
- Erros comuns e soluções
- Troubleshooting detalhado
- Auto-avaliação (3-5 perguntas reflexivas)

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus opcional
- Conexão com próximo dia
- Recursos extras para aprofundamento

TÉCNICAS PEDAGÓGICAS A USAR:
- Andragogia (aprendizagem de adultos)
- Storytelling (história do maestro)
- Scaffolding (suporte gradual)
- Chunking (informação em pedaços digestíveis)
- Dual coding (texto + visual)
- Elaboration (conexões com conhecimento prévio)
- Retrieval practice (questões de fixação)
- Spaced repetition (revisar conceitos anteriores)

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura em camadas do SO
2. Fluxograma de system call
3. Comparação entre tipos de SO
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Use MUITAS analogias do mundo real
- Explique como se fosse para uma pessoa sem conhecimento técnico
- Não assuma conhecimento prévio de SO
- Cada conceito técnico: analogia + explicação + diagrama + exemplo
- Intercale teoria e prática constantemente
- Tom encorajador e motivacional
- Celebre pequenas vitórias

Formato: markdown estruturado, muito visual, com diagramas Mermaid, analogias criativas e checkpoints.
```

---

## 📅 DIA 2 - Arquitetura de Hardware: A Fundação da Casa Digital

**📚 Recursos:**
- [Computer Organization and Design - Patterson & Hennessy](https://www.elsevier.com/books/computer-organization-and-design-risc-v-edition/patterson/978-0-12-820331-6)
- [CPU Architecture Explained](https://cpu.land/)
- [How Computers Really Work](https://howcomputersreallywork.com/)

**🎯 Tópicos:**
- Arquitetura Von Neumann vs Harvard
- CPU: registradores, ALU, Control Unit
- Hierarquia de memória (registradores, cache, RAM, disco)
- Barramentos (dados, endereço, controle)
- Modos de operação (user mode vs kernel mode)
- Interrupções e exceções

**💻 Exercício Prático:**
- Visualizar uso de CPU e memória
- Entender códigos de interrupção
- Simular execução de instruções

**✅ Checkpoint:**
- [ ] Entende arquitetura básica do computador
- [ ] Diferencia user mode e kernel mode
- [ ] Compreende hierarquia de memória

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre hardware. Dia 2 de estudos.

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre arquitetura de hardware relevante para SO:

CONTEÚDO TÉCNICO:
1. Arquitetura Von Neumann: componentes e funcionamento
2. CPU: registradores, ALU, unidade de controle
3. Hierarquia de memória: por que existe e como funciona
4. Barramentos: comunicação entre componentes
5. User mode vs Kernel mode: proteção e segurança
6. Interrupções e exceções: eventos assíncronos

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida do Dia 1
- Analogia central: "A Fundação da Casa Digital"
- História introdutória sobre arquitetura

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Diagrama de arquitetura Von Neumann
  * Hierarquia de memória (pirâmide)
  * Fluxograma de tratamento de interrupção
  * Comparação user mode vs kernel mode
- Tabela de tempos de acesso à memória
- Visualização de registradores da CPU

💡 DEMONSTRAÇÃO E MODELAGEM:
- Simulação de ciclo de instrução
- Exemplo de mudança de modo (user → kernel)
- Demonstração de interrupção de hardware

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Monitor de Sistema em Tempo Real
  * Observar uso de CPU por processo
  * Analisar consumo de memória
  * Identificar interrupções
  * Interpretar resultados
  * Contexto motivador
  * Especificação clara
  * Comandos passo a passo
  * Dicas progressivas
  * Análise guiada dos dados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns de interpretação
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Calcular tempo de acesso à memória
- Preparação para Dia 3
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogias visuais (casa, fundações, pisos)
- Exemplos do cotidiano
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura Von Neumann completa
2. Pirâmide de hierarquia de memória
3. Fluxograma de tratamento de interrupção
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Conectar com experiências cotidianas
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 3 - Boot Process: O Despertar da Máquina

**📚 Recursos:**
- [BIOS and UEFI Explained](https://www.happyassassin.net/posts/2014/01/25/uefi-boot-how-does-that-actually-work-then/)
- [Linux Boot Process](https://www.linuxjournal.com/content/linux-boot-process)
- [Windows Boot Process](https://learn.microsoft.com/en-us/windows-hardware/drivers/bringup/boot-and-uefi)

**🎯 Tópicos:**
- BIOS/UEFI: firmware inicial
- POST (Power-On Self-Test)
- Boot loader (GRUB, Windows Boot Manager)
- Carregamento do kernel
- Init/systemd: primeiro processo
- Runlevels e targets

**💻 Exercício Prático:**
- Analisar logs de boot
- Modificar ordem de boot
- Explorar configurações do GRUB

**✅ Checkpoint:**
- [ ] Compreende sequência de boot
- [ ] Identifica componentes de inicialização
- [ ] Navega em logs de boot

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre boot process. Dia 3 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre o processo de inicialização do sistema:

CONTEÚDO TÉCNICO:
1. BIOS vs UEFI: evolução e diferenças
2. POST (Power-On Self-Test): verificações iniciais
3. Boot loaders: GRUB, Windows Boot Manager
4. Carregamento do kernel na memória
5. Init systems: SysVinit, systemd, Upstart
6. Runlevels (SysV) e targets (systemd)

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida dos Dias 1-2
- Analogia central: "O Despertar da Máquina" - como acordar pela manhã
- História introdutória sobre o processo de inicialização

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Sequência completa do boot process
  * Comparação BIOS vs UEFI
  * Fluxograma de decisão do boot loader
  * Diagrama de targets do systemd
- Linha do tempo visual do boot
- Anatomia do arquivo de configuração do GRUB

💡 DEMONSTRAÇÃO E MODELAGEM:
- Passo a passo visual do boot
- Exemplo de arquivo grub.cfg
- Demonstração de systemd targets

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Analisando o Boot do Sistema
  * Visualizar mensagens de boot (dmesg)
  * Analisar tempo de boot (systemd-analyze)
  * Explorar configurações do GRUB
  * Modificar timeout do boot loader
  * Contexto motivador
  * Especificação clara
  * Comandos detalhados (Linux e Windows)
  * Dicas progressivas
  * Interpretação dos logs
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns durante boot
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Criar entrada personalizada no GRUB
- Preparação para Dia 4
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia do despertar matinal
- Exemplos visuais do processo
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Sequenciamento lógico
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Sequência completa do boot (power on → OS running)
2. Comparação visual BIOS vs UEFI
3. Fluxograma de decisões do boot loader
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Mostrar logs reais comentados
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 4 - Kernel: O Coração do Sistema

**📚 Recursos:**
- [Linux Kernel Map](https://makelinux.github.io/kernel/map/)
- [Kernel Architecture](https://www.kernel.org/doc/html/latest/kernel-hacking/hacking.html)
- [Monolithic vs Microkernel](https://wiki.osdev.org/Kernel_Designs)

**🎯 Tópicos:**
- Funções do kernel
- Tipos de kernel: monolítico, microkernel, híbrido
- Espaço do kernel vs espaço do usuário
- Módulos do kernel
- Device drivers
- Kernel panic e debugging

**💻 Exercício Prático:**
- Listar módulos do kernel carregados
- Visualizar logs do kernel (dmesg)
- Explorar /proc e /sys

**✅ Checkpoint:**
- [ ] Diferencia tipos de kernel
- [ ] Compreende papel do kernel
- [ ] Interpreta mensagens do kernel

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre kernel. Dia 4 de estudos.

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre o kernel do sistema operacional:

CONTEÚDO TÉCNICO:
1. O que é o kernel e suas responsabilidades principais
2. Tipos de kernel: monolítico (Linux), microkernel (Minix), híbrido (Windows NT)
3. Kernel space vs User space: isolamento e proteção
4. Módulos do kernel: carregamento dinâmico
5. Device drivers: ponte com hardware
6. Kernel panic: quando tudo dá errado

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida dos Dias 1-3
- Analogia central: "O Coração do Sistema" - órgão vital
- História introdutória sobre a importância do kernel

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Comparação visual: monolítico vs microkernel vs híbrido
  * Diagrama de camadas: kernel space vs user space
  * Arquitetura do Linux kernel (subsistemas)
  * Fluxo de carregamento de módulo
- Tabela comparativa de tipos de kernel
- Visualização de subsistemas do kernel

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de interação kernel-userspace
- Demonstração de lsmod, modprobe
- Exploração de /proc/sys/kernel

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Explorando o Kernel em Ação
  * Listar módulos carregados (lsmod)
  * Visualizar logs do kernel (dmesg, journalctl -k)
  * Explorar /proc e /sys
  * Carregar e descarregar módulo
  * Analisar informações do kernel (uname -a)
  * Contexto motivador
  * Especificação clara
  * Comandos detalhados (Linux e Windows equivalentes)
  * Dicas progressivas
  * Interpretação dos resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns de interpretação
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Investigar causa de kernel panic em log
- Preparação para Dia 5
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia do coração e sistema circulatório
- Exemplos visuais de arquiteturas
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Comparação arquitetural: monolítico vs microkernel vs híbrido
2. Separação kernel space e user space
3. Subsistemas principais do Linux kernel
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Mostrar exemplos reais de sistemas
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 5 - System Calls: A Ponte Entre Mundos

**📚 Recursos:**
- [Linux System Calls Table](https://filippo.io/linux-syscall-table/)
- [System Call Implementation](http://man7.org/linux/man-pages/man2/syscalls.2.html)
- [Windows API vs POSIX](https://learn.microsoft.com/en-us/windows/win32/api/)

**🎯 Tópicos:**
- O que são system calls
- Tabela de system calls
- Transição user → kernel mode
- Principais categorias: processo, arquivo, memória, rede
- POSIX standard
- Diferenças Windows vs Linux

**💻 Exercício Prático:**
- Rastrear system calls com strace/Process Monitor
- Programar sistema call básico em C
- Comparar chamadas entre sistemas

**✅ Checkpoint:**
- [ ] Identifica system calls em código
- [ ] Usa ferramentas de rastreamento
- [ ] Compreende fluxo de execução

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre system calls. Dia 5 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre system calls:

CONTEÚDO TÉCNICO:
1. Definição de system call: interface kernel-userspace
2. Como funcionam: trap instruction, mode switch
3. Categorias principais: processo (fork, exec), arquivo (open, read, write), memória (mmap, brk), rede (socket)
4. POSIX standard: portabilidade
5. Diferenças entre sistemas: Linux (POSIX) vs Windows (Win32 API)
6. Ferramentas de rastreamento: strace (Linux), Process Monitor (Windows)

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida dos Dias 1-4 (especialmente user/kernel mode)
- Analogia central: "A Ponte Entre Mundos" - fronteira controlada
- História introdutória sobre comunicação segura

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Fluxo completo de uma system call (app → biblioteca → kernel → hardware)
  * Diagrama de sequência: transição user mode → kernel mode
  * Taxonomia das system calls por categoria
  * Comparação POSIX vs Win32 API
- Tabela das system calls mais comuns
- Anatomia de uma system call em código

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de código com system calls (open, read, write, close)
- Demonstração de strace passo a passo
- Visualização de mode switch

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Rastreando System Calls na Prática
  * Instalar ferramentas (strace, ltrace)
  * Rastrear programa simples (ls, cat)
  * Identificar system calls específicas
  * Programar exemplo em C usando syscalls
  * Comparar alto nível vs syscall direta
  * Contexto motivador
  * Especificação clara
  * Código completo comentado
  * Comandos detalhados
  * Dicas progressivas
  * Interpretação dos resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir library call com syscall)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Criar wrapper para system call
- Preparação para Dia 6
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia da ponte/fronteira controlada
- Exemplos visuais de transição
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on coding
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo detalhado de uma system call (todas as camadas)
2. Diagrama de sequência: user → kernel mode switch
3. Taxonomia/classificação das system calls
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código real executável
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 6 - Processos vs Threads: Cidadãos do Sistema

**📚 Recursos:**
- [Process Management](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-intro.pdf)
- [Threads Explained](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-intro.pdf)
- [Multithreading Guide](https://www.backblaze.com/blog/whats-the-diff-programs-processes-and-threads/)

**🎯 Tópicos:**
- Definição de processo
- Process Control Block (PCB)
- Estados do processo (new, ready, running, waiting, terminated)
- Diagrama de estados
- Threads: lightweight processes
- Diferenças processo vs thread
- Multithreading

**💻 Exercício Prático:**
- Criar e gerenciar processos
- Visualizar PCB de processos
- Implementar programa multithread básico

**✅ Checkpoint:**
- [ ] Diferencia processo e thread
- [ ] Identifica estados de processo
- [ ] Cria processos e threads

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre processos e threads. Dia 6 de estudos.

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre processos e threads:

CONTEÚDO TÉCNICO:
1. Definição de processo: programa em execução
2. Process Control Block (PCB): estrutura de dados do processo
3. Estados do processo: new, ready, running, waiting, terminated
4. Diagrama de transição de estados
5. Threads: unidades leves de execução
6. Diferenças fundamentais: processo vs thread (memória, overhead, comunicação)
7. Modelos de threading: user-level, kernel-level, híbrido
8. Multithreading: vantagens e desafios

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida dos Dias 1-5
- Analogia central: "Cidadãos do Sistema" - pessoas (processos) e suas tarefas (threads)
- História introdutória sobre organização e multitarefa

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Diagrama de estados do processo (completo com transições)
  * Estrutura do PCB (campos principais)
  * Comparação visual: processo vs thread (memória compartilhada)
  * Modelos de threading (user-level, kernel-level, híbrido)
- Tabela comparativa processo vs thread
- Visualização de memória compartilhada em threads

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de código criando processo (fork)
- Exemplo de código criando thread (pthread)
- Demonstração de ps, top, htop

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Criando e Gerenciando Processos e Threads
  * Visualizar processos (ps aux, top, /proc/[pid])
  * Criar processo com fork() em C
  * Criar threads com pthread
  * Observar diferenças de overhead
  * Comparar uso de memória
  * Contexto motivador
  * Especificação clara
  * Código completo comentado (C e Python)
  * Comandos detalhados
  * Dicas progressivas
  * Interpretação dos resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir processo com programa, thread com processo)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Programa multithread com sincronização básica
- Preparação para Dia 7
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de pessoas e tarefas
- Exemplos visuais de estados
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on coding
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Diagrama de estados do processo (5 estados + transições)
2. Estrutura do PCB detalhada
3. Comparação memória: processo isolado vs threads compartilhadas
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código real executável
- Visualizações de memória
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 7 - Shells e CLI: A Interface de Comando

**📚 Recursos:**
- [Bash Guide](https://mywiki.wooledge.org/BashGuide)
- [PowerShell Documentation](https://learn.microsoft.com/en-us/powershell/)
- [Shell Scripting Tutorial](https://www.shellscript.sh/)

**🎯 Tópicos:**
- O que é uma shell
- Tipos de shell (bash, zsh, fish, PowerShell)
- Comandos essenciais (ls, cd, ps, grep, find)
- Pipes e redirecionamento
- Variáveis de ambiente
- Scripts básicos

**💻 Exercício Prático:**
- Dominar 20 comandos essenciais
- Criar script de automação simples
- Usar pipes para processar dados

**✅ Checkpoint:**
- [ ] Domina comandos básicos
- [ ] Cria scripts funcionais
- [ ] Usa pipes eficientemente

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre shells e CLI. Dia 7 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre shells e interface de linha de comando:

CONTEÚDO TÉCNICO:
1. O que é uma shell: interpretador de comandos
2. Tipos de shell: bash, zsh, fish, csh, PowerShell
3. 20 comandos essenciais: navegação (cd, ls, pwd), manipulação (cp, mv, rm, mkdir), visualização (cat, less, head, tail), busca (grep, find), processos (ps, top, kill), permissões (chmod, chown)
4. Pipes (|) e redirecionamento (>, <, >>)
5. Variáveis de ambiente (PATH, HOME, etc)
6. Shell scripting: automação básica

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida dos Dias 1-6
- Analogia central: "O Volante do Sistema" - controle direto
- História introdutória sobre poder da linha de comando

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Arquitetura: usuário → shell → kernel
  * Fluxograma de interpretação de comando
  * Diagrama de pipes e redirecionamento
  * Família de shells (árvore genealógica)
- Tabela dos 20 comandos essenciais (com exemplos)
- Sintaxe visual de pipes

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplos de cada comando com saída real
- Demonstração de pipes encadeados
- Script de automação comentado

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Dominando a Linha de Comando
  * Praticar 20 comandos essenciais
  * Combinar comandos com pipes
  * Criar script de backup automatizado
  * Configurar variáveis de ambiente
  * Personalizar prompt
  * Contexto motivador
  * Especificação clara
  * Comandos para Linux e Windows (PowerShell)
  * Exemplos progressivos (simples → complexo)
  * Dicas progressivas
  * Scripts completos comentados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de comandos dominados
- Erros comuns (sintaxe, permissões)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Script de monitoramento do sistema
- Preparação para Dia 8 (revisão)
- Recursos complementares (cheat sheets)

TÉCNICAS PEDAGÓGICAS:
- Analogia do controle/volante
- Exemplos práticos do dia a dia
- Storytelling
- Scaffolding (comandos simples → complexos)
- Chunking
- Dual coding
- Hands-on prático intenso
- Repetição espaçada
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura: usuário → shell → kernel → hardware
2. Fluxograma de interpretação e execução de comando
3. Visualização de pipes e redirecionamento
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Exemplos executáveis para praticar
- Cheat sheet visual
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 8 - Revisão Semana 1 + Mini-Projeto

**🎯 Objetivo:** Consolidar conhecimentos da primeira semana

**📝 Atividades:**
- Revisão de todos os conceitos (Dias 1-7)
- Quiz abrangente (20 questões)
- Mapa mental geral da Fase 1

**💻 Mini-Projeto:**
**"Monitor de Sistema Personalizado"**
- Criar script que mostra:
  * Informações do SO e kernel
  * Processos em execução
  * Uso de CPU e memória
  * Tempo de uptime
  * Últimas entradas de log

**✅ Checkpoint:**
- [ ] Completou revisão
- [ ] Acertou 80%+ no quiz
- [ ] Mini-projeto funcionando

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da primeira semana. Dia 8 de estudos.

Crie material de REVISÃO E CONSOLIDAÇÃO usando DESIGN INSTRUCIONAL para a primeira semana:

CONTEÚDO A REVISAR (Dias 1-7):
1. Introdução aos SO: componentes, tipos, arquitetura
2. Arquitetura de hardware: Von Neumann, CPU, memória, interrupções
3. Boot process: BIOS/UEFI, boot loader, init
4. Kernel: tipos, espaço kernel/user, módulos
5. System calls: ponte kernel-user, categorias, POSIX
6. Processos e threads: PCB, estados, diferenças
7. Shells e CLI: comandos, pipes, scripts

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DA REVISÃO:
- Consolidar conhecimentos da semana 1
- Identificar gaps de aprendizagem
- Preparar para semana 2
- Integrar conceitos através de projeto prático

🔄 REVISÃO INTEGRADA:
- Mapa mental COMPLETO integrando todos os 7 dias
- Resumo executivo de cada dia (3-5 pontos principais)
- Conexões entre conceitos (como tudo se relaciona)
- DIAGRAMAS MERMAID:
  * Visão geral integrada: hardware → boot → kernel → processos → interface
  * Mapa mental de toda a semana
  * Diagrama de dependências entre conceitos

📝 QUIZ ABRANGENTE (20 questões):
- 3 questões de múltipla escolha por dia (dias 1-7)
- Questões integradoras (conectam múltiplos conceitos)
- Níveis: fácil (40%), médio (40%), difícil (20%)
- Gabarito com explicações detalhadas
- Identificação de áreas para reforço

💻 MINI-PROJETO: "Monitor de Sistema Personalizado"
- Descrição completa do projeto
- Objetivos de aprendizagem do projeto
- Especificação funcional detalhada:
  * Exibir informações do SO (nome, versão, arquitetura)
  * Mostrar informações do kernel (versão, módulos)
  * Listar processos em execução (top 10 por CPU/memória)
  * Exibir uso de CPU e memória em tempo real
  * Mostrar tempo de uptime
  * Exibir últimas 20 linhas de log do sistema
  * Interface formatada e amigável
- Estrutura do projeto (arquivos, organização)
- Implementação passo a passo:
  * Passo 1: Informações básicas do sistema
  * Passo 2: Processos e recursos
  * Passo 3: Logs e uptime
  * Passo 4: Formatação e interface
- Código completo comentado (Bash/Python para Linux, PowerShell para Windows)
- Testes e validação
- Extensões opcionais (recursos adicionais)

🎯 PRÁTICA DE FIXAÇÃO:
- Exercícios rápidos de cada conceito
- Desafios de integração
- Troubleshooting scenarios

🚀 PREPARAÇÃO PARA SEMANA 2:
- Preview dos tópicos da semana 2
- Pré-requisitos confirmados
- Motivação e roadmap

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice (trazer da memória)
- Spaced repetition (revisar após intervalo)
- Interleaving (misturar conceitos)
- Elaboration (explicar com suas palavras)
- Conexões visuais (mapas mentais)
- Projeto integrativo
- Auto-avaliação

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 3):
1. Mapa mental integrado de toda a semana 1
2. Diagrama de fluxo: do hardware ao usuário
3. Arquitetura do mini-projeto

IMPORTANTE:
- Foco em integração de conceitos
- Identificar lacunas de aprendizagem
- Tom encorajador e motivacional
- Celebrar progresso da semana
- Projeto deve ser EXECUTÁVEL e ÚTIL
- Preparar confiança para semana 2

Formato: markdown estruturado, visual, com diagramas Mermaid, quiz completo e projeto detalhado.
```

---

## 📅 DIA 9 - Virtualização: Múltiplos Sistemas em Um

**📚 Recursos:**
- [Virtualization Basics](https://www.redhat.com/en/topics/virtualization/what-is-virtualization)
- [KVM, VirtualBox, VMware Comparison](https://www.nakivo.com/blog/kvm-vs-vmware-comparison/)
- [Containers vs VMs](https://www.docker.com/resources/what-container/)

**🎯 Tópicos:**
- Conceito de virtualização
- Hipervisores tipo 1 vs tipo 2
- VMs vs Containers
- Paravirtualização
- Isolamento e segurança
- Uso prático

**💻 Exercício Prático:**
- Instalar VirtualBox
- Criar VM Linux
- Explorar Docker containers

**✅ Checkpoint:**
- [ ] Compreende virtualização
- [ ] Diferencia VMs e containers
- [ ] Cria e gerencia VMs

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre virtualização. Dia 9 de estudos (início da semana 2).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre virtualização:

CONTEÚDO TÉCNICO:
1. Conceito de virtualização: executar múltiplos SO em um hardware
2. Hipervisores tipo 1 (bare-metal): VMware ESXi, Xen, KVM
3. Hipervisores tipo 2 (hosted): VirtualBox, VMware Workstation, QEMU
4. Máquinas virtuais: isolamento completo
5. Containers: isolamento leve (Docker, LXC)
6. Comparação VMs vs Containers: overhead, isolamento, casos de uso
7. Paravirtualização: otimização com cooperação do guest
8. Segurança e isolamento

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão rápida da semana 1
- Analogia central: "Apartamentos no Mesmo Prédio" - compartilhar recursos
- História introdutória sobre evolução da virtualização

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Comparação arquitetural: tipo 1 vs tipo 2 vs containers
  * Camadas de virtualização (hardware → hypervisor → VMs)
  * Diferenças VMs vs Containers (memória, kernel, overhead)
  * Timeline de tecnologias de virtualização
- Tabela comparativa: VMs vs Containers
- Visualização de isolamento

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de criação de VM passo a passo
- Demonstração de Docker container
- Comparação de consumo de recursos

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Primeiros Passos com Virtualização
  * Instalar VirtualBox ou VMware Player
  * Baixar ISO do Linux (Ubuntu/Fedora)
  * Criar primeira máquina virtual
  * Configurar recursos (CPU, RAM, disco)
  * Instalar sistema guest
  * Testar isolamento
  * [OPCIONAL] Instalar Docker
  * [OPCIONAL] Executar container básico
  * Contexto motivador
  * Especificação clara
  * Guia passo a passo com screenshots conceituais
  * Dicas progressivas
  * Troubleshooting comum
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns de configuração
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Criar ambiente de teste multi-VM
- Preparação para Dia 10
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de apartamentos/prédio
- Exemplos visuais de arquiteturas
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on prático
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Comparação arquitetural: bare-metal vs hosted vs containers
2. Camadas de abstração em cada tecnologia
3. Overhead comparativo (recursos)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Guia visual de instalação
- Foco em conceitos antes de ferramentas
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 10 - Comunicação Entre Processos (IPC): Conversas do Sistema

**📚 Recursos:**
- [IPC Mechanisms](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf)
- [POSIX IPC](https://man7.org/linux/man-pages/man7/shm_overview.7.html)
- [IPC Tutorial](https://beej.us/guide/bgipc/)

**🎯 Tópicos:**
- Por que IPC é necessário
- Pipes e named pipes (FIFO)
- Message queues
- Shared memory
- Semáforos
- Sockets

**💻 Exercício Prático:**
- Implementar comunicação via pipe
- Criar memória compartilhada
- Sincronizar com semáforos

**✅ Checkpoint:**
- [ ] Conhece mecanismos de IPC
- [ ] Implementa IPC básico
- [ ] Entende sincronização

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre IPC (Inter-Process Communication). Dia 10 de estudos.

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre comunicação entre processos:

CONTEÚDO TÉCNICO:
1. Por que IPC: processos isolados precisam se comunicar
2. Pipes: comunicação unidirecional (| no shell)
3. Named pipes (FIFOs): pipes persistentes
4. Message queues: fila de mensagens estruturadas
5. Shared memory: região de memória compartilhada (mais rápido)
6. Semáforos: sincronização de acesso
7. Sockets: comunicação local e em rede
8. Comparação: quando usar cada mecanismo

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: processos isolados (Dia 6)
- Analogia central: "Conversas Entre Vizinhos" - diferentes formas de comunicação
- História introdutória sobre necessidade de IPC

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Taxonomia de mecanismos IPC
  * Fluxo de comunicação em cada mecanismo (pipes, shared memory, etc)
  * Comparação de velocidade e complexidade
  * Diagrama de sequência: processos se comunicando
- Tabela comparativa de todos os mecanismos IPC
- Visualização de memória compartilhada

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de pipe em shell (ls | grep)
- Código C com pipes
- Código C com shared memory
- Exemplo de semáforo

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Implementando IPC na Prática
  * Exemplo 1: Pipe anônimo (pai-filho)
  * Exemplo 2: Named pipe (processos independentes)
  * Exemplo 3: Shared memory com sincronização
  * Exemplo 4: Message queue simples
  * Contexto motivador
  * Especificação clara
  * Código completo comentado (C e Python)
  * Dicas progressivas
  * Compilação e execução
  * Interpretação dos resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (race conditions, deadlocks)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Chat local usando sockets
- Preparação para Dia 11
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de comunicação entre vizinhos
- Exemplos visuais de cada mecanismo
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on coding
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Taxonomia/classificação dos mecanismos IPC
2. Fluxos de comunicação de cada mecanismo
3. Comparação de performance e complexidade
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código executável e testado
- Foco em conceitos antes de implementação
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 11 - Deadlocks: O Impasse Mortal

**📚 Recursos:**
- [Deadlock Explanation](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-bugs.pdf)
- [Dining Philosophers Problem](https://en.wikipedia.org/wiki/Dining_philosophers_problem)
- [Deadlock Prevention](https://www.geeksforgeeks.org/deadlock-prevention/)

**🎯 Tópicos:**
- Definição de deadlock
- 4 condições necessárias (Coffman)
- Resource allocation graph
- Estratégias: prevenção, detecção, recuperação
- Algoritmo do banqueiro
- Exemplos clássicos (jantar dos filósofos)

**💻 Exercício Prático:**
- Criar programa com deadlock intencional
- Implementar prevenção de deadlock
- Visualizar resource allocation graph

**✅ Checkpoint:**
- [ ] Identifica condições de deadlock
- [ ] Previne deadlocks
- [ ] Aplica algoritmo do banqueiro

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre deadlocks. Dia 11 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre deadlocks:

CONTEÚDO TÉCNICO:
1. Definição de deadlock: impasse onde processos esperam eternamente
2. Quatro condições necessárias de Coffman: mutual exclusion, hold and wait, no preemption, circular wait
3. Resource Allocation Graph (RAG): visualização de alocação de recursos
4. Detecção de deadlock: algoritmos e ciclos no RAG
5. Prevenção: quebrar uma das 4 condições
6. Evitação: algoritmo do banqueiro (Dijkstra)
7. Recuperação: terminação de processos, preemption de recursos
8. Exemplos clássicos: jantar dos filósofos, problema dos leitores-escritores

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: IPC e sincronização (Dia 10)
- Analogia central: "Cruzamento de Trânsito Bloqueado" - impasse circular
- História introdutória sobre deadlocks famosos

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Resource Allocation Graph (RAG) com e sem deadlock
  * Diagrama das 4 condições de Coffman
  * Fluxograma do algoritmo do banqueiro
  * Visualização do jantar dos filósofos
- Tabela de estratégias (prevenção, evitação, detecção, recuperação)
- Árvore de decisão para lidar com deadlocks

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de código com deadlock
- Demonstração de detecção de ciclo em RAG
- Simulação do algoritmo do banqueiro
- Solução do jantar dos filósofos

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Criando e Resolvendo Deadlocks
  * Parte 1: Criar deadlock intencional (2 threads, 2 locks)
  * Parte 2: Visualizar com RAG
  * Parte 3: Prevenir com ordenação de locks
  * Parte 4: Implementar algoritmo do banqueiro simplificado
  * Parte 5: Simular jantar dos filósofos
  * Contexto motivador
  * Especificação clara
  * Código completo comentado (C, Python, Java)
  * Dicas progressivas
  * Análise de cada solução
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (não identificar circular wait)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Resolver problema dos leitores-escritores
- Preparação para Dia 12
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia do cruzamento de trânsito
- Exemplos visuais de RAG
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on coding
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Resource Allocation Graph com deadlock
2. As 4 condições de Coffman (visual)
3. Fluxograma do algoritmo do banqueiro
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código que demonstra o problema E a solução
- Visualizações de grafos
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 12 - Segurança e Proteção: Guardiões do Sistema

**📚 Recursos:**
- [OS Security Fundamentals](https://www.cisecurity.org/insights/white-papers/cis-controls-v8)
- [Linux Security Modules](https://www.kernel.org/doc/html/latest/admin-guide/LSM/index.html)
- [Windows Security](https://learn.microsoft.com/en-us/windows/security/)

**🎯 Tópicos:**
- Princípios de segurança (CIA triad)
- Autenticação vs autorização
- Controle de acesso (DAC, MAC, RBAC)
- Permissões de arquivo (rwx)
- Usuários e grupos
- Princípio do menor privilégio

**💻 Exercício Prático:**
- Configurar permissões de arquivo
- Criar usuários e grupos
- Implementar controle de acesso

**✅ Checkpoint:**
- [ ] Compreende modelos de segurança
- [ ] Configura permissões corretamente
- [ ] Aplica princípios de segurança

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre segurança e proteção. Dia 12 de estudos.

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre segurança em sistemas operacionais:

CONTEÚDO TÉCNICO:
1. Princípios fundamentais: CIA triad (Confidentiality, Integrity, Availability)
2. Autenticação: verificar identidade (senhas, biometria, tokens)
3. Autorização: controle de acesso a recursos
4. Modelos de controle de acesso: DAC (Discretionary), MAC (Mandatory), RBAC (Role-Based)
5. Permissões de arquivo Unix: rwx (read, write, execute) para owner, group, others
6. Usuários e grupos: organização e hierarquia
7. Princípio do menor privilégio: acesso mínimo necessário
8. SELinux e AppArmor: MAC no Linux
9. Vulnerabilidades comuns: privilege escalation, buffer overflow

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: user mode vs kernel mode (Dia 2)
- Analogia central: "Porteiros e Crachás" - controle de acesso
- História introdutória sobre segurança de sistemas

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * CIA Triad (triângulo visual)
  * Fluxo: autenticação → autorização → acesso
  * Comparação: DAC vs MAC vs RBAC
  * Estrutura de permissões Unix (visual de bits)
- Tabela de permissões Unix (octal e simbólica)
- Matriz de controle de acesso

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de chmod, chown, chgrp
- Demonstração de criação de usuários e grupos
- Exemplo de ACL (Access Control List)
- Visualização de /etc/passwd e /etc/shadow

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Configurando Segurança no Sistema
  * Criar usuários e grupos
  * Configurar permissões de arquivos e diretórios
  * Implementar princípio do menor privilégio
  * Usar sudo corretamente
  * Analisar logs de autenticação
  * Configurar ACL avançadas
  * Contexto motivador (cenário de empresa)
  * Especificação clara
  * Comandos detalhados (Linux e Windows)
  * Dicas progressivas
  * Verificação de segurança
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos de segurança
- Erros comuns (permissões 777, rodar tudo como root)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Auditoria de segurança de um sistema
- Preparação para Dia 13
- Recursos complementares (OWASP, CIS)

TÉCNICAS PEDAGÓGICAS:
- Analogia de porteiros e controle de acesso
- Exemplos visuais de permissões
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on prático
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. CIA Triad visual
2. Fluxo de autenticação e autorização
3. Comparação de modelos de controle de acesso
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Exemplos práticos de configuração
- Foco em boas práticas
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 13 - Logs e Monitoramento: Os Olhos do Sistema

**📚 Recursos:**
- [Linux Logging](https://www.loggly.com/ultimate-guide/linux-logging-basics/)
- [Syslog Protocol](https://tools.ietf.org/html/rfc5424)
- [Windows Event Viewer](https://learn.microsoft.com/en-us/windows/win32/eventlog/event-logging)

**🎯 Tópicos:**
- Importância dos logs
- Syslog e journald
- Níveis de log (emergency, alert, critical...)
- Localização de logs no sistema
- Ferramentas de análise
- Rotação de logs

**💻 Exercício Prático:**
- Analisar logs do sistema
- Configurar logging personalizado
- Criar dashboard de monitoramento

**✅ Checkpoint:**
- [ ] Navega pelos logs do sistema
- [ ] Interpreta mensagens de log
- [ ] Configura logging

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre logs e monitoramento. Dia 13 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre logging e monitoramento de sistemas:

CONTEÚDO TÉCNICO:
1. Importância dos logs: debugging, auditoria, monitoramento
2. Syslog: protocolo padrão de logging (RFC 5424)
3. Journald (systemd): sistema moderno de logging no Linux
4. Níveis de severidade: emergency (0), alert (1), critical (2), error (3), warning (4), notice (5), info (6), debug (7)
5. Localização de logs: /var/log (Linux), Event Viewer (Windows)
6. Principais logs: syslog, kern.log, auth.log, dmesg, messages
7. Ferramentas de análise: tail, grep, awk, less, journalctl
8. Rotação de logs: logrotate, compressão, retenção
9. Monitoramento em tempo real: top, htop, iotop, netstat

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: processos, segurança (Dias 6, 12)
- Analogia central: "Câmeras de Segurança do Sistema" - registro de eventos
- História introdutória sobre debugging com logs

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Arquitetura de logging: aplicação → syslog/journald → arquivos
  * Níveis de severidade (pirâmide)
  * Fluxo de rotação de logs
  * Mapa de diretórios /var/log
- Tabela de níveis de log com exemplos
- Anatomia de uma mensagem syslog

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de análise de log com tail, grep
- Demonstração de journalctl (filtros, tempo)
- Exemplo de configuração de logrotate
- Visualização de Event Viewer (Windows)

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Dominando Logs e Monitoramento
  * Explorar /var/log (Linux) ou Event Viewer (Windows)
  * Usar tail -f para monitoramento em tempo real
  * Filtrar logs com grep e awk
  * Usar journalctl (filtros por tempo, severidade, serviço)
  * Analisar logs de autenticação (login failures)
  * Configurar logrotate
  * Criar script de monitoramento
  * Contexto motivador (troubleshooting)
  * Especificação clara
  * Comandos detalhados
  * Dicas progressivas
  * Interpretação de logs reais
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (não usar filtros, perder contexto)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Criar sistema de alertas baseado em logs
- Preparação para Dia 14 (revisão da fase)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de câmeras de segurança
- Exemplos visuais de logs
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on prático intenso
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura de logging completa
2. Pirâmide de níveis de severidade
3. Fluxo de rotação de logs
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Exemplos de logs reais
- Foco em troubleshooting prático
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 14 - Revisão Fase 1 + Projeto Integrador

**🎯 Objetivo:** Consolidar TODA a Fase 1

**📝 Atividades:**
- Revisão completa (Dias 1-13)
- Quiz final da fase (30 questões)
- Mapa mental integrado

**💻 PROJETO INTEGRADOR:**
**"Sistema de Informações do SO"**

Criar um programa completo que:
1. Exibe informações do SO e hardware
2. Lista processos e threads
3. Mostra uso de recursos
4. Analisa logs recentes
5. Verifica segurança básica
6. Gera relatório em HTML

**Especificações:**
- Usar system calls
- Implementar IPC entre módulos
- Logs estruturados
- Interface CLI interativa
- Documentação completa

**✅ Checkpoint:**
- [ ] Revisão completa
- [ ] 85%+ no quiz
- [ ] Projeto funcionando
- [ ] Pronto para Fase 2

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da FASE 1 COMPLETA. Dia 14 de estudos.

Crie material de REVISÃO ABRANGENTE E PROJETO INTEGRADOR usando DESIGN INSTRUCIONAL para toda a Fase 1:

CONTEÚDO A REVISAR (Dias 1-13):
1. Introdução aos SO: componentes, tipos, arquitetura
2. Arquitetura de hardware: Von Neumann, CPU, memória, interrupções
3. Boot process: BIOS/UEFI, boot loader, init
4. Kernel: tipos, espaço kernel/user, módulos
5. System calls: ponte kernel-user, categorias, POSIX
6. Processos e threads: PCB, estados, diferenças
7. Shells e CLI: comandos, pipes, scripts
8. [Revisão semana 1 + Mini-projeto]
9. Virtualização: hipervisores, VMs, containers
10. IPC: pipes, shared memory, semáforos, sockets
11. Deadlocks: condições, prevenção, algoritmo do banqueiro
12. Segurança: CIA, controle de acesso, permissões
13. Logs e monitoramento: syslog, journald, análise

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DA REVISÃO DA FASE:
- Consolidar TODOS os conhecimentos da Fase 1
- Integrar conceitos em visão holística
- Identificar gaps remanescentes
- Aplicar conhecimentos em projeto complexo
- Preparar para Fase 2 (Processos)

🔄 REVISÃO INTEGRADA COMPLETA:
- Mapa mental GIGANTE integrando TODOS os 13 dias
- Resumo executivo de cada dia (3-4 pontos principais)
- Conexões entre todos os conceitos
- Visão geral: da inicialização ao monitoramento
- DIAGRAMAS MERMAID:
  * Visão integrada completa da Fase 1
  * Jornada: power on → boot → kernel → processos → segurança → monitoramento
  * Mapa mental detalhado
  * Diagrama de dependências entre conceitos

📝 QUIZ FINAL DA FASE (30 questões):
- 2-3 questões por tópico (dias 1-13)
- 5 questões integradoras (conectam múltiplos conceitos)
- Níveis: fácil (30%), médio (50%), difícil (20%)
- Gabarito com explicações detalhadas
- Análise de áreas para reforço

💻 PROJETO INTEGRADOR: "Sistema de Informações e Monitoramento do SO"

**Descrição completa:**
Sistema abrangente que integra TODOS os conceitos da Fase 1

**Objetivos de aprendizagem:**
- Aplicar system calls
- Gerenciar processos e threads
- Implementar IPC
- Aplicar segurança
- Trabalhar com logs
- Integrar conhecimentos

**Especificação funcional detalhada:**

MÓDULO 1: Informações do Sistema
- Nome, versão, arquitetura do SO
- Informações do kernel (versão, módulos carregados)
- Informações de hardware (CPU, memória, disco)
- Tempo de boot e uptime

MÓDULO 2: Gerenciamento de Processos
- Listar processos em execução
- Top 10 por CPU e memória
- Árvore de processos (parent-child)
- Estados dos processos
- Threads por processo

MÓDULO 3: Monitoramento de Recursos
- Uso de CPU (total e por core)
- Uso de memória (RAM, swap)
- Uso de disco (I/O, espaço)
- Monitoramento em tempo real

MÓDULO 4: Análise de Logs
- Ler últimos 50 logs do sistema
- Filtrar por severidade
- Identificar eventos críticos
- Estatísticas de eventos

MÓDULO 5: Verificação de Segurança
- Listar usuários e grupos
- Verificar permissões de arquivos críticos
- Identificar processos rodando como root
- Checar logs de autenticação falha

MÓDULO 6: Relatório e Interface
- Interface CLI interativa (menu)
- Geração de relatório HTML
- Exportação de dados (JSON/CSV)
- Dashboard visual

**Requisitos técnicos:**
- IPC entre módulos (pipes ou shared memory)
- Uso direto de system calls (não apenas bibliotecas)
- Logging estruturado do próprio sistema
- Tratamento de erros robusto
- Documentação completa

**Estrutura do projeto:**
```
system-monitor/
├── src/
│   ├── main.c/py
│   ├── sysinfo.c/py
│   ├── process.c/py
│   ├── resources.c/py
│   ├── logs.c/py
│   ├── security.c/py
│   └── report.c/py
├── include/
│   └── common.h
├── docs/
│   ├── README.md
│   ├── ARCHITECTURE.md
│   └── API.md
├── tests/
└── Makefile
```

**Implementação passo a passo:**

Passo 1: Setup e Arquitetura (2h)
- Estrutura de diretórios
- Definir interfaces entre módulos
- Setup de comunicação IPC

Passo 2: Módulo de Sistema (2h)
- Implementar coleta de informações do SO
- System calls: uname, sysinfo
- Parsing de /proc

Passo 3: Módulo de Processos (3h)
- Listar processos (/proc/[pid])
- Árvore de processos
- Informações de threads

Passo 4: Módulo de Recursos (2h)
- CPU: /proc/stat
- Memória: /proc/meminfo
- Disco: statvfs

Passo 5: Módulo de Logs (2h)
- Integração com syslog/journald
- Parsing e filtragem
- Estatísticas

Passo 6: Módulo de Segurança (2h)
- Análise de usuários e grupos
- Verificação de permissões
- Auditoria básica

Passo 7: Interface e Relatório (3h)
- Menu interativo
- Geração de HTML
- Integração de módulos

Passo 8: Testes e Documentação (2h)
- Testes de cada módulo
- Integração
- Documentação final

**Código exemplo (estrutura base):**
[Fornecer esqueleto de código em C e Python]

**Critérios de avaliação:**
- Funcionalidade completa (40%)
- Uso correto de conceitos (30%)
- Qualidade de código (15%)
- Documentação (15%)

🎯 EXERCÍCIOS DE FIXAÇÃO:
- Questões rápidas de cada conceito
- Desafios de integração
- Troubleshooting scenarios

🚀 PREPARAÇÃO PARA FASE 2:
- Preview: Gerenciamento de Processos (Dias 15-28)
- Tópicos: CPU scheduling, sincronização, concorrência
- Pré-requisitos confirmados
- Motivação e roadmap

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice massiva
- Spaced repetition
- Interleaving
- Elaboration
- Project-based learning
- Synthesis (integração de conceitos)
- Auto-avaliação profunda

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Mapa mental integrado GIGANTE de toda a Fase 1
2. Jornada completa: hardware → SO → usuário
3. Arquitetura do projeto integrador
4. Diagrama de módulos e suas comunicações

IMPORTANTE:
- Foco em INTEGRAÇÃO de conceitos
- Projeto deve ser DESAFIADOR mas REALIZÁVEL
- Celebrar CONCLUSÃO DA FASE 1
- Tom motivacional para Fase 2
- Projeto deve consolidar TUDO que foi aprendido
- Preparar confiança e momentum

Formato: markdown estruturado, visual, com diagramas Mermaid, quiz completo e projeto detalhado.
```

---

<a name="fase-2"></a>
# ⚙️ FASE 2: GERENCIAMENTO DE PROCESSOS (Dias 15-28)

**Objetivo:** Dominar escalonamento, sincronização e concorrência

---

## 📅 DIA 15 - CPU Scheduling Basics: A Fila do Banco

**📚 Recursos:**
- [CPU Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf)
- [Scheduling Algorithms](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/6_CPU_Scheduling.html)

**🎯 Tópicos:**
- Por que escalonar?
- Métricas: turnaround, response time, throughput
- Escalonamento preemptivo vs não-preemptivo
- Context switch overhead
- Dispatcher

**💻 Exercício Prático:**
- Simular FCFS (First Come First Served)
- Calcular métricas de desempenho

**✅ Checkpoint:**
- [ ] Compreende necessidade de escalonamento
- [ ] Calcula métricas básicas
- [ ] Diferencia tipos de escalonamento

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais começando FASE 2: Gerenciamento de Processos. Dia 15 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre fundamentos de CPU scheduling:

CONTEÚDO TÉCNICO:
1. Por que precisamos de escalonamento: maximizar CPU utilization, throughput
2. Métricas de desempenho:
   - Turnaround time: tempo total (chegada → conclusão)
   - Response time: tempo até primeira resposta
   - Waiting time: tempo em fila
   - Throughput: processos concluídos por tempo
3. Escalonamento preemptivo: SO pode interromper processo
4. Escalonamento não-preemptivo: processo roda até completar ou bloquear
5. Context switch: custo de trocar processos
6. Dispatcher: módulo que faz a troca de contexto
7. CPU burst vs I/O burst

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: processos e estados (Fase 1, Dia 6)
- Analogia central: "Fila do Banco" - atendimento de clientes
- História introdutória sobre necessidade de organizar filas

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Diagrama de CPU burst e I/O burst
  * Comparação visual: preemptivo vs não-preemptivo
  * Fluxograma do dispatcher
  * Gráfico de Gantt explicado
- Tabela de métricas com exemplos
- Fórmulas de cálculo

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de cálculo de turnaround e response time
- Demonstração de context switch
- Exemplo visual de Gráfico de Gantt

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Calculando Métricas de Scheduling
  * Cenário: 5 processos com arrival time e burst time
  * Calcular turnaround time para cada processo
  * Calcular average turnaround time
  * Calcular response time
  * Calcular waiting time
  * Criar gráfico de Gantt manual
  * Implementar simulador básico FCFS em Python
  * Contexto motivador
  * Especificação clara
  * Dados de exemplo
  * Passo a passo dos cálculos
  * Código simulador completo
  * Dicas progressivas
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir métricas)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Comparar preemptivo vs não-preemptivo
- Preparação para Dia 16 (algoritmos específicos)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de fila de banco
- Exemplos visuais (Gantt charts)
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com cálculos
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. CPU burst e I/O burst (alternância)
2. Preemptivo vs não-preemptivo (comparação)
3. Fluxo do dispatcher
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Foco em ENTENDER antes de algoritmos
- Exercícios de cálculo manual
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 16 - Algoritmos de Escalonamento I: FCFS, SJF, SRTF

**📚 Recursos:**
- [FCFS Scheduling](https://www.geeksforgeeks.org/fcfs-scheduling-full-form/)
- [SJF Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf)
- [Scheduling Algorithms Comparison](https://www.guru99.com/cpu-scheduling-algorithms.html)

**🎯 Tópicos:**
- FCFS (First-Come, First-Served): simplicidade
- Convoy effect: problema do FCFS
- SJF (Shortest Job First): otimalidade teórica
- SRTF (Shortest Remaining Time First): versão preemptiva
- Starvation problem
- Previsão de burst time

**💻 Exercício Prático:**
- Implementar simulador de FCFS e SJF
- Comparar desempenho com diferentes workloads
- Demonstrar convoy effect

**✅ Checkpoint:**
- [ ] Implementa FCFS e SJF
- [ ] Identifica problemas de cada algoritmo
- [ ] Compara resultados

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo algoritmos FCFS, SJF e SRTF. Dia 16 de estudos (Fase 2).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre os primeiros algoritmos de escalonamento:

CONTEÚDO TÉCNICO:
1. FCFS (First-Come, First-Served): o mais simples e intuitivo
2. Funcionamento do FCFS: fila FIFO estrita
3. Convoy effect: processos curtos esperando processos longos
4. SJF (Shortest Job First): minimiza average turnaround time
5. Prova de otimalidade do SJF
6. SRTF (Shortest Remaining Time First): versão preemptiva do SJF
7. Problema de starvation: processos longos nunca executam
8. Impossibilidade prática: não sabemos burst time futuro
9. Técnicas de estimação: exponential averaging

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: métricas de scheduling (Dia 15)
- Analogia central: "Fila do Supermercado" - caixa normal vs caixa rápida
- História introdutória sobre otimização de filas

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Gráfico de Gantt: FCFS com convoy effect
  * Gráfico de Gantt: SJF otimizando tempo médio
  * Comparação: FCFS vs SJF vs SRTF (mesmos processos)
  * Fluxograma de decisão SRTF (quando preemptar)
- Tabela comparativa: vantagens e desvantagens
- Demonstração matemática de otimalidade do SJF

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo numérico FCFS passo a passo
- Demonstração de convoy effect
- Exemplo SJF com cálculos
- Exemplo SRTF com preempção
- Estimação de burst time

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Simulador de Algoritmos de Escalonamento
  * Implementar FCFS
  * Implementar SJF (não-preemptivo)
  * Implementar SRTF (preemptivo)
  * Conjunto de processos de teste:
    - P1: arrival=0, burst=8
    - P2: arrival=1, burst=4
    - P3: arrival=2, burst=2
    - P4: arrival=3, burst=1
  * Calcular métricas para cada algoritmo
  * Gerar gráficos de Gantt
  * Demonstrar convoy effect
  * Demonstrar starvation
  * Comparar resultados
  * Contexto motivador
  * Especificação clara
  * Código completo em Python
  * Visualizações gráficas
  * Dicas progressivas
  * Análise detalhada
  * Variações opcionais (mais processos, I/O)

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (esquecer arrival time, confundir SJF com SRTF)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar previsão de burst time
- Preparação para Dia 17 (Round Robin e Priority)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de filas de supermercado
- Exemplos visuais (Gantt charts)
- Storytelling
- Scaffolding (simples → complexo)
- Chunking
- Dual coding
- Hands-on com simulações
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. FCFS mostrando convoy effect
2. SJF otimizando tempo médio
3. SRTF com preempções marcadas
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código executável com saída visual
- Foco em trade-offs de cada algoritmo
- Demonstrar problemas E soluções
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 17 - Algoritmos de Escalonamento II: Round Robin, Priority

**📚 Recursos:**
- [Round Robin Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched.pdf)
- [Priority Scheduling](https://www.tutorialspoint.com/operating_system/os_priority_scheduling.htm)
- [Multilevel Queue Scheduling](https://www.geeksforgeeks.org/multilevel-queue-mlq-cpu-scheduling/)

**🎯 Tópicos:**
- Round Robin: time quantum e fairness
- Escolha do quantum: impacto no desempenho
- Priority Scheduling: estático vs dinâmico
- Aging technique: prevenir starvation
- Escalonamento multinível
- Feedback queues

**💻 Exercício Prático:**
- Implementar Round Robin com diferentes quanta
- Simular Priority Scheduling com aging
- Comparar desempenho dos algoritmos

**✅ Checkpoint:**
- [ ] Implementa Round Robin
- [ ] Resolve starvation com aging
- [ ] Escolhe quantum adequado

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo algoritmos Round Robin e Priority. Dia 17 de estudos (Fase 2).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre Round Robin e Priority Scheduling:

CONTEÚDO TÉCNICO:
1. Round Robin (RR): escalonamento circular com time quantum
2. Time quantum (time slice): escolha e impactos (pequeno vs grande)
3. Trade-off: quantum pequeno (maior overhead) vs grande (pior response time)
4. Fairness: todos os processos recebem CPU regularmente
5. Priority Scheduling: processos com diferentes prioridades
6. Prioridade estática: definida na criação, não muda
7. Prioridade dinâmica: ajustada durante execução
8. Aging: aumentar prioridade de processos esperando (prevenir starvation)
9. Multilevel Queue: múltiplas filas com diferentes prioridades
10. Multilevel Feedback Queue: processos movem entre filas baseado em comportamento

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: FCFS, SJF, SRTF (Dia 16)
- Analogia central: "Revezamento na Quadra de Esportes" - todos jogam, turnos justos
- História introdutória sobre fairness vs eficiência

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Gráfico de Gantt: Round Robin (quantum = 4)
  * Comparação: quantum pequeno (q=2) vs grande (q=10) - overhead
  * Priority Scheduling com e sem aging (timeline)
  * Multilevel Feedback Queue (arquitetura com 3 níveis)
- Tabela: impacto do tamanho do quantum em métricas
- Visualização de aging ao longo do tempo
- Fórmula de aging

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo Round Robin passo a passo (quantum=4)
- Demonstração de starvation em Priority (sem aging)
- Solução com aging implementado
- Exemplo de multilevel feedback (processo migra entre filas)

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Implementando RR e Priority com Aging
  * Parte 1: Round Robin
    - Implementar simulador RR
    - Testar com quantum = 2, 4, 8, 16
    - Calcular turnaround, response, waiting time
    - Medir overhead de context switch
    - Gerar Gantt charts
  * Parte 2: Priority Scheduling
    - Implementar Priority (estático)
    - Demonstrar starvation com cenário específico
    - Implementar aging
    - Comparar com e sem aging
  * Parte 3: Comparação
    - Mesmos processos em FCFS, SJF, RR, Priority
    - Tabela comparativa de resultados
    - Análise de quando usar cada um
  * Contexto motivador (sistemas reais)
  * Especificação clara
  * Código completo em Python com classes
  * Visualização de resultados (gráficos)
  * Dicas progressivas
  * Análise de trade-offs
  * Variações opcionais (multilevel feedback)

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (quantum muito pequeno causando overhead, ignorar starvation)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar Multilevel Feedback Queue completo
- Preparação para Dia 18 (schedulers reais: Linux CFS, Windows)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de revezamento justo no esporte
- Exemplos visuais de Gantt charts
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com simulações
- Comparação e contraste
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Round Robin com quantum = 4 (Gantt chart animado)
2. Impacto do quantum (gráfico: overhead vs response time)
3. Priority Scheduling com aging visual (prioridades aumentando)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código executável com visualizações
- Foco em trade-offs (fairness vs throughput)
- Demonstrar problemas reais e soluções
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 18 - Escalonamento Real: Linux CFS e Windows Scheduler

**📚 Recursos:**
- [Completely Fair Scheduler](https://www.kernel.org/doc/html/latest/scheduler/sched-design-CFS.html)
- [Linux Scheduler](https://www.kernel.org/doc/Documentation/scheduler/sched-design-CFS.txt)
- [Windows Thread Scheduling](https://learn.microsoft.com/en-us/windows/win32/procthread/scheduling)

**🎯 Tópicos:**
- Linux CFS: virtual runtime
- Red-black tree para processos
- Nice values e prioridades
- Windows multilevel feedback queue
- Priority classes no Windows
- Real-time scheduling classes

**💻 Exercício Prático:**
- Modificar nice values no Linux
- Observar comportamento do CFS
- Comparar Linux vs Windows scheduling

**✅ Checkpoint:**
- [ ] Compreende CFS
- [ ] Manipula prioridades
- [ ] Analisa comportamento real

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre schedulers reais. Dia 18 de estudos (Fase 2).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre Linux CFS e Windows Scheduler:

CONTEÚDO TÉCNICO:
1. Linux CFS (Completely Fair Scheduler): scheduler padrão desde kernel 2.6.23 (2007)
2. Conceito de virtual runtime (vruntime): tempo de CPU normalizado por peso
3. Red-black tree: estrutura de dados auto-balanceada (O(log n))
4. Nice values: -20 (alta prioridade, mais CPU) a +19 (baixa prioridade, menos CPU)
5. Peso por nice value: cada nice reduz CPU em ~10%
6. Scheduling classes Linux: SCHED_NORMAL, SCHED_FIFO, SCHED_RR, SCHED_BATCH, SCHED_IDLE
7. Windows Scheduler: multilevel feedback queue com 32 níveis de prioridade
8. Priority classes Windows: Realtime (24-31), High (13-15), Above Normal (10-12), Normal (8-9), Below Normal (6-7), Idle (4-5)
9. Priority boost dinâmico no Windows: eventos de I/O aumentam prioridade temporariamente
10. Comparação detalhada: Linux CFS vs Windows Scheduler

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: algoritmos teóricos (Dias 15-17)
- Analogia central: "Sistema de Pontos em Jogo Multiplayer" - justiça baseada em créditos
- História introdutória sobre evolução dos schedulers reais

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Arquitetura do CFS (red-black tree com processos)
  * Cálculo de vruntime (fórmula visual passo a passo)
  * Hierarquia de scheduling classes Linux (prioridade)
  * Níveis de prioridade do Windows (0-31 com classes)
- Tabela: nice values e pesos correspondentes
- Comparação lado a lado: Linux CFS vs Windows Scheduler
- Visualização de red-black tree

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de cálculo de vruntime com diferentes nice values
- Demonstração de nice/renice no terminal
- Exemplo de chrt (change real-time attributes)
- Visualização de prioridades no Windows Task Manager

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Manipulando Schedulers Reais
  * Linux:
    - Verificar scheduler atual: cat /sys/block/sda/queue/scheduler
    - Criar processos CPU-intensive (loop infinito)
    - Monitorar com top/htop
    - Modificar nice values (nice, renice)
    - Observar impacto no tempo de CPU
    - Calcular vruntime teoricamente
    - Usar chrt para scheduling real-time
    - Testar SCHED_FIFO vs SCHED_NORMAL
    - Cuidados com RT priority
  * Windows (se aplicável):
    - Verificar prioridades no Task Manager
    - Modificar priority class de processo
    - Observar comportamento com ProcessExplorer
    - Testar priority boost
  * Comparação:
    - Comportamento com mesma carga
    - Fairness de cada sistema
    - Performance em diferentes cenários
  * Contexto motivador
  * Especificação clara
  * Comandos detalhados (scripts prontos)
  * Scripts de teste automatizados
  * Dicas progressivas
  * Análise dos resultados (gráficos)
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (usar RT priority sem necessidade, risco de travar sistema)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Otimizar aplicação real ajustando prioridades
- Preparação para Dia 19 (sincronização e seção crítica)
- Recursos complementares (kernel documentation)

TÉCNICAS PEDAGÓGICAS:
- Analogia de sistema de pontos em jogo
- Exemplos visuais de árvores (red-black)
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com sistema real (não simulação!)
- Comparação entre sistemas
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Red-black tree do CFS (visual com processos e vruntime)
2. Cálculo de vruntime explicado (fórmula + exemplo)
3. Hierarquia de scheduling classes (Linux e Windows lado a lado)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Foco em SISTEMAS REAIS (não teoria!)
- Experimentos práticos com comandos
- Cuidado com segurança (RT pode travar sistema)
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 19 - Sincronização: O Problema da Seção Crítica

**📚 Recursos:**
- [Critical Section Problem](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf)
- [Peterson's Solution](https://www.geeksforgeeks.org/petersons-algorithm-for-mutual-exclusion-set-1/)
- [Race Conditions](https://www.baeldung.com/cs/race-conditions)

**🎯 Tópicos:**
- Race conditions
- Seção crítica: requisitos (exclusão mútua, progresso, espera limitada)
- Soluções de software: algoritmo de Peterson
- Soluções de hardware: test-and-set, compare-and-swap
- Atomic operations
- Memory barriers

**💻 Exercício Prático:**
- Demonstrar race condition
- Implementar algoritmo de Peterson
- Usar atomic operations

**✅ Checkpoint:**
- [ ] Identifica race conditions
- [ ] Implementa exclusão mútua
- [ ] Usa primitivas atômicas

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre sincronização e seção crítica. Dia 19 de estudos (Fase 2).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre o problema da seção crítica:

CONTEÚDO TÉCNICO:
1. Race conditions: resultado depende da ordem de execução (não-determinístico)
2. Seção crítica: região de código que acessa recurso compartilhado
3. Três requisitos da solução:
   - Exclusão mútua: apenas um processo na seção crítica
   - Progresso: decisão de entrar não pode ser adiada indefinidamente
   - Espera limitada (bounded waiting): limite de vezes que outros entram antes de você
4. Tentativas ingênuas: flag, turn (por que falham)
5. Algoritmo de Peterson: solução de software para 2 processos
6. Limitações de Peterson: não funciona em arquiteturas modernas (reordenação)
7. Soluções de hardware:
   - Test-and-Set: instrução atômica
   - Compare-and-Swap (CAS): instrução atômica condicional
   - Fetch-and-Add: incremento atômico
8. Atomic operations: garantem atomicidade
9. Memory barriers: previnem reordenação de instruções

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: threads compartilham memória (Fase 1, Dia 6)
- Analogia central: "Banheiro Compartilhado" - apenas uma pessoa por vez
- História introdutória sobre problemas de concorrência famosos

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Diagrama de race condition (timeline de 2 threads)
  * Estrutura da seção crítica (entry → critical → exit → remainder)
  * Algoritmo de Peterson (pseudocódigo visual)
  * Comparação: tentativas ingênuas vs Peterson vs hardware
- Tabela: soluções e propriedades satisfeitas
- Visualização de instruções atômicas

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de race condition (contador compartilhado)
- Demonstração de código com race condition
- Solução com Peterson (2 threads)
- Exemplo de test-and-set
- Código com atomic operations

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Race Conditions e Soluções
  * Parte 1: Demonstrar Race Condition
    - Programa com contador compartilhado
    - 2 threads incrementando 1 milhão de vezes cada
    - Resultado esperado: 2 milhões
    - Resultado real: < 2 milhões (race!)
    - Executar múltiplas vezes, mostrar não-determinismo
  * Parte 2: Tentativas Ingênuas
    - Implementar solução com flag
    - Mostrar por que falha
    - Implementar solução com turn
    - Mostrar por que falha (progresso)
  * Parte 3: Algoritmo de Peterson
    - Implementar Peterson
    - Testar com 2 threads
    - Verificar resultado correto
    - Discussão de limitações
  * Parte 4: Atomic Operations
    - Usar __sync_fetch_and_add (GCC)
    - Usar std::atomic (C++)
    - Usar threading.Lock (Python)
    - Comparar performance
  * Contexto motivador
  * Especificação clara
  * Código completo (C, C++, Python)
  * Visualização de execuções
  * Dicas progressivas
  * Análise detalhada
  * Variações opcionais (mais threads)

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (esquecer barrier, assumir atomicidade)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Generalizar Peterson para N processos
- Preparação para Dia 20 (locks e mutexes)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de banheiro compartilhado
- Exemplos visuais de timelines
- Storytelling (bugs históricos)
- Scaffolding
- Chunking
- Dual coding
- Hands-on com código que quebra
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Race condition (timeline de 2 threads incrementando)
2. Estrutura da seção crítica (4 partes)
3. Algoritmo de Peterson (fluxograma)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código que QUEBRA para demonstrar problema
- Depois mostrar SOLUÇÕES
- Foco em entender o PROBLEMA primeiro
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 20 - Locks e Mutexes: Trancando Recursos

**📚 Recursos:**
- [Locks Implementation](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-locks.pdf)
- [POSIX Threads Programming](https://hpc-tutorials.llnl.gov/posix/)
- [Mutex vs Spinlock](https://www.kernel.org/doc/Documentation/locking/mutex-design.txt)

**🎯 Tópicos:**
- Mutex (mutual exclusion)
- Spinlocks vs sleeping locks
- Lock granularidade (coarse-grained vs fine-grained)
- Deadlock com locks
- Try-lock e timed locks
- Lock-free programming

**💻 Exercício Prático:**
- Implementar contador thread-safe com mutex
- Comparar spinlock vs mutex
- Criar hierarquia de locks

**✅ Checkpoint:**
- [ ] Usa mutexes corretamente
- [ ] Escolhe tipo de lock adequado
- [ ] Evita deadlocks

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre locks e mutexes. Dia 20 de estudos (Fase 2).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre locks e mutexes:

CONTEÚDO TÉCNICO:
1. Mutex (Mutual Exclusion): abstração de alto nível para seção crítica
2. API básica: lock() / acquire(), unlock() / release()
3. Spinlock: busy-waiting (consome CPU enquanto espera)
4. Sleeping lock (mutex): bloqueia thread, libera CPU
5. Quando usar cada tipo:
   - Spinlock: seção crítica curta, sistemas multicore
   - Mutex: seção crítica longa, pode bloquear
6. Lock granularidade:
   - Coarse-grained: um lock para muitos dados (simples, menos concorrente)
   - Fine-grained: muitos locks, cada um protege pouco (complexo, mais concorrente)
7. Deadlock com locks: circular wait
8. Try-lock: tenta adquirir, retorna imediatamente se falhar
9. Timed lock: espera até timeout
10. Lock-free programming: algoritmos sem locks (muito avançado)
11. POSIX threads (pthreads): pthread_mutex_t

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: seção crítica (Dia 19)
- Analogia central: "Chave do Banheiro" - apenas quem tem a chave entra
- História introdutória sobre abstrações simplificando programação

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Fluxo de lock/unlock (estados da thread)
  * Comparação: spinlock (busy-wait) vs mutex (sleep)
  * Granularidade: coarse vs fine (visual)
  * Deadlock com 2 locks (diagrama de recursos)
- Tabela: spinlock vs mutex (características)
- Código exemplo de uso correto

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de pthread_mutex em C
- Demonstração de spinlock (C com atomic)
- Exemplo de deadlock com 2 locks
- Solução: lock ordering

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Usando Locks na Prática
  * Parte 1: Mutex Básico
    - Contador compartilhado com pthread_mutex
    - Múltiplas threads incrementando
    - Verificar resultado correto
    - Medir performance (tempo)
  * Parte 2: Spinlock
    - Implementar spinlock simples
    - Comparar com mutex (mesma carga)
    - Observar uso de CPU
    - Quando spinlock é melhor
  * Parte 3: Granularidade
    - Array compartilhado
    - Coarse-grained: 1 lock para todo array
    - Fine-grained: 1 lock por elemento
    - Comparar concorrência e overhead
  * Parte 4: Deadlock
    - Criar deadlock intencional (2 threads, 2 locks)
    - Demonstrar travamento
    - Solução 1: lock ordering
    - Solução 2: try-lock com backoff
  * Parte 5: Try-lock
    - Implementar com pthread_mutex_trylock
    - Estratégia de retry
    - Evitar deadlock
  * Contexto motivador
  * Especificação clara
  * Código completo (C com pthreads, Python)
  * Scripts de teste
  * Dicas progressivas
  * Análise de performance
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (esquecer unlock, double lock, lock ordering errado)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar reader-writer lock
- Preparação para Dia 21 (semáforos e monitores)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de chave física
- Exemplos visuais de estados
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com código real
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo de lock/unlock (estados da thread: running → blocked → ready)
2. Spinlock vs Mutex (uso de CPU ao longo do tempo)
3. Granularidade visual (1 lock vs múltiplos locks)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código real executável
- Demonstrar PROBLEMAS (deadlock) E SOLUÇÕES
- Foco em boas práticas
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 21 - Semáforos e Monitores: Coordenação Avançada

**📚 Recursos:**
- [Semaphores](http://pages.cs.wisc.edu/~remzi/OSTEP/threads-sema.pdf)
- [Monitors](https://www.geeksforgeeks.org/monitors-in-process-synchronization/)
- [Producer-Consumer Problem](https://en.wikipedia.org/wiki/Producer%E2%80%93consumer_problem)

**🎯 Tópicos:**
- Semáforos: counting vs binary
- Operações P (wait) e V (signal)
- Problemas clássicos: produtor-consumidor, leitores-escritores
- Monitores: abstração de alto nível
- Condition variables
- Mesa vs Hoare semantics

**💻 Exercício Prático:**
- Resolver produtor-consumidor com semáforos
- Implementar leitores-escritores
- Usar condition variables

**✅ Checkpoint:**
- [ ] Domina semáforos
- [ ] Resolve problemas clássicos
- [ ] Usa condition variables

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre semáforos e monitores. Dia 21 de estudos (Fase 2).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre semáforos e monitores:

CONTEÚDO TÉCNICO:
1. Semáforos: variável inteira + operações atômicas (inventado por Dijkstra, 1965)
2. Semáforo binário: 0 ou 1 (equivalente a mutex)
3. Semáforo contador: qualquer valor não-negativo
4. Operações:
   - P() / wait() / down(): decrementa, bloqueia se < 0
   - V() / signal() / up(): incrementa, acorda thread se necessário
5. Problema do Produtor-Consumidor (bounded buffer):
   - Buffer compartilhado de tamanho finito
   - Produtor adiciona itens
   - Consumidor remove itens
   - Sincronização necessária
6. Solução com semáforos: empty, full, mutex
7. Problema dos Leitores-Escritores:
   - Múltiplos leitores simultâneos OK
   - Escritor precisa exclusividade
   - Variações: reader-preference, writer-preference, fair
8. Monitores: abstração de alto nível (linguagem, não SO)
9. Condition variables: wait() e signal() em monitores
10. Mesa semantics vs Hoare semantics
11. POSIX: sem_t, pthread_cond_t

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: locks e mutexes (Dia 20)
- Analogia central: "Vagas de Estacionamento" - contador de recursos disponíveis
- História introdutória sobre Dijkstra e invenção dos semáforos

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Semáforo: operações P e V (fluxo de estados)
  * Produtor-Consumidor: diagrama com buffer circular
  * Leitores-Escritores: estados permitidos
  * Monitor: estrutura (mutex + condition variables)
- Tabela: binário vs contador
- Pseudocódigo visual de soluções

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de semáforo binário (como mutex)
- Demonstração de semáforo contador (pool de recursos)
- Solução produtor-consumidor passo a passo
- Exemplo de condition variable

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Problemas Clássicos com Semáforos
  * Parte 1: Semáforo Básico
    - Implementar semáforo contador
    - Testar P() e V()
    - Visualizar fila de threads esperando
  * Parte 2: Produtor-Consumidor
    - Buffer circular de tamanho 10
    - 3 produtores, 2 consumidores
    - Implementar com semáforos:
      * empty (vagas disponíveis)
      * full (itens disponíveis)
      * mutex (proteção do buffer)
    - Produtores produzem 100 itens cada
    - Consumidores consomem até acabar
    - Verificar: nenhum item perdido
    - Visualizar estado do buffer
  * Parte 3: Leitores-Escritores
    - Múltiplos leitores (5) simultâneos
    - Escritores (2) com exclusividade
    - Implementar reader-preference
    - Implementar writer-preference
    - Comparar comportamentos
    - Problema de starvation
  * Parte 4: Condition Variables
    - Reimplementar produtor-consumidor com monitor
    - pthread_cond_wait e pthread_cond_signal
    - Comparar com implementação de semáforos
  * Contexto motivador
  * Especificação clara
  * Código completo (C com pthreads, Python)
  * Dicas progressivas
  * Visualização de execução
  * Análise de correção
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (ordem de semáforos errada, deadlock, busy-wait desnecessário)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Problema do Jantar dos Filósofos com semáforos
- Preparação para Dia 22 (revisão semana 3)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de vagas de estacionamento
- Exemplos visuais de buffers
- Storytelling (história de Dijkstra)
- Scaffolding
- Chunking
- Dual coding
- Hands-on com problemas clássicos
- Problem-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Operações P e V em semáforo (fluxo completo)
2. Produtor-Consumidor (buffer + semáforos)
3. Leitores-Escritores (estados permitidos)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Código executável de problemas clássicos
- Foco em PADRÕES de solução
- Demonstrar diferentes abordagens
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 22 - Revisão Semana 3 + Simulador de Scheduling

**🎯 Objetivo:** Consolidar conceitos de escalonamento e sincronização

**📝 Atividades:**
- Revisão Dias 15-21
- Quiz de escalonamento e sincronização (20 questões)
- Mapa mental integrado

**💻 MINI-PROJETO:**
**"Simulador Visual de CPU Scheduling e Sincronização"**
- Implementar 4+ algoritmos de scheduling
- Resolver problemas de sincronização
- Interface gráfica ou CLI visual
- Comparação de métricas
- Gráficos de Gantt
- Relatório de análise

**✅ Checkpoint:**
- [ ] Revisão completa
- [ ] 80%+ no quiz
- [ ] Simulador funcionando

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da semana 3. Dia 22 de estudos (Fase 2).

Crie material de REVISÃO E MINI-PROJETO usando DESIGN INSTRUCIONAL para consolidar semana 3:

CONTEÚDO A REVISAR (Dias 15-21):
1. CPU Scheduling Basics: métricas, preemptivo vs não-preemptivo
2. FCFS, SJF, SRTF: algoritmos básicos
3. Round Robin, Priority: fairness e aging
4. Linux CFS, Windows Scheduler: sistemas reais
5. Seção Crítica: race conditions, requisitos
6. Locks e Mutexes: spinlock vs mutex, granularidade
7. Semáforos e Monitores: problemas clássicos

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DA REVISÃO:
- Consolidar scheduling e sincronização
- Integrar conceitos
- Aplicar em projeto prático
- Preparar para segunda parte da Fase 2

🔄 REVISÃO INTEGRADA:
- Mapa mental integrando Dias 15-21
- Resumo executivo de cada dia (3-4 pontos)
- Conexões entre conceitos
- Como scheduling e sincronização se relacionam
- DIAGRAMAS MERMAID:
  * Visão geral: scheduling + sincronização
  * Taxonomia de algoritmos de scheduling
  * Taxonomia de primitivas de sincronização
  * Mapa mental completo da semana

📝 QUIZ ABRANGENTE (20 questões):
- 3 questões por tópico (dias 15-21)
- Questões integradoras
- Níveis: fácil (35%), médio (45%), difícil (20%)
- Gabarito com explicações
- Identificação de áreas para reforço

💻 MINI-PROJETO: "Simulador Visual de Scheduling e Sincronização"

**Descrição:**
Sistema que simula algoritmos de scheduling e demonstra problemas de sincronização

**Objetivos de aprendizagem:**
- Implementar 4+ algoritmos de scheduling
- Resolver 2+ problemas de sincronização
- Visualizar execução em tempo real
- Calcular e comparar métricas
- Gerar relatórios

**Especificação funcional:**

MÓDULO 1: Simulador de Scheduling
- Implementar algoritmos:
  * FCFS
  * SJF / SRTF
  * Round Robin (quantum configurável)
  * Priority (com aging)
- Entrada: lista de processos (arrival, burst, priority)
- Saída:
  * Gráfico de Gantt
  * Métricas (turnaround, waiting, response)
  * Comparação lado a lado

MÓDULO 2: Problemas de Sincronização
- Produtor-Consumidor:
  * Buffer visual
  * Semáforos: empty, full, mutex
  * Animação de produção/consumo
- Leitores-Escritores:
  * Visualização de quem está lendo/escrevendo
  * Implementação com semáforos

MÓDULO 3: Visualização
- Interface: CLI com animação OU GUI simples
- Cores para estados
- Atualização em tempo real (ou passo a passo)
- Logs de eventos

MÓDULO 4: Análise e Relatórios
- Estatísticas detalhadas
- Gráficos comparativos
- Exportar resultados (JSON/CSV)

**Estrutura do projeto:**
```
scheduler-sync-simulator/
├── src/
│   ├── main.py
│   ├── scheduler.py (algoritmos)
│   ├── process.py (classe Process)
│   ├── sync.py (produtor-consumidor, etc)
│   ├── visualizer.py (Gantt, animação)
│   └── metrics.py (cálculos)
├── tests/
│   ├── test_scheduler.py
│   └── test_sync.py
├── examples/
│   ├── workload1.json
│   └── workload2.json
├── docs/
│   ├── README.md
│   └── USAGE.md
└── requirements.txt
```

**Implementação passo a passo:**

Passo 1: Estrutura Básica (1h)
- Classes: Process, Scheduler
- Interface básica

Passo 2: Algoritmos de Scheduling (3h)
- FCFS
- SJF/SRTF
- Round Robin
- Priority com aging
- Testes unitários

Passo 3: Métricas e Gantt (2h)
- Calcular turnaround, waiting, response
- Gerar Gantt chart (ASCII ou matplotlib)

Passo 4: Sincronização (2h)
- Produtor-Consumidor
- Leitores-Escritores
- Usar threading + semaphores

Passo 5: Visualização (2h)
- Animação de execução
- Interface amigável
- Cores e formatação

Passo 6: Análise e Relatórios (1h)
- Comparação de algoritmos
- Gráficos
- Exportação

Passo 7: Testes e Documentação (1h)
- Casos de teste
- README completo
- Exemplos de uso

**Código exemplo (estrutura base):**
[Fornecer esqueleto em Python]

**Critérios de avaliação:**
- Funcionalidade completa (40%)
- Correção de algoritmos (25%)
- Visualização (20%)
- Documentação (15%)

🎯 EXERCÍCIOS DE FIXAÇÃO:
- Questões rápidas por conceito
- Desafios de integração

🚀 PREPARAÇÃO PARA DIAS 23-28:
- Preview: context switch, multiprocessing, fork/exec, signals, real-time
- Conexões com o que foi visto
- Motivação e roadmap

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice
- Spaced repetition
- Interleaving
- Project-based learning
- Synthesis de conceitos
- Auto-avaliação

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 3):
1. Mapa mental integrado da semana 3
2. Taxonomias (scheduling + sincronização)
3. Arquitetura do simulador

IMPORTANTE:
- Foco em INTEGRAÇÃO
- Projeto deve ser VISUAL
- Celebrar progresso
- Tom motivacional
- Código deve consolidar aprendizado
- Preparar confiança para resto da Fase 2

Formato: markdown estruturado, visual, com diagramas Mermaid, quiz e projeto detalhado.
```

---

[**Continuando com os dias restantes...**]

Devido ao limite de espaço, vou fornecer agora os Dias 23-28 (completando Fase 2) de forma estruturada e completa:

---

## 📅 DIA 23 - Context Switching: A Troca de Guarda

**📚 Recursos:**
- [Context Switch Overhead](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-mechanisms.pdf)
- [Process Context](https://www.geeksforgeeks.org/context-switch-in-operating-system/)

**🎯 Tópicos:**
- O que é context switch
- Salvando estado do processo (PCB)
- Registradores, stack pointer, program counter
- Overhead e custo
- Cache pollution
- Medindo context switch

**💻 Exercício Prático:**
- Medir tempo de context switch
- Observar impacto no desempenho
- Analisar PCB

**✅ Checkpoint:**
- [ ] Compreende context switch
- [ ] Mede overhead
- [ ] Otimiza trocas de contexto

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre context switching. Dia 23 de estudos (Fase 2).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre context switching:

CONTEÚDO TÉCNICO:
1. Context switch: trocar CPU de um processo para outro
2. Quando ocorre: timer interrupt, system call, I/O, preempção
3. O que é salvo no PCB (Process Control Block):
   - Registradores gerais (EAX, EBX, etc)
   - Program counter (PC)
   - Stack pointer (SP)
   - Status registers
   - Memory management info (page table pointer)
4. Etapas do context switch:
   - Salvar estado do processo atual no PCB
   - Atualizar PCB (estado, estatísticas)
   - Mover PCB para fila apropriada
   - Selecionar próximo processo (scheduler)
   - Restaurar estado do novo processo do PCB
   - Retomar execução
5. Overhead: tempo gasto sem executar código útil
6. Custo típico: microsegundos (depende da arquitetura)
7. Cache pollution: perda de cache do processo anterior
8. TLB flush: perda de traduções de endereço
9. Como medir: lmbench, getrusage()
10. Otimizações: reduzir frequency, usar threads (menos overhead)

[Incluir TODAS as seções: Objetivos, Ativação, Apresentação com 4+ diagramas Mermaid, Demonstração, Prática Guiada completa, Feedback, Transferência, Técnicas Pedagógicas]

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo completo do context switch (passo a passo)
2. Estrutura do PCB (campos salvos)
3. Overhead no tempo de execução (gráfico)
4. Mapa mental dos conceitos

EXERCÍCIO PRÁTICO:
- Medir tempo de context switch com lmbench ou código personalizado
- Comparar: processos vs threads
- Visualizar /proc/[pid]/status
- Analisar overhead com diferentes workloads

IMPORTANTE:
- Foco em CUSTO real
- Medições práticas
- Impacto na performance
- Otimizações
```

---

## 📅 DIA 24 - Multiprocessing e Multicore: Paralelismo Real

**📚 Recursos:**
- [Multiprocessor Scheduling](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-sched-multi.pdf)
- [NUMA Architecture](https://www.kernel.org/doc/html/latest/vm/numa.html)

**🎯 Tópicos:**
- SMP (Symmetric Multiprocessing)
- Affinity de CPU
- Load balancing
- Cache coherence
- NUMA (Non-Uniform Memory Access)
- Escalonamento multicore

**💻 Exercício Prático:**
- Configurar CPU affinity
- Medir impacto de NUMA
- Parallelizar programa

**✅ Checkpoint:**
- [ ] Entende arquiteturas multicore
- [ ] Configura affinity
- [ ] Otimiza para multicore

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre multiprocessing e multicore. Dia 24 de estudos (Fase 2).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre arquiteturas multicore e multiprocessamento:

CONTEÚDO TÉCNICO:
1. SMP (Symmetric Multiprocessing): múltiplas CPUs com acesso simétrico à memória
2. Multicore: múltiplos núcleos no mesmo chip
3. CPU affinity: fixar processo/thread em CPU específica
4. Soft affinity: preferência por CPU (padrão)
5. Hard affinity: forçar CPU específica
6. Load balancing: distribuir carga entre CPUs
7. Work stealing: CPUs ociosas roubam trabalho de CPUs ocupadas
8. Cache coherence: garantir consistência de caches
9. Protocolos: MESI, MOESI
10. NUMA (Non-Uniform Memory Access): acesso à memória tem latências diferentes
11. NUMA node: grupo de CPUs com memória local
12. Scheduling em multicore: complexidade aumentada
13. Hyper-Threading (Intel): SMT (Simultaneous Multithreading)

[Incluir estrutura completa de Design Instrucional com todos os componentes]

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura SMP vs NUMA
2. Cache coherence (protocolo MESI)
3. Load balancing entre CPUs
4. Mapa mental dos conceitos

EXERCÍCIO PRÁTICO:
- Verificar topology: lscpu, /proc/cpuinfo
- Configurar affinity: taskset, sched_setaffinity()
- Medir impacto: numactl, perf
- Parallelizar código CPU-intensive
- Comparar com e sem affinity

IMPORTANTE:
- Foco em arquiteturas REAIS
- Medições práticas de performance
- Otimizações concretas
- Hardware moderno
```

---

## 📅 DIA 25 - Process Creation e Management: fork(), exec(), wait()

**📚 Recursos:**
- [Process API](http://pages.cs.wisc.edu/~remzi/OSTEP/cpu-api.pdf)
- [Fork Explained](https://www.geeksforgeeks.org/fork-system-call/)

**🎯 Tópicos:**
- fork(): criando processos
- exec(): substituindo imagem do processo
- wait(): sincronização pai-filho
- Processos zumbis e órfãos
- Árvore de processos
- Process groups e sessions

**💻 Exercício Prático:**
- Criar processos com fork
- Implementar mini-shell
- Gerenciar processos filhos

**✅ Checkpoint:**
- [ ] Usa fork/exec/wait
- [ ] Cria árvore de processos
- [ ] Evita zombies

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre criação de processos. Dia 25 de estudos (Fase 2).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre fork(), exec() e wait():

CONTEÚDO TÉCNICO:
1. fork(): system call que cria processo filho
   - Retorna 0 no filho, PID do filho no pai
   - Duplica: memória, descritores de arquivo, registradores
   - Copy-on-Write (CoW): otimização
2. exec() família: substitui imagem do processo
   - execl, execlp, execle, execv, execvp, execve
   - Não retorna se sucesso
   - Mantém PID, descritores abertos
3. wait() / waitpid(): pai espera filho terminar
   - Coleta exit status
   - Previne zombie
4. Processo zombie: terminou mas pai não coletou status
5. Processo órfão: pai terminou, adotado por init/systemd
6. Árvore de processos: hierarquia pai-filho
7. Process groups: conjunto de processos relacionados
8. Sessions: grupo de process groups (terminal)
9. Daemon processes: serviços em background

[Estrutura completa de Design Instrucional]

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo do fork() (pai e filho)
2. Execução de exec() (antes e depois)
3. Árvore de processos (pstree visual)
4. Estados: running → zombie → coletado

EXERCÍCIO PRÁTICO:
- Programa com fork(): pai e filho imprimem
- Usar exec() para executar /bin/ls
- Implementar mini-shell:
  * Ler comando
  * fork()
  * exec() no filho
  * wait() no pai
- Criar zombie intencional
- Visualizar com ps, pstree

IMPORTANTE:
- Código executável completo
- Demonstrar zombies
- Mini-shell funcional
- Foco em system calls POSIX
```

---

## 📅 DIA 26 - Signals: Comunicação Assíncrona

**📚 Recursos:**
- [Signal Handling](https://man7.org/linux/man-pages/man7/signal.7.html)
- [POSIX Signals](https://www.gnu.org/software/libc/manual/html_node/Signal-Handling.html)

**🎯 Tópicos:**
- O que são signals
- Signals comuns (SIGINT, SIGTERM, SIGKILL, SIGCHLD)
- Signal handlers
- Bloqueando signals
- Signal masks
- Signals vs interrupts

**💻 Exercício Prático:**
- Implementar signal handlers
- Criar programa com controle via signals
- Implementar timeout com signals

**✅ Checkpoint:**
- [ ] Compreende signals
- [ ] Implementa handlers
- [ ] Usa signals para IPC

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre signals. Dia 26 de estudos (Fase 2).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre signals:

CONTEÚDO TÉCNICO:
1. Signals: notificação assíncrona para processos
2. Gerados por: kernel (erro), outro processo (kill), teclas (Ctrl+C)
3. Signals comuns:
   - SIGINT (2): Ctrl+C, interrupção
   - SIGTERM (15): terminação gentil
   - SIGKILL (9): terminação forçada (não pode ser capturado!)
   - SIGSEGV (11): segmentation fault
   - SIGCHLD (17): filho terminou
   - SIGALRM (14): alarme de timer
4. Signal handler: função customizada para tratar signal
5. signal() / sigaction(): registrar handler
6. Ações padrão: terminate, ignore, core dump, stop
7. Signals não podem ser enfileirados (exceto real-time signals)
8. Signal masks: bloquear temporariamente signals
9. sigprocmask(): modificar mask
10. Signals vs interrupts: signals são software, interrupts são hardware
11. Async-signal-safe functions: apenas certas funções são seguras em handlers

[Estrutura completa de Design Instrucional]

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo de signal (geração → entrega → handler)
2. Signal disposition (ignore, default, handler)
3. Signal mask e bloqueio
4. Mapa mental dos conceitos

EXERCÍCIO PRÁTICO:
- Handler para SIGINT (Ctrl+C personalizado)
- Implementar timeout com SIGALRM
- Comunicação entre processos com SIGUSR1/SIGUSR2
- Bloquear signals temporariamente
- Evitar race conditions em handlers

IMPORTANTE:
- Foco em async-signal-safety
- Demonstrar handlers SEGUROS
- Casos de uso reais
- Cuidados com concorrência
```

---

## 📅 DIA 27 - Real-Time Systems: Tempo é Crítico

**📚 Recursos:**
- [Real-Time Operating Systems](https://www.freertos.org/RTOS.html)
- [Real-Time Linux](https://wiki.linuxfoundation.org/realtime/start)

**🎯 Tópicos:**
- Hard vs soft real-time
- Garantias de timing
- Priority inversion
- Priority inheritance
- Rate Monotonic Scheduling
- Earliest Deadline First

**💻 Exercício Prático:**
- Configurar real-time priorities no Linux
- Simular rate monotonic
- Detectar priority inversion

**✅ Checkpoint:**
- [ ] Diferencia RT systems
- [ ] Aplica algoritmos RT
- [ ] Resolve priority inversion

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre sistemas de tempo real. Dia 27 de estudos (Fase 2).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre Real-Time Systems:

CONTEÚDO TÉCNICO:
1. Real-Time: sistema com restrições de tempo (timing constraints)
2. Hard real-time: deadline DEVE ser cumprido (ex: airbag)
3. Soft real-time: deadline é desejável mas pode ser perdido (ex: streaming de vídeo)
4. Firm real-time: entre hard e soft
5. Características RT:
   - Determinismo: comportamento previsível
   - Latência limitada: tempo máximo de resposta
   - Jitter mínimo: variação de latência
6. Scheduling real-time:
   - Rate Monotonic (RM): prioridade baseada em período
   - Earliest Deadline First (EDF): prioridade baseada em deadline
7. Priority inversion: processo de baixa prioridade bloqueia alta
8. Soluções:
   - Priority inheritance: temporariamente elevar prioridade
   - Priority ceiling: teto de prioridade por recurso
9. RTOS: FreeRTOS, VxWorks, RT-Linux
10. Linux real-time: PREEMPT_RT patch, scheduling policies (SCHED_FIFO, SCHED_RR)

[Estrutura completa de Design Instrucional]

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Hard vs Soft real-time (comparação)
2. Rate Monotonic Scheduling (exemplo)
3. Priority inversion (problema e solução)
4. Mapa mental dos conceitos

EXERCÍCIO PRÁTICO:
- Configurar SCHED_FIFO no Linux (chrt)
- Simular Rate Monotonic (tarefas periódicas)
- Demonstrar priority inversion
- Aplicar priority inheritance
- Medir jitter e latência

IMPORTANTE:
- Foco em APLICAÇÕES reais
- Demonstrar problemas E soluções
- Cálculos de schedulability
- Sistemas críticos
```

---

## 📅 DIA 28 - Revisão Fase 2 + Projeto Final da Fase

**🎯 Objetivo:** Consolidar TODA a Fase 2

**📝 Atividades:**
- Revisão completa (Dias 15-27)
- Quiz final da fase (30 questões)
- Mapa mental integrado

**💻 PROJETO FINAL FASE 2:**
**"Sistema Avançado de Gerenciamento de Processos"**

Criar um sistema completo que:
1. Implementa 3+ algoritmos de scheduling
2. Cria e gerencia processos dinamicamente (fork/exec)
3. Sincronização com mutexes e semáforos
4. Comunicação via signals
5. Suporte a multicore (affinity)
6. Monitoramento de desempenho
7. Interface interativa
8. Relatórios e visualizações

**✅ Checkpoint:**
- [ ] Revisão completa
- [ ] 85%+ no quiz
- [ ] Projeto robusto e documentado
- [ ] Pronto para Fase 3

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da FASE 2 COMPLETA. Dia 28 de estudos.

Crie material de REVISÃO ABRANGENTE E PROJETO FINAL usando DESIGN INSTRUCIONAL para toda a Fase 2:

CONTEÚDO A REVISAR (Dias 15-27):
1. CPU Scheduling Basics: métricas, tipos
2. Algoritmos I: FCFS, SJF, SRTF
3. Algoritmos II: RR, Priority
4. Schedulers Reais: Linux CFS, Windows
5. Seção Crítica: race conditions, Peterson
6. Locks e Mutexes: tipos, granularidade
7. Semáforos e Monitores: problemas clássicos
8. [Revisão semana 3 + Simulador]
9. Context Switching: overhead, cache
10. Multiprocessing: SMP, NUMA, affinity
11. Process Creation: fork, exec, wait
12. Signals: handlers, comunicação
13. Real-Time Systems: hard/soft, algorithms

ESTRUTURA:

📋 OBJETIVOS DA REVISÃO:
- Consolidar TODA Fase 2
- Visão holística de processos
- Projeto final integrador
- Preparar para Fase 3 (Memória)

🔄 REVISÃO INTEGRADA COMPLETA:
- Mapa mental GIGANTE da Fase 2
- Resumo executivo de cada dia
- Conexões profundas entre conceitos
- DIAGRAMAS MERMAID:
  * Visão integrada completa
  * Jornada: processo criado → scheduled → sincronizado → terminado
  * Taxonomias completas

📝 QUIZ FINAL (30 questões):
- 2 questões por dia (15-27)
- 8 questões integradoras
- Níveis: fácil (30%), médio (50%), difícil (20%)
- Gabarito detalhado

💻 PROJETO FINAL: "Sistema Completo de Gerenciamento de Processos"

**Especificação completa:**

MÓDULO 1: Process Scheduler
- Implementar FCFS, SJF, RR, Priority
- Suporte a multicore (affinity)
- Métricas em tempo real
- Visualização de Gantt

MÓDULO 2: Process Manager
- Criar processos (fork/exec)
- Gerenciar árvore de processos
- Comunicação via signals
- Evitar zombies/órfãos

MÓDULO 3: Synchronization
- Contador compartilhado thread-safe
- Produtor-Consumidor
- Leitores-Escritores
- Demonstrar race conditions

MÓDULO 4: Performance Monitor
- Context switch tracking
- CPU utilization por core
- Load balancing
- Latência e jitter

MÓDULO 5: Interface e Controle
- CLI interativa
- Comandos: create, kill, list, schedule, stats
- Signals para controle
- Real-time dashboard

MÓDULO 6: Relatórios
- Estatísticas detalhadas
- Gráficos de performance
- Comparação de algoritmos
- Exportação (HTML, JSON)

**Estrutura do projeto:**
```
process-manager/
├── src/
│   ├── main.c
│   ├── scheduler.c
│   ├── process.c
│   ├── sync.c
│   ├── monitor.c
│   └── interface.c
├── include/
├── tests/
├── docs/
└── Makefile
```

**Implementação guiada:**
[Detalhes passo a passo completos]

**Critérios de avaliação:**
- Funcionalidade (40%)
- Correção (30%)
- Performance (15%)
- Documentação (15%)

🚀 PREPARAÇÃO PARA FASE 3:
- Preview: Memory Management (Dias 29-42)
- Tópicos: paging, TLB, swapping, allocation
- Motivação

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice massiva
- Project-based learning
- Synthesis completa
- Auto-avaliação profunda

DIAGRAMAS MERMAID (mínimo 4):
1. Mapa mental GIGANTE Fase 2
2. Jornada completa do processo
3. Arquitetura do projeto
4. Módulos e integrações

IMPORTANTE:
- INTEGRAÇÃO total de conceitos
- Projeto DESAFIADOR e COMPLETO
- Celebrar CONCLUSÃO DA FASE 2
- Tom motivacional para Fase 3
- Código deve consolidar TUDO

Formato: markdown estruturado, visual, com quiz e projeto detalhado.
```

---

<a name="fase-3"></a>
# 💾 FASE 3: GERENCIAMENTO DE MEMÓRIA (Dias 29-42)

**Objetivo:** Dominar virtual memory, paginação, swapping e otimizações

---

## 📅 DIA 29 - Memory Hierarchy: A Pirâmide da Velocidade

**📚 Recursos:**
- [Memory Hierarchy](https://www.geeksforgeeks.org/memory-hierarchy-design-and-its-characteristics/)
- [Cache Memory](https://www.cs.umd.edu/~meesh/411/CA-online/chapter/memory-hierarchy-design-basics/index.html)
- [Locality Principle](https://en.wikipedia.org/wiki/Locality_of_reference)

**🎯 Tópicos:**
- Pirâmide de memória revisitada
- Cache L1, L2, L3
- Cache hit vs miss
- Princípio da localidade (temporal, espacial)
- Cache replacement policies (LRU, FIFO)
- Write-through vs write-back

**💻 Exercício Prático:**
- Medir cache hit rate
- Otimizar código para cache
- Simular políticas de substituição

**✅ Checkpoint:**
- [ ] Compreende hierarquia completa
- [ ] Otimiza para cache
- [ ] Mede desempenho de cache

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais começando FASE 3: Gerenciamento de Memória. Dia 29 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre hierarquia de memória:

CONTEÚDO TÉCNICO:
1. Hierarquia de memória: trade-off entre velocidade e capacidade
2. Níveis (do mais rápido ao mais lento):
   - Registradores: < 1 ns, bytes
   - Cache L1: ~1 ns, KB (por core)
   - Cache L2: ~4 ns, centenas de KB (por core)
   - Cache L3: ~10-20 ns, MB (compartilhado)
   - RAM: ~100 ns, GB
   - SSD: ~100 µs, TB
   - HDD: ~10 ms, TB
3. Cache hit: dado está no cache (rápido)
4. Cache miss: dado não está no cache (lento, buscar da memória)
5. Hit rate: % de acessos que são hits
6. Princípio da localidade:
   - Temporal: dado usado recentemente será usado de novo
   - Espacial: dados próximos serão usados juntos
7. Cache line: unidade de transferência (tipicamente 64 bytes)
8. Cache replacement policies:
   - LRU (Least Recently Used): remove menos usado recentemente
   - FIFO (First-In-First-Out): remove mais antigo
   - Random: remove aleatório
9. Write policies:
   - Write-through: escreve em cache e memória
   - Write-back: escreve apenas em cache (dirty bit)
10. Cache coherence em multicore: MESI protocol

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: hierarquia já vista (Fase 1, Dia 2)
- Analogia central: "Biblioteca com Estantes" - livros mais usados ficam mais próximos
- História introdutória sobre por que memória não pode ser toda rápida

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Pirâmide da hierarquia de memória (velocidade vs capacidade)
  * Fluxo de acesso: CPU → L1 → L2 → L3 → RAM
  * Cache line e layout
  * Comparação de políticas de substituição (LRU, FIFO, Random)
- Tabela: níveis de memória com latências e capacidades
- Visualização de localidade temporal e espacial
- Fórmula de AMAT (Average Memory Access Time)

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de cálculo de hit rate
- Demonstração de AMAT
- Código otimizado vs não otimizado (cache-friendly)
- Exemplo de LRU step-by-step

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Explorando e Otimizando para Cache
  * Parte 1: Medir Cache Performance
    - Usar perf (Linux) para medir cache misses
    - Programa 1: array traversal linear (cache-friendly)
    - Programa 2: array traversal com stride grande (cache-unfriendly)
    - Comparar cache miss rate
  * Parte 2: Demonstrar Localidade
    - Temporal: acessar mesmo dado repetidamente
    - Espacial: acessar dados adjacentes
    - Medir diferença de performance
  * Parte 3: Otimizar Código
    - Matrix multiplication naive (row-major)
    - Matrix multiplication optimizada (blocking/tiling)
    - Medir speedup
  * Parte 4: Simular Cache Replacement
    - Implementar simulador de cache
    - Testar LRU, FIFO, Random
    - Comparar hit rates com traces de acesso
  * Contexto motivador
  * Especificação clara
  * Código completo (C, Python)
  * Comandos perf
  * Dicas progressivas
  * Análise de resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (assumir cache infinito, ignorar cache line size)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Otimizar algoritmo real para cache
- Preparação para Dia 30 (address spaces)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de biblioteca
- Exemplos visuais de hierarquia
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com medições reais
- Comparação de políticas
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Pirâmide de hierarquia (velocidade, capacidade, custo)
2. Fluxo de acesso à memória (multi-level)
3. Cache line e organização
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Medições REAIS com perf
- Otimizações práticas
- Foco em performance
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 30 - Address Spaces: Espaços Privativos

**📚 Recursos:**
- [Address Spaces](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-intro.pdf)
- [Virtual Memory Basics](https://www.kernel.org/doc/html/latest/admin-guide/mm/concepts.html)
- [Memory Layout](https://www.geeksforgeeks.org/memory-layout-of-c-program/)

**🎯 Tópicos:**
- Espaço de endereçamento físico vs virtual
- Por que virtualizar memória?
- Isolamento entre processos
- Memory layout: text, data, heap, stack
- Address translation
- Base and bounds

**💻 Exercício Prático:**
- Visualizar memory map de processo
- Analisar /proc/[pid]/maps
- Criar programa que mapeia memória

**✅ Checkpoint:**
- [ ] Diferencia endereços físicos e virtuais
- [ ] Entende layout de memória
- [ ] Analisa memory maps

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre espaços de endereçamento. Dia 30 de estudos (Fase 3).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre address spaces:

CONTEÚDO TÉCNICO:
1. Endereço físico: localização real na RAM
2. Endereço virtual: abstração vista pelo programa
3. Por que virtualização de memória:
   - Isolamento: processos não interferem entre si
   - Proteção: processo não acessa memória alheia
   - Ilusão: cada processo acha que tem toda a memória
   - Compartilhamento: múltiplos processos, memória limitada
4. Memory layout de processo (endereços virtuais):
   - Text segment: código do programa (read-only, executável)
   - Data segment: variáveis globais inicializadas
   - BSS segment: variáveis globais não-inicializadas
   - Heap: memória dinâmica (malloc, cresce para cima ↑)
   - Stack: variáveis locais, chamadas de função (cresce para baixo ↓)
5. Address translation: virtual → físico (feito por MMU)
6. Base and bounds: técnica simples de virtualização
   - Base register: início do espaço físico
   - Bounds register: tamanho do espaço
   - Physical = Virtual + Base (se Virtual < Bounds)
7. Problemas do base and bounds:
   - Fragmentação externa
   - Crescimento de heap/stack
8. Proteção: kernel space vs user space

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: processos isolados (Fase 1)
- Analogia central: "Apartamentos em Prédio" - cada um tem seu espaço privado
- História introdutória sobre necessidade de proteção

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Endereço virtual vs físico (dois espaços)
  * Memory layout de processo (text, data, BSS, heap, stack)
  * Base and bounds (translation)
  * Múltiplos processos em memória física
- Tabela: segmentos de memória e características
- Visualização de crescimento heap/stack
- Fórmula de address translation

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de address translation com base and bounds
- Código mostrando diferentes segmentos
- Demonstração de /proc/[pid]/maps
- Visualização com pmap

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Explorando Memory Layout
  * Parte 1: Visualizar Layout
    - Programa que imprime endereços de:
      * Variável global (data)
      * Variável local (stack)
      * malloc (heap)
      * Função (text)
    - Observar ordem dos endereços
    - Compilar com/sem otimizações
  * Parte 2: Analisar /proc/[pid]/maps
    - Executar programa long-running
    - Ler /proc/[pid]/maps
    - Identificar cada segmento
    - Verificar permissões (r, w, x)
    - Usar pmap para visualização melhor
  * Parte 3: Address Translation Manual
    - Cenário: base=16384, bounds=32768
    - Virtual addresses: 0, 1024, 16384, 40000
    - Calcular physical address ou erro
  * Parte 4: Crescimento de Heap/Stack
    - Programa que aloca muito em heap (malloc loop)
    - Programa com recursão profunda (stack)
    - Observar mudança em /proc/[pid]/maps
    - Provocar stack overflow
  * Contexto motivador
  * Especificação clara
  * Código completo (C)
  * Comandos Linux
  * Dicas progressivas
  * Análise detalhada
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir virtual com físico)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar simulador de base and bounds
- Preparação para Dia 31 (paginação)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de apartamentos
- Exemplos visuais de layouts
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com /proc
- Exploration-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Espaços: virtual (processo) → MMU → físico (RAM)
2. Memory layout completo (5 segmentos)
3. Base and bounds translation
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Exploração de sistema real
- Visualizações práticas
- Foco em CONCEITO antes de implementação
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 31 - Paginação: Dividir para Conquistar

**📚 Recursos:**
- [Paging](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-paging.pdf)
- [Page Tables](https://www.geeksforgeeks.org/paging-in-operating-system/)
- [Paging Tutorial](https://www.tutorialspoint.com/operating_system/os_paging.htm)

**🎯 Tópicos:**
- Conceito de página e frame
- Page table: estrutura e função
- Address translation com paginação
- Page table entry (PTE)
- Fragmentação interna
- Page size tradeoffs

**💻 Exercício Prático:**
- Simular address translation
- Calcular overhead de page table
- Implementar page table simples

**✅ Checkpoint:**
- [ ] Compreende paginação
- [ ] Traduz endereços manualmente
- [ ] Calcula tamanhos

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre paginação. Dia 31 de estudos (Fase 3).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre paginação de memória:

CONTEÚDO TÉCNICO:
1. Paginação: dividir memória virtual e física em blocos de tamanho fixo
2. Página (page): bloco de memória virtual (ex: 4KB)
3. Frame (page frame): bloco de memória física (mesmo tamanho)
4. Page table: mapeia páginas virtuais para frames físicos
5. Address translation com paginação:
   - Virtual address dividido: [page number | offset]
   - Page number → indexa page table → frame number
   - Physical address: [frame number | offset]
6. Page table entry (PTE): informações sobre uma página
   - Valid bit: página está na memória?
   - Protection bits: read, write, execute
   - Present bit: está carregada?
   - Dirty bit: foi modificada?
   - Reference bit: foi acessada?
   - Frame number: localização física
7. Fragmentação interna: desperdício dentro da página
8. Page size tradeoffs:
   - Pequena: menos fragmentação interna, mais entradas na page table
   - Grande: mais fragmentação interna, menos entradas na page table
9. Typical page sizes: 4KB (comum), 2MB, 1GB (huge pages)
10. Page table pode ser MUITO grande (problema!)

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: address spaces (Dia 30)
- Analogia central: "Índice de Livro" - encontrar página rapidamente
- História introdutória sobre problema de base and bounds

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Paginação: memória virtual e física divididas
  * Address translation (virtual → page table → physical)
  * Estrutura de PTE (bits e campos)
  * Comparação: base and bounds vs paginação
- Tabela: campos do PTE
- Cálculo de tamanho de page table
- Exemplos numéricos de translation

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de address translation passo a passo
- Cálculo de page number e offset
- Exemplo de page table pequena (8 páginas)
- Demonstração de fragmentação interna

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Simulando Paginação
  * Parte 1: Address Translation Manual
    - Sistema: 32-bit address, page size 4KB
    - Calcular: bits para page number, bits para offset
    - Virtual addresses dados: traduzir para físico
    - Page table fornecida
    - Identificar valid/invalid accesses
  * Parte 2: Calcular Overhead
    - Address space: 32-bit (4GB)
    - Page size: 4KB
    - PTE size: 4 bytes
    - Calcular: número de páginas, tamanho da page table
    - Comparar com outros page sizes (2KB, 8KB, 2MB)
  * Parte 3: Implementar Simulador
    - Estrutura Page Table Entry
    - Função translate(virtual_address)
    - Simular acesso: hit, miss, protection fault
    - Estatísticas: hits, misses, faults
  * Parte 4: Fragmentação Interna
    - Processos com tamanhos variados
    - Page size: 4KB
    - Calcular desperdício médio
    - Comparar com outros page sizes
  * Contexto motivador
  * Especificação clara
  * Código completo (Python, C)
  * Exemplos numéricos detalhados
  * Dicas progressivas
  * Análise de trade-offs
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir page number com frame, esquecer offset)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar page table com proteção
- Preparação para Dia 32 (TLB)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de índice de livro
- Exemplos visuais de translation
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com cálculos
- Simulation-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Paginação visual (páginas → frames)
2. Address translation completo (bits e fluxo)
3. Page Table Entry (estrutura detalhada)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Foco em CÁLCULOS práticos
- Exemplos numéricos abundantes
- Address translation step-by-step
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 32 - TLB: Translation Lookaside Buffer

**📚 Recursos:**
- [TLB Explained](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-tlbs.pdf)
- [TLB Performance](https://www.cs.princeton.edu/courses/archive/fall16/cos318/lectures/TLB.pdf)
- [Understanding TLB](https://www.kernel.org/doc/gorman/html/understand/understand006.html)

**🎯 Tópicos:**
- Por que TLB existe
- TLB como cache de traduções
- TLB hit vs miss
- Context switch e TLB flush
- ASID (Address Space ID)
- Huge pages e TLB coverage

**💻 Exercício Prático:**
- Medir TLB miss rate
- Configurar huge pages
- Otimizar para TLB

**✅ Checkpoint:**
- [ ] Compreende papel do TLB
- [ ] Mede TLB performance
- [ ] Usa huge pages

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre TLB. Dia 32 de estudos (Fase 3).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre Translation Lookaside Buffer:

CONTEÚDO TÉCNICO:
1. Problema: acessar page table para CADA acesso à memória é lento
2. TLB (Translation Lookaside Buffer): cache de traduções de endereço
3. Localização: dentro da MMU (Memory Management Unit)
4. TLB entry: [VPN | PFN | protection bits]
5. TLB hit: tradução está no TLB (rápido! ~1 cycle)
6. TLB miss: tradução não está no TLB (lento, acessar page table)
7. TLB reach: quantidade de memória coberta pelo TLB
   - TLB reach = # entries × page size
   - Ex: 64 entries × 4KB = 256KB
8. Context switch: TLB flush (invalidar todas as entradas)
9. ASID (Address Space Identifier): evitar flush total
   - Tag TLB entries com process ID
   - Permite entries de múltiplos processos
10. Huge pages: páginas maiores (2MB, 1GB)
    - Menos entries necessárias no TLB
    - Maior TLB reach
    - Menos TLB misses
11. TLB miss handling:
    - Hardware-managed: MMU walks page table
    - Software-managed: OS trap handler
12. Typical TLB: 64-128 entries, fully associative

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: paginação e page table (Dia 31)
- Analogia central: "Catálogo na Mesa" - traduções mais usadas à mão
- História introdutória sobre otimização de acesso

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Fluxo de acesso: TLB hit vs TLB miss
  * Localização do TLB na arquitetura (CPU → TLB → MMU → RAM)
  * Context switch e TLB flush (antes e depois)
  * Huge pages: mais coverage com menos entries
- Tabela: TLB hit vs miss (latência)
- Cálculo de TLB reach
- Fórmula de EAT (Effective Access Time)

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de TLB lookup step-by-step
- Cálculo de EAT com diferentes hit rates
- Demonstração de huge pages no Linux
- Exemplo de ASID

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Medindo e Otimizando TLB
  * Parte 1: Simular TLB
    - Implementar TLB simples (8 entries, fully associative)
    - LRU replacement
    - Trace de acessos à memória
    - Calcular hit rate, miss rate
    - Comparar com tamanhos diferentes (4, 16, 32 entries)
  * Parte 2: Calcular EAT
    - TLB access time: 1 cycle
    - Memory access time: 100 cycles
    - TLB hit rate: 95%
    - Calcular EAT
    - Variar hit rate: 80%, 90%, 99%
    - Análise de sensibilidade
  * Parte 3: Medir TLB Misses Reais
    - Usar perf (Linux): perf stat -e dTLB-loads,dTLB-load-misses
    - Programa 1: acesso sequencial (TLB-friendly)
    - Programa 2: acesso aleatório (TLB-unfriendly)
    - Comparar TLB miss rates
  * Parte 4: Huge Pages
    - Verificar suporte: cat /proc/meminfo | grep Huge
    - Programa que aloca muita memória
    - Executar com páginas normais (4KB)
    - Executar com huge pages (2MB)
      * mmap com MAP_HUGETLB
      * ou transparent huge pages
    - Comparar TLB misses e performance
  * Contexto motivador
  * Especificação clara
  * Código completo (C, Python para simulador)
  * Comandos perf
  * Dicas progressivas
  * Análise de resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir TLB com cache, ignorar context switch cost)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar TLB com ASID
- Preparação para Dia 33 (advanced page tables)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de catálogo na mesa
- Exemplos visuais de hit/miss
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com medições reais
- Simulation + real system
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo completo: TLB hit (rápido) vs TLB miss (lento)
2. TLB na arquitetura (posição entre CPU e memória)
3. Context switch e flush do TLB
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Medições REAIS com perf
- Demonstrar impacto CONCRETO
- Foco em otimização prática
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 33 - Advanced Page Tables: Estruturas Eficientes

**📚 Recursos:**
- [Multi-level Page Tables](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-smalltables.pdf)
- [Page Table Structures](https://www.kernel.org/doc/gorman/html/understand/understand006.html)
- [x86-64 Paging](https://wiki.osdev.org/Paging)

**🎯 Tópicos:**
- Problema: page tables grandes
- Multi-level page tables (2, 3, 4 níveis)
- Inverted page tables
- Hashed page tables
- x86-64: 4-level paging
- ARM: translation table walks

**💻 Exercício Prático:**
- Calcular overhead multi-level
- Simular tradução 4-level
- Comparar estruturas

**✅ Checkpoint:**
- [ ] Compreende multi-level paging
- [ ] Traduz em múltiplos níveis
- [ ] Avalia tradeoffs

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre page tables avançadas. Dia 33 de estudos (Fase 3).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre estruturas avançadas de page tables:

CONTEÚDO TÉCNICO:
1. Problema: page table linear é ENORME
   - Exemplo: 32-bit, page 4KB, PTE 4B → 4MB por processo!
   - 64-bit: inviável (PB de page table!)
2. Solução 1: Multi-level Page Tables
   - Dividir page table em páginas
   - Usar outra page table para indexar
   - Sparse address spaces: economiza memória
3. Two-level page table:
   - Page directory (nível 1): aponta para page tables
   - Page tables (nível 2): aponta para frames
   - Virtual address: [dir | table | offset]
4. x86-64: Four-level page table (48-bit address space)
   - PML4 (Page Map Level 4)
   - PDP (Page Directory Pointer)
   - PD (Page Directory)
   - PT (Page Table)
   - Virtual address: [PML4 | PDP | PD | PT | offset]
5. Trade-offs multi-level:
   - Espaço: economiza muito (alocação sob demanda)
   - Tempo: múltiplos acessos à memória (mas TLB ajuda!)
6. Solução 2: Inverted Page Table
   - Uma entrada por FRAME (não por página)
   - Hash table: VPN → frame
   - Economiza espaço (um por sistema, não por processo)
   - Lento para buscar (hash collisions)
7. Solução 3: Hashed Page Table
   - Hash VPN para encontrar PTE
   - Collision handling com chaining
8. ARM: ARMv8 pode usar 3 ou 4 níveis

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: page tables lineares (Dia 31)
- Analogia central: "Índice de Índices" - árvore de busca
- História introdutória sobre escalabilidade

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Two-level page table (estrutura hierárquica)
  * x86-64 four-level paging (completo)
  * Comparação: linear vs multi-level (uso de memória)
  * Inverted page table (hash-based)
- Tabela: comparação de estruturas
- Cálculo de overhead de cada tipo
- Address translation multi-level step-by-step

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de two-level translation
- Demonstração de x86-64 four-level
- Cálculo de economia de espaço
- Exemplo de inverted page table

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Multi-level Page Tables
  * Parte 1: Two-level Translation
    - Sistema: 32-bit, page 4KB
    - 10 bits dir, 10 bits table, 12 bits offset
    - Virtual addresses dados
    - Page directory e page tables fornecidos
    - Traduzir manualmente step-by-step
    - Identificar entradas inválidas
  * Parte 2: Calcular Overhead
    - Linear page table: 32-bit, 4KB pages
      * Tamanho total: calcular
    - Two-level: mesmas specs
      * Worst case (todas alocadas): calcular
      * Best case (sparse): calcular
    - Four-level (x86-64): 48-bit
      * Calcular overhead
  * Parte 3: Implementar Simulador Two-level
    - Estruturas: PageDirectory, PageTable
    - Função: translate_two_level(vaddr)
    - Alocação sob demanda (lazy allocation)
    - Estatísticas: memória usada
    - Comparar com linear
  * Parte 4: Simular Inverted Page Table
    - Hash table: VPN → frame
    - Collision handling
    - Buscar tradução
    - Comparar tempo vs espaço
  * Contexto motivador
  * Especificação clara
  * Código completo (Python, C)
  * Cálculos detalhados
  * Dicas progressivas
  * Análise de trade-offs
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir níveis, calcular overhead errado)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar four-level page table
- Preparação para Dia 34 (swapping)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de índice de índices/árvore
- Exemplos visuais de hierarquias
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com cálculos
- Simulation-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Two-level page table (hierarquia visual)
2. x86-64 four-level (todos os níveis)
3. Comparação memória: linear vs multi-level
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Foco em ESCALABILIDADE
- Cálculos de overhead detalhados
- Demonstrar economia de espaço
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 34 - Swapping e Paging to Disk: Memória Virtual Completa

**📚 Recursos:**
- [Swapping](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys.pdf)
- [Swap Space Management](https://www.kernel.org/doc/gorman/html/understand/understand011.html)
- [Page Faults](https://www.geeksforgeeks.org/page-fault-handling-in-operating-system/)

**🎯 Tópicos:**
- Por que swap?
- Present bit na PTE
- Page fault handling
- Swap space no disco
- Swap in e swap out
- Performance implications
- Thrashing

**💻 Exercício Prático:**
- Configurar swap space
- Monitorar swapping
- Simular page fault handler

**✅ Checkpoint:**
- [ ] Compreende swapping
- [ ] Configura swap
- [ ] Identifica thrashing

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre swapping. Dia 34 de estudos (Fase 3).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre swapping e paging to disk:

CONTEÚDO TÉCNICO:
1. Memória virtual completa: ilusão de memória infinita
2. Present bit (valid bit): página está na memória física?
   - Present = 1: está na RAM
   - Present = 0: está no disco (swap) ou não alocada
3. Page fault: acesso a página não presente
   - Hardware: detecta present=0, trap para OS
   - Software (OS): page fault handler
4. Page fault handling:
   - Verificar se endereço é válido
   - Se inválido: segmentation fault (kill process)
   - Se válido mas swapped: trazer do disco
5. Swap space: área no disco para páginas
   - Partition dedicada ou arquivo
   - Linux: /dev/sda2 (swap partition) ou swapfile
6. Swap out: mover página RAM → disco (liberar frame)
7. Swap in: trazer página disco → RAM (atender fault)
8. Page replacement: se RAM cheia, escolher vítima
9. Performance:
   - RAM access: ~100 ns
   - Disk access: ~10 ms (100,000x mais lento!)
   - SSD: ~100 μs (1000x mais lento)
10. Thrashing: sistema passa mais tempo swapping que executando
    - Causa: working set > RAM disponível
    - Solução: adicionar RAM, matar processos, reduzir carga
11. Demand paging: carregar páginas apenas quando necessárias
12. Copy-on-write (CoW): otimização para fork()

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: paginação e PTEs (Dias 31-33)
- Analogia central: "Arquivo Morto" - documentos raramente usados vão para storage
- História introdutória sobre ilusão de memória infinita

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Fluxo completo de page fault (trap → handler → disk I/O → resume)
  * Memória virtual estendida (RAM + swap no disco)
  * Page fault handler (algoritmo step-by-step)
  * Thrashing: ciclo vicioso
- Tabela: latências (RAM, SSD, HDD)
- Visualização de swap in/out
- Anatomia de um PTE com present bit

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de page fault step-by-step
- Demonstração de configuração de swap no Linux
- Código que causa page faults
- Monitoramento com vmstat

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Swapping na Prática
  * Parte 1: Configurar Swap
    - Linux: verificar swap atual (free -h, swapon --show)
    - Criar swapfile:
      * dd if=/dev/zero of=/swapfile bs=1M count=1024
      * mkswap /swapfile
      * swapon /swapfile
    - Verificar ativação
    - Desativar: swapoff
  * Parte 2: Simular Page Fault Handler
    - Implementar simulador simplificado:
      * Page table com present bit
      * Função access_page(vpn)
      * Se present=0: page fault
        - Alocar frame (ou substituir)
        - "Carregar do disco" (simular delay)
        - Atualizar PTE
        - Retornar
    - Estatísticas: page faults, disk accesses
  * Parte 3: Monitorar Swapping Real
    - Programa que aloca MUITA memória:
      * malloc loop até ultrapassar RAM física
      * Touch páginas (escrever para alocar)
    - Monitorar em outra janela:
      * vmstat 1 (colunas si, so - swap in/out)
      * free -h (swap usado)
      * iotop (I/O do swap)
    - Observar quando começa swapping
    - Observar degradação de performance
  * Parte 4: Demonstrar Thrashing
    - Múltiplos programas alocando memória
    - Observar sistema ficar extremamente lento
    - Monitorar: swap in/out constante
    - Solução: matar processos
  * Contexto motivador
  * Especificação clara
  * Código completo (C para alocar, Python para simulador)
  * Comandos Linux detalhados
  * Dicas progressivas
  * Análise de performance
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir page fault com segfault, ignorar custo de I/O)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar page replacement (preparação dia 36)
- Preparação para Dia 35 (revisão semana 5)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de arquivo morto
- Exemplos visuais de fault handling
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com sistema real
- Demonstração de problemas reais (thrashing)
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Page fault handling (fluxo completo com todos os passos)
2. Memória virtual = RAM + Swap (visual)
3. Swap in/out (movimentação de páginas)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Demonstrar impacto REAL de swapping
- Foco em PERFORMANCE
- Mostrar thrashing (problema sério!)
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 35 - Revisão Semana 5 + Simulador de Memória Virtual

**🎯 Objetivo:** Consolidar conceitos de memória virtual

**📝 Atividades:**
- Revisão Dias 29-34
- Quiz de memória (20 questões)
- Mapa mental integrado

**💻 MINI-PROJETO:**
**"Simulador de Memória Virtual Completo"**
- Implementar paginação com page table
- Simular TLB
- Page faults e swapping
- Políticas de substituição
- Visualização gráfica ou CLI
- Estatísticas de desempenho

**✅ Checkpoint:**
- [ ] Revisão completa
- [ ] 80%+ no quiz
- [ ] Simulador funcional

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da semana 5. Dia 35 de estudos (Fase 3).

Crie material de REVISÃO E MINI-PROJETO usando DESIGN INSTRUCIONAL para consolidar semana 5:

CONTEÚDO A REVISAR (Dias 29-34):
1. Memory Hierarchy: cache, localidade, políticas
2. Address Spaces: virtual vs físico, memory layout
3. Paginação: páginas, frames, page tables
4. TLB: cache de traduções, huge pages
5. Advanced Page Tables: multi-level, inverted
6. Swapping: page faults, swap space, thrashing

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DA REVISÃO:
- Consolidar memória virtual
- Integrar conceitos
- Aplicar em simulador prático
- Preparar para algoritmos de substituição

🔄 REVISÃO INTEGRADA:
- Mapa mental integrando Dias 29-34
- Resumo executivo de cada dia
- Conexões entre conceitos
- Jornada completa: endereço virtual → TLB → page table → RAM/swap
- DIAGRAMAS MERMAID:
  * Visão geral integrada de memória virtual
  * Fluxo completo de acesso à memória (todos os componentes)
  * Mapa mental da semana

📝 QUIZ ABRANGENTE (20 questões):
- 3-4 questões por tópico
- Questões integradoras
- Níveis: fácil (35%), médio (45%), difícil (20%)
- Gabarito com explicações
- Áreas para reforço

💻 MINI-PROJETO: "Simulador de Memória Virtual Completo"

**Descrição:**
Sistema que simula todos os aspectos de memória virtual: paginação, TLB, page faults, swapping

**Objetivos de aprendizagem:**
- Implementar paginação multi-level
- Simular TLB com replacement
- Simular page faults e swapping
- Implementar política de substituição básica
- Visualizar estado do sistema
- Calcular estatísticas

**Especificação funcional:**

MÓDULO 1: Page Table e Address Translation
- Implementar two-level page table
- Função translate(virtual_address)
- Retorna: physical_address ou page_fault
- Estatísticas: translations, page faults

MÓDULO 2: TLB
- Cache de traduções (ex: 16 entries)
- Fully associative
- LRU replacement
- Função tlb_lookup(vpn)
- Estatísticas: hits, misses, hit rate

MÓDULO 3: Physical Memory
- Frames de RAM (ex: 64 frames)
- Bitmap de alocação
- Função alloc_frame(), free_frame()

MÓDULO 4: Swap Space
- Simular disco (array)
- Swap out: frame → disk
- Swap in: disk → frame
- Estatísticas: swap ins, swap outs

MÓDULO 5: Page Fault Handler
- Detectar present bit = 0
- Alocar frame (ou substituir página)
- Carregar do swap (simular delay)
- Atualizar page table e TLB

MÓDULO 6: Page Replacement (básico)
- FIFO: remover página mais antiga
- [Preparação para dia 36 com mais algoritmos]

MÓDULO 7: Simulação e Visualização
- Trace de acessos à memória (sequência de endereços)
- Processar cada acesso
- Visualizar estado:
  * TLB entries
  * Page table
  * Physical memory (frames alocados)
  * Swap usage
- Estatísticas finais:
  * TLB hit rate
  * Page fault rate
  * Swap in/out count
  * Average access time

**Estrutura do projeto:**
```
vm-simulator/
├── src/
│   ├── main.py
│   ├── page_table.py
│   ├── tlb.py
│   ├── physical_memory.py
│   ├── swap.py
│   ├── fault_handler.py
│   └── visualizer.py
├── tests/
│   ├── test_page_table.py
│   ├── test_tlb.py
│   └── test_faults.py
├── traces/
│   ├── sequential.txt
│   ├── random.txt
│   └── locality.txt
├── docs/
│   ├── README.md
│   └── DESIGN.md
└── requirements.txt
```

**Implementação passo a passo:**

Passo 1: Estrutura Básica (1h)
- Classes: PageTable, TLB, PhysicalMemory
- Definir interfaces

Passo 2: Page Table (2h)
- Two-level implementation
- Translation function
- Testes unitários

Passo 3: TLB (1.5h)
- Cache implementation
- LRU replacement
- Lookup function

Passo 4: Physical Memory (1h)
- Frame allocation
- Bitmap management

Passo 5: Swap e Page Faults (2h)
- Swap space
- Fault handler
- Swap in/out

Passo 6: Integração (1.5h)
- Conectar todos os módulos
- Fluxo completo de acesso

Passo 7: Visualização (2h)
- Display de estado
- Gráficos (matplotlib)
- Logs detalhados

Passo 8: Testes e Docs (1h)
- Traces de teste
- Documentação
- Exemplos de uso

**Código exemplo (estrutura base):**
[Fornecer esqueleto em Python]

**Critérios de avaliação:**
- Funcionalidade completa (40%)
- Correção de algoritmos (30%)
- Visualização (15%)
- Documentação (15%)

🎯 EXERCÍCIOS DE FIXAÇÃO:
- Questões rápidas por conceito
- Cenários de troubleshooting

🚀 PREPARAÇÃO PARA DIAS 36-42:
- Preview: page replacement algorithms, memory allocation, GC
- Conexões com semana 5
- Roadmap

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice
- Spaced repetition
- Interleaving
- Project-based learning
- Synthesis
- Auto-avaliação

DIAGRAMAS MERMAID (mínimo 3):
1. Mapa mental integrado semana 5
2. Fluxo completo de acesso à memória (todas as etapas)
3. Arquitetura do simulador

IMPORTANTE:
- INTEGRAÇÃO total
- Simulador deve ser VISUAL e EDUCATIVO
- Celebrar progresso
- Preparar para algoritmos de substituição
- Código consolida aprendizado

Formato: markdown estruturado, visual, com quiz e projeto detalhado.
```

---

## 📅 DIA 36 - Page Replacement Algorithms: Escolhendo Vítimas

**📚 Recursos:**
- [Page Replacement](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-beyondphys-policy.pdf)
- [Replacement Algorithms](https://www.geeksforgeeks.org/page-replacement-algorithms-in-operating-systems/)
- [Belady's Anomaly](https://en.wikipedia.org/wiki/B%C3%A9l%C3%A1dy%27s_anomaly)

**🎯 Tópicos:**
- Optimal algorithm (teórico)
- FIFO: simplicidade e Belady's anomaly
- LRU (Least Recently Used)
- Clock algorithm (second chance)
- LFU (Least Frequently Used)
- Working set model

**💻 Exercício Prático:**
- Implementar FIFO, LRU, Clock
- Comparar com diferentes traces
- Demonstrar Belady's anomaly

**✅ Checkpoint:**
- [ ] Implementa 3+ algoritmos
- [ ] Compara desempenho
- [ ] Escolhe algoritmo apropriado

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre algoritmos de substituição de páginas. Dia 36 de estudos (Fase 3).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre page replacement algorithms:

CONTEÚDO TÉCNICO:
1. Problema: RAM cheia, preciso alocar frame para nova página
   - Solução: escolher página vítima para remover (swap out)
2. Optimal (OPT): substitui página que será usada mais tarde no futuro
   - Impossível implementar (precisa saber o futuro!)
   - Usado como baseline teórico
   - Menor número possível de page faults
3. FIFO (First-In, First-Out): remove página mais antiga
   - Simples: fila circular
   - Problema: pode remover página muito usada
   - Belady's Anomaly: mais frames podem causar MAIS faults!
4. LRU (Least Recently Used): remove página menos usada recentemente
   - Aproximação do Optimal
   - Princípio: passado recente prediz futuro próximo
   - Implementação: timestamp ou stack
   - Custo: overhead de rastreamento
5. Clock (Second Chance): aproximação de LRU mais eficiente
   - Circular list com reference bit
   - Varredura: se ref=1, dá segunda chance (ref=0), se ref=0, substitui
   - Usado em muitos sistemas reais
6. LFU (Least Frequently Used): remove página menos usada
   - Contador de acessos
   - Problema: página antiga com muitos acessos nunca sai
7. Working set model: páginas ativas de um processo
8. MRU (Most Recently Used): remove mais recente (casos específicos)
9. Random: escolhe aleatoriamente (baseline simples)

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: swapping e page faults (Dia 34)
- Analogia central: "Biblioteca com Espaço Limitado" - escolher livros para remover
- História introdutória sobre Belady descobrindo a anomalia

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Comparação visual: FIFO vs LRU vs Clock (mesmo trace)
  * Clock algorithm (circular list com ponteiro)
  * Belady's Anomaly (gráfico: frames vs faults)
  * Timeline de LRU (acesso e timestamp)
- Tabela comparativa: algoritmos (complexidade, performance, overhead)
- Exemplos step-by-step de cada algoritmo
- Fórmula de page fault rate

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo FIFO step-by-step (5 páginas, 3 frames)
- Demonstração de LRU (rastreamento de acesso)
- Clock algorithm visual (varredura)
- Demonstração de Belady's Anomaly

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Simulando Algoritmos de Substituição
  * Parte 1: Implementar Algoritmos
    - FIFO: fila circular
    - LRU: usar OrderedDict ou lista + timestamp
    - Clock: circular list + reference bit
    - Random: baseline
  * Parte 2: Simulação Manual
    - Trace: [1, 2, 3, 4, 1, 2, 5, 1, 2, 3, 4, 5]
    - Frames: 3
    - Executar cada algoritmo manualmente
    - Contar page faults
    - Comparar resultados
  * Parte 3: Simulação Automatizada
    - Gerar traces:
      * Sequential: 1, 2, 3, ..., N, 1, 2, ...
      * Random: acessos aleatórios
      * Locality: loops pequenos (simular working set)
    - Executar todos os algoritmos
    - Variar número de frames (1-20)
    - Plotar gráficos: frames vs fault rate
  * Parte 4: Demonstrar Belady's Anomaly
    - FIFO com trace específico
    - 3 frames: X faults
    - 4 frames: X+1 faults (anomalia!)
    - Demonstrar que LRU não tem anomalia
  * Parte 5: Comparação e Análise
    - Qual algoritmo é melhor?
    - Depende do padrão de acesso
    - Trade-off: simplicidade vs performance vs overhead
    - Quando usar cada um
  * Contexto motivador
  * Especificação clara
  * Código completo (Python com visualizações)
  * Dicas progressivas
  * Gráficos de resultados
  * Análise detalhada
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir LRU com LFU, não entender Clock)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar LRU-K ou ARC
- Preparação para Dia 37 (memory allocation)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de biblioteca
- Exemplos visuais step-by-step
- Storytelling (história de Belady)
- Scaffolding
- Chunking
- Dual coding
- Hands-on com simulações
- Comparação extensiva
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Comparação lado a lado: FIFO, LRU, Clock (mesmo trace)
2. Clock algorithm (circular list visual)
3. Belady's Anomaly (gráfico)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Simulações VISUAIS
- Comparações extensivas
- Demonstrar Belady's Anomaly (importante!)
- Foco em trade-offs
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 37 - Memory Allocation: malloc() e free()

**📚 Recursos:**
- [Dynamic Memory Allocation](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-freespace.pdf)
- [malloc Implementation](https://sourceware.org/glibc/wiki/MallocInternals)
- [Memory Allocators](https://www.gingerbill.org/article/2019/02/08/memory-allocation-strategies-002/)

**🎯 Tópicos:**
- Heap management
- Free list management
- Allocation strategies: first fit, best fit, worst fit
- Splitting e coalescing
- Fragmentação externa
- Memory allocators: dlmalloc, tcmalloc, jemalloc

**💻 Exercício Prático:**
- Implementar malloc/free simples
- Comparar estratégias de alocação
- Medir fragmentação

**✅ Checkpoint:**
- [ ] Implementa allocator básico
- [ ] Entende fragmentação
- [ ] Compara allocators

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre alocação de memória dinâmica. Dia 37 de estudos (Fase 3).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre memory allocation (malloc/free):

CONTEÚDO TÉCNICO:
1. Heap: região de memória para alocação dinâmica
2. malloc(size): aloca bloco de memória, retorna ponteiro
3. free(ptr): libera bloco previamente alocado
4. Free list: lista de blocos livres
5. Allocation strategies:
   - First fit: primeiro bloco que cabe
   - Best fit: menor bloco que cabe (minimiza desperdício)
   - Worst fit: maior bloco disponível
   - Next fit: como first fit, mas continua de onde parou
6. Splitting: dividir bloco grande em dois (usado + livre)
7. Coalescing: unir blocos livres adjacentes
8. Fragmentação externa: espaço livre mas fragmentado
   - Total free: suficiente
   - Maior bloco contíguo: insuficiente
9. Metadata: header em cada bloco (size, free/used)
10. Boundary tags: footer para coalescing eficiente
11. Segregated lists: listas separadas por tamanho
12. Allocators reais:
    - dlmalloc (Doug Lea): usado no glibc
    - tcmalloc (Google): thread-caching malloc
    - jemalloc (Facebook): otimizado para multithreading
13. sbrk() / brk(): system calls para expandir heap

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: heap no memory layout (Dia 30)
- Analogia central: "Estacionamento com Vagas Variáveis" - alocar espaços de tamanhos diferentes
- História introdutória sobre gerenciamento de memória

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Heap com blocos alocados e livres
  * Free list (linked list de blocos)
  * Comparação: first fit vs best fit vs worst fit
  * Splitting e coalescing (antes e depois)
- Tabela comparativa: estratégias de alocação
- Estrutura de metadata (header/footer)
- Visualização de fragmentação externa

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de malloc/free step-by-step
- Demonstração de first fit
- Demonstração de coalescing
- Fragmentação externa visual

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Implementando Memory Allocator
  * Parte 1: Estrutura Básica
    - Heap como array de bytes
    - Struct Block: {size, is_free, next}
    - Free list inicial
  * Parte 2: malloc() - First Fit
    - Percorrer free list
    - Encontrar primeiro bloco >= size
    - Splitting se bloco muito maior
    - Atualizar metadata
    - Retornar ponteiro
  * Parte 3: free()
    - Marcar bloco como livre
    - Adicionar à free list
    - Coalescing com vizinhos
    - Atualizar ponteiros
  * Parte 4: Comparar Estratégias
    - Implementar best fit
    - Implementar worst fit
    - Sequência de alocações/liberações
    - Medir:
      * Tempo de alocação
      * Fragmentação externa
      * Utilização de memória
    - Comparar resultados
  * Parte 5: Demonstrar Fragmentação
    - Alocar: 100, 200, 100, 200 bytes
    - Liberar: blocos de 200 bytes
    - Tentar alocar 300 bytes
    - Falha! (fragmentação)
    - Coalescing resolve
  * Parte 6: Visualização
    - Imprimir estado do heap
    - Blocos alocados (verde)
    - Blocos livres (vermelho)
    - Visualizar fragmentação
  * Contexto motivador
  * Especificação clara
  * Código completo (C, Python)
  * Dicas progressivas
  * Análise de performance
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (esquecer coalescing, memory leaks, double free)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar segregated free lists
- Preparação para Dia 38 (segmentação)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de estacionamento
- Exemplos visuais de heap
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com implementação
- Visualização de fragmentação
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Heap com blocos alocados/livres
2. Free list (linked list visual)
3. Splitting e coalescing (antes/depois)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Implementação FUNCIONAL
- Visualização do heap
- Demonstrar fragmentação
- Foco em trade-offs
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 38 - Segmentação: Divisão Lógica

**📚 Recursos:**
- [Segmentation](http://pages.cs.wisc.edu/~remzi/OSTEP/vm-segmentation.pdf)
- [Segmentation vs Paging](https://www.geeksforgeeks.org/difference-between-paging-and-segmentation/)
- [x86 Segmentation](https://wiki.osdev.org/Segmentation)

**🎯 Tópicos:**
- Conceito de segmento
- Segment table
- Segmentation com paginação
- x86 segmentation (histórico)
- Proteção por segmento
- Fragmentação externa

**💻 Exercício Prático:**
- Simular address translation com segmentos
- Implementar proteção por segmento
- Comparar segmentação vs paginação

**✅ Checkpoint:**
- [ ] Compreende segmentação
- [ ] Diferencia de paginação
- [ ] Implementa proteção

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre segmentação. Dia 38 de estudos (Fase 3).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre segmentação de memória:

CONTEÚDO TÉCNICO:
1. Segmentação: dividir memória em blocos lógicos de tamanhos variáveis
2. Segmento: unidade lógica (code, data, stack, heap)
3. Por que segmentação:
   - Corresponde à estrutura do programa
   - Proteção por segmento (code read-only, stack no-execute)
   - Compartilhamento de code entre processos
4. Segment table: mapeia segmentos para memória física
5. Segment table entry:
   - Base: endereço físico inicial
   - Limit (bounds): tamanho do segmento
   - Protection bits: read, write, execute
   - Valid bit
6. Address translation:
   - Logical address: [segment # | offset]
   - Verificar: offset < limit
   - Physical address: base + offset
7. Segmentation fault: acesso além do limit
8. Fragmentação externa: segmentos de tamanhos variáveis
   - Compaction: reorganizar memória (caro!)
9. Segmentação + Paginação (x86):
   - Segmentos divididos em páginas
   - Duas etapas de translation
10. x86 segmentation (histórico):
    - CS, DS, SS, ES (segment registers)
    - Modo protegido vs real
    - x86-64: segmentação quase abolida
11. Comparação: segmentação vs paginação
    - Segmentação: tamanho variável, fragmentação externa, lógico
    - Paginação: tamanho fixo, fragmentação interna, físico

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: paginação (Dias 31-34), memory layout (Dia 30)
- Analogia central: "Departamentos de Empresa" - divisões lógicas com tamanhos diferentes
- História introdutória sobre arquitetura x86

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Segmentação: segmentos mapeados para memória física
  * Segment table (estrutura)
  * Address translation com segmentos
  * Comparação visual: segmentação vs paginação
- Tabela comparativa: segmentação vs paginação
- Estrutura de segment table entry
- Fragmentação externa visual

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de address translation com segmentos
- Demonstração de proteção (code read-only)
- Exemplo de segmentation fault
- Fragmentação externa step-by-step

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Simulando Segmentação
  * Parte 1: Address Translation Manual
    - Segment table:
      * Seg 0 (code): base=4000, limit=1000, read+exec
      * Seg 1 (data): base=8000, limit=2000, read+write
      * Seg 2 (stack): base=15000, limit=500, read+write
    - Logical addresses: [seg | offset]
    - Traduzir: (0, 100), (1, 500), (2, 600)
    - Detectar erro: (1, 3000) - beyond limit!
  * Parte 2: Implementar Simulador
    - Struct Segment: {base, limit, permissions}
    - Segment table: array de segments
    - Função translate(seg_num, offset)
    - Verificações:
      * offset < limit?
      * permissões corretas?
    - Retornar physical address ou erro
  * Parte 3: Proteção por Segmento
    - Code segment: read+execute only
    - Tentar escrever em code: permission denied
    - Stack segment: read+write, no-execute
    - Tentar executar stack: permission denied (previne buffer overflow!)
  * Parte 4: Fragmentação Externa
    - Memória física: 10000 bytes
    - Alocar segmentos: 2000, 3000, 1500, 2500
    - Liberar: 3000 e 1500 (meio)
    - Tentar alocar 5000: falha! (fragmentação)
    - Total livre: 4500, mas não contíguo
    - Compaction: reorganizar
  * Parte 5: Comparação com Paginação
    - Mesmo programa
    - Implementar com segmentação
    - Implementar com paginação
    - Comparar:
      * Fragmentação
      * Overhead de translation
      * Proteção
      * Complexidade
  * Contexto motivador
  * Especificação clara
  * Código completo (Python, C)
  * Dicas progressivas
  * Análise comparativa
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir com paginação, ignorar proteção)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar segmentação + paginação
- Preparação para Dia 39 (copy-on-write, mmap)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de departamentos
- Exemplos visuais de segmentos
- Storytelling (história x86)
- Scaffolding
- Chunking
- Dual coding
- Hands-on com simulação
- Comparação extensiva
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Segmentação visual (segmentos → memória física)
2. Segment table e address translation
3. Proteção por segmento (bits de permissão)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Comparar SEMPRE com paginação
- Demonstrar proteção (importante!)
- Fragmentação externa visual
- Contexto histórico (x86)
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 39 - Copy-on-Write e Memory Mapping: Otimizações Inteligentes

**📚 Recursos:**
- [Copy-on-Write](https://www.kernel.org/doc/gorman/html/understand/understand010.html)
- [mmap()](https://man7.org/linux/man-pages/man2/mmap.2.html)
- [Memory-Mapped Files](https://www.kernel.org/doc/html/latest/admin-guide/mm/transhuge.html)

**🎯 Tópicos:**
- Copy-on-Write (CoW): otimizando fork()
- Shared libraries
- Memory-mapped files: mmap()
- Anonymous mapping
- Demand paging
- Prefetching

**💻 Exercício Prático:**
- Demonstrar CoW com fork
- Usar mmap para I/O eficiente
- Criar shared memory com mmap

**✅ Checkpoint:**
- [ ] Compreende CoW
- [ ] Usa mmap efetivamente
- [ ] Otimiza com mapping

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre otimizações de memória. Dia 39 de estudos (Fase 3).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre Copy-on-Write e mmap:

CONTEÚDO TÉCNICO:
1. Copy-on-Write (CoW): otimização para fork()
   - Problema: fork() copia toda a memória (caro!)
   - Solução CoW: compartilhar páginas, copiar apenas quando escrever
   - Processo: fork() → páginas marcadas read-only → write → page fault → copiar página
2. Benefícios CoW:
   - fork() muito rápido
   - Economiza memória (processos compartilham)
   - Usado em fork() + exec() (comum)
3. Memory-mapped files: mmap()
   - Mapear arquivo diretamente no address space
   - Acessar arquivo como memória (ponteiro)
   - I/O implícito (page faults)
   - Sistema trata file I/O como page faults
4. Tipos de mmap:
   - File-backed: mapeia arquivo real
   - Anonymous: memória sem arquivo (como malloc)
5. Shared vs Private mapping:
   - Shared (MAP_SHARED): mudanças visíveis para todos
   - Private (MAP_PRIVATE): CoW, mudanças privadas
6. Benefícios de mmap:
   - I/O eficiente (zero-copy)
   - Shared memory entre processos
   - Code sharing (shared libraries)
   - Large files sem ler tudo
7. Shared libraries (.so, .dll):
   - Code compartilhado entre processos
   - mmap com MAP_SHARED
   - Economia massiva de memória
8. Demand paging: carregar páginas sob demanda
   - Não carregar programa inteiro
   - Carregar apenas páginas acessadas
   - Otimização de startup time
9. Prefetching: carregar páginas antecipadamente
   - Prever acessos futuros (localidade espacial)
   - Carregar páginas vizinhas
10. Lazy allocation: adiar alocação real

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: fork() (Dia 25), page faults (Dia 34)
- Analogia central: "Biblioteca com Fotocópias" - compartilhar até precisar modificar
- História introdutória sobre otimização de sistemas

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Copy-on-Write (antes fork, depois fork, depois write)
  * mmap: arquivo mapeado no address space
  * Shared libraries (múltiplos processos compartilhando)
  * Demand paging (carregamento incremental)
- Tabela: mmap flags e comportamentos
- Comparação: read/write vs mmap
- CoW step-by-step

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de fork() com CoW
- Demonstração de mmap para ler arquivo
- Exemplo de shared memory com mmap
- Código de shared library

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Copy-on-Write e mmap na Prática
  * Parte 1: Demonstrar Copy-on-Write
    - Programa pai: aloca array grande
    - fork()
    - Filho: lê array (sem copiar!)
    - Filho: modifica uma posição
    - Page fault → cópia daquela página
    - Observar /proc/[pid]/maps
    - Comparar RSS (resident set size)
    - Demonstrar economia de memória
  * Parte 2: mmap para I/O
    - Criar arquivo grande (1GB)
    - Método 1: read/write tradicional
      * Abrir, read, processar, write
      * Medir tempo
    - Método 2: mmap
      * mmap arquivo
      * Acessar como array
      * Modificar diretamente
      * munmap
      * Medir tempo
    - Comparar performance (mmap é mais rápido!)
  * Parte 3: Shared Memory com mmap
    - Processo A:
      * mmap anônimo com MAP_SHARED
      * Escrever dados
      * Esperar
    - Processo B:
      * mmap mesmo região
      * Ler dados escritos por A
    - Comunicação via memória compartilhada
    - Comparar com pipes (mmap mais rápido!)
  * Parte 4: Simular Demand Paging
    - Programa grande
    - Medir: apenas páginas acessadas são carregadas
    - Monitorar page faults (perf)
    - Comparar com carregar tudo
  * Parte 5: Analisar Shared Libraries
    - ldd /bin/ls (listar shared libs)
    - cat /proc/[pid]/maps
    - Identificar libc.so
    - Múltiplos processos usando mesma libc
    - Economia de memória
  * Contexto motivador
  * Especificação clara
  * Código completo (C, alguns em Python)
  * Comandos Linux
  * Dicas progressivas
  * Medições de performance
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir CoW com compartilhamento simples)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar simulador de CoW
- Preparação para Dia 40 (Linux memory management)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de fotocópias
- Exemplos visuais de CoW
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com código real
- Medições de performance
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Copy-on-Write (3 etapas: fork, leitura, escrita)
2. mmap: arquivo no address space
3. Shared libraries entre processos
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Demonstrar ECONOMIA de recursos
- Medições concretas
- Foco em OTIMIZAÇÃO
- Código funcional
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 40 - Linux Memory Management: Implementação Real

**📚 Recursos:**
- [Linux VM](https://www.kernel.org/doc/html/latest/admin-guide/mm/concepts.html)
- [Buddy System](https://www.kernel.org/doc/gorman/html/understand/understand009.html)
- [Slab Allocator](https://www.kernel.org/doc/gorman/html/understand/understand011.html)

**🎯 Tópicos:**
- Buddy allocator
- Slab allocator
- Zone allocator (DMA, Normal, HighMem)
- Page cache
- OOM Killer
- /proc/meminfo interpretação

**💻 Exercício Prático:**
- Analisar /proc/meminfo
- Monitorar page cache
- Configurar OOM behavior

**✅ Checkpoint:**
- [ ] Compreende Linux MM
- [ ] Interpreta métricas
- [ ] Ajusta configurações

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre gerenciamento de memória do Linux. Dia 40 de estudos (Fase 3).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre Linux memory management:

CONTEÚDO TÉCNICO:
1. Buddy allocator: alocação de páginas físicas
   - Blocos de tamanhos 2^n (1, 2, 4, 8, ... 512 páginas)
   - Splitting: dividir bloco grande
   - Coalescing: unir blocos buddy (vizinhos potências de 2)
   - Eficiente para alocações de páginas
2. Slab allocator: alocação de objetos pequenos do kernel
   - Cache de objetos de tamanho fixo
   - Reduz overhead de buddy para objetos pequenos
   - Slabs: grupos de objetos
   - Usado para structs do kernel (inodes, dentries, etc)
3. Zone allocator: diferentes tipos de memória
   - ZONE_DMA: primeiros 16MB (ISA devices)
   - ZONE_NORMAL: 16MB-896MB (kernel direct mapping)
   - ZONE_HIGHMEM: >896MB (32-bit, requer mapping)
   - x86-64: sem HIGHMEM (64-bit address space)
4. Page cache: cache de páginas de arquivo
   - Buffer cache: cache de blocos de disco
   - Unificado no Linux moderno
   - LRU lists: active e inactive
   - Dirty pages: modificadas mas não escritas
   - Writeback: flush dirty pages para disco
5. OOM Killer (Out-of-Memory):
   - Detecta: memória física esgotada
   - Escolhe vítima (heurística)
   - Mata processo para liberar memória
   - oom_score: pontuação de cada processo
   - oom_adj: ajustar prioridade
6. /proc/meminfo: estatísticas de memória
   - MemTotal, MemFree, MemAvailable
   - Buffers, Cached
   - SwapTotal, SwapFree
   - Dirty, Writeback
   - Slab
7. /proc/[pid]/smaps: mapa detalhado por processo
8. vmstat: estatísticas de virtual memory
9. Transparent Huge Pages (THP): páginas de 2MB automáticas

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: todos os conceitos de memória (Dias 29-39)
- Analogia central: "Sistema de Logística" - múltiplos subsistemas coordenados
- História introdutória sobre evolução do Linux MM

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Buddy allocator (árvore de blocos)
  * Slab allocator (caches de objetos)
  * Memory zones (DMA, Normal, High)
  * Page cache e LRU lists
- Tabela: zones e características
- /proc/meminfo explicado linha por linha
- OOM Killer heuristic

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de buddy split e coalesce
- Demonstração de /proc/meminfo
- Exemplo de page cache em ação
- OOM Killer trigger (cuidado!)

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Explorando Linux Memory Management
  * Parte 1: Buddy Allocator
    - Ler /proc/buddyinfo
    - Interpretar: blocos livres de cada ordem
    - Simular buddy allocation:
      * Alocar 8 páginas
      * Alocar 3 páginas (split de bloco 4)
      * Liberar e coalesce
  * Parte 2: Slab Allocator
    - cat /proc/slabinfo
    - Identificar caches principais:
      * dentry, inode_cache, buffer_head
    - Interpretar campos: active objs, total objs
    - slabtop (monitoramento)
  * Parte 3: Page Cache
    - Ler arquivo grande
    - free -h (ver Cached aumentar)
    - cat /proc/meminfo | grep -i cache
    - Ler arquivo novamente (muito mais rápido!)
    - Limpar cache: sync; echo 3 > /proc/sys/vm/drop_caches
    - Ler novamente (lento de novo)
  * Parte 4: Memory Zones
    - cat /proc/zoneinfo
    - Identificar zones
    - Páginas free em cada zone
    - Watermarks: min, low, high
  * Parte 5: OOM Killer
    - Analisar /proc/[pid]/oom_score
    - Processos com maior score (prováveis vítimas)
    - Ajustar: echo -1000 > /proc/[pid]/oom_adj (proteger)
    - Ver logs: dmesg | grep -i oom
    - [CUIDADO] Não triggerar OOM de propósito!
  * Parte 6: vmstat e Monitoring
    - vmstat 1 (atualizar a cada segundo)
    - Colunas importantes:
      * si, so: swap in/out
      * bi, bo: block in/out
      * us, sy, id: CPU user, system, idle
    - Monitorar durante workload
  * Contexto motivador
  * Especificação clara
  * Comandos Linux detalhados
  * Análise de cada subsistema
  * Dicas progressivas
  * Interpretação de métricas
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir cached com usado, não entender OOM)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Tunning de memória do sistema
- Preparação para Dia 41 (garbage collection)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de logística
- Exemplos visuais de estruturas
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com sistema real
- Exploration-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Buddy allocator (árvore binária)
2. Slab allocator (caches e slabs)
3. Memory zones (layout)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Foco em sistema REAL (Linux)
- Comandos práticos
- Interpretação de métricas
- Monitoramento hands-on
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 41 - Garbage Collection: Memória Gerenciada

**📚 Recursos:**
- [GC Algorithms](https://www.memorymanagement.org/)
- [Java GC](https://www.oracle.com/webfolder/technetwork/tutorials/obe/java/gc01/index.html)
- [GC Handbook](https://gchandbook.org/)

**🎯 Tópicos:**
- Por que GC?
- Reference counting
- Mark and Sweep
- Copying collectors
- Generational GC
- Concurrent e parallel GC
- GC pauses

**💻 Exercício Prático:**
- Implementar reference counting simples
- Simular mark-and-sweep
- Analisar GC logs (Java/Python)

**✅ Checkpoint:**
- [ ] Compreende GC algorithms
- [ ] Implementa GC básico
- [ ] Analisa GC behavior

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre garbage collection. Dia 41 de estudos (Fase 3).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre garbage collection:

CONTEÚDO TÉCNICO:
1. Garbage Collection: gerenciamento automático de memória
2. Por que GC:
   - Elimina memory leaks
   - Elimina dangling pointers
   - Simplifica programação
   - Trade-off: performance e controle
3. Reference Counting:
   - Cada objeto tem contador de referências
   - Incrementa: nova referência
   - Decrementa: referência removida
   - Se count = 0: liberar
   - Problema: ciclos (A → B → A)
4. Mark and Sweep (Tracing GC):
   - Mark phase: marcar objetos alcançáveis (DFS/BFS de roots)
   - Sweep phase: liberar objetos não marcados
   - STW (Stop-the-World): pausar aplicação
5. Copying Collector:
   - Dividir heap: from-space e to-space
   - Copiar objetos vivos para to-space
   - Trocar espaços
   - Compaction automático
   - Custo: metade do heap inutilizado
6. Generational GC (usado em Java, Python, .NET):
   - Hipótese: objetos jovens morrem rápido
   - Heap dividido: young generation e old generation
   - Minor GC: coleta young (frequente, rápido)
   - Major GC: coleta old (raro, lento)
   - Promotion: objetos sobreviventes vão para old
7. Concurrent GC: coleta paralela à aplicação
   - Reduz pausas
   - Complexo (objetos mudam durante coleta)
8. Parallel GC: múltiplas threads de GC
   - Mais throughput
   - Pausa ainda existe (mas menor)
9. GC pauses: impacto em latência
   - Crítico para aplicações real-time
   - GCs modernos: pausas < 10ms
10. Languages: Java (G1, ZGC), Python (ref counting + cycle detector), Go (concurrent mark-sweep)

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: malloc/free (Dia 37)
- Analogia central: "Limpeza Automática de Casa" - sistema remove lixo automaticamente
- História introdutória sobre John McCarthy e Lisp (primeiro GC)

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Reference counting (objetos e contadores)
  * Mark and Sweep (fases mark e sweep)
  * Generational GC (young e old generations)
  * Comparação de algoritmos (pros/cons)
- Tabela comparativa: algoritmos de GC
- Timeline de pause times
- Ciclos em reference counting

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de reference counting
- Demonstração de mark-and-sweep step-by-step
- Generational GC visual
- Análise de GC logs

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Implementando e Analisando GC
  * Parte 1: Reference Counting
    - Implementar objetos com ref counter
    - Funções: ref(), unref()
    - Criar objetos, fazer referências
    - Remover referências
    - Auto-free quando count = 0
    - Criar ciclo: A → B → A
    - Demonstrar memory leak (ciclo!)
  * Parte 2: Mark and Sweep
    - Heap de objetos (lista/array)
    - Roots: variáveis globais/stack
    - Mark phase:
      * DFS a partir de roots
      * Marcar objetos alcançáveis
    - Sweep phase:
      * Percorrer heap
      * Liberar não marcados
    - Estatísticas: objetos vivos, coletados
    - Resolver ciclos (diferente de ref counting)
  * Parte 3: Simular Generational GC
    - Young generation (pequeno)
    - Old generation (grande)
    - Alocar objetos em young
    - Minor GC: copiar survivors
    - Promotion após N survivals
    - Major GC quando old enche
    - Contar GCs de cada tipo
  * Parte 4: Analisar GC Real
    - Java:
      * Programa com -XX:+PrintGCDetails
      * Criar muitos objetos
      * Analisar output: young GC, full GC
      * Pausas (tempo)
    - Python:
      * import gc
      * gc.get_stats()
      * gc.collect() forçar coleta
      * Observar comportamento
  * Parte 5: Medir Impacto de GC
    - Programa com alocação intensiva
    - Com GC: pausas periódicas
    - Sem GC (manual): controle total mas complexo
    - Trade-off: conveniência vs performance
  * Contexto motivador
  * Especificação clara
  * Código completo (Python, Java)
  * Dicas progressivas
  * Visualizações
  * Análise de logs
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (ciclos em ref counting, não entender generations)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar generational GC completo
- Preparação para Dia 42 (revisão Fase 3)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de limpeza automática
- Exemplos visuais de grafos de objetos
- Storytelling (história de McCarthy)
- Scaffolding
- Chunking
- Dual coding
- Hands-on com implementação
- Análise de sistemas reais
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Reference counting (objetos, contadores, ciclo)
2. Mark and Sweep (mark phase, sweep phase)
3. Generational GC (young, old, promotion)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Implementação funcional
- Análise de linguagens reais
- Foco em trade-offs
- Demonstrar problema de ciclos
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 42 - Revisão Fase 3 + Projeto Final da Fase

**🎯 Objetivo:** Consolidar TODA a Fase 3

**📝 Atividades:**
- Revisão completa (Dias 29-41)
- Quiz final da fase (35 questões)
- Mapa mental integrado

**💻 PROJETO FINAL FASE 3:**
**"Memory Manager Completo e Avançado"**

Criar um sistema de gerenciamento de memória que:
1. Implementa paginação multi-level (4 níveis)
2. Simula TLB com replacement
3. Page replacement com 3+ algoritmos
4. Memory allocator (malloc/free) com estratégias
5. Swapping to disk simulado
6. Copy-on-Write simulation
7. Visualização de memory layout
8. Estatísticas detalhadas e comparações
9. Interface interativa
10. Documentação técnica completa

**✅ Checkpoint:**
- [ ] Revisão completa
- [ ] 85%+ no quiz
- [ ] Projeto robusto e completo
- [ ] Pronto para Fase 4

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da FASE 3 COMPLETA. Dia 42 de estudos.

Crie material de REVISÃO ABRANGENTE E PROJETO FINAL usando DESIGN INSTRUCIONAL para toda a Fase 3:

CONTEÚDO A REVISAR (Dias 29-41):
1. Memory Hierarchy: cache, localidade
2. Address Spaces: virtual vs físico, layout
3. Paginação: páginas, frames, page tables
4. TLB: cache de traduções
5. Advanced Page Tables: multi-level, inverted
6. Swapping: page faults, swap space
7. [Revisão semana 5 + Simulador]
8. Page Replacement: FIFO, LRU, Clock
9. Memory Allocation: malloc/free, estratégias
10. Segmentação: divisão lógica
11. CoW e mmap: otimizações
12. Linux MM: buddy, slab, zones
13. Garbage Collection: algoritmos, trade-offs

ESTRUTURA:

📋 OBJETIVOS DA REVISÃO:
- Consolidar TODA Fase 3
- Visão holística de memória
- Projeto final integrador complexo
- Preparar para Fase 4 (File Systems e I/O)

🔄 REVISÃO INTEGRADA COMPLETA:
- Mapa mental GIGANTE da Fase 3
- Resumo executivo de cada dia
- Conexões profundas
- Jornada completa: virtual address → TLB → page table (multi-level) → physical memory/swap
- DIAGRAMAS MERMAID:
  * Visão integrada completa
  * Todos os componentes de memória
  * Fluxo end-to-end

📝 QUIZ FINAL (35 questões):
- 2-3 questões por dia (29-41)
- 10 questões integradoras
- Níveis: fácil (25%), médio (50%), difícil (25%)
- Gabarito detalhado

💻 PROJETO FINAL: "Memory Manager Completo"

**Descrição:**
Sistema COMPLETO que integra TODOS os conceitos da Fase 3

**Especificação completa:**

MÓDULO 1: Four-Level Page Table
- Implementar x86-64 style (PML4 → PDP → PD → PT)
- Address translation completa
- Allocation sob demanda
- Protection bits

MÓDULO 2: TLB Cache
- 64 entries, fully associative
- LRU replacement
- Context switch simulation
- ASID support

MÓDULO 3: Physical Memory Manager
- Buddy allocator simulation
- Frame allocation/free
- Memory zones (DMA, Normal)
- Statistics

MÓDULO 4: Swap Space
- Disk simulation
- Page replacement algorithms:
  * FIFO
  * LRU
  * Clock (second chance)
- Swap in/out
- Thrashing detection

MÓDULO 5: Memory Allocator (Heap)
- malloc/free implementation
- First fit, best fit, worst fit
- Splitting e coalescing
- Fragmentation metrics

MÓDULO 6: Copy-on-Write
- Shared pages entre "processos"
- Write triggers copy
- Reference counting

MÓDULO 7: Memory-Mapped Files
- Simular mmap
- File-backed pages
- Demand paging

MÓDULO 8: Visualização e Análise
- Memory layout visual
- Page table walk animation
- TLB state
- Heap state
- Swap usage
- Gráficos de performance

MÓDULO 9: Workload Simulation
- Traces de acesso
- Múltiplos "processos"
- fork() simulation
- Benchmarks

MÓDULO 10: Estatísticas e Relatórios
- TLB hit rate
- Page fault rate
- Swap in/out count
- Memory utilization
- Fragmentation
- Comparação de algoritmos
- Exportação (HTML, JSON)

**Estrutura do projeto:**
```
advanced-memory-manager/
├── src/
│   ├── main.py
│   ├── page_table_multilevel.py
│   ├── tlb.py
│   ├── physical_memory.py
│   ├── buddy_allocator.py
│   ├── swap.py
│   ├── page_replacement.py
│   ├── heap_allocator.py
│   ├── cow.py
│   ├── mmap_sim.py
│   ├── process_sim.py
│   ├── visualizer.py
│   └── stats.py
├── tests/
│   └── [testes para cada módulo]
├── traces/
│   ├── sequential.txt
│   ├── random.txt
│   ├── locality.txt
│   └── mixed.txt
├── docs/
│   ├── README.md
│   ├── ARCHITECTURE.md
│   ├── API.md
│   └── USER_GUIDE.md
└── requirements.txt
```

**Implementação guiada (12-16 horas):**

[Detalhar cada passo com tempo estimado]

**Critérios de avaliação:**
- Funcionalidade completa (35%)
- Correção de algoritmos (25%)
- Integração entre módulos (20%)
- Visualização e UX (10%)
- Documentação (10%)

**Features bônus:**
- Transparent Huge Pages
- NUMA simulation
- GC integration
- Performance profiling

🚀 PREPARAÇÃO PARA FASE 4:
- Preview: File Systems e I/O (Dias 43-52)
- Tópicos: devices, disks, file systems, I/O scheduling
- Conexões: memória ↔ armazenamento
- Motivação

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice massiva
- Project-based learning
- Synthesis total
- Integration de TODOS os conceitos
- Auto-avaliação profunda

DIAGRAMAS MERMAID (mínimo 5):
1. Mapa mental GIGANTE Fase 3
2. Jornada end-to-end completa
3. Arquitetura do projeto (10 módulos)
4. Fluxo de dados entre módulos
5. Casos de uso principais

IMPORTANTE:
- INTEGRAÇÃO TOTAL de conceitos
- Projeto MAIS COMPLEXO até agora
- Deve ser IMPRESSIONANTE
- Celebrar CONCLUSÃO DA FASE 3
- Tom motivacional máximo
- Preparar momentum para Fase 4
- Código deve ser SHOW-OFF worthy

Formato: markdown estruturado, visual, com quiz e projeto detalhado completo.
```

---

<a name="fase-4"></a>
# 📁 FASE 4: SISTEMAS DE ARQUIVOS E I/O (Dias 43-52)

**Objetivo:** Dominar filesystems, I/O devices e drivers

---

## 📅 DIA 43 - I/O Devices: Conversando com Hardware

**📚 Recursos:**
- [I/O Devices](http://pages.cs.wisc.edu/~remzi/OSTEP/file-devices.pdf)
- [Device Drivers](https://www.kernel.org/doc/html/latest/driver-api/basics.html)
- [I/O Architecture](https://www.geeksforgeeks.org/computer-organization-i-o-interface/)

**🎯 Tópicos:**
- Tipos de dispositivos: block vs character
- I/O ports e memory-mapped I/O
- Polling vs interrupts vs DMA
- Device controllers
- Device drivers: estrutura e função
- Camadas de I/O

**💻 Exercício Prático:**
- Explorar /dev
- Analisar device drivers carregados
- Observar interrupções (cat /proc/interrupts)

**✅ Checkpoint:**
- [ ] Diferencia tipos de dispositivos
- [ ] Compreende DMA
- [ ] Explora dispositivos do sistema

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais começando FASE 4: Sistemas de Arquivos e I/O. Dia 43 de estudos.

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre I/O devices:

CONTEÚDO TÉCNICO:
1. I/O devices: comunicação com hardware externo
2. Tipos de dispositivos:
   - Block devices: acesso em blocos (HDD, SSD, USB drive)
   - Character devices: stream de caracteres (teclado, mouse, serial port)
3. I/O ports: endereços para comunicação (x86: in/out instructions)
4. Memory-mapped I/O: dispositivos mapeados no address space
5. Métodos de I/O:
   - Polling (programmed I/O): CPU checa status repetidamente (busy-wait, ineficiente)
   - Interrupt-driven: dispositivo avisa CPU via interrupção (eficiente)
   - DMA (Direct Memory Access): dispositivo acessa memória sem CPU (mais eficiente!)
6. Device controller: chip que controla dispositivo
7. Device driver: software que controla device controller
   - Parte do kernel
   - Interface padronizada: open, close, read, write, ioctl
   - Específico para cada dispositivo
8. Camadas de I/O:
   - Application → System calls → Generic block/char layer → Device driver → Controller → Device
9. /dev: diretório de device files no Unix/Linux
10. Major/minor numbers: identificam driver e dispositivo específico

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: interrupções (Fase 1, Dia 2)
- Analogia central: "Mensageiros entre Departamentos" - comunicação entre CPU e periféricos
- História introdutória sobre evolução de I/O

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Arquitetura de I/O (CPU ↔ Controller ↔ Device)
  * Comparação: polling vs interrupts vs DMA
  * Camadas de I/O (stack completo)
  * Device driver no kernel
- Tabela: block vs character devices
- Comparação de métodos de I/O (eficiência)
- Fluxo de uma operação de I/O

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de polling vs interrupt
- Demonstração de DMA
- Código de device driver simples (conceitual)
- /dev exploration

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Explorando Dispositivos de I/O
  * Parte 1: Explorar /dev
    - ls -l /dev (listar todos)
    - Identificar block devices (b)
    - Identificar character devices (c)
    - Major/minor numbers
    - Exemplos:
      * /dev/sda (block, disco)
      * /dev/tty (char, terminal)
      * /dev/null (char, special)
      * /dev/random (char, random)
  * Parte 2: Analisar Drivers
    - lsmod (listar módulos/drivers carregados)
    - modinfo <module> (info sobre driver)
    - ls /sys/class/block (block devices)
    - ls /sys/class/tty (char devices)
  * Parte 3: Interrupções
    - cat /proc/interrupts
    - Identificar interrupções de I/O:
      * Disco (IRQ)
      * Teclado (IRQ 1)
      * Mouse
      * Network
    - Monitorar em tempo real (watch -n1 cat /proc/interrupts)
  * Parte 4: Simular I/O Methods
    - Polling (pseudocódigo):
      * while (device.status != READY) { }
      * read_data()
      * Problema: CPU desperdiçada
    - Interrupt-driven:
      * issue_read()
      * return (CPU livre)
      * [interrupt] → handler: process_data()
    - DMA:
      * setup_dma(buffer, size)
      * return (CPU livre)
      * [interrupt when done] → DMA complete
    - Comparar tempos e CPU usage
  * Parte 5: Device File Operations
    - Escrever em /dev/null (desaparece)
    - Ler de /dev/zero (zeros infinitos)
    - Ler de /dev/random (random bytes)
    - Demonstrar abstração: mesma interface (read/write)
  * Contexto motivador
  * Especificação clara
  * Comandos Linux detalhados
  * Simulação de métodos
  * Dicas progressivas
  * Análise de eficiência
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir block com char, não entender DMA)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar simulador de DMA
- Preparação para Dia 44 (discos)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de mensageiros
- Exemplos visuais de métodos I/O
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com sistema real
- Exploration-based learning
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura completa de I/O
2. Polling vs Interrupts vs DMA (comparação)
3. Camadas de I/O (stack)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Exploração de sistema REAL
- Foco em EFICIÊNCIA
- Demonstrar vantagens de DMA
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 44 - Hard Disks e SSDs: Armazenamento Persistente

**📚 Recursos:**
- [Hard Disk Drives](http://pages.cs.wisc.edu/~remzi/OSTEP/file-disks.pdf)
- [SSD Architecture](https://codecapsule.com/2014/02/12/coding-for-ssds-part-1-introduction-and-table-of-contents/)
- [Storage Devices](https://www.thomas-krenn.com/en/wiki/SSD_Basics)

**🎯 Tópicos:**
- HDD: geometria, seek time, rotational latency
- Disk scheduling: FCFS, SSTF, SCAN, C-SCAN
- SSD: flash memory, páginas, blocos, erase
- Wear leveling
- TRIM command
- Comparação HDD vs SSD

**💻 Exercício Prático:**
- Simular disk scheduling algorithms
- Medir latência de disco
- Comparar I/O sequential vs random

**✅ Checkpoint:**
- [ ] Compreende física de discos
- [ ] Implementa scheduling
- [ ] Otimiza para SSD vs HDD

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre discos rígidos e SSDs. Dia 44 de estudos (Fase 4).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre HDDs e SSDs:

CONTEÚDO TÉCNICO:
1. HDD (Hard Disk Drive): armazenamento magnético
2. Geometria de HDD:
   - Platters: discos magnéticos
   - Tracks: círculos concêntricos
   - Sectors: segmentos de track (512B ou 4KB)
   - Cylinders: tracks alinhados verticalmente
   - Head: cabeça de leitura/escrita
3. Tempo de acesso HDD:
   - Seek time: mover head para track correto (~5-10ms)
   - Rotational latency: esperar setor girar (~4-8ms para 7200 RPM)
   - Transfer time: ler/escrever dados (rápido)
   - Total: ~10-20ms por acesso
4. Disk scheduling algorithms:
   - FCFS: ordem de chegada (simples, não otimiza)
   - SSTF (Shortest Seek Time First): menor seek (starvation possível)
   - SCAN (Elevator): vai até fim, inverte (fair)
   - C-SCAN: vai até fim, volta ao início (mais uniforme)
   - LOOK/C-LOOK: como SCAN mas só até última requisição
5. SSD (Solid State Drive): armazenamento flash
6. Arquitetura SSD:
   - Flash memory: células NAND
   - Pages: unidade de leitura/escrita (4KB-16KB)
   - Blocks: grupo de pages (128-256 pages)
   - Erase: só pode apagar block inteiro!
7. Write amplification: escrever causa mais escritas internas
8. Wear leveling: distribuir writes uniformemente
   - Flash cells têm vida limitada (~100k-1M writes)
9. TRIM command: OS informa SSD sobre blocos livres
10. Comparação HDD vs SSD:
    - HDD: mecânico, lento random, barato, grande capacidade
    - SSD: eletrônico, rápido, caro, menor capacidade, sem partes móveis

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: I/O devices (Dia 43)
- Analogia central: "Vinil vs CD Player" - mecânico vs eletrônico
- História introdutória sobre evolução de storage

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Geometria de HDD (platters, tracks, sectors)
  * Disk scheduling (gráfico de movimento do head)
  * Arquitetura SSD (pages, blocks, controller)
  * Comparação HDD vs SSD (latências)
- Tabela: comparação HDD vs SSD (todas as métricas)
- Cálculo de access time
- Visualização de wear leveling

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de cálculo de access time HDD
- Demonstração de SCAN algorithm
- Exemplo de write amplification SSD
- Comparação sequential vs random I/O

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Simulando Discos e Scheduling
  * Parte 1: Simular Disk Scheduling
    - HDD com 200 tracks (0-199)
    - Head initial position: 53
    - Request queue: [98, 183, 37, 122, 14, 124, 65, 67]
    - Implementar algoritmos:
      * FCFS
      * SSTF
      * SCAN
      * C-SCAN
    - Calcular total head movement
    - Plotar gráfico de movimento
    - Comparar eficiência
  * Parte 2: Medir Latência Real
    - Criar arquivo grande (1GB)
    - Teste 1: Sequential read
      * dd if=file of=/dev/null bs=1M
      * Medir throughput (MB/s)
    - Teste 2: Random read
      * fio com random reads
      * Medir IOPS e latência
    - Comparar: sequential muito mais rápido em HDD
    - Em SSD: diferença menor
  * Parte 3: Simular SSD Internals
    - Flash memory: array de blocks
    - Cada block: array de pages
    - Operações:
      * Write page (se livre)
      * Read page
      * Erase block (apaga todas pages)
    - Implementar write com wear leveling
    - Rastrear write count por block
    - Demonstrar write amplification
  * Parte 4: Benchmark Real
    - hdparm -t /dev/sda (sequential read)
    - hdparm -T /dev/sda (cache read)
    - iostat -x 1 (monitorar I/O)
    - Comparar HDD vs SSD (se disponível)
  * Parte 5: TRIM Simulation
    - Arquivo grande
    - Escrever dados
    - Deletar arquivo
    - Sem TRIM: SSD não sabe (garbage dentro)
    - Com TRIM: SSD marca blocks livres
    - Melhora performance futura
  * Contexto motivador
  * Especificação clara
  * Código de simulação (Python)
  * Comandos de benchmark
  * Dicas progressivas
  * Análise de resultados
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir seek com rotational, não entender erase em SSD)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Otimizar padrão de acesso para HDD vs SSD
- Preparação para Dia 45 (file systems basics)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de vinil vs CD
- Exemplos visuais de geometria
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com simulação E benchmarks reais
- Comparação extensiva
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Geometria de HDD (completa)
2. Disk scheduling (movimento do head)
3. Arquitetura SSD (layers)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Simulação + medições reais
- Foco em PERFORMANCE
- Demonstrar diferenças HDD vs SSD
- Cálculos de latência
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 45 - File Systems Basics: Organizando Dados

**📚 Recursos:**
- [File System Implementation](http://pages.cs.wisc.edu/~remzi/OSTEP/file-implementation.pdf)
- [File Systems Explained](https://www.kernel.org/doc/html/latest/filesystems/index.html)
- [Inode Structure](https://www.geeksforgeeks.org/inode-in-operating-system/)

**🎯 Tópicos:**
- O que é um filesystem
- Files: dados + metadados
- Directories: organização hierárquica
- Inode structure
- Data blocks allocation
- Free space management
- Mount points

**💻 Exercício Prático:**
- Analisar inode com stat
- Explorar estrutura de diretório
- Criar filesystem em arquivo (loop device)

**✅ Checkpoint:**
- [ ] Compreende estrutura de FS
- [ ] Analisa inodes
- [ ] Navega hierarquia

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre file systems básicos. Dia 45 de estudos (Fase 4).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre fundamentos de file systems:

CONTEÚDO TÉCNICO:
1. Filesystem: sistema para organizar e armazenar arquivos em disco
2. File: sequência nomeada de bytes
3. Metadata: informações sobre arquivo (tamanho, dono, permissões, timestamps)
4. Directory: lista de arquivos e subdiretórios (árvore hierárquica)
5. Inode: estrutura de dados com metadata do arquivo
   - Inode number: identificador único
   - File type: regular, directory, symlink, etc
   - Permissions: rwx
   - Owner: uid, gid
   - Size: bytes
   - Timestamps: atime, mtime, ctime
   - Pointers: para data blocks
6. Data blocks: blocos no disco com conteúdo do arquivo
7. Directory entry (dentry): nome → inode number
8. Hard link: múltiplos nomes apontando para mesmo inode
9. Symbolic link (symlink): arquivo especial com path para outro arquivo
10. Free space management:
    - Bitmap: bit por block (0=livre, 1=usado)
    - Free list: linked list de blocos livres
11. Superblock: metadata do filesystem (tamanho, número de inodes, etc)
12. Mount point: diretório onde filesystem é montado
13. VFS (Virtual File System): abstração para diferentes FS

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: discos e blocks (Dia 44)
- Analogia central: "Biblioteca Organizada" - catálogo (inodes) e prateleiras (data blocks)
- História introdutória sobre organização de dados

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Arquitetura de FS (superblock, inodes, data blocks)
  * Inode structure (campos detalhados)
  * Directory tree (hierarquia)
  * Hard link vs symlink
- Tabela: campos do inode
- Visualização de blocos no disco
- Fluxo de leitura de arquivo (path → inode → data)

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de resolução de path (/home/user/file.txt)
- Demonstração de inode com stat
- Exemplo de hard link vs symlink
- Visualização de directory entries

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Explorando File Systems
  * Parte 1: Analisar Inodes
    - Criar arquivo: touch myfile.txt
    - stat myfile.txt (ver todas as informações)
    - Interpretar:
      * Inode number
      * Size
      * Blocks alocados
      * Permissions (octal e simbólico)
      * Timestamps
      * Links count
    - ls -i (mostrar inode numbers)
  * Parte 2: Hard Links e Symlinks
    - Criar arquivo original: echo "data" > original.txt
    - Hard link: ln original.txt hardlink.txt
    - Symlink: ln -s original.txt symlink.txt
    - stat cada um:
      * Hard link: mesmo inode number, links=2
      * Symlink: inode diferente, tipo=symlink
    - Deletar original
    - Hard link ainda funciona
    - Symlink quebra (dangling)
  * Parte 3: Explorar Directory Structure
    - mkdir testdir
    - cd testdir
    - touch file1 file2
    - ls -ai (inodes)
    - Observar:
      * . (diretório atual)
      * .. (diretório pai)
      * file1, file2
    - Cada directory entry: nome → inode
  * Parte 4: Criar Filesystem Simples
    - Criar arquivo para ser disco: dd if=/dev/zero of=mydisk.img bs=1M count=100
    - Formatar com ext4: mkfs.ext4 mydisk.img
    - Montar: sudo mount -o loop mydisk.img /mnt
    - Usar como disco normal
    - df -h /mnt (ver espaço)
    - Criar arquivos, diretórios
    - Desmontar: sudo umount /mnt
  * Parte 5: Simular Filesystem
    - Implementar FS minimalista:
      * Superblock: total blocks, free blocks
      * Bitmap de blocos livres
      * Array de inodes
      * Blocos de dados
    - Operações:
      * create(filename): alocar inode, criar dentry
      * write(filename, data): alocar blocos, escrever
      * read(filename): ler blocos via inode
      * delete(filename): liberar inode e blocos
    - Visualizar estado do FS
  * Contexto motivador
  * Especificação clara
  * Comandos Linux detalhados
  * Código de simulação (Python)
  * Dicas progressivas
  * Análise de estruturas
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (confundir hard link com symlink, não entender inodes)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar FS com inodes indiretos
- Preparação para Dia 46 (ext4, NTFS)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de biblioteca
- Exemplos visuais de estruturas
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com sistema real
- Implementação de FS simples
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Arquitetura de FS (layout em disco)
2. Inode structure (todos os campos)
3. Directory tree e resolution de path
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Exploração de sistema real
- Implementação funcional
- Foco em ESTRUTURAS
- Demonstrar links
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 46 - File System Implementation: ext4, NTFS

**📚 Recursos:**
- [ext4 Filesystem](https://ext4.wiki.kernel.org/)
- [NTFS Documentation](https://docs.microsoft.com/en-us/windows-server/storage/file-server/ntfs-overview)
- [Journaling Filesystems](https://www.kernel.org/doc/html/latest/filesystems/ext4/journal.html)

**🎯 Tópicos:**
- ext4: journal, extents, features
- NTFS: MFT, streams, compression
- FAT32: simplicidade e compatibilidade
- Journaling filesystems
- Soft updates
- Log-structured filesystems

**💻 Exercício Prático:**
- Criar e formatar partições
- Analisar journal do ext4
- Comparar performance entre FS

**✅ Checkpoint:**
- [ ] Diferencia filesystems
- [ ] Compreende journaling
- [ ] Formata e monta FS

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre implementações de file systems. Dia 46 de estudos (Fase 4).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre ext4, NTFS e journaling:

CONTEÚDO TÉCNICO:
1. ext4 (Fourth Extended Filesystem): FS padrão do Linux
2. Características ext4:
   - Extents: range contíguo de blocos (eficiente para arquivos grandes)
   - Journaling: log de operações (crash consistency)
   - Large file support: até 16TB
   - Timestamps em nanosegundos
   - Delayed allocation: alocar apenas no flush
3. Journal do ext4:
   - Metadata journaling: apenas metadata (padrão)
   - Full journaling: data + metadata (mais seguro, mais lento)
   - Writeback: sem ordem garantida (mais rápido, menos seguro)
4. NTFS (New Technology File System): FS do Windows
5. Características NTFS:
   - MFT (Master File Table): como inode table gigante
   - Everything is a file (até metadata)
   - Multiple data streams: arquivo pode ter múltiplos streams
   - Compression: transparente
   - Encryption: EFS (Encrypting File System)
   - ACLs: controle de acesso avançado
6. FAT32: File Allocation Table
   - Simples, compatível universalmente
   - Sem permissões, sem journaling
   - Limite 4GB por arquivo
   - Usado em USB drives, SD cards
7. Journaling: técnica para crash consistency
   - Problema: crash durante write pode corromper FS
   - Solução: log (journal) de operações
   - Write-ahead logging: escrever no journal primeiro
   - Recovery: replay journal após crash
8. Soft updates: alternativa ao journaling (FreeBSD)
9. Log-structured FS: tudo é append-only (LFS, F2FS)
10. Comparação: ext4 vs NTFS vs FAT32

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: FS basics (Dia 45)
- Analogia central: "Diário de Bordo" - journal registra mudanças
- História introdutória sobre consistência de dados

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * ext4 layout (superblock, block groups, journal)
  * NTFS MFT structure
  * Journaling (write-ahead log)
  * Comparação de filesystems
- Tabela comparativa: ext4 vs NTFS vs FAT32
- Fluxo de operação com journaling
- Extents vs indirect blocks

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de extent em ext4
- Demonstração de journal
- Exemplo de MFT entry
- Recovery após crash

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Trabalhando com Filesystems Reais
  * Parte 1: Criar e Formatar
    - Criar arquivo para disco: dd if=/dev/zero of=disk1.img bs=1M count=500
    - Formatar ext4: mkfs.ext4 disk1.img
    - Formatar FAT32: mkfs.vfat disk1.img (em outra imagem)
    - Montar ambos
    - Comparar estruturas
  * Parte 2: Explorar ext4
    - tune2fs -l disk1.img (ver superblock)
    - Informações:
      * Block size
      * Inode count
      * Block count
      * Journal size
      * Features
    - dumpe2fs disk1.img (detalhes de block groups)
  * Parte 3: Journaling em Ação
    - Montar ext4 com journal: mount -o data=journal
    - Escrever arquivos
    - Ver journal: debugfs disk1.img
      * logdump (ver transações no journal)
    - Simular crash (não completar sync)
    - fsck (recovery via journal)
  * Parte 4: Comparar Performance
    - Benchmark ext4:
      * Criar 1000 arquivos pequenos
      * Criar 1 arquivo grande (1GB)
      * Medir tempo
    - Benchmark FAT32 (mesmo teste)
    - Comparar:
      * ext4 mais rápido (extents, journaling)
      * FAT32 mais simples, compatível
  * Parte 5: Simular Journaling
    - Implementar journal simplificado:
      * Log de operações: [op, file, data]
      * Write-ahead: log → commit → apply
      * Recovery: replay log
    - Operações: create, write, delete
    - Simular crash: interromper no meio
    - Recovery: completar operações do log
    - Demonstrar consistência
  * Parte 6: NTFS (se Windows disponível)
    - Criar arquivo NTFS
    - Alternate data streams:
      * echo "hidden" > file.txt:secret
      * type file.txt (normal data)
      * type file.txt:secret (stream data)
    - Compression: compact /c file.txt
  * Contexto motivador
  * Especificação clara
  * Comandos detalhados (Linux, Windows)
  * Código de simulação de journal
  * Dicas progressivas
  * Benchmarks práticos
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (não entender journal, confundir metadata e data)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar filesystem com journal completo
- Preparação para Dia 47 (caching e buffering)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de diário de bordo
- Exemplos visuais de estruturas
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com FSs reais
- Benchmarking prático
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. ext4 layout completo
2. Journaling (write-ahead log)
3. NTFS MFT structure
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Trabalhar com FSs REAIS
- Demonstrar journaling
- Comparações práticas
- Foco em CONSISTÊNCIA
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 47 - File System Performance: Buffering e Caching

**📚 Recursos:**
- [File System Caching](http://pages.cs.wisc.edu/~remzi/OSTEP/file-journaling.pdf)
- [Linux Page Cache](https://www.kernel.org/doc/gorman/html/understand/understand013.html)
- [Buffer Cache](https://www.kernel.org/doc/html/latest/filesystems/vfs.html)

**🎯 Tópicos:**
- Page cache: caching de blocos
- Buffer cache
- Dirty pages e writeback
- Read-ahead prefetching
- Direct I/O vs buffered I/O
- fsync() e durabilidade

**💻 Exercício Prático:**
- Medir impacto do page cache
- Usar direct I/O
- Benchmarking de filesystem

**✅ Checkpoint:**
- [ ] Compreende caching de FS
- [ ] Otimiza I/O
- [ ] Garante durabilidade

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre performance de file systems. Dia 47 de estudos (Fase 4).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre caching e buffering de FS:

CONTEÚDO TÉCNICO:
1. Page cache: cache de páginas de arquivo na RAM
2. Por que caching:
   - Disco ~10ms, RAM ~100ns (100,000x mais rápido!)
   - Localidade: dados acessados recentemente serão acessados novamente
3. Buffer cache: cache de blocos de disco
   - Linux moderno: unificado com page cache
4. Operações de I/O:
   - Read: verificar cache → hit (rápido) ou miss (ler disco)
   - Write: escrever cache (rápido), disco depois (async)
5. Dirty pages: páginas modificadas mas não escritas em disco
6. Writeback: flush dirty pages para disco
   - Daemon: pdflush/kswapd
   - Triggers: página velha, cache cheio, sync
7. Write policies:
   - Write-back: escrever cache, disco depois (padrão, rápido)
   - Write-through: escrever cache E disco imediatamente (seguro, lento)
8. Read-ahead (prefetching): ler blocos seguintes antecipadamente
   - Baseado em localidade espacial
   - Otimiza sequential reads
9. Direct I/O: bypass do cache (O_DIRECT flag)
   - Usado por databases (gerenciam próprio cache)
10. fsync(): forçar flush de dirty pages
    - Garantir durabilidade
    - Retorna apenas quando dados estão em disco
11. sync(): flush todo o sistema
12. Consistency vs Performance trade-off

ESTRUTURA BASEADA EM DESIGN INSTRUCIONAL:

📋 OBJETIVOS DE APRENDIZAGEM (SMART):
- 3-5 objetivos mensuráveis do dia
- Verbos de ação claros

🎭 ATIVAÇÃO DO CONHECIMENTO PRÉVIO:
- Revisão: caching (Dia 29), journaling (Dia 46)
- Analogia central: "Notas Adesivas na Mesa" - cache para acesso rápido
- História introdutória sobre otimização de I/O

📚 APRESENTAÇÃO DO CONTEÚDO:
- Blocos pequenos de informação
- DIAGRAMAS MERMAID OBRIGATÓRIOS:
  * Fluxo de read: app → page cache → disco
  * Fluxo de write: app → page cache → writeback → disco
  * Read-ahead (prefetching)
  * Direct I/O vs Buffered I/O
- Tabela: write-back vs write-through
- Comparação de latências (cache hit vs miss)
- Visualização de dirty pages

💡 DEMONSTRAÇÃO E MODELAGEM:
- Exemplo de cache hit vs miss
- Demonstração de dirty pages crescendo
- Exemplo de fsync()
- Read-ahead em ação

🎯 PRÁTICA GUIADA (1 EXERCÍCIO COMPLETO):
- Exercício: Medindo e Otimizando I/O
  * Parte 1: Demonstrar Page Cache
    - Criar arquivo grande: dd if=/dev/zero of=bigfile bs=1M count=1000
    - Limpar cache: sync; echo 3 > /proc/sys/vm/drop_caches
    - Primeira leitura: time cat bigfile > /dev/null (LENTA, miss)
    - free -h (ver Cached aumentar)
    - Segunda leitura: time cat bigfile > /dev/null (RÁPIDA, hit)
    - Speedup dramático!
  * Parte 2: Dirty Pages e Writeback
    - Escrever arquivo grande: dd if=/dev/zero of=dirtyfile bs=1M count=500
    - Não retornou ainda, mas dd já terminou (write-back)
    - cat /proc/meminfo | grep Dirty (ver dirty pages)
    - sync (forçar writeback)
    - Dirty volta a 0
    - Durante sync: iotop (ver I/O de writeback)
  * Parte 3: Direct I/O
    - Programa C com O_DIRECT:
      * Abrir arquivo com O_DIRECT
      * Ler/escrever (bypass cache)
      * Fechar
    - Medir tempo
    - Comparar com I/O normal (buffered)
    - Direct I/O: sem overhead de cache, mas sem benefício de cache
    - Quando usar: databases
  * Parte 4: fsync() e Durabilidade
    - Programa:
      * Escrever dados
      * Sem fsync: retornar
      * Com fsync: garantir disco
    - Medir tempo com/sem fsync
    - Simular crash (kill -9):
      * Sem fsync: dados perdidos
      * Com fsync: dados salvos
    - Trade-off: durabilidade vs performance
  * Parte 5: Read-ahead
    - Sequential read: cat arquivo > /dev/null
    - Monitorar: iostat -x 1
    - Observar: reads maiores que solicitado (read-ahead)
    - Random read: programa com seeks aleatórios
    - Read-ahead não ajuda (sem localidade)
  * Parte 6: Benchmark Completo
    - fio (Flexible I/O tester):
      * Sequential read
      * Sequential write
      * Random read 4K
      * Random write 4K
    - Com cache vs direct I/O
    - Gerar relatório com gráficos
  * Contexto motivador
  * Especificação clara
  * Comandos e código (C, scripts)
  * Dicas progressivas
  * Medições detalhadas
  * Análise de trade-offs
  * Variações opcionais

🔄 FEEDBACK E AVALIAÇÃO:
- Checklist de conceitos
- Erros comuns (não usar fsync quando necessário, não entender cache)
- Quiz de fixação (5 questões)
- Auto-avaliação

🚀 TRANSFERÊNCIA E APLICAÇÃO:
- Desafio bônus: Implementar LRU cache para FS
- Preparação para Dia 48 (advanced file systems)
- Recursos complementares

TÉCNICAS PEDAGÓGICAS:
- Analogia de notas adesivas
- Exemplos visuais de cache
- Storytelling
- Scaffolding
- Chunking
- Dual coding
- Hands-on com medições
- Benchmarking extensivo
- Aprendizagem por descoberta guiada

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Fluxo de read com page cache
2. Fluxo de write com writeback
3. Read-ahead (prefetching)
4. Mapa mental dos conceitos do dia

IMPORTANTE:
- Muitas analogias do mundo real
- Linguagem simples e acessível
- Tom encorajador
- Celebrar progressos
- Medições REAIS e dramáticas
- Demonstrar speedup do cache
- Foco em PERFORMANCE
- Trade-offs claros
- Evitar sobrecarga cognitiva

Formato: markdown estruturado, visual, com diagramas Mermaid e checkpoints claros.
```

---

## 📅 DIA 48 - Advanced File Systems: ZFS, Btrfs

**📚 Recursos:**
- [ZFS Architecture](https://docs.oracle.com/cd/E19253-01/819-5461/zfsover-2/)
- [Btrfs Documentation](https://btrfs.wiki.kernel.org/)
- [Copy-on-Write Filesystems](https://en.wikipedia.org/wiki/Copy-on-write#In_computer_storage)

**🎯 Tópicos:**
- Copy-on-Write filesystems
- Snapshots e clones
- RAID integrado
- Checksumming e integridade
- Compression e deduplication
- Volume management

**💻 Exercício Prático:**
- Criar ZFS pool (ou Btrfs)
- Trabalhar com snapshots
- Testar RAID integrado

**✅ Checkpoint:**
- [ ] Compreende CoW FS
- [ ] Usa snapshots
- [ ] Configura RAID

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre file systems avançados. Dia 48 de estudos (Fase 4).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre ZFS e Btrfs:

CONTEÚDO TÉCNICO:
1. Copy-on-Write (CoW) filesystems: nunca modificam dados in-place
2. CoW write:
   - Alocar novo bloco
   - Escrever dados novos
   - Atualizar ponteiro
   - Bloco antigo fica (até GC)
3. Benefícios CoW:
   - Snapshots instantâneos
   - Crash consistency natural
   - Sem journal necessário
4. ZFS (Zettabyte File System): desenvolvido pela Sun/Oracle
5. Características ZFS:
   - Pool-based: gerenciamento de storage flexível
   - Built-in RAID: mirror, RAIDZ (1,2,3)
   - Snapshots: instantâneos, copy-on-write
   - Clones: snapshots writeable
   - Checksumming: integridade de dados (detecta bit rot)
   - Compression: transparente (lz4, zstd)
   - Deduplication: eliminar duplicatas (caro em RAM)
   - ARC (Adaptive Replacement Cache): cache inteligente
6. Btrfs (B-tree FS): desenvolvido para Linux
7. Características Btrfs:
   - CoW filesystem
   - Snapshots e subvolumes
   - Built-in RAID
   - Checksumming
   - Compression (zlib, lzo, zstd)
   - Self-healing: detecta e corrige corrupção (com RAID)
   - Online resize
8. Comparação ZFS vs Btrfs:
   - ZFS: mais maduro, usado em produção (FreeBSD, TrueNAS)
   - Btrfs: integrado ao Linux kernel, mais novo
9. Snapshots: ponto no tempo imutável
10. Clones: snapshot modificável (branch)
11. RAID levels: RAID 0, 1, 5, 6, 10

[Estrutura completa de Design Instrucional com todos os componentes]

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Copy-on-Write (antes e depois de write)
2. ZFS pool architecture (vdevs, datasets)
3. Snapshot tree (CoW structure)
4. RAID levels visual

EXERCÍCIO PRÁTICO:
- Instalar ZFS ou Btrfs
- Criar pool/filesystem
- Criar e gerenciar snapshots
- Testar RAID (mirror ou RAIDZ)
- Simular falha de disco
- Recovery
- Medir performance com compression

IMPORTANTE:
- Foco em recursos AVANÇADOS
- Demonstrar snapshots (killer feature)
- CoW visual
- RAID integrado
- Comparações práticas
```

---

## 📅 DIA 49 - RAID: Redundância e Performance

**📚 Recursos:**
- [RAID Levels Explained](https://www.prepressure.com/library/technology/raid)
- [Software RAID in Linux](https://raid.wiki.kernel.org/)
- [mdadm Tutorial](https://raid.wiki.kernel.org/index.php/RAID_setup)

**🎯 Tópicos:**
- Por que RAID?
- RAID 0: striping (performance)
- RAID 1: mirroring (redundância)
- RAID 5: paridade distribuída
- RAID 6: dupla paridade
- RAID 10: combinando níveis
- Hardware vs software RAID

**💻 Exercício Prático:**
- Configurar software RAID
- Simular falha de disco
- Medir performance RAID

**✅ Checkpoint:**
- [ ] Compreende RAID levels
- [ ] Configura RAID
- [ ] Recupera de falhas

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre RAID. Dia 49 de estudos (Fase 4).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre RAID:

CONTEÚDO TÉCNICO:
1. RAID (Redundant Array of Independent Disks): combinar múltiplos discos
2. Objetivos: performance, redundância, ou ambos
3. RAID 0 (Striping):
   - Dividir dados entre discos (stripe)
   - Performance: 2x throughput (leitura E escrita)
   - Sem redundância: 1 disco falha = perda total
   - Uso: performance crítico, dados não críticos
4. RAID 1 (Mirroring):
   - Duplicar dados em 2+ discos
   - Redundância: tolera falha de 1 disco
   - Performance leitura: 2x (pode ler de qualquer)
   - Performance escrita: 1x (escrever em ambos)
   - Uso: dados críticos, alta disponibilidade
5. RAID 5 (Striping com Paridade):
   - Dados + paridade distribuídos (mínimo 3 discos)
   - Redundância: tolera falha de 1 disco
   - Capacidade: (N-1) discos
   - Performance: boa leitura, escrita média (parity overhead)
   - Rebuild: calcular dados perdidos via paridade
6. RAID 6 (Dupla Paridade):
   - Como RAID 5, mas 2 paridades
   - Toleraa falha de 2 discos
   - Capacidade: (N-2) discos
7. RAID 10 (1+0): mirror de stripes
   - Combina RAID 1 e RAID 0
   - Performance E redundância
   - Mínimo 4 discos
8. Hardware RAID: controladora dedicada (cara, rápida)
9. Software RAID: Linux mdadm, Windows Storage Spaces
10. Hot spare: disco de reserva (automatic rebuild)

[Estrutura completa de Design Instrucional]

DIAGRAMAS MERMAID (mínimo 4):
1. RAID 0 (striping visual)
2. RAID 1 (mirroring)
3. RAID 5 (paridade distribuída)
4. Comparação de todos os níveis

EXERCÍCIO PRÁTICO:
- Criar arquivos de loop como discos virtuais
- mdadm para criar RAID:
  * RAID 0 com 2 discos
  * RAID 1 com 2 discos
  * RAID 5 com 3 discos
- Benchmark cada configuração
- Simular falha: mdadm --fail
- Observar rebuild
- Remover disco falho
- Adicionar novo disco
- Completar rebuild

IMPORTANTE:
- Visualizações de cada nível
- Demonstrar falha E recovery
- Comparar performance
- Cálculos de capacidade
- Trade-offs claros
```

---

## 📅 DIA 50 - Network File Systems: NFS, SMB/CIFS

**📚 Recursos:**
- [NFS Documentation](https://www.kernel.org/doc/Documentation/filesystems/nfs/)
- [SMB Protocol](https://learn.microsoft.com/en-us/windows-server/storage/file-server/file-server-smb-overview)
- [Distributed Filesystems](https://en.wikipedia.org/wiki/Clustered_file_system)

**🎯 Tópicos:**
- Distributed filesystems
- NFS: arquitetura e protocolo
- SMB/CIFS: compartilhamento Windows
- Stateless vs stateful protocols
- Caching em network FS
- Performance e latência

**💻 Exercício Prático:**
- Configurar NFS server/client
- Montar compartilhamento SMB
- Benchmarking de network FS

**✅ Checkpoint:**
- [ ] Configura NFS
- [ ] Usa SMB/CIFS
- [ ] Otimiza network I/O

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre network file systems. Dia 50 de estudos (Fase 4).

Crie material SUPER didático usando DESIGN INSTRUCIONAL sobre NFS e SMB:

CONTEÚDO TÉCNICO:
1. Network File System: acesso remoto a arquivos
2. NFS (Network File System): protocolo Unix/Linux
3. Arquitetura NFS:
   - NFS server: exporta diretórios
   - NFS client: monta remotamente
   - RPC (Remote Procedure Call): comunicação
4. NFSv3 vs NFSv4:
   - v3: stateless (servidor não rastreia opens)
   - v4: stateful, melhor performance, segurança
5. Montagem NFS: mount -t nfs server:/path /mnt
6. SMB/CIFS (Server Message Block): Windows file sharing
7. Samba: implementação SMB para Linux
8. Autenticação: guest, user, domain
9. Caching:
   - Client-side caching para performance
   - Cache consistency: problema!
   - Close-to-open consistency (NFS)
10. Performance:
    - Latência de rede: ~1ms LAN, ~100ms WAN
    - Throughput limitado por rede
    - Caching crucial
11. Use cases: home directories, shared storage

[Estrutura completa de Design Instrucional]

DIAGRAMAS MERMAID (mínimo 4):
1. Arquitetura NFS (client/server)
2. SMB/CIFS stack
3. Caching e consistency
4. Latência: local vs network FS

EXERCÍCIO PRÁTICO:
- Configurar NFS server:
  * /etc/exports
  * exportfs -a
- NFS client: mount remoto
- Configurar Samba:
  * /etc/samba/smb.conf
  * Criar share
- Windows: montar \\server\share
- Linux: mount -t cifs
- Benchmark:
  * cp arquivo local (baseline)
  * cp para NFS mount
  * cp para SMB mount
  * Comparar throughput

IMPORTANTE:
- Configuração passo a passo
- Demonstrar uso REAL
- Medir latência
- Comparar protocolos
- Foco em REDE
```

---

## 📅 DIA 51 - VFS: Virtual File System Layer

**📚 Recursos:**
- [Linux VFS](https://www.kernel.org/doc/html/latest/filesystems/vfs.html)
- [VFS Architecture](https://www.tldp.org/LDP/tlk/fs/filesystem.html)
- [FUSE](https://github.com/libfuse/libfuse)

**🎯 Tópicos:**
- Abstração de filesystem
- VFS objects: superblock, inode, dentry, file
- VFS operations
- Pluggable filesystems
- Special filesystems: proc, sys, tmpfs
- FUSE: userspace filesystems

**💻 Exercício Prático:**
- Explorar /proc e /sys
- Criar filesystem FUSE simples
- Analisar VFS structures

**✅ Checkpoint:**
- [ ] Compreende VFS layer
- [ ] Explora filesystems especiais
- [ ] Cria FUSE filesystem

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais aprendendo sobre VFS. Dia 51 de estudos (Fase 4).

Crie material COMPLETO usando DESIGN INSTRUCIONAL sobre Virtual File System:

CONTEÚDO TÉCNICO:
1. VFS (Virtual File System): abstração para diferentes FSs
2. Problema: múltiplos FSs (ext4, NTFS, FAT32, NFS...)
3. Solução VFS: interface comum
   - Aplicação usa syscalls padrão (open, read, write)
   - VFS traduz para FS específico
4. VFS objects:
   - Superblock: representa filesystem montado
   - Inode: representa arquivo (metadata)
   - Dentry (directory entry): componente de path
   - File: arquivo aberto por processo
5. VFS operations (function pointers):
   - Superblock ops: mount, unmount
   - Inode ops: create, lookup, mkdir
   - File ops: open, read, write, close
   - Dentry ops: compare, hash
6. Pluggable filesystems: registrar novo FS
7. Special filesystems:
   - /proc: informações de processos e kernel
   - /sys: device tree e kernel objects
   - /dev: device files
   - tmpfs: filesystem em RAM
   - pipefs: pipes
8. FUSE (Filesystem in Userspace):
   - Implementar FS em userspace
   - Kernel module FUSE: redirect para userspace
   - Exemplos: sshfs, ntfs-3g
9. Mounting: anexar filesystem à árvore

[Estrutura completa de Design Instrucional]

DIAGRAMAS MERMAID (mínimo 4):
1. VFS architecture (layered)
2. VFS objects e relationships
3. Path resolution (dentry cache)
4. FUSE architecture

EXERCÍCIO PRÁTICO:
- Explorar /proc:
  * /proc/cpuinfo
  * /proc/meminfo
  * /proc/[pid]/
- Explorar /sys:
  * /sys/class/
  * /sys/devices/
- Implementar FUSE simples:
  * Hello World FS
  * Apenas 1 arquivo: /hello
  * read() retorna "Hello, World!"
  * Código Python com fusepy
- Montar e testar

IMPORTANTE:
- Foco em ABSTRAÇÃO
- Demonstrar flexibilidade
- FUSE hands-on
- Exploração de /proc e /sys
- Visualizar camadas
```

---

## 📅 DIA 52 - Revisão Fase 4 + Projeto Final da Fase

**🎯 Objetivo:** Consolidar TODA a Fase 4

**📝 Atividades:**
- Revisão completa (Dias 43-51)
- Quiz final da fase (30 questões)
- Mapa mental integrado

**💻 PROJETO FINAL FASE 4:**
**"Sistema de Arquivos Educacional Completo"**

Criar um filesystem simulado completo que:
1. Implementa estrutura de inodes
2. Diretórios e navegação hierárquica
3. Operações: create, read, write, delete, mkdir, rmdir
4. Free space management (bitmap)
5. Block allocation strategies
6. Journaling básico
7. RAID simulation (opcional)
8. Interface FUSE (montável)
9. Ferramentas de diagnóstico (fsck)
10. Documentação detalhada

**✅ Checkpoint:**
- [ ] Revisão completa
- [ ] 85%+ no quiz
- [ ] Filesystem funcional e montável
- [ ] Pronto para Fase 5

**🤖 PROMPT PARA GERAR CONTEÚDO:**

```
Sou INICIANTE em Sistemas Operacionais fazendo revisão da FASE 4 COMPLETA. Dia 52 de estudos.

Crie material de REVISÃO ABRANGENTE E PROJETO FINAL usando DESIGN INSTRUCIONAL para toda a Fase 4:

CONTEÚDO A REVISAR (Dias 43-51):
1. I/O Devices: block vs char, DMA
2. Disks: HDD geometry, SSD, scheduling
3. FS Basics: inodes, directories, free space
4. FS Implementation: ext4, NTFS, journaling
5. FS Performance: caching, buffering, fsync
6. Advanced FS: ZFS, Btrfs, CoW, snapshots
7. RAID: níveis, redundância, performance
8. Network FS: NFS, SMB
9. VFS: abstração, FUSE

[Estrutura completa com revisão integrada, quiz de 30 questões, projeto detalhado]

PROJETO FINAL: "Educational Filesystem (EduFS)"

Implementar filesystem COMPLETO com:
- Inode-based structure
- Directory hierarchy
- File operations
- Journaling
- FUSE interface (montável!)
- fsck utility
- Visualization tools

[Especificação COMPLETA e detalhada do projeto, 15-20 horas]

IMPORTANTE:
- INTEGRAÇÃO total Fase 4
- Filesystem MONTÁVEL
- Deve ser IMPRESSIONANTE
- Preparar para Fase 5 (projeto integrador final)
```

---
<a name="fase-5"></a>
# 🚀 FASE 5: PROJETO FINAL INTEGRADOR (Dias 53-60)

**Objetivo:** Integrar TODOS os conhecimentos das 4 fases em um projeto complexo e impressionante

---

## 📅 DIAS 53-54 - Planejamento e Arquitetura do Projeto Final

**🎯 Objetivo:** Planejar e arquitetar o projeto final integrando todos os conceitos

**📝 Atividades:**
- Revisão geral de todas as fases
- Escolha do projeto final
- Definição de requisitos
- Arquitetura do sistema
- Divisão em módulos
- Cronograma detalhado

**💡 Sugestões de Projeto Final:**

**Opção 1: Mini Sistema Operacional Educacional**
- Boot loader básico (GRUB ou custom)
- Kernel minimalista com system calls
- Process scheduler (3+ algoritmos)
- Memory management (paging, swapping)
- Simple filesystem (inode-based)
- Shell básica interativa
- Device drivers simulados

**Opção 2: Simulador Completo de SO**
- Visualização de TODOS os conceitos
- Simuladores interativos integrados
- Interface gráfica (GUI ou TUI avançada)
- Métricas e análises em tempo real
- Material educacional integrado
- Comparação de algoritmos
- Exportação de relatórios

**Opção 3: Sistema de Gerenciamento Avançado**
- Resource scheduler multicore
- Memory allocator otimizado
- File system completo com journaling
- Network stack básico
- Performance profiler
- Monitoramento em tempo real
- Dashboard interativo

**✅ Checkpoint:**
- [ ] Projeto escolhido e definido
- [ ] Arquitetura documentada
- [ ] Cronograma criado
- [ ] Pronto para implementação

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 53:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 53 - início da FASE 5 (PROJETO FINAL INTEGRADOR). Completei todas as 4 fases anteriores.

Crie material COMPLETO usando DESIGN INSTRUCIONAL para PLANEJAMENTO do projeto final:

CONTEXTO:
- Completei Fase 1: Fundamentos (boot, kernel, processos, IPC, segurança)
- Completei Fase 2: Processos (scheduling, sincronização, deadlocks, signals)
- Completei Fase 3: Memória (paginação, TLB, swapping, allocation, GC)
- Completei Fase 4: I/O e FS (devices, discos, filesystems, RAID, VFS)
- Agora: Integrar TUDO em projeto final impressionante

CONTEÚDO DO DIA 53:

📋 OBJETIVOS DO DIA:
- Revisar TODOS os conceitos das 4 fases
- Escolher projeto final adequado ao nível
- Definir escopo realista mas desafiador
- Criar arquitetura inicial

🎭 MOTIVAÇÃO E CONTEXTO:
- Este é o MOMENTO CULMINANTE do aprendizado
- Oportunidade de aplicar TUDO que foi aprendido
- Projeto será showcase de conhecimento
- Preparação para mercado de trabalho

📚 REVISÃO INTEGRADA DAS 4 FASES:

**Fase 1 - Fundamentos:**
- System calls e kernel space
- Processos e threads
- IPC (pipes, shared memory)
- Segurança e permissões

**Fase 2 - Gerenciamento de Processos:**
- CPU scheduling (FCFS, SJF, RR, Priority, CFS)
- Sincronização (locks, semáforos, monitores)
- Deadlocks (detecção, prevenção)
- Signals e comunicação

**Fase 3 - Gerenciamento de Memória:**
- Paginação multi-level
- TLB e cache
- Swapping e page replacement
- Memory allocation (malloc/free)
- Garbage collection

**Fase 4 - File Systems e I/O:**
- Dispositivos e drivers
- Discos (HDD, SSD, scheduling)
- Filesystems (inodes, journaling)
- Caching e buffering
- RAID e VFS

💡 APRESENTAÇÃO DAS OPÇÕES DE PROJETO:

**OPÇÃO 1: Mini Sistema Operacional Educacional**

Descrição: Construir um SO minimalista mas funcional

Complexidade: ALTA (desafiador)

Módulos principais:
1. Boot Loader
   - Carregar kernel na memória
   - Transferir controle
   - Modo protegido (x86)

2. Kernel Minimalista
   - System calls básicos
   - Interrupt handlers
   - Timer interrupt

3. Process Management
   - Process table
   - Scheduler (Round Robin ou Priority)
   - Context switching
   - fork() simulado

4. Memory Management
   - Paginação simples
   - Alocador de páginas
   - Kernel heap allocator

5. Simple Filesystem
   - Inode-based
   - Operações: create, read, write, delete
   - Montagem

6. Shell
   - Parser de comandos
   - Executar processos
   - Built-ins básicos

Tecnologias: C, Assembly (x86), QEMU/Bochs

Referências:
- OSDev Wiki
- xv6 (MIT teaching OS)
- JamesM's kernel tutorial

Tempo estimado: 30-40 horas

Pontos positivos:
- Extremamente educativo
- Impressionante em portfólio
- Entendimento profundo

Desafios:
- Assembly e low-level
- Debugging complexo
- Curva de aprendizado steep

**OPÇÃO 2: Simulador Completo de SO (RECOMENDADO para iniciantes)**

Descrição: Sistema que simula TODOS os componentes de um SO com visualização

Complexidade: MÉDIA-ALTA (desafiador mas gerenciável)

Módulos principais:
1. Process Scheduler Simulator
   - 5+ algoritmos implementados
   - Visualização de Gantt charts
   - Comparação de métricas
   - Workloads customizáveis

2. Memory Manager Simulator
   - Paginação 4-level
   - TLB simulation
   - Page replacement (FIFO, LRU, Clock, Optimal)
   - Swapping
   - Visualização de page table

3. File System Simulator
   - Inode-based structure
   - Operações completas
   - Journaling
   - Caching simulation
   - Visualização de estrutura

4. I/O and Disk Simulator
   - Disk scheduling algorithms
   - DMA simulation
   - Device drivers simulados

5. Synchronization Demos
   - Produtor-Consumidor
   - Leitores-Escritores
   - Jantar dos Filósofos
   - Visualização de deadlocks

6. Dashboard Integrado
   - Interface TUI (Terminal UI) ou GUI
   - Estatísticas em tempo real
   - Gráficos e visualizações
   - Comparação de algoritmos
   - Exportação de relatórios

7. Educational Content
   - Explicações inline
   - Tutoriais interativos
   - Quizzes integrados

Tecnologias: Python (recomendado), C++, ou Rust
UI: Rich (Python TUI), Qt, Electron, ou terminal colors

Tempo estimado: 25-35 horas

Pontos positivos:
- Integra TODOS os conceitos
- Visual e impressionante
- Portfolio-ready
- Menos debugging low-level

Desafios:
- Muitos módulos para integrar
- UI/UX design
- Performance de simulações

**OPÇÃO 3: Sistema de Gerenciamento Avançado**

Descrição: Ferramenta profissional de monitoramento e gerenciamento

Complexidade: MÉDIA

Módulos principais:
1. Advanced Scheduler
   - Multicore scheduling
   - CPU affinity
   - Real-time priorities
   - Load balancing

2. Memory Profiler
   - Heap analysis
   - Memory leak detection
   - Allocation patterns
   - Fragmentation analysis

3. File System Manager
   - Múltiplos FS suportados
   - Operações em batch
   - Integrity checking
   - Performance tuning

4. System Monitor
   - Real-time metrics
   - Historical data
   - Alertas e notificações
   - Logs centralizados

5. Performance Profiler
   - CPU profiling
   - Memory profiling
   - I/O profiling
   - Bottleneck detection

Tecnologias: C/C++, Python, Go

Tempo estimado: 25-30 horas

Pontos positivos:
- Ferramenta útil e prática
- Próximo de ferramentas reais
- Bom para portfolio

Desafios:
- Menos educativo que outros
- Foco em ferramentas, não conceitos

🎯 GUIA DE DECISÃO:

**Escolha OPÇÃO 1 se:**
- Quer entendimento MAIS PROFUNDO
- Tem experiência com C e Assembly
- Quer impressionar MUITO
- Tem tempo e paciência

**Escolha OPÇÃO 2 se:** ⭐ RECOMENDADO
- Quer integrar TODOS os conceitos
- Prefere visualização e ensino
- Quer algo impressionante MAS gerenciável
- Quer portfolio educativo

**Escolha OPÇÃO 3 se:**
- Prefere ferramenta prática
- Quer algo próximo do mercado
- Tem experiência prévia

📐 ARQUITETURA INICIAL (para Opção 2 - Simulador):

**Estrutura de Diretórios:**
```
os-simulator/
├── src/
│   ├── core/
│   │   ├── __init__.py
│   │   ├── config.py
│   │   └── constants.py
│   ├── process/
│   │   ├── scheduler.py
│   │   ├── process.py
│   │   ├── algorithms.py (FCFS, SJF, RR, Priority)
│   │   └── sync.py (locks, semaphores)
│   ├── memory/
│   │   ├── paging.py (multi-level page table)
│   │   ├── tlb.py
│   │   ├── replacement.py (FIFO, LRU, Clock)
│   │   ├── allocator.py (malloc/free)
│   │   └── swap.py
│   ├── filesystem/
│   │   ├── inode.py
│   │   ├── directory.py
│   │   ├── file_operations.py
│   │   ├── journal.py
│   │   └── cache.py
│   ├── io/
│   │   ├── disk.py (HDD/SSD simulation)
│   │   ├── scheduling.py (disk scheduling)
│   │   └── devices.py
│   ├── visualization/
│   │   ├── ui.py (main UI)
│   │   ├── gantt.py
│   │   ├── memory_vis.py
│   │   ├── fs_vis.py
│   │   └── graphs.py
│   ├── utils/
│   │   ├── logger.py
│   │   ├── stats.py
│   │   └── export.py
│   └── main.py
├── tests/
│   ├── test_scheduler.py
│   ├── test_memory.py
│   ├── test_filesystem.py
│   └── test_integration.py
├── workloads/
│   ├── processes.json
│   ├── memory_traces.txt
│   └── file_operations.json
├── docs/
│   ├── README.md
│   ├── ARCHITECTURE.md
│   ├── API.md
│   └── USER_GUIDE.md
├── examples/
│   └── demo_scenarios.py
├── requirements.txt
└── setup.py
```

**Arquitetura de Componentes:**

[DIAGRAMA MERMAID]
- Core Engine
- Process Module
- Memory Module
- Filesystem Module
- I/O Module
- Visualization Layer
- CLI/GUI Interface

**Fluxo de Dados:**
- User Input → Core Engine → Specific Module → Simulation → Stats → Visualization

**Dependências entre Módulos:**
- Process depende de Memory (context switch)
- Filesystem depende de I/O (disk access)
- Todos dependem de Core

📅 CRONOGRAMA DETALHADO:

**Dia 53 (hoje):**
- ✅ Revisão de conceitos
- ✅ Escolha de projeto
- ✅ Arquitetura inicial

**Dia 54 (amanhã):**
- Refinamento de arquitetura
- Definição de interfaces (APIs)
- Setup de projeto (estrutura, git, etc)
- Prototipagem de UI
- Definição de casos de teste

**Dia 55:**
- Módulo de Process Scheduling
- Implementação de algoritmos
- Testes unitários

**Dia 56:**
- Módulo de Memory Management
- Paginação e TLB
- Page replacement
- Testes

**Dia 57:**
- Módulo de File System
- Estruturas de dados
- Operações básicas
- Testes

**Dia 58:**
- Integração de todos os módulos
- Visualização e UI
- Testes de integração

**Dia 59:**
- Testes finais
- Documentação completa
- Apresentação preparada

**Dia 60:**
- Demonstração final
- Reflexão e celebração

📝 ATIVIDADE DO DIA 53:

**Tarefa 1: Escolher Projeto (30 min)**
- Ler todas as opções
- Avaliar complexidade vs tempo
- Decidir qual projeto

**Tarefa 2: Definir Escopo Detalhado (1h)**
- Listar TODOS os requisitos funcionais
- Listar requisitos não-funcionais
- Definir MVP (Minimum Viable Product)
- Definir features opcionais

**Tarefa 3: Criar Arquitetura (2h)**
- Diagrama de componentes
- Diagrama de classes principais
- Fluxo de dados
- Interfaces entre módulos

**Tarefa 4: Configurar Ambiente (1h)**
- Criar repositório Git
- Setup de estrutura de diretórios
- Instalar dependências
- Criar README inicial

**Tarefa 5: Planejar Testes (30 min)**
- Definir estratégia de testes
- Listar casos de teste principais
- Setup de framework de testes

🔄 CHECKLIST DO DIA 53:
- [ ] Revisei conceitos das 4 fases
- [ ] Escolhi projeto final
- [ ] Defini escopo detalhado
- [ ] Criei arquitetura inicial
- [ ] Configurei ambiente de desenvolvimento
- [ ] Tenho cronograma claro
- [ ] Estou MOTIVADO para começar!

🚀 PRÓXIMOS PASSOS:
- Amanhã (Dia 54): Refinamento e detalhamento
- Depois: Implementação focada

💪 MENSAGEM MOTIVACIONAL:
"Você chegou até aqui! Completou 52 dias de aprendizado intenso. Agora é hora de BRILHAR e mostrar tudo que aprendeu. Este projeto será a PROVA do seu domínio de Sistemas Operacionais. Faça algo que você terá ORGULHO de mostrar!"

TÉCNICAS PEDAGÓGICAS:
- Retrieval practice (revisão ativa)
- Elaboration (planejar em detalhes)
- Project-based learning
- Metacognition (refletir sobre aprendizado)

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 3):
1. Mapa mental integrando as 4 fases
2. Arquitetura de componentes do projeto escolhido
3. Cronograma visual (Dias 53-60)

IMPORTANTE:
- Ser REALISTA com tempo
- Escolher projeto adequado ao nível
- Priorizar INTEGRAÇÃO de conceitos
- MVP primeiro, features depois
- Documentar desde o início
- Git commits frequentes
- CELEBRAR cada milestone

Formato: markdown estruturado, visual, motivacional, com planos detalhados.
```

---

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 54:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 54 - segundo dia de planejamento do PROJETO FINAL.

Ontem (Dia 53) eu:
- Revisei todas as 4 fases
- Escolhi meu projeto final: [OPÇÃO ESCOLHIDA]
- Criei arquitetura inicial
- Configurei ambiente

Hoje preciso REFINAR e DETALHAR antes de começar implementação amanhã.

Crie material COMPLETO usando DESIGN INSTRUCIONAL para DETALHAMENTO do projeto:

CONTEÚDO DO DIA 54:

📋 OBJETIVOS DO DIA:
- Refinar arquitetura do projeto
- Definir interfaces (APIs) de cada módulo
- Criar protótipo de UI/UX
- Escrever especificações técnicas
- Preparar ambiente de testes
- Finalizar planejamento

🎯 REFINAMENTO DE ARQUITETURA:

**Para cada módulo principal, definir:**

1. **Responsabilidades:**
   - O que o módulo faz?
   - Quais problemas resolve?

2. **Interfaces (API):**
   - Funções públicas
   - Parâmetros e retornos
   - Exceções/erros

3. **Estruturas de Dados:**
   - Classes/structs principais
   - Relacionamentos
   - Invariantes

4. **Dependências:**
   - De quais módulos depende?
   - Quem depende deste módulo?

5. **Testes:**
   - Casos de teste principais
   - Mocks necessários

📐 ESPECIFICAÇÃO POR MÓDULO:

**MÓDULO 1: Process Scheduler**

Responsabilidades:
- Gerenciar fila de processos ready
- Implementar algoritmos de scheduling
- Calcular métricas (turnaround, waiting, response time)
- Simular context switches

API Principal:
```python
class Scheduler:
    def __init__(self, algorithm: SchedulingAlgorithm)
    def add_process(self, process: Process) -> None
    def schedule(self) -> Process | None
    def run_simulation(self, duration: int) -> SimulationResult
    def get_metrics(self) -> Dict[str, float]
    def visualize_gantt(self) -> GanttChart
```

Estruturas de Dados:
```python
@dataclass
class Process:
    pid: int
    arrival_time: int
    burst_time: int
    priority: int
    state: ProcessState
    
@dataclass
class SimulationResult:
    gantt_chart: List[Tuple[int, int, int]]  # (pid, start, end)
    metrics: Dict[str, float]
    total_time: int
```

Algoritmos a Implementar:
- FCFS (First-Come, First-Served)
- SJF (Shortest Job First)
- SRTF (Shortest Remaining Time First)
- Round Robin (configurável quantum)
- Priority (com aging)
- Multilevel Feedback Queue (opcional)

Testes:
- Teste com 5 processos conhecidos
- Verificar ordem de execução
- Calcular métricas manualmente e comparar
- Testar starvation e aging

**MÓDULO 2: Memory Manager**

Responsabilidades:
- Gerenciar memória virtual (paginação)
- Simular TLB
- Implementar page replacement
- Gerenciar swap space
- Heap allocator (malloc/free)

API Principal:
```python
class MemoryManager:
    def __init__(self, page_size: int, num_frames: int)
    def allocate_page(self, vpn: int) -> int  # retorna frame
    def access_memory(self, virtual_address: int) -> PhysicalAddress
    def free_page(self, vpn: int) -> None
    def get_page_table(self) -> PageTable
    def get_tlb_stats(self) -> TLBStats
```

[Continuar detalhando cada módulo...]

**MÓDULO 3: File System**
[Especificação completa]

**MÓDULO 4: I/O e Disk**
[Especificação completa]

**MÓDULO 5: Visualization**
[Especificação completa]

🎨 PROTOTIPAGEM DE UI/UX:

**Opção 1: Terminal UI (TUI) - Recomendado**

Framework: Rich (Python)

Layout Principal:
```
┌─────────────────────────────────────────────────────────┐
│  OS Simulator - Process Scheduler                       │
├─────────────────────────────────────────────────────────┤
│                                                           │
│  Algorithm: [Round Robin]  Quantum: [4]  [Start]        │
│                                                           │
│  ┌─ Gantt Chart ────────────────────────────────────┐   │
│  │ P1 │ P2 │ P3 │ P1 │ P2 │ P1 │ P3 │ ...          │   │
│  └────────────────────────────────────────────────────┘   │
│                                                           │
│  ┌─ Metrics ──────────────┐  ┌─ Ready Queue ────────┐   │
│  │ Avg Turnaround: 15.3  │  │ P1 (burst: 5)        │   │
│  │ Avg Waiting: 8.7      │  │ P2 (burst: 3)        │   │
│  │ Throughput: 2.5       │  │ P3 (burst: 8)        │   │
│  └───────────────────────┘  └──────────────────────┘   │
│                                                           │
│  [Process]  [Memory]  [FileSystem]  [I/O]  [Help]        │
└─────────────────────────────────────────────────────────┘
```

**Opção 2: GUI (se preferir)**

Framework: Qt (PyQt6), Tkinter, ou Electron

Mockup: [Descrever layout]

📝 ESPECIFICAÇÃO DE CASOS DE USO:

**Caso de Uso 1: Comparar Algoritmos de Scheduling**

Ator: Usuário/Estudante

Pré-condições:
- Sistema iniciado
- Workload carregado

Fluxo Principal:
1. Usuário seleciona "Process Scheduler"
2. Sistema mostra interface de scheduler
3. Usuário carrega workload (5 processos)
4. Usuário seleciona FCFS
5. Sistema executa simulação
6. Sistema exibe Gantt chart e métricas
7. Usuário seleciona Round Robin (quantum=4)
8. Sistema executa simulação
9. Sistema exibe resultados lado a lado
10. Usuário compara métricas

Pós-condições:
- Relatório de comparação gerado
- Usuário entende diferenças

**Caso de Uso 2: Visualizar Page Faults**
[Detalhar]

**Caso de Uso 3: Explorar File System**
[Detalhar]

[Definir 5-10 casos de uso principais]

🧪 ESTRATÉGIA DE TESTES:

**Testes Unitários:**
- Cada módulo testado isoladamente
- Mocks para dependências
- Coverage > 80%

**Testes de Integração:**
- Módulos interagindo
- Fluxos completos
- Dados realistas

**Testes de Aceitação:**
- Casos de uso end-to-end
- Interface completa
- Usuário consegue usar?

**Framework:** pytest (Python), GTest (C++), ou equivalente

Estrutura de Testes:
```
tests/
├── unit/
│   ├── test_scheduler.py
│   ├── test_memory.py
│   ├── test_filesystem.py
│   └── test_io.py
├── integration/
│   ├── test_process_memory.py
│   ├── test_filesystem_io.py
│   └── test_full_system.py
└── acceptance/
    └── test_use_cases.py
```

📂 ESTRUTURA DE DADOS DETALHADA:

[Definir todas as classes e structs principais com campos e métodos]

🔧 CONFIGURAÇÃO DE AMBIENTE:

**Dependências (Python):**
```txt
rich==13.7.0          # TUI
pytest==7.4.3         # Testing
pytest-cov==4.1.0     # Coverage
matplotlib==3.8.2     # Graphs
numpy==1.26.2         # Numeric
pydantic==2.5.0       # Data validation
click==8.1.7          # CLI
```

**Setup.py:**
[Código completo]

**Git Workflow:**
- main: código estável
- develop: integração
- feature/*: features individuais
- Commits: convenção conventional commits

📋 ATIVIDADES DO DIA 54:

**Tarefa 1: Especificar Módulos (3h)**
- Escrever spec completa de cada módulo
- Definir APIs
- Documentar estruturas de dados

**Tarefa 2: Prototipar UI (1.5h)**
- Criar mockup de interface
- Implementar layout básico
- Testar navegação

**Tarefa 3: Configurar Testes (1h)**
- Setup pytest
- Criar estrutura de testes
- Escrever 3-5 testes de exemplo

**Tarefa 4: Documentar (1h)**
- Escrever ARCHITECTURE.md completo
- Atualizar README
- Documentar decisões técnicas

**Tarefa 5: Preparar para Implementação (30min)**
- Criar branches
- Setup CI/CD (opcional)
- Checklist de tarefas para Dias 55-58

🔄 CHECKLIST DO DIA 54:
- [ ] Todos os módulos especificados
- [ ] APIs definidas e documentadas
- [ ] Protótipo de UI funcional
- [ ] Estrutura de testes pronta
- [ ] Documentação técnica completa
- [ ] Ambiente configurado
- [ ] Pronto para COMEÇAR A CODAR!

🚀 AMANHÃ (DIA 55):
- Implementação do Módulo de Processos
- Código, código, código!

💡 DICAS:
- Seja minucioso hoje, economiza tempo depois
- APIs bem definidas = módulos desacoplados
- Testes desde o início = menos bugs
- Documentar decisões = futuro você agradece

TÉCNICAS PEDAGÓGICAS:
- Elaboration (detalhamento profundo)
- Scaffolding (estruturas de suporte)
- Metacognition (planejar como aprender fazendo)

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 4):
1. Diagrama de classes completo
2. Fluxo de dados entre módulos
3. Sequência de caso de uso principal
4. Layout de UI (wireframe)

IMPORTANTE:
- DETALHAR ao máximo hoje
- Pensar em casos extremos (edge cases)
- APIs devem ser CLARAS e SIMPLES
- Testes são PRIORIDADE
- Documentar DECISÕES técnicas
- Amanhã: IMPLEMENTAÇÃO FOCADA

Formato: markdown estruturado, técnico, detalhado, com especificações completas.
```

---

## 📅 DIA 55 - Implementação: Módulo de Processos

**🎯 Objetivo:** Implementar completamente o módulo de gerenciamento de processos

**📝 Atividades:**
- Implementar Process class
- Implementar Scheduler class
- Implementar 4+ algoritmos de scheduling
- Criar testes unitários
- Integrar com visualização básica

**✅ Checkpoint:**
- [ ] Process class completo
- [ ] Scheduler funcional
- [ ] 4+ algoritmos implementados
- [ ] Testes passando (>80% coverage)
- [ ] Visualização de Gantt funcionando

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 55:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 55 - PRIMEIRO DIA DE IMPLEMENTAÇÃO do projeto final.

Dias 53-54: Planejei e arquitetei o projeto
Hoje: Implementar MÓDULO DE PROCESSOS completamente

Crie material COMPLETO usando DESIGN INSTRUCIONAL para IMPLEMENTAÇÃO focada:

CONTEÚDO DO DIA 55:

📋 OBJETIVOS DO DIA:
- Implementar estrutura Process completa
- Implementar Scheduler com 4+ algoritmos
- Criar testes unitários abrangentes
- Integrar com visualização básica
- Código limpo e documentado

💻 IMPLEMENTAÇÃO GUIADA:

**PASSO 1: Implementar Process Class (45 min)**

Código Completo:
```python
from dataclasses import dataclass
from enum import Enum
from typing import Optional

class ProcessState(Enum):
    NEW = "new"
    READY = "ready"
    RUNNING = "running"
    WAITING = "waiting"
    TERMINATED = "terminated"

@dataclass
class Process:
    """Representa um processo no sistema."""
    
    pid: int
    arrival_time: int
    burst_time: int
    priority: int = 0
    
    # Estado interno
    remaining_time: int = None
    start_time: Optional[int] = None
    finish_time: Optional[int] = None
    state: ProcessState = ProcessState.NEW
    
    # Para Round Robin
    time_quantum_used: int = 0
    
    def __post_init__(self):
        if self.remaining_time is None:
            self.remaining_time = self.burst_time
    
    @property
    def turnaround_time(self) -> Optional[int]:
        """Tempo total no sistema."""
        if self.finish_time is None:
            return None
        return self.finish_time - self.arrival_time
    
    @property
    def waiting_time(self) -> Optional[int]:
        """Tempo esperando na fila."""
        if self.turnaround_time is None:
            return None
        return self.turnaround_time - self.burst_time
    
    @property
    def response_time(self) -> Optional[int]:
        """Tempo até primeira execução."""
        if self.start_time is None:
            return None
        return self.start_time - self.arrival_time
    
    def execute(self, time_units: int) -> int:
        """Executa processo por time_units. Retorna tempo realmente executado."""
        time_to_execute = min(time_units, self.remaining_time)
        
        if self.state == ProcessState.NEW or self.state == ProcessState.READY:
            self.state = ProcessState.RUNNING
            if self.start_time is None:
                self.start_time = current_time  # precisa do contexto
        
        self.remaining_time -= time_to_execute
        
        if self.remaining_time == 0:
            self.state = ProcessState.TERMINATED
            # finish_time será setado pelo scheduler
        
        return time_to_execute
    
    def __repr__(self):
        return f"P{self.pid}(burst={self.burst_time}, arrival={self.arrival_time})"
```

**Teste do Process:**
```python
def test_process_execution():
    p = Process(pid=1, arrival_time=0, burst_time=10, priority=1)
    
    assert p.remaining_time == 10
    assert p.state == ProcessState.NEW
    
    executed = p.execute(5)
    assert executed == 5
    assert p.remaining_time == 5
    assert p.state == ProcessState.RUNNING
    
    executed = p.execute(10)  # tenta executar 10 mas só tem 5
    assert executed == 5
    assert p.remaining_time == 0
    assert p.state == ProcessState.TERMINATED
```

**PASSO 2: Implementar Scheduler Base (1h)**

```python
from abc import ABC, abstractmethod
from typing import List, Optional, Dict, Tuple
from collections import deque

class SchedulingAlgorithm(ABC):
    """Interface para algoritmos de scheduling."""
    
    @abstractmethod
    def select_next(self, ready_queue: List[Process], current_time: int) -> Optional[Process]:
        """Seleciona próximo processo a executar."""
        pass
    
    @abstractmethod
    def should_preempt(self, running: Process, ready_queue: List[Process], current_time: int) -> bool:
        """Decide se deve preemptar processo atual."""
        pass

class Scheduler:
    """Scheduler de processos."""
    
    def __init__(self, algorithm: SchedulingAlgorithm, time_quantum: int = 4):
        self.algorithm = algorithm
        self.time_quantum = time_quantum
        
        self.processes: List[Process] = []
        self.ready_queue: List[Process] = []
        self.current_process: Optional[Process] = None
        self.current_time: int = 0
        
        # Para visualização
        self.gantt_chart: List[Tuple[int, int, int]] = []  # (pid, start, end)
        self.timeline: List[Tuple[int, str, int]] = []  # (time, event, pid)
    
    def add_process(self, process: Process):
        """Adiciona processo ao scheduler."""
        self.processes.append(process)
    
    def run_simulation(self, duration: Optional[int] = None) -> Dict:
        """Executa simulação completa."""
        
        # Se duration não fornecido, calcular
        if duration is None:
            duration = max(p.arrival_time + p.burst_time for p in self.processes) * 2
        
        while self.current_time < duration:
            # Adicionar processos que chegaram à ready queue
            self._check_arrivals()
            
            # Verificar preempção
            if self.current_process and self.algorithm.should_preempt(
                self.current_process, self.ready_queue, self.current_time
            ):
                self._preempt_current()
            
            # Selecionar próximo processo se necessário
            if self.current_process is None and self.ready_queue:
                self.current_process = self.algorithm.select_next(
                    self.ready_queue, self.current_time
                )
                if self.current_process:
                    self.ready_queue.remove(self.current_process)
                    self.timeline.append((self.current_time, "START", self.current_process.pid))
            
            # Executar processo atual
            if self.current_process:
                start_time = self.current_time
                executed = self.current_process.execute(1)  # executar 1 unidade
                self.current_time += executed
                
                # Adicionar ao Gantt
                if not self.gantt_chart or self.gantt_chart[-1][0] != self.current_process.pid:
                    # Novo segmento
                    self.gantt_chart.append((self.current_process.pid, start_time, self.current_time))
                else:
                    # Estender segmento atual
                    self.gantt_chart[-1] = (self.current_process.pid, self.gantt_chart[-1][1], self.current_time)
                
                # Verificar se terminou
                if self.current_process.state == ProcessState.TERMINATED:
                    self.current_process.finish_time = self.current_time
                    self.timeline.append((self.current_time, "FINISH", self.current_process.pid))
                    self.current_process = None
                
            else:
                # CPU idle
                self.current_time += 1
            
            # Verificar se todos terminaram
            if all(p.state == ProcessState.TERMINATED for p in self.processes):
                break
        
        return self._calculate_metrics()
    
    def _check_arrivals(self):
        """Adiciona processos que chegaram à ready queue."""
        for p in self.processes:
            if p.state == ProcessState.NEW and p.arrival_time <= self.current_time:
                p.state = ProcessState.READY
                self.ready_queue.append(p)
                self.timeline.append((self.current_time, "ARRIVE", p.pid))
    
    def _preempt_current(self):
        """Preempta processo atual."""
        if self.current_process:
            self.current_process.state = ProcessState.READY
            self.ready_queue.append(self.current_process)
            self.timeline.append((self.current_time, "PREEMPT", self.current_process.pid))
            self.current_process = None
    
    def _calculate_metrics(self) -> Dict:
        """Calcula métricas de performance."""
        completed = [p for p in self.processes if p.state == ProcessState.TERMINATED]
        
        if not completed:
            return {}
        
        avg_turnaround = sum(p.turnaround_time for p in completed) / len(completed)
        avg_waiting = sum(p.waiting_time for p in completed) / len(completed)
        avg_response = sum(p.response_time for p in completed) / len(completed)
        
        total_burst = sum(p.burst_time for p in self.processes)
        throughput = len(completed) / self.current_time if self.current_time > 0 else 0
        cpu_utilization = total_burst / self.current_time if self.current_time > 0 else 0
        
        return {
            "avg_turnaround_time": avg_turnaround,
            "avg_waiting_time": avg_waiting,
            "avg_response_time": avg_response,
            "throughput": throughput,
            "cpu_utilization": cpu_utilization,
            "total_time": self.current_time,
            "processes_completed": len(completed),
        }
```

**PASSO 3: Implementar Algoritmos (2h)**

**FCFS (First-Come, First-Served):**
```python
class FCFS(SchedulingAlgorithm):
    """First-Come, First-Served: não-preemptivo."""
    
    def select_next(self, ready_queue: List[Process], current_time: int) -> Optional[Process]:
        if not ready_queue:
            return None
        # Retorna processo que chegou primeiro
        return min(ready_queue, key=lambda p: p.arrival_time)
    
    def should_preempt(self, running: Process, ready_queue: List[Process], current_time: int) -> bool:
        return False  # FCFS é não-preemptivo
```

**SJF (Shortest Job First):**
```python
class SJF(SchedulingAlgorithm):
    """Shortest Job First: não-preemptivo."""
    
    def select_next(self, ready_queue: List[Process], current_time: int) -> Optional[Process]:
        if not ready_queue:
            return None
        # Retorna processo com menor burst time
        return min(ready_queue, key=lambda p: p.burst_time)
    
    def should_preempt(self, running: Process, ready_queue: List[Process], current_time: int) -> bool:
        return False  # SJF é não-preemptivo
```

**SRTF (Shortest Remaining Time First):**
```python
class SRTF(SchedulingAlgorithm):
    """Shortest Remaining Time First: preemptivo."""
    
    def select_next(self, ready_queue: List[Process], current_time: int) -> Optional[Process]:
        if not ready_queue:
            return None
        # Retorna processo com menor tempo restante
        return min(ready_queue, key=lambda p: p.remaining_time)
    
    def should_preempt(self, running: Process, ready_queue: List[Process], current_time: int) -> bool:
        if not ready_queue:
            return False
        shortest_in_queue = min(ready_queue, key=lambda p: p.remaining_time)
        # Preempta se há processo na fila com menor tempo restante
        return shortest_in_queue.remaining_time < running.remaining_time
```

**Round Robin:**
```python
class RoundRobin(SchedulingAlgorithm):
    """Round Robin: preemptivo com time quantum."""
    
    def __init__(self, time_quantum: int = 4):
        self.time_quantum = time_quantum
        self.last_switch_time: int = 0
    
    def select_next(self, ready_queue: List[Process], current_time: int) -> Optional[Process]:
        if not ready_queue:
            return None
        # FIFO da fila
        process = ready_queue[0]
        self.last_switch_time = current_time
        return process
    
    def should_preempt(self, running: Process, ready_queue: List[Process], current_time: int) -> bool:
        # Preempta se quantum expirou
        time_running = current_time - self.last_switch_time
        return time_running >= self.time_quantum
```

**Priority Scheduling com Aging:**
```python
class PriorityScheduling(SchedulingAlgorithm):
    """Priority Scheduling com aging para prevenir starvation."""
    
    def __init__(self, aging_rate: float = 0.1):
        self.aging_rate = aging_rate
        self.wait_times: Dict[int, int] = {}  # pid -> wait time
    
    def select_next(self, ready_queue: List[Process], current_time: int) -> Optional[Process]:
        if not ready_queue:
            return None
        
        # Aplicar aging: aumentar prioridade baseado em tempo de espera
        effective_priorities = {}
        for p in ready_queue:
            wait_time = self.wait_times.get(p.pid, 0)
            # Prioridade menor = mais urgente
            effective_priority = p.priority - (wait_time * self.aging_rate)
            effective_priorities[p.pid] = effective_priority
        
        # Selecionar processo com menor prioridade efetiva
        selected = min(ready_queue, key=lambda p: effective_priorities[p.pid])
        self.wait_times[selected.pid] = 0  # reset wait time
        return selected
    
    def should_preempt(self, running: Process, ready_queue: List[Process], current_time: int) -> bool:
        # Atualizar wait times
        for p in ready_queue:
            self.wait_times[p.pid] = self.wait_times.get(p.pid, 0) + 1
        
        # Pode implementar preempção se priority de alguém na fila ficou maior
        return False  # ou implementar lógica de preempção
```

**PASSO 4: Testes Unitários (1h)**

```python
import pytest

def test_fcfs_scheduling():
    processes = [
        Process(pid=1, arrival_time=0, burst_time=8, priority=1),
        Process(pid=2, arrival_time=1, burst_time=4, priority=1),
        Process(pid=3, arrival_time=2, burst_time=2, priority=1),
    ]
    
    scheduler = Scheduler(algorithm=FCFS())
    for p in processes:
        scheduler.add_process(p)
    
    metrics = scheduler.run_simulation()
    
    # FCFS: ordem de chegada
    # P1: 0-8, P2: 8-12, P3: 12-14
    assert processes[0].finish_time == 8
    assert processes[1].finish_time == 12
    assert processes[2].finish_time == 14
    
    # Turnaround: P1=8, P2=11, P3=12 → avg=10.33
    assert abs(metrics["avg_turnaround_time"] - 10.33) < 0.1

def test_sjf_scheduling():
    # [Implementar teste SJF]
    pass

def test_round_robin():
    # [Implementar teste RR]
    pass

# Mais testes...
```

**PASSO 5: Visualização de Gantt (1h)**

```python
def visualize_gantt(scheduler: Scheduler):
    """Cria visualização de Gantt chart."""
    from rich.console import Console
    from rich.table import Table
    
    console = Console()
    
    # Criar tabela
    table = Table(title="Gantt Chart")
    
    # Criar linha visual
    gantt_line = ""
    for pid, start, end in scheduler.gantt_chart:
        width = end - start
        gantt_line += f"[bold cyan]P{pid}[/]" + "─" * (width - 1) + "│"
    
    table.add_row(gantt_line)
    
    # Timeline
    timeline = ""
    for pid, start, end in scheduler.gantt_chart:
        timeline += f"{start}{'─' * (end - start - len(str(start)))}"
    timeline += f"{scheduler.current_time}"
    
    table.add_row(timeline)
    
    console.print(table)
    
    # Métricas
    metrics_table = Table(title="Metrics")
    metrics_table.add_column("Metric", style="cyan")
    metrics_table.add_column("Value", style="magenta")
    
    metrics = scheduler._calculate_metrics()
    for key, value in metrics.items():
        metrics_table.add_row(key.replace("_", " ").title(), f"{value:.2f}")
    
    console.print(metrics_table)
```

🧪 TESTES E VALIDAÇÃO:

**Executar Testes:**
```bash
pytest tests/test_scheduler.py -v --cov=src/process
```

**Cobertura Esperada:** > 80%

📊 DEMONSTRAÇÃO:

**Script de Demo:**
```python
def demo_schedulers():
    """Demonstração comparando algoritmos."""
    
    processes = [
        Process(pid=1, arrival_time=0, burst_time=8, priority=2),
        Process(pid=2, arrival_time=1, burst_time=4, priority=1),
        Process(pid=3, arrival_time=2, burst_time=9, priority=3),
        Process(pid=4, arrival_time=3, burst_time=5, priority=2),
    ]
    
    algorithms = {
        "FCFS": FCFS(),
        "SJF": SJF(),
        "SRTF": SRTF(),
        "Round Robin (q=4)": RoundRobin(time_quantum=4),
        "Priority": PriorityScheduling(),
    }
    
    for name, algorithm in algorithms.items():
        # Copiar processos (fresh state)
        procs = [Process(p.pid, p.arrival_time, p.burst_time, p.priority) for p in processes]
        
        scheduler = Scheduler(algorithm)
        for p in procs:
            scheduler.add_process(p)
        
        print(f"\n{'='*50}")
        print(f"Algorithm: {name}")
        print(f"{'='*50}")
        
        scheduler.run_simulation()
        visualize_gantt(scheduler)

if __name__ == "__main__":
    demo_schedulers()
```

🔄 CHECKLIST DO DIA 55:
- [ ] Process class implementado e testado
- [ ] Scheduler base implementado
- [ ] FCFS implementado e testado
- [ ] SJF implementado e testado
- [ ] SRTF implementado e testado
- [ ] Round Robin implementado e testado
- [ ] Priority implementado e testado
- [ ] Visualização de Gantt funcionando
- [ ] Testes unitários passando (>80% coverage)
- [ ] Código commitado no Git
- [ ] Documentação atualizada

💪 CONQUISTA DO DIA:
"Módulo de Processos COMPLETO! Você implementou 5 algoritmos de scheduling, testes abrangentes e visualização. IMPRESSIONANTE!"

🚀 AMANHÃ (DIA 56):
- Implementação do Módulo de Memória
- Paginação, TLB, Page Replacement

TÉCNICAS PEDAGÓGICAS:
- Coding-by-doing
- Test-driven development
- Incremental implementation
- Immediate feedback

IMPORTANTE:
- TESTAR cada função antes de seguir
- COMMITAR frequentemente
- DOCUMENTAR decisões
- VISUALIZAR resultados
- CELEBRAR progressos pequenos

Formato: markdown com código completo, testes, e visualizações.
```

---

## 📅 DIA 56 - Implementação: Módulo de Memória

**🎯 Objetivo:** Implementar completamente o módulo de gerenciamento de memória

**📝 Atividades:**
- Implementar paginação multi-level
- Implementar TLB com replacement
- Implementar page replacement algorithms
- Implementar heap allocator
- Criar testes unitários
- Integrar com visualização

**✅ Checkpoint:**
- [ ] Paginação 4-level funcional
- [ ] TLB com LRU implementado
- [ ] 3+ algoritmos de page replacement
- [ ] Heap allocator (malloc/free) funcionando
- [ ] Testes passando (>80% coverage)
- [ ] Visualização de page table e TLB

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 56:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 56 - SEGUNDO DIA DE IMPLEMENTAÇÃO.

Ontem (Dia 55): Implementei módulo de processos completo
Hoje: Implementar MÓDULO DE MEMÓRIA completamente

Crie material COMPLETO usando DESIGN INSTRUCIONAL para implementação de memória:

CONTEÚDO DO DIA 56:

📋 OBJETIVOS DO DIA:
- Implementar paginação multi-level (4 níveis)
- Implementar TLB com cache LRU
- Implementar page replacement (FIFO, LRU, Clock)
- Implementar heap allocator básico
- Criar testes abrangentes
- Visualização de estruturas de memória

💻 IMPLEMENTAÇÃO GUIADA:

**PASSO 1: Estruturas Básicas de Memória (45 min)**

```python
from dataclasses import dataclass
from typing import Optional, Dict, List
from enum import Enum

# Configurações
PAGE_SIZE = 4096  # 4KB
FRAME_SIZE = PAGE_SIZE
ADDRESS_BITS = 48  # x86-64 usa 48 bits
OFFSET_BITS = 12  # log2(4096)
VPN_BITS = ADDRESS_BITS - OFFSET_BITS  # 36 bits para VPN

# Divisão para 4 níveis (9 bits cada)
BITS_PER_LEVEL = 9  # 2^9 = 512 entries per table

@dataclass
class PageTableEntry:
    """Entrada da page table."""
    
    present: bool = False          # Página está na memória?
    frame_number: Optional[int] = None  # Frame físico
    read: bool = True
    write: bool = True
    execute: bool = False
    dirty: bool = False            # Foi modificada?
    accessed: bool = False         # Foi acessada?
    
    # Para swapping
    disk_location: Optional[int] = None
    
    def __repr__(self):
        status = "Present" if self.present else "Swapped"
        return f"PTE(frame={self.frame_number}, {status})"

class PageTable:
    """Page table multi-level (4 níveis)."""
    
    def __init__(self):
        # PML4 é o nível raiz
        self.pml4: Dict[int, 'PageDirectoryPointer'] = {}
    
    def translate(self, virtual_address: int) -> Optional[int]:
        """Traduz endereço virtual para físico."""
        
        # Extrair índices dos 4 níveis
        offset = virtual_address & ((1 << OFFSET_BITS) - 1)
        vpn = virtual_address >> OFFSET_BITS
        
        pml4_index = (vpn >> (BITS_PER_LEVEL * 3)) & ((1 << BITS_PER_LEVEL) - 1)
        pdp_index = (vpn >> (BITS_PER_LEVEL * 2)) & ((1 << BITS_PER_LEVEL) - 1)
        pd_index = (vpn >> BITS_PER_LEVEL) & ((1 << BITS_PER_LEVEL) - 1)
        pt_index = vpn & ((1 << BITS_PER_LEVEL) - 1)
        
        # Walk através dos 4 níveis
        if pml4_index not in self.pml4:
            return None  # Page fault
        
        pdp = self.pml4[pml4_index]
        if pdp_index not in pdp.entries:
            return None
        
        pd = pdp.entries[pdp_index]
        if pd_index not in pd.entries:
            return None
        
        pt = pd.entries[pd_index]
        if pt_index not in pt.entries:
            return None
        
        pte = pt.entries[pt_index]
        if not pte.present:
            return None  # Page fault (swapped)
        
        # Construir endereço físico
        physical_address = (pte.frame_number << OFFSET_BITS) | offset
        pte.accessed = True  # Marcar como acessada
        
        return physical_address
    
    def map_page(self, vpn: int, frame: int, permissions: Dict[str, bool] = None):
        """Mapeia página virtual para frame físico."""
        
        # Extrair índices
        pml4_index = (vpn >> (BITS_PER_LEVEL * 3)) & ((1 << BITS_PER_LEVEL) - 1)
        pdp_index = (vpn >> (BITS_PER_LEVEL * 2)) & ((1 << BITS_PER_LEVEL) - 1)
        pd_index = (vpn >> BITS_PER_LEVEL) & ((1 << BITS_PER_LEVEL) - 1)
        pt_index = vpn & ((1 << BITS_PER_LEVEL) - 1)
        
        # Criar estruturas se necessário (allocation on demand)
        if pml4_index not in self.pml4:
            self.pml4[pml4_index] = PageDirectoryPointer()
        
        pdp = self.pml4[pml4_index]
        if pdp_index not in pdp.entries:
            pdp.entries[pdp_index] = PageDirectory()
        
        pd = pdp.entries[pdp_index]
        if pd_index not in pd.entries:
            pd.entries[pd_index] = PageTableLevel()
        
        pt = pd.entries[pd_index]
        
        # Criar PTE
        pte = PageTableEntry(
            present=True,
            frame_number=frame,
            read=permissions.get('read', True) if permissions else True,
            write=permissions.get('write', True) if permissions else True,
            execute=permissions.get('execute', False) if permissions else False,
        )
        
        pt.entries[pt_index] = pte

class PageDirectoryPointer:
    def __init__(self):
        self.entries: Dict[int, 'PageDirectory'] = {}

class PageDirectory:
    def __init__(self):
        self.entries: Dict[int, 'PageTableLevel'] = {}

class PageTableLevel:
    def __init__(self):
        self.entries: Dict[int, PageTableEntry] = {}
```

**PASSO 2: Implementar TLB (1h)**

```python
from collections import OrderedDict

class TLBEntry:
    """Entrada no TLB."""
    def __init__(self, vpn: int, frame: int, permissions: PageTableEntry):
        self.vpn = vpn
        self.frame = frame
        self.permissions = permissions
        self.access_time = 0  # Para LRU

class TLB:
    """Translation Lookaside Buffer - Cache de traduções."""
    
    def __init__(self, size: int = 64):
        self.size = size
        self.entries: OrderedDict[int, TLBEntry] = OrderedDict()
        
        # Estatísticas
        self.hits = 0
        self.misses = 0
    
    def lookup(self, vpn: int) -> Optional[TLBEntry]:
        """Busca tradução no TLB."""
        if vpn in self.entries:
            self.hits += 1
            # Move para o fim (LRU - mais recente)
            self.entries.move_to_end(vpn)
            return self.entries[vpn]
        else:
            self.misses += 1
            return None
    
    def insert(self, vpn: int, frame: int, permissions: PageTableEntry):
        """Insere tradução no TLB."""
        
        # Se já existe, atualizar
        if vpn in self.entries:
            self.entries[vpn] = TLBEntry(vpn, frame, permissions)
            self.entries.move_to_end(vpn)
            return
        
        # Se cheio, remover LRU (primeiro da OrderedDict)
        if len(self.entries) >= self.size:
            self.entries.popitem(last=False)  # Remove oldest
        
        # Inserir novo
        self.entries[vpn] = TLBEntry(vpn, frame, permissions)
    
    def flush(self):
        """Limpa todo o TLB (context switch)."""
        self.entries.clear()
    
    def invalidate(self, vpn: int):
        """Invalida entrada específica."""
        if vpn in self.entries:
            del self.entries[vpn]
    
    @property
    def hit_rate(self) -> float:
        """Taxa de acerto do TLB."""
        total = self.hits + self.misses
        return self.hits / total if total > 0 else 0.0
    
    def get_stats(self) -> Dict:
        """Retorna estatísticas."""
        return {
            "hits": self.hits,
            "misses": self.misses,
            "hit_rate": self.hit_rate,
            "entries_used": len(self.entries),
            "size": self.size,
        }
```

**PASSO 3: Memory Manager com Physical Memory (1h)**

```python
class PhysicalMemory:
    """Gerenciador de memória física (frames)."""
    
    def __init__(self, num_frames: int = 256):
        self.num_frames = num_frames
        self.frames: List[Optional[bytes]] = [None] * num_frames
        self.free_frames: List[int] = list(range(num_frames))
        self.frame_to_vpn: Dict[int, int] = {}  # Para page replacement
    
    def allocate_frame(self) -> Optional[int]:
        """Aloca um frame livre."""
        if self.free_frames:
            return self.free_frames.pop(0)
        return None  # Sem frames livres - precisa page replacement
    
    def free_frame(self, frame: int):
        """Libera um frame."""
        if 0 <= frame < self.num_frames:
            self.frames[frame] = None
            if frame not in self.free_frames:
                self.free_frames.append(frame)
            if frame in self.frame_to_vpn:
                del self.frame_to_vpn[frame]
    
    def read_frame(self, frame: int) -> Optional[bytes]:
        """Lê dados de um frame."""
        if 0 <= frame < self.num_frames:
            return self.frames[frame]
        return None
    
    def write_frame(self, frame: int, data: bytes):
        """Escreve dados em um frame."""
        if 0 <= frame < self.num_frames:
            self.frames[frame] = data

class MemoryManager:
    """Gerenciador de memória completo."""
    
    def __init__(self, num_frames: int = 256, tlb_size: int = 64):
        self.page_table = PageTable()
        self.tlb = TLB(size=tlb_size)
        self.physical_memory = PhysicalMemory(num_frames=num_frames)
        
        # Page replacement
        self.page_replacement_algo = None  # Será setado depois
        
        # Swap space (simulado)
        self.swap_space: Dict[int, bytes] = {}
        self.next_swap_location = 0
        
        # Estatísticas
        self.page_faults = 0
        self.disk_reads = 0
        self.disk_writes = 0
    
    def access_memory(self, virtual_address: int, write: bool = False) -> Optional[int]:
        """Acessa memória virtual, retorna endereço físico."""
        
        vpn = virtual_address >> OFFSET_BITS
        offset = virtual_address & ((1 << OFFSET_BITS) - 1)
        
        # 1. Verificar TLB
        tlb_entry = self.tlb.lookup(vpn)
        if tlb_entry:
            # TLB hit!
            if write:
                tlb_entry.permissions.dirty = True
            physical_address = (tlb_entry.frame << OFFSET_BITS) | offset
            return physical_address
        
        # 2. TLB miss - consultar page table
        physical_address = self.page_table.translate(virtual_address)
        
        if physical_address is not None:
            # Página presente - atualizar TLB
            frame = physical_address >> OFFSET_BITS
            # Precisamos do PTE para permissões
            pte = self._get_pte(vpn)
            if pte:
                self.tlb.insert(vpn, frame, pte)
                if write:
                    pte.dirty = True
            return physical_address
        
        # 3. Page fault!
        self.page_faults += 1
        return self._handle_page_fault(vpn, write)
    
    def _handle_page_fault(self, vpn: int, write: bool) -> Optional[int]:
        """Trata page fault."""
        
        # Alocar frame
        frame = self.physical_memory.allocate_frame()
        
        if frame is None:
            # Sem frames livres - page replacement
            frame = self._page_replacement()
            if frame is None:
                raise MemoryError("Cannot allocate frame")
        
        # Verificar se página está no swap
        pte = self._get_pte(vpn)
        if pte and pte.disk_location is not None:
            # Swap in
            data = self.swap_space.get(pte.disk_location)
            if data:
                self.physical_memory.write_frame(frame, data)
                self.disk_reads += 1
        else:
            # Nova página - zerar
            self.physical_memory.write_frame(frame, b'\x00' * PAGE_SIZE)
        
        # Mapear página
        self.page_table.map_page(vpn, frame)
        self.physical_memory.frame_to_vpn[frame] = vpn
        
        # Atualizar TLB
        pte = self._get_pte(vpn)
        if pte:
            self.tlb.insert(vpn, frame, pte)
            if write:
                pte.dirty = True
        
        # Construir endereço físico
        offset = 0  # Simplificado
        physical_address = (frame << OFFSET_BITS) | offset
        return physical_address
    
    def _page_replacement(self) -> Optional[int]:
        """Seleciona página vítima para substituir."""
        if self.page_replacement_algo:
            return self.page_replacement_algo.select_victim()
        return None
    
    def _get_pte(self, vpn: int) -> Optional[PageTableEntry]:
        """Obtém PTE para VPN."""
        # Implementação simplificada - navegar page table
        # [Código para extrair PTE da estrutura multi-level]
        pass
    
    def get_stats(self) -> Dict:
        """Retorna estatísticas."""
        return {
            **self.tlb.get_stats(),
            "page_faults": self.page_faults,
            "disk_reads": self.disk_reads,
            "disk_writes": self.disk_writes,
        }
```

**PASSO 4: Page Replacement Algorithms (1.5h)**

```python
from abc import ABC, abstractmethod

class PageReplacementAlgorithm(ABC):
    """Interface para algoritmos de page replacement."""
    
    def __init__(self, physical_memory: PhysicalMemory):
        self.physical_memory = physical_memory
    
    @abstractmethod
    def select_victim(self) -> Optional[int]:
        """Seleciona frame vítima para substituir."""
        pass
    
    @abstractmethod
    def on_page_access(self, frame: int):
        """Notifica acesso a página."""
        pass

class FIFO_PageReplacement(PageReplacementAlgorithm):
    """FIFO: substitui página mais antiga."""
    
    def __init__(self, physical_memory: PhysicalMemory):
        super().__init__(physical_memory)
        self.queue: List[int] = []
    
    def select_victim(self) -> Optional[int]:
        if self.queue:
            return self.queue.pop(0)
        return None
    
    def on_page_access(self, frame: int):
        if frame not in self.queue:
            self.queue.append(frame)

class LRU_PageReplacement(PageReplacementAlgorithm):
    """LRU: substitui página menos recentemente usada."""
    
    def __init__(self, physical_memory: PhysicalMemory):
        super().__init__(physical_memory)
        self.access_times: Dict[int, int] = {}
        self.current_time = 0
    
    def select_victim(self) -> Optional[int]:
        if not self.access_times:
            return None
        # Retorna frame com menor access_time
        victim = min(self.access_times.keys(), key=lambda f: self.access_times[f])
        del self.access_times[victim]
        return victim
    
    def on_page_access(self, frame: int):
        self.current_time += 1
        self.access_times[frame] = self.current_time

class Clock_PageReplacement(PageReplacementAlgorithm):
    """Clock (Second Chance): aproximação de LRU."""
    
    def __init__(self, physical_memory: PhysicalMemory):
        super().__init__(physical_memory)
        self.frames: List[int] = list(range(physical_memory.num_frames))
        self.reference_bits: Dict[int, bool] = {f: False for f in self.frames}
        self.clock_hand = 0
    
    def select_victim(self) -> Optional[int]:
        """Varredura circular procurando ref_bit=0."""
        checked = 0
        num_frames = len(self.frames)
        
        while checked < num_frames * 2:  # Máximo 2 voltas
            frame = self.frames[self.clock_hand]
            
            if not self.reference_bits[frame]:
                # Ref bit = 0, pode substituir
                self.clock_hand = (self.clock_hand + 1) % num_frames
                return frame
            else:
                # Ref bit = 1, dar segunda chance (setar para 0)
                self.reference_bits[frame] = False
                self.clock_hand = (self.clock_hand + 1) % num_frames
            
            checked += 1
        
        # Se chegou aqui, todos têm ref=1, pegar qualquer
        return self.frames[self.clock_hand]
    
    def on_page_access(self, frame: int):
        """Setar reference bit."""
        self.reference_bits[frame] = True
```

**PASSO 5: Heap Allocator Básico (1h)**

```python
@dataclass
class Block:
    """Bloco de memória do heap."""
    size: int
    is_free: bool
    next: Optional['Block'] = None
    data_address: int = 0  # Endereço virtual do início dos dados

class HeapAllocator:
    """Heap allocator (malloc/free) simplificado."""
    
    def __init__(self, heap_start: int, heap_size: int):
        self.heap_start = heap_start
        self.heap_size = heap_size
        
        # Free list
        self.free_list: List[Block] = [Block(size=heap_size, is_free=True, data_address=heap_start)]
        
        # Estatísticas
        self.total_allocated = 0
        self.num_allocations = 0
        self.num_frees = 0
    
    def malloc(self, size: int) -> Optional[int]:
        """Aloca bloco de memória. Retorna endereço virtual ou None."""
        
        # Arredondar para múltiplo de 8 (alignment)
        size = ((size + 7) // 8) * 8
        
        # First fit: encontrar primeiro bloco que cabe
        for block in self.free_list:
            if block.is_free and block.size >= size:
                # Encontrou bloco adequado
                self.num_allocations += 1
                self.total_allocated += size
                
                # Se bloco é muito maior, split
                if block.size > size + 16:  # 16 bytes mínimo para fragmento
                    # Criar novo bloco com o resto
                    new_block = Block(
                        size=block.size - size,
                        is_free=True,
                        data_address=block.data_address + size
                    )
                    new_block.next = block.next
                    block.next = new_block
                    self.free_list.insert(self.free_list.index(block) + 1, new_block)
                    
                    # Ajustar tamanho do bloco alocado
                    block.size = size
                
                block.is_free = False
                return block.data_address
        
        # Não encontrou bloco adequado
        return None
    
    def free(self, address: int):
        """Libera bloco previamente alocado."""
        
        # Encontrar bloco com esse endereço
        for i, block in enumerate(self.free_list):
            if block.data_address == address:
                if block.is_free:
                    raise ValueError(f"Double free at address {address}")
                
                block.is_free = True
                self.num_frees += 1
                self.total_allocated -= block.size
                
                # Coalescing: unir com vizinhos livres
                self._coalesce(i)
                return
        
        raise ValueError(f"Invalid free at address {address}")
    
    def _coalesce(self, index: int):
        """Une blocos livres adjacentes."""
        
        # Unir com próximo se livre
        if index < len(self.free_list) - 1:
            current = self.free_list[index]
            next_block = self.free_list[index + 1]
            
            if current.is_free and next_block.is_free:
                # Unir
                current.size += next_block.size
                current.next = next_block.next
                self.free_list.pop(index + 1)
        
        # Unir com anterior se livre
        if index > 0:
            prev = self.free_list[index - 1]
            current = self.free_list[index]
            
            if prev.is_free and current.is_free:
                # Unir
                prev.size += current.size
                prev.next = current.next
                self.free_list.pop(index)
    
    def get_fragmentation(self) -> float:
        """Calcula fragmentação externa."""
        total_free = sum(b.size for b in self.free_list if b.is_free)
        if total_free == 0:
            return 0.0
        
        largest_free = max((b.size for b in self.free_list if b.is_free), default=0)
        return 1.0 - (largest_free / total_free)
    
    def visualize(self):
        """Visualiza estado do heap."""
        print(f"\nHeap: {self.heap_start} - {self.heap_start + self.heap_size}")
        print("=" * 60)
        
        for block in self.free_list:
            status = "FREE" if block.is_free else "USED"
            bar = "░" * (block.size // 1024) if block.is_free else "█" * (block.size // 1024)
            print(f"[{status}] {block.data_address:08x} | {block.size:6d} bytes | {bar}")
        
        print(f"\nAllocated: {self.total_allocated} / {self.heap_size}")
        print(f"Fragmentation: {self.get_fragmentation():.2%}")
```

**PASSO 6: Testes Unitários (1h)**

```python
def test_page_table_translation():
    """Testa tradução de endereços."""
    pt = PageTable()
    
    # Mapear algumas páginas
    pt.map_page(vpn=0, frame=10)
    pt.map_page(vpn=1, frame=20)
    pt.map_page(vpn=100, frame=50)
    
    # Testar traduções
    vaddr = 0  # VPN=0, offset=0
    paddr = pt.translate(vaddr)
    assert paddr == (10 << OFFSET_BITS)  # Frame 10
    
    vaddr = PAGE_SIZE  # VPN=1, offset=0
    paddr = pt.translate(vaddr)
    assert paddr == (20 << OFFSET_BITS)  # Frame 20
    
    # Página não mapeada
    vaddr = 2 * PAGE_SIZE  # VPN=2
    paddr = pt.translate(vaddr)
    assert paddr is None

def test_tlb():
    """Testa TLB."""
    tlb = TLB(size=4)
    
    # Misses iniciais
    assert tlb.lookup(1) is None
    assert tlb.misses == 1
    
    # Inserir entradas
    tlb.insert(1, 10, PageTableEntry())
    tlb.insert(2, 20, PageTableEntry())
    
    # Hits
    assert tlb.lookup(1) is not None
    assert tlb.hits == 1
    
    # LRU replacement
    tlb.insert(3, 30, PageTableEntry())
    tlb.insert(4, 40, PageTableEntry())
    tlb.insert(5, 50, PageTableEntry())  # Deve remover entrada mais antiga
    
    assert len(tlb.entries) == 4  # Tamanho máximo

def test_heap_allocator():
    """Testa heap allocator."""
    heap = HeapAllocator(heap_start=0x1000, heap_size=1024)
    
    # Alocar
    addr1 = heap.malloc(100)
    assert addr1 == 0x1000
    
    addr2 = heap.malloc(200)
    assert addr2 is not None
    assert addr2 > addr1
    
    # Liberar e realocar
    heap.free(addr1)
    addr3 = heap.malloc(50)
    assert addr3 == addr1  # Reutilizou espaço
    
    # Liberar tudo
    heap.free(addr2)
    heap.free(addr3)
    
    # Coalescing deve ter unido tudo
    assert len([b for b in heap.free_list if b.is_free]) >= 1

def test_page_replacement():
    """Testa algoritmos de page replacement."""
    pm = PhysicalMemory(num_frames=3)
    
    # FIFO
    fifo = FIFO_PageReplacement(pm)
    fifo.on_page_access(0)
    fifo.on_page_access(1)
    fifo.on_page_access(2)
    
    victim = fifo.select_victim()
    assert victim == 0  # Primeiro a entrar
    
    # LRU
    lru = LRU_PageReplacement(pm)
    lru.on_page_access(0)
    lru.on_page_access(1)
    lru.on_page_access(2)
    lru.on_page_access(0)  # Usar 0 de novo
    
    victim = lru.select_victim()
    assert victim == 1  # Menos recentemente usado

# Executar testes
if __name__ == "__main__":
    pytest.main([__file__, "-v"])
```

**PASSO 7: Visualização de Memória (1h)**

```python
from rich.console import Console
from rich.table import Table
from rich.panel import Panel

def visualize_memory_manager(mm: MemoryManager):
    """Visualiza estado do memory manager."""
    console = Console()
    
    # TLB Stats
    tlb_stats = mm.tlb.get_stats()
    tlb_table = Table(title="TLB Statistics")
    tlb_table.add_column("Metric", style="cyan")
    tlb_table.add_column("Value", style="magenta")
    
    for key, value in tlb_stats.items():
        if isinstance(value, float):
            tlb_table.add_row(key, f"{value:.2%}" if "rate" in key else f"{value:.2f}")
        else:
            tlb_table.add_row(key, str(value))
    
    console.print(tlb_table)
    
    # Page Table (amostra)
    pt_table = Table(title="Page Table (Sample)")
    pt_table.add_column("VPN", style="cyan")
    pt_table.add_column("Frame", style="green")
    pt_table.add_column("Status", style="yellow")
    
    # Mostrar algumas entradas
    # [Código para iterar page table]
    
    console.print(pt_table)
    
    # Memory Stats
    stats = mm.get_stats()
    stats_table = Table(title="Memory Statistics")
    stats_table.add_column("Metric", style="cyan")
    stats_table.add_column("Value", style="magenta")
    
    for key, value in stats.items():
        stats_table.add_row(key.replace("_", " ").title(), str(value))
    
    console.print(stats_table)

def demo_memory_system():
    """Demonstração do sistema de memória."""
    console = Console()
    
    # Criar memory manager
    mm = MemoryManager(num_frames=16, tlb_size=8)
    mm.page_replacement_algo = FIFO_PageReplacement(mm.physical_memory)
    
    console.print(Panel("[bold cyan]Memory Management Demo[/]"))
    
    # Simular acessos
    addresses = [0x1000, 0x2000, 0x1000, 0x3000, 0x2000, 0x4000]
    
    for vaddr in addresses:
        console.print(f"\n[yellow]Accessing virtual address: 0x{vaddr:08x}[/]")
        paddr = mm.access_memory(vaddr)
        if paddr:
            console.print(f"[green]→ Physical address: 0x{paddr:08x}[/]")
        else:
            console.print("[red]→ Page fault![/]")
    
    # Visualizar estado
    visualize_memory_manager(mm)

if __name__ == "__main__":
    demo_memory_system()
```

🔄 CHECKLIST DO DIA 56:
- [ ] Page Table multi-level implementada
- [ ] TLB com LRU implementado
- [ ] Page replacement (FIFO, LRU, Clock) implementados
- [ ] Heap allocator funcionando
- [ ] Memory Manager integrado
- [ ] Testes unitários passando (>80% coverage)
- [ ] Visualização funcionando
- [ ] Código commitado no Git
- [ ] Documentação atualizada

💪 CONQUISTA DO DIA:
"Módulo de Memória COMPLETO! Você implementou paginação 4-level, TLB, page replacement e heap allocator. Sistema de memória funcionando!"

🚀 AMANHÃ (DIA 57):
- Implementação do Módulo de File System
- Inodes, operações, caching

IMPORTANTE:
- Memory management é COMPLEXO
- TESTAR extensivamente
- VISUALIZAR para entender
- INTEGRAR com processos (context switch)
- Documentar estruturas

Formato: markdown com código completo e testes.
```

---

## 📅 DIA 57 - Implementação: Módulo de File System

**🎯 Objetivo:** Implementar file system completo com inodes

**📝 Atividades:**
- Implementar estrutura de inodes
- Implementar diretórios
- Operações de arquivo (create, read, write, delete)
- Free space management
- Caching básico
- Testes e visualização

**✅ Checkpoint:**
- [ ] Inode structure implementado
- [ ] Directory operations funcionando
- [ ] File I/O completo
- [ ] Free space bitmap funcional
- [ ] Testes passando
- [ ] Visualização de FS

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 57:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 57 - TERCEIRO DIA DE IMPLEMENTAÇÃO.

Dias anteriores:
- Dia 55: Módulo de Processos ✅
- Dia 56: Módulo de Memória ✅
Hoje: Implementar MÓDULO DE FILE SYSTEM completamente

Crie material COMPLETO usando DESIGN INSTRUCIONAL para implementação de file system:

[ESTRUTURA SIMILAR AOS DIAS ANTERIORES]

CONTEÚDO DO DIA 57:

📋 OBJETIVOS DO DIA:
- Implementar estrutura de inodes e metadata
- Implementar árvore de diretórios
- Implementar operações de arquivo (CRUD)
- Implementar free space management (bitmap)
- Implementar caching de blocos
- Testes abrangentes
- Visualização de estrutura de FS

💻 IMPLEMENTAÇÃO GUIADA:

**PASSO 1: Estruturas Básicas do FS (1h)**

```python
from dataclasses import dataclass, field
from typing import Optional, List, Dict
from datetime import datetime
from enum import Enum

BLOCK_SIZE = 4096  # 4KB blocks
INODE_SIZE = 128   # bytes
MAX_NAME_LEN = 255

class FileType(Enum):
    REGULAR = 1
    DIRECTORY = 2
    SYMLINK = 3

@dataclass
class Inode:
    """Estrutura de inode (metadata de arquivo)."""
    
    inode_number: int
    file_type: FileType
    size: int = 0
    
    # Permissions (simplificado)
    owner_uid: int = 0
    group_gid: int = 0
    permissions: int = 0o644  # rwxrwxrwx
    
    # Timestamps
    created_time: datetime = field(default_factory=datetime.now)
    modified_time: datetime = field(default_factory=datetime.now)
    accessed_time: datetime = field(default_factory=datetime.now)
    
    # Block pointers (simplificado - sem indirect blocks)
    direct_blocks: List[Optional[int]] = field(default_factory=lambda: [None] * 12)
    
    # Links
    hard_link_count: int = 1
    
    def allocate_block(self, block_num: int) -> bool:
        """Aloca um bloco para este inode."""
        for i in range(len(self.direct_blocks)):
            if self.direct_blocks[i] is None:
                self.direct_blocks[i] = block_num
                return True
        return False  # Todos os direct blocks usados
    
    def get_blocks(self) -> List[int]:
        """Retorna lista de blocos alocados."""
        return [b for b in self.direct_blocks if b is not None]
    
    def __repr__(self):
        return f"Inode({self.inode_number}, {self.file_type.name}, {self.size}B)"

@dataclass
class DirectoryEntry:
    """Entrada de diretório."""
    name: str
    inode_number: int
    
    def __repr__(self):
        return f"{self.name} -> inode {self.inode_number}"

class Directory:
    """Diretório contendo arquivos e subdiretórios."""
    
    def __init__(self, inode: Inode):
        self.inode = inode
        self.entries: List[DirectoryEntry] = []
        
        # Todo diretório tem . e ..
        self.entries.append(DirectoryEntry(".", inode.inode_number))
    
    def add_entry(self, name: str, inode_number: int) -> bool:
        """Adiciona entrada ao diretório."""
        if self.find_entry(name):
            return False  # Nome já existe
        
        self.entries.append(DirectoryEntry(name, inode_number))
        return True
    
    def remove_entry(self, name: str) -> bool:
        """Remove entrada do diretório."""
        if name in [".", ".."]:
            return False  # Não pode remover . ou ..
        
        for i, entry in enumerate(self.entries):
            if entry.name == name:
                self.entries.pop(i)
                return True
        return False
    
    def find_entry(self, name: str) -> Optional[DirectoryEntry]:
        """Busca entrada por nome."""
        for entry in self.entries:
            if entry.name == name:
                return entry
        return None
    
    def list_entries(self) -> List[DirectoryEntry]:
        """Lista todas as entradas."""
        return self.entries.copy()
```

**PASSO 2: Block Management (45 min)**

```python
class BlockBitmap:
    """Bitmap de blocos livres."""
    
    def __init__(self, num_blocks: int):
        self.num_blocks = num_blocks
        # Cada byte representa 8 blocos
        self.bitmap = bytearray((num_blocks + 7) // 8)
        
        # Marcar todos como livres inicialmente
        for i in range(len(self.bitmap)):
            self.bitmap[i] = 0xFF
    
    def allocate_block(self) -> Optional[int]:
        """Aloca um bloco livre."""
        for byte_index in range(len(self.bitmap)):
            if self.bitmap[byte_index] != 0:
                # Tem bits livres neste byte
                for bit_index in range(8):
                    if self.bitmap[byte_index] & (1 << bit_index):
                        # Bit está livre
                        block_num = byte_index * 8 + bit_index
                        if block_num < self.num_blocks:
                            self.bitmap[byte_index] &= ~(1 << bit_index)
                            return block_num
        return None  # Sem blocos livres
    
    def free_block(self, block_num: int):
        """Libera um bloco."""
        if 0 <= block_num < self.num_blocks:
            byte_index = block_num // 8
            bit_index = block_num % 8
            self.bitmap[byte_index] |= (1 << bit_index)
    
    def is_allocated(self, block_num: int) -> bool:
        """Verifica se bloco está alocado."""
        byte_index = block_num // 8
        bit_index = block_num % 8
        return not (self.bitmap[byte_index] & (1 << bit_index))
    
    def count_free(self) -> int:
        """Conta blocos livres."""
        count = 0
        for byte in self.bitmap:
            count += bin(byte).count('1')
        return min(count, self.num_blocks)

class BlockCache:
    """Cache de blocos (simplificado)."""
    
    def __init__(self, max_size: int = 100):
        self.max_size = max_size
        self.cache: Dict[int, bytes] = {}
        self.access_order: List[int] = []  # Para LRU
    
    def get(self, block_num: int) -> Optional[bytes]:
        """Busca bloco no cache."""
        if block_num in self.cache:
            # Move para fim (mais recente)
            self.access_order.remove(block_num)
            self.access_order.append(block_num)
            return self.cache[block_num]
        return None
    
    def put(self, block_num: int, data: bytes):
        """Adiciona bloco ao cache."""
        if block_num in self.cache:
            self.access_order.remove(block_num)
        elif len(self.cache) >= self.max_size:
            # Remover LRU
            lru = self.access_order.pop(0)
            del self.cache[lru]
        
        self.cache[block_num] = data
        self.access_order.append(block_num)
    
    def invalidate(self, block_num: int):
        """Invalida entrada do cache."""
        if block_num in self.cache:
            del self.cache[block_num]
            self.access_order.remove(block_num)
```

**PASSO 3: File System Implementation (2h)**

```python
class SimpleFileSystem:
    """File system simplificado com inodes."""
    
    def __init__(self, num_blocks: int = 1000, num_inodes: int = 100):
        self.num_blocks = num_blocks
        self.num_inodes = num_inodes
        
        # Superblock (metadata do FS)
        self.superblock = {
            "num_blocks": num_blocks,
            "num_inodes": num_inodes,
            "block_size": BLOCK_SIZE,
            "inode_size": INODE_SIZE,
        }
        
        # Estruturas de dados
        self.inodes: Dict[int, Inode] = {}
        self.free_inodes: List[int] = list(range(num_inodes))
        self.block_bitmap = BlockBitmap(num_blocks)
        self.blocks: Dict[int, bytes] = {}  # Simulação de disco
        self.block_cache = BlockCache()
        
        # Diretórios
        self.directories: Dict[int, Directory] = {}
        
        # Criar root directory (inode 0)
        self._create_root()
        
        # Estatísticas
        self.stats = {
            "reads": 0,
            "writes": 0,
            "cache_hits": 0,
            "cache_misses": 0,
        }
    
    def _create_root(self):
        """Cria diretório raiz."""
        root_inode = Inode(
            inode_number=0,
            file_type=FileType.DIRECTORY,
            permissions=0o755
        )
        self.inodes[0] = root_inode
        self.free_inodes.remove(0)
        
        root_dir = Directory(root_inode)
        root_dir.entries.append(DirectoryEntry("..", 0))  # .. aponta para si mesmo
        self.directories[0] = root_dir
    
    def _allocate_inode(self) -> Optional[Inode]:
        """Aloca um novo inode."""
        if not self.free_inodes:
            return None
        
        inode_num = self.free_inodes.pop(0)
        inode = Inode(inode_number=inode_num, file_type=FileType.REGULAR)
        self.inodes[inode_num] = inode
        return inode
    
    def _free_inode(self, inode_num: int):
        """Libera um inode."""
        if inode_num in self.inodes:
            # Liberar blocos alocados
            inode = self.inodes[inode_num]
            for block_num in inode.get_blocks():
                self.block_bitmap.free_block(block_num)
            
            del self.inodes[inode_num]
            self.free_inodes.append(inode_num)
    
    def create_file(self, path: str) -> bool:
        """Cria um novo arquivo."""
        # Parse path
        dirname, filename = self._split_path(path)
        
        # Encontrar diretório pai
        parent_inode_num = self._resolve_path(dirname)
        if parent_inode_num is None:
            return False
        
        parent_dir = self.directories.get(parent_inode_num)
        if not parent_dir:
            return False
        
        # Verificar se arquivo já existe
        if parent_dir.find_entry(filename):
            return False
        
        # Alocar inode
        inode = self._allocate_inode()
        if not inode:
            return False
        
        # Adicionar ao diretório
        parent_dir.add_entry(filename, inode.inode_number)
        
        return True
    
    def write_file(self, path: str, data: bytes) -> bool:
        """Escreve dados em arquivo."""
        inode_num = self._resolve_path(path)
        if inode_num is None:
            return False
        
        inode = self.inodes.get(inode_num)
        if not inode or inode.file_type != FileType.REGULAR:
            return False
        
        # Calcular blocos necessários
        blocks_needed = (len(data) + BLOCK_SIZE - 1) // BLOCK_SIZE
        
        # Alocar blocos
        for i in range(blocks_needed):
            block_num = self.block_bitmap.allocate_block()
            if block_num is None:
                return False  # Sem espaço
            
            if not inode.allocate_block(block_num):
                self.block_bitmap.free_block(block_num)
                return False
            
            # Escrever dados no bloco
            start = i * BLOCK_SIZE
            end = min(start + BLOCK_SIZE, len(data))
            block_data = data[start:end]
            
            # Pad com zeros se necessário
            if len(block_data) < BLOCK_SIZE:
                block_data += b'\x00' * (BLOCK_SIZE - len(block_data))
            
            self.blocks[block_num] = block_data
            self.block_cache.put(block_num, block_data)
            self.stats["writes"] += 1
        
        inode.size = len(data)
        inode.modified_time = datetime.now()
        
        return True
    
    def read_file(self, path: str) -> Optional[bytes]:
        """Lê dados de arquivo."""
        inode_num = self._resolve_path(path)
        if inode_num is None:
            return None
        
        inode = self.inodes.get(inode_num)
        if not inode or inode.file_type != FileType.REGULAR:
            return None
        
        # Ler blocos
        data = b''
        for block_num in inode.get_blocks():
            # Verificar cache
            block_data = self.block_cache.get(block_num)
            if block_data:
                self.stats["cache_hits"] += 1
            else:
                self.stats["cache_misses"] += 1
                block_data = self.blocks.get(block_num, b'\x00' * BLOCK_SIZE)
                self.block_cache.put(block_num, block_data)
            
            self.stats["reads"] += 1
            data += block_data
        
        # Truncar para tamanho real
        data = data[:inode.size]
        
        inode.accessed_time = datetime.now()
        return data
    
    def delete_file(self, path: str) -> bool:
        """Deleta arquivo."""
        dirname, filename = self._split_path(path)
        
        parent_inode_num = self._resolve_path(dirname)
        if parent_inode_num is None:
            return False
        
        parent_dir = self.directories.get(parent_inode_num)
        if not parent_dir:
            return False
        
        # Encontrar entrada
        entry = parent_dir.find_entry(filename)
        if not entry:
            return False
        
        # Remover do diretório
        parent_dir.remove_entry(filename)
        
        # Decrementar hard link count
        inode = self.inodes.get(entry.inode_number)
        if inode:
            inode.hard_link_count -= 1
            
            # Se não há mais links, liberar inode
            if inode.hard_link_count == 0:
                self._free_inode(entry.inode_number)
        
        return True
    
    def mkdir(self, path: str) -> bool:
        """Cria diretório."""
        dirname, subdir_name = self._split_path(path)
        
        parent_inode_num = self._resolve_path(dirname)
        if parent_inode_num is None:
            return False
        
        parent_dir = self.directories.get(parent_inode_num)
        if not parent_dir:
            return False
        
        # Criar inode para diretório
        inode = self._allocate_inode()
        if not inode:
            return False
        
        inode.file_type = FileType.DIRECTORY
        inode.permissions = 0o755
        
        # Criar estrutura de diretório
        new_dir = Directory(inode)
        new_dir.entries.append(DirectoryEntry("..", parent_inode_num))
        self.directories[inode.inode_number] = new_dir
        
        # Adicionar ao pai
        parent_dir.add_entry(subdir_name, inode.inode_number)
        
        return True
    
    def list_dir(self, path: str) -> Optional[List[DirectoryEntry]]:
        """Lista conteúdo de diretório."""
        inode_num = self._resolve_path(path)
        if inode_num is None:
            return None
        
        directory = self.directories.get(inode_num)
        if not directory:
            return None
        
        return directory.list_entries()
    
    def _resolve_path(self, path: str) -> Optional[int]:
        """Resolve caminho para inode number."""
        if path == "/":
            return 0  # Root
        
        # Começar do root
        current_inode = 0
        components = [c for c in path.split("/") if c]
        
        for component in components:
            directory = self.directories.get(current_inode)
            if not directory:
                return None
            
            entry = directory.find_entry(component)
            if not entry:
                return None
            
            current_inode = entry.inode_number
        
        return current_inode
    
    def _split_path(self, path: str) -> tuple:
        """Divide path em (dirname, filename)."""
        if "/" not in path:
            return "/", path
        
        parts = path.rsplit("/", 1)
        dirname = parts[0] if parts[0] else "/"
        filename = parts[1]
        return dirname, filename
    
    def get_stats(self) -> Dict:
        """Retorna estatísticas do FS."""
        return {
            **self.stats,
            "total_blocks": self.num_blocks,
            "free_blocks": self.block_bitmap.count_free(),
            "used_blocks": self.num_blocks - self.block_bitmap.count_free(),
            "total_inodes": self.num_inodes,
            "free_inodes": len(self.free_inodes),
            "used_inodes": self.num_inodes - len(self.free_inodes),
        }
```

**PASSO 4: Testes (1h)**

```python
def test_file_creation():
    fs = SimpleFileSystem()
    
    # Criar arquivo
    assert fs.create_file("/test.txt")
    
    # Não pode criar duplicado
    assert not fs.create_file("/test.txt")
    
    # Escrever dados
    data = b"Hello, World!"
    assert fs.write_file("/test.txt", data)
    
    # Ler dados
    read_data = fs.read_file("/test.txt")
    assert read_data == data
    
    # Deletar
    assert fs.delete_file("/test.txt")
    assert fs.read_file("/test.txt") is None

def test_directories():
    fs = SimpleFileSystem()
    
    # Criar diretório
    assert fs.mkdir("/dir1")
    
    # Criar arquivo dentro
    assert fs.create_file("/dir1/file.txt")
    
    # Listar
    entries = fs.list_dir("/dir1")
    assert len(entries) == 3  # ., .., file.txt
    
    # Nested directories
    assert fs.mkdir("/dir1/subdir")
    assert fs.create_file("/dir1/subdir/nested.txt")

def test_caching():
    fs = SimpleFileSystem()
    
    fs.create_file("/cached.txt")
    fs.write_file("/cached.txt", b"x" * 5000)
    
    # Primeira leitura (cache miss)
    fs.read_file("/cached.txt")
    misses1 = fs.stats["cache_misses"]
    
    # Segunda leitura (cache hit)
    fs.read_file("/cached.txt")
    hits = fs.stats["cache_hits"]
    
    assert hits > 0  # Deve ter hits

# Executar testes
pytest.main([__file__, "-v"])
```

**PASSO 5: Visualização (1h)**

```python
from rich.tree import Tree
from rich.console import Console

def visualize_filesystem(fs: SimpleFileSystem):
    """Visualiza estrutura do filesystem."""
    console = Console()
    
    # Árvore de diretórios
    tree = Tree("[bold cyan]/[/] (root)")
    _build_tree(fs, 0, tree)
    
    console.print("\n[bold]Filesystem Tree:[/]")
    console.print(tree)
    
    # Estatísticas
    stats = fs.get_stats()
    stats_table = Table(title="Filesystem Statistics")
    stats_table.add_column("Metric", style="cyan")
    stats_table.add_column("Value", style="magenta")
    
    for key, value in stats.items():
        stats_table.add_row(key.replace("_", " ").title(), str(value))
    
    console.print("\n")
    console.print(stats_table)
    
    # Uso de espaço
    used_pct = (stats["used_blocks"] / stats["total_blocks"]) * 100
    bar_length = 50
    used_bar = "█" * int(used_pct / 100 * bar_length)
    free_bar = "░" * (bar_length - len(used_bar))
    
    console.print(f"\n[bold]Disk Usage:[/]")
    console.print(f"[green]{used_bar}[/][white]{free_bar}[/] {used_pct:.1f}%")

def _build_tree(fs: SimpleFileSystem, inode_num: int, tree: Tree):
    """Constrói árvore recursivamente."""
    directory = fs.directories.get(inode_num)
    if not directory:
        return
    
    for entry in directory.entries:
        if entry.name in [".", ".."]:
            continue
        
        inode = fs.inodes.get(entry.inode_number)
        if not inode:
            continue
        
        if inode.file_type == FileType.DIRECTORY:
            branch = tree.add(f"[bold blue]{entry.name}/[/]")
            _build_tree(fs, entry.inode_number, branch)
        else:
            size_kb = inode.size / 1024
            tree.add(f"[green]{entry.name}[/] ({size_kb:.1f} KB)")

def demo_filesystem():
    """Demonstração completa do filesystem."""
    console = Console()
    console.print(Panel("[bold cyan]File System Demo[/]"))
    
    fs = SimpleFileSystem()
    
    # Criar estrutura
    console.print("\n[yellow]Creating files and directories...[/]")
    fs.mkdir("/documents")
    fs.mkdir("/pictures")
    fs.create_file("/documents/readme.txt")
    fs.write_file("/documents/readme.txt", b"Hello from SimpleFS!")
    fs.create_file("/documents/notes.txt")
    fs.write_file("/documents/notes.txt", b"Some notes..." * 100)
    fs.mkdir("/documents/reports")
    fs.create_file("/documents/reports/2024.txt")
    
    # Visualizar
    visualize_filesystem(fs)
    
    # Operações
    console.print("\n[yellow]Reading file...[/]")
    data = fs.read_file("/documents/readme.txt")
    console.print(f"Content: {data.decode()}")
    
    console.print("\n[yellow]Listing directory...[/]")
    entries = fs.list_dir("/documents")
    for entry in entries:
        console.print(f"  {entry}")

if __name__ == "__main__":
    demo_filesystem()
```

🔄 CHECKLIST DO DIA 57:
- [ ] Inode structure completo
- [ ] Directory operations funcionando
- [ ] File I/O (create, read, write, delete)
- [ ] Free space bitmap
- [ ] Block caching
- [ ] Testes passando
- [ ] Visualização funcionando
- [ ] Integração básica com I/O module
- [ ] Código commitado
- [ ] Documentação atualizada

💪 CONQUISTA DO DIA:
"File System COMPLETO! Você tem um FS funcional com inodes, diretórios, caching e operações de arquivo!"

🚀 AMANHÃ (DIA 58):
- Integração de TODOS os módulos
- I/O e Disk simulation
- Testes de integração
- UI/Dashboard

IMPORTANTE:
- File systems são COMPLEXOS
- Cada operação deve ser ATÔMICA
- CACHING é crucial para performance
- TESTAR edge cases
- Visualizar estrutura

Formato: markdown com código completo, testes e visualizações.
```

---

## 📅 DIA 58 - Integração: Unindo Todos os Módulos

**🎯 Objetivo:** Integrar todos os módulos e implementar I/O simulation

**📝 Atividades:**
- Integrar Process + Memory + FileSystem
- Implementar I/O e Disk simulation
- Criar interface unificada (Dashboard)
- Testes de integração
- Polimento e otimização

**✅ Checkpoint:**
- [ ] Todos os módulos integrados
- [ ] I/O e Disk funcionando
- [ ] Dashboard completo e interativo
- [ ] Testes de integração passando
- [ ] Sistema funciona end-to-end
- [ ] Performance aceitável

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 58:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 58 - DIA DE INTEGRAÇÃO de todos os módulos.

Dias anteriores:
- Dia 55: Módulo de Processos ✅
- Dia 56: Módulo de Memória ✅
- Dia 57: Módulo de File System ✅
Hoje: INTEGRAR TUDO + I/O + Dashboard

Crie material COMPLETO usando DESIGN INSTRUCIONAL para integração final:

CONTEÚDO DO DIA 58:

📋 OBJETIVOS DO DIA:
- Integrar Process + Memory + FileSystem + I/O
- Implementar Disk simulation e I/O scheduling
- Criar Dashboard unificado (TUI ou GUI)
- Testes de integração end-to-end
- Polimento e correção de bugs
- Otimização de performance

💻 IMPLEMENTAÇÃO GUIADA:

**PASSO 1: I/O e Disk Simulation (1.5h)**

```python
from enum import Enum
from dataclasses import dataclass
from typing import List, Optional
import time

class DiskType(Enum):
    HDD = "hdd"
    SSD = "ssd"

@dataclass
class DiskRequest:
    """Requisição de I/O para disco."""
    request_id: int
    track: int  # Para HDD
    block: int
    operation: str  # "read" ou "write"
    data: Optional[bytes] = None
    timestamp: float = 0.0

class DiskScheduler:
    """Scheduler de requisições de disco."""
    
    def __init__(self, algorithm: str = "FCFS"):
        self.algorithm = algorithm
        self.queue: List[DiskRequest] = []
        self.current_track = 0
        self.total_seek_distance = 0
    
    def add_request(self, request: DiskRequest):
        """Adiciona requisição à fila."""
        request.timestamp = time.time()
        self.queue.append(request)
    
    def get_next(self) -> Optional[DiskRequest]:
        """Seleciona próxima requisição baseado no algoritmo."""
        if not self.queue:
            return None
        
        if self.algorithm == "FCFS":
            return self.queue.pop(0)
        
        elif self.algorithm == "SSTF":  # Shortest Seek Time First
            closest = min(self.queue, key=lambda r: abs(r.track - self.current_track))
            self.queue.remove(closest)
            return closest
        
        elif self.algorithm == "SCAN":
            # Implementação simplificada
            going_up = sorted([r for r in self.queue if r.track >= self.current_track], 
                            key=lambda r: r.track)
            going_down = sorted([r for r in self.queue if r.track < self.current_track], 
                               key=lambda r: r.track, reverse=True)
            
            if going_up:
                request = going_up[0]
            elif going_down:
                request = going_down[0]
            else:
                return None
            
            self.queue.remove(request)
            return request
        
        return None
    
    def execute_request(self, request: DiskRequest) -> float:
        """Executa requisição e retorna tempo de acesso."""
        # Calcular seek time
        seek_distance = abs(request.track - self.current_track)
        self.total_seek_distance += seek_distance
        
        # Simular latências
        seek_time = seek_distance * 0.001  # 1ms por track
        rotational_latency = 0.004  # 4ms média
        transfer_time = 0.001  # 1ms
        
        total_time = seek_time + rotational_latency + transfer_time
        
        self.current_track = request.track
        return total_time

class Disk:
    """Simulação de disco (HDD ou SSD)."""
    
    def __init__(self, disk_type: DiskType = DiskType.HDD, 
                 capacity_mb: int = 1000, 
                 block_size: int = 4096):
        self.disk_type = disk_type
        self.capacity_mb = capacity_mb
        self.block_size = block_size
        self.num_blocks = (capacity_mb * 1024 * 1024) // block_size
        
        # Armazenamento simulado
        self.blocks: Dict[int, bytes] = {}
        
        # Scheduler
        self.scheduler = DiskScheduler(algorithm="SSTF")
        
        # Estatísticas
        self.total_reads = 0
        self.total_writes = 0
        self.total_access_time = 0.0
    
    def read_block(self, block_num: int) -> Optional[bytes]:
        """Lê um bloco do disco."""
        if block_num >= self.num_blocks:
            return None
        
        # Criar requisição
        track = block_num // 100  # Simplificação
        request = DiskRequest(
            request_id=self.total_reads,
            track=track,
            block=block_num,
            operation="read"
        )
        
        self.scheduler.add_request(request)
        next_req = self.scheduler.get_next()
        
        if next_req:
            access_time = self.scheduler.execute_request(next_req)
            self.total_access_time += access_time
            self.total_reads += 1
            
            # Simular latência
            if self.disk_type == DiskType.HDD:
                time.sleep(access_time / 1000)  # Reduzido para demo
            
            return self.blocks.get(block_num, b'\x00' * self.block_size)
        
        return None
    
    def write_block(self, block_num: int, data: bytes) -> bool:
        """Escreve um bloco no disco."""
        if block_num >= self.num_blocks:
            return False
        
        # Criar requisição
        track = block_num // 100
        request = DiskRequest(
            request_id=self.total_writes,
            track=track,
            block=block_num,
            operation="write",
            data=data
        )
        
        self.scheduler.add_request(request)
        next_req = self.scheduler.get_next()
        
        if next_req:
            access_time = self.scheduler.execute_request(next_req)
            self.total_access_time += access_time
            self.total_writes += 1
            
            # Simular latência
            if self.disk_type == DiskType.HDD:
                time.sleep(access_time / 1000)
            
            self.blocks[block_num] = data[:self.block_size]
            return True
        
        return False
    
    def get_stats(self) -> Dict:
        """Retorna estatísticas do disco."""
        return {
            "type": self.disk_type.value,
            "capacity_mb": self.capacity_mb,
            "total_reads": self.total_reads,
            "total_writes": self.total_writes,
            "avg_access_time_ms": (self.total_access_time * 1000 / 
                                   (self.total_reads + self.total_writes)) 
                                   if (self.total_reads + self.total_writes) > 0 else 0,
            "total_seek_distance": self.scheduler.total_seek_distance,
        }
```

**PASSO 2: Sistema Integrado (2h)**

```python
class OperatingSystemSimulator:
    """Simulador de SO integrado - Core do sistema."""
    
    def __init__(self):
        # Componentes
        self.memory_manager = MemoryManager(num_frames=256, tlb_size=64)
        self.scheduler = None  # Será setado pelo usuário
        self.filesystem = SimpleFileSystem(num_blocks=1000, num_inodes=100)
        self.disk = Disk(disk_type=DiskType.HDD, capacity_mb=500)
        
        # Integração: FS usa Disk
        self._integrate_fs_disk()
        
        # Processos rodando
        self.running_processes: Dict[int, Process] = {}
        self.next_pid = 1
        
        # Estado do sistema
        self.system_time = 0
        self.is_running = False
        
        # Estatísticas globais
        self.global_stats = {
            "uptime": 0,
            "context_switches": 0,
            "interrupts": 0,
        }
    
    def _integrate_fs_disk(self):
        """Integra filesystem com disco."""
        # Substituir armazenamento em memória do FS por disco
        original_read = self.filesystem.blocks.get
        original_write = self.filesystem.blocks.__setitem__
        
        def read_from_disk(block_num, default=None):
            data = self.disk.read_block(block_num)
            return data if data else default
        
        def write_to_disk(block_num, data):
            self.disk.write_block(block_num, data)
        
        # Monkey patch (simplificado)
        # Em implementação real, refatorar FS para aceitar backend
    
    def create_process(self, name: str, burst_time: int, priority: int = 0) -> int:
        """Cria um novo processo."""
        pid = self.next_pid
        self.next_pid += 1
        
        process = Process(
            pid=pid,
            arrival_time=self.system_time,
            burst_time=burst_time,
            priority=priority
        )
        
        # Alocar memória para o processo (simplificado)
        # Na prática: alocar page table, heap, stack
        base_address = pid * 0x100000  # 1MB por processo
        
        # Mapear algumas páginas
        for i in range(10):  # 10 páginas = 40KB
            vpn = (base_address >> 12) + i
            frame = self.memory_manager.physical_memory.allocate_frame()
            if frame:
                self.memory_manager.page_table.map_page(vpn, frame)
        
        self.running_processes[pid] = process
        
        if self.scheduler:
            self.scheduler.add_process(process)
        
        return pid
    
    def run_simulation(self, duration: int = 100):
        """Executa simulação integrada."""
        self.is_running = True
        
        if not self.scheduler:
            raise ValueError("Scheduler não configurado")
        
        # Executar scheduler
        result = self.scheduler.run_simulation(duration)
        
        self.system_time += duration
        self.global_stats["uptime"] = self.system_time
        
        return result
    
    def file_operation(self, operation: str, path: str, data: bytes = None) -> Any:
        """Executa operação de arquivo."""
        if operation == "create":
            return self.filesystem.create_file(path)
        elif operation == "write":
            return self.filesystem.write_file(path, data)
        elif operation == "read":
            return self.filesystem.read_file(path)
        elif operation == "delete":
            return self.filesystem.delete_file(path)
        elif operation == "mkdir":
            return self.filesystem.mkdir(path)
        elif operation == "ls":
            return self.filesystem.list_dir(path)
        else:
            return None
    
    def get_system_stats(self) -> Dict:
        """Retorna todas as estatísticas do sistema."""
        return {
            "global": self.global_stats,
            "memory": self.memory_manager.get_stats(),
            "filesystem": self.filesystem.get_stats(),
            "disk": self.disk.get_stats(),
            "scheduler": self.scheduler._calculate_metrics() if self.scheduler else {},
        }
```

**PASSO 3: Dashboard Interativo (2.5h)**

```python
from rich.console import Console
from rich.layout import Layout
from rich.panel import Panel
from rich.table import Table
from rich.live import Live
from rich.text import Text
import threading
import time

class Dashboard:
    """Dashboard interativo do simulador."""
    
    def __init__(self, os_sim: OperatingSystemSimulator):
        self.os_sim = os_sim
        self.console = Console()
        self.layout = Layout()
        self.is_running = False
    
    def setup_layout(self):
        """Configura layout do dashboard."""
        self.layout.split(
            Layout(name="header", size=3),
            Layout(name="body"),
            Layout(name="footer", size=3)
        )
        
        self.layout["body"].split_row(
            Layout(name="left"),
            Layout(name="right")
        )
        
        self.layout["left"].split(
            Layout(name="processes", ratio=2),
            Layout(name="memory", ratio=1)
        )
        
        self.layout["right"].split(
            Layout(name="filesystem"),
            Layout(name="disk")
        )
    
    def render_header(self) -> Panel:
        """Renderiza cabeçalho."""
        stats = self.os_sim.global_stats
        text = Text()
        text.append("OS Simulator Dashboard", style="bold cyan")
        text.append(f" | Uptime: {stats['uptime']}s", style="yellow")
        text.append(f" | Context Switches: {stats['context_switches']}", style="green")
        
        return Panel(text, style="white on blue")
    
    def render_processes(self) -> Panel:
        """Renderiza painel de processos."""
        if not self.os_sim.scheduler:
            return Panel("No scheduler configured", title="Processes")
        
        table = Table(title="Running Processes", expand=True)
        table.add_column("PID", style="cyan")
        table.add_column("State", style="green")
        table.add_column("Burst", style="yellow")
        table.add_column("Remaining", style="magenta")
        
        for process in self.os_sim.scheduler.processes[:10]:  # Top 10
            table.add_row(
                f"P{process.pid}",
                process.state.value,
                str(process.burst_time),
                str(process.remaining_time)
            )
        
        # Gantt chart simplificado
        gantt = ""
        for pid, start, end in self.os_sim.scheduler.gantt_chart[-20:]:
            gantt += f"P{pid}|"
        
        content = Table.grid()
        content.add_row(table)
        content.add_row(Text(f"\nGantt: {gantt}", style="dim"))
        
        return Panel(content, title="[bold]Process Scheduler[/]", border_style="blue")
    
    def render_memory(self) -> Panel:
        """Renderiza painel de memória."""
        stats = self.os_sim.memory_manager.get_stats()
        
        table = Table(expand=True)
        table.add_column("Metric", style="cyan")
        table.add_column("Value", style="magenta")
        
        table.add_row("TLB Hit Rate", f"{stats.get('hit_rate', 0):.1%}")
        table.add_row("Page Faults", str(stats.get('page_faults', 0)))
        table.add_row("Swap I/O", 
                     f"{stats.get('disk_reads', 0)}R / {stats.get('disk_writes', 0)}W")
        
        return Panel(table, title="[bold]Memory Manager[/]", border_style="green")
    
    def render_filesystem(self) -> Panel:
        """Renderiza painel de filesystem."""
        stats = self.os_sim.filesystem.get_stats()
        
        table = Table(expand=True)
        table.add_column("Metric", style="cyan")
        table.add_column("Value", style="magenta")
        
        used_inodes = stats.get('used_inodes', 0)
        total_inodes = stats.get('total_inodes', 1)
        used_blocks = stats.get('used_blocks', 0)
        total_blocks = stats.get('total_blocks', 1)
        
        table.add_row("Inodes", f"{used_inodes}/{total_inodes}")
        table.add_row("Blocks", f"{used_blocks}/{total_blocks}")
        table.add_row("Cache Hits", str(stats.get('cache_hits', 0)))
        table.add_row("Cache Misses", str(stats.get('cache_misses', 0)))
        
        # Barra de uso
        usage_pct = (used_blocks / total_blocks) * 100
        bar_len = 20
        filled = int(usage_pct / 100 * bar_len)
        bar = "█" * filled + "░" * (bar_len - filled)
        
        content = Table.grid()
        content.add_row(table)
        content.add_row(Text(f"\nUsage: {bar} {usage_pct:.1f}%", style="yellow"))
        
        return Panel(content, title="[bold]File System[/]", border_style="yellow")
    
    def render_disk(self) -> Panel:
        """Renderiza painel de disco."""
        stats = self.os_sim.disk.get_stats()
        
        table = Table(expand=True)
        table.add_column("Metric", style="cyan")
        table.add_column("Value", style="magenta")
        
        table.add_row("Type", stats.get('type', 'unknown').upper())
        table.add_row("Capacity", f"{stats.get('capacity_mb', 0)} MB")
        table.add_row("Reads", str(stats.get('total_reads', 0)))
        table.add_row("Writes", str(stats.get('total_writes', 0)))
        table.add_row("Avg Latency", f"{stats.get('avg_access_time_ms', 0):.2f} ms")
        
        return Panel(table, title="[bold]Disk I/O[/]", border_style="red")
    
    def render_footer(self) -> Panel:
        """Renderiza rodapé."""
        text = Text()
        text.append("Commands: ", style="bold")
        text.append("[P]rocesses ", style="cyan")
        text.append("[M]emory ", style="green")
        text.append("[F]ileSystem ", style="yellow")
        text.append("[Q]uit", style="red")
        
        return Panel(text, style="white on black")
    
    def update_display(self) -> Layout:
        """Atualiza display completo."""
        self.layout["header"].update(self.render_header())
        self.layout["processes"].update(self.render_processes())
        self.layout["memory"].update(self.render_memory())
        self.layout["filesystem"].update(self.render_filesystem())
        self.layout["disk"].update(self.render_disk())
        self.layout["footer"].update(self.render_footer())
        
        return self.layout
    
    def run(self, update_interval: float = 1.0):
        """Executa dashboard com atualização em tempo real."""
        self.setup_layout()
        self.is_running = True
        
        with Live(self.update_display(), console=self.console, 
                  refresh_per_second=1/update_interval) as live:
            try:
                while self.is_running:
                    time.sleep(update_interval)
                    live.update(self.update_display())
            except KeyboardInterrupt:
                self.is_running = False
```

**PASSO 4: Testes de Integração (1h)**

```python
def test_integrated_system():
    """Testa sistema integrado end-to-end."""
    
    # Criar sistema
    os_sim = OperatingSystemSimulator()
    os_sim.scheduler = Scheduler(algorithm=RoundRobin(time_quantum=4))
    
    # Criar processos
    pid1 = os_sim.create_process("Process1", burst_time=10, priority=1)
    pid2 = os_sim.create_process("Process2", burst_time=5, priority=2)
    pid3 = os_sim.create_process("Process3", burst_time=8, priority=1)
    
    # Executar scheduling
    result = os_sim.run_simulation(duration=50)
    
    assert result is not None
    assert os_sim.system_time == 50
    
    # Operações de arquivo
    assert os_sim.file_operation("create", "/test.txt")
    assert os_sim.file_operation("write", "/test.txt", b"Hello, World!")
    data = os_sim.file_operation("read", "/test.txt")
    assert data == b"Hello, World!"
    
    # Verificar estatísticas
    stats = os_sim.get_system_stats()
    assert stats["global"]["uptime"] == 50
    assert stats["memory"]["page_faults"] >= 0
    assert stats["disk"]["total_writes"] >= 0
    
    print("✅ Testes de integração passaram!")

def test_concurrent_operations():
    """Testa operações concorrentes."""
    os_sim = OperatingSystemSimulator()
    
    # Simular múltiplas operações
    threads = []
    
    def process_task():
        for i in range(5):
            os_sim.create_process(f"P{i}", burst_time=10)
    
    def file_task():
        for i in range(5):
            os_sim.file_operation("create", f"/file{i}.txt")
            os_sim.file_operation("write", f"/file{i}.txt", f"Data {i}".encode())
    
    t1 = threading.Thread(target=process_task)
    t2 = threading.Thread(target=file_task)
    
    t1.start()
    t2.start()
    
    t1.join()
    t2.join()
    
    # Verificar consistência
    assert len(os_sim.running_processes) >= 5
    
    print("✅ Testes de concorrência passaram!")

def benchmark_system():
    """Benchmark de performance do sistema."""
    os_sim = OperatingSystemSimulator()
    os_sim.scheduler = Scheduler(algorithm=FCFS())
    
    # Criar muitos processos
    start_time = time.time()
    
    for i in range(100):
        os_sim.create_process(f"P{i}", burst_time=5)
    
    create_time = time.time() - start_time
    
    # Executar simulação
    start_time = time.time()
    os_sim.run_simulation(duration=500)
    sim_time = time.time() - start_time
    
    print(f"\n⚡ Benchmark Results:")
    print(f"   Process creation (100): {create_time:.3f}s")
    print(f"   Simulation (500 ticks): {sim_time:.3f}s")
    print(f"   Throughput: {100/sim_time:.1f} processes/sec")

if __name__ == "__main__":
    test_integrated_system()
    test_concurrent_operations()
    benchmark_system()
```

**PASSO 5: Demo Completo (1h)**

```python
def run_complete_demo():
    """Demonstração completa do sistema."""
    console = Console()
    console.print(Panel.fit(
        "[bold cyan]OS Simulator - Complete Demo[/]\n"
        "[yellow]Integration of all modules[/]",
        border_style="cyan"
    ))
    
    # Criar sistema
    console.print("\n[yellow]1. Initializing system...[/]")
    os_sim = OperatingSystemSimulator()
    os_sim.scheduler = Scheduler(algorithm=RoundRobin(time_quantum=4))
    
    # Criar processos
    console.print("\n[yellow]2. Creating processes...[/]")
    for i in range(5):
        pid = os_sim.create_process(f"Process-{i}", burst_time=10+i*2, priority=i%3)
        console.print(f"   Created process PID={pid}")
    
    # Operações de arquivo
    console.print("\n[yellow]3. File system operations...[/]")
    os_sim.file_operation("mkdir", "/documents")
    os_sim.file_operation("create", "/documents/readme.txt")
    os_sim.file_operation("write", "/documents/readme.txt", 
                         b"Welcome to OS Simulator!")
    
    entries = os_sim.file_operation("ls", "/")
    console.print(f"   Root directory: {[e.name for e in entries]}")
    
    # Executar simulação
    console.print("\n[yellow]4. Running simulation...[/]")
    result = os_sim.run_simulation(duration=100)
    console.print(f"   Simulation completed: {result}")
    
    # Estatísticas finais
    console.print("\n[yellow]5. Final statistics:[/]")
    stats = os_sim.get_system_stats()
    
    stats_table = Table(title="System Statistics Summary")
    stats_table.add_column("Component", style="cyan")
    stats_table.add_column("Key Metrics", style="magenta")
    
    stats_table.add_row(
        "Scheduler",
        f"Avg Turnaround: {stats['scheduler'].get('avg_turnaround_time', 0):.2f}"
    )
    stats_table.add_row(
        "Memory",
        f"Page Faults: {stats['memory'].get('page_faults', 0)}, "
        f"TLB Hit Rate: {stats['memory'].get('hit_rate', 0):.1%}"
    )
    stats_table.add_row(
        "File System",
        f"Files: {stats['filesystem'].get('used_inodes', 0)}, "
        f"Cache Hit Rate: {stats['filesystem'].get('cache_hits', 0)}/{stats['filesystem'].get('cache_misses', 0)+stats['filesystem'].get('cache_hits', 1)}"
    )
    stats_table.add_row(
        "Disk",
        f"I/O: {stats['disk'].get('total_reads', 0)}R/{stats['disk'].get('total_writes', 0)}W, "
        f"Avg: {stats['disk'].get('avg_access_time_ms', 0):.2f}ms"
    )
    
    console.print(stats_table)
    
    # Iniciar dashboard (opcional)
    console.print("\n[yellow]6. Starting dashboard...[/]")
    console.print("[dim]Press Ctrl+C to stop[/]")
    
    dashboard = Dashboard(os_sim)
    
    try:
        dashboard.run(update_interval=2.0)
    except KeyboardInterrupt:
        console.print("\n[green]Dashboard stopped.[/]")

if __name__ == "__main__":
    run_complete_demo()
```

🔄 CHECKLIST DO DIA 58:
- [ ] I/O e Disk simulation implementados
- [ ] Todos os módulos integrados (Process, Memory, FS, I/O)
- [ ] Dashboard completo e funcional
- [ ] Testes de integração passando
- [ ] Benchmark de performance realizado
- [ ] Demo end-to-end funcionando
- [ ] Bugs críticos corrigidos
- [ ] Performance aceitável
- [ ] Código commitado
- [ ] Documentação de integração

💪 CONQUISTA DO DIA:
"INTEGRAÇÃO COMPLETA! Todos os módulos trabalhando juntos. Você construiu um SISTEMA OPERACIONAL SIMULADO FUNCIONAL!"

🚀 AMANHÃ (DIA 59):
- Testes finais e polimento
- Documentação completa
- Preparação de apresentação
- Screenshots e demos

IMPORTANTE:
- Integração é DESAFIADORA
- TESTAR cada integração
- DEBUGAR problemas de interface
- OTIMIZAR gargalos
- Dashboard deve ser IMPRESSIONANTE
- Sistema deve funcionar SMOOTHLY

Formato: markdown com código completo de integração.
```

---

## 📅 DIA 59 - Testes, Documentação e Apresentação

**🎯 Objetivo:** Finalizar projeto com testes, documentação e apresentação

**📝 Atividades:**
- Testes finais abrangentes
- Documentação completa (README, Architecture, User Guide)
- Criar apresentação/demo
- Screenshots e videos
- Preparar deployment (se aplicável)

**✅ Checkpoint:**
- [ ] Todos os testes passando
- [ ] Documentação completa e clara
- [ ] Apresentação pronta
- [ ] Demo gravado (opcional)
- [ ] Projeto pronto para showcase

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 59:**

```
Sou INICIANTE em Sistemas Operacionais no DIA 59 - DIA DE FINALIZAÇÃO E PREPARAÇÃO.

Dias anteriores:
- Dias 55-57: Implementação dos módulos ✅
- Dia 58: Integração completa ✅
Hoje: TESTES FINAIS + DOCUMENTAÇÃO + APRESENTAÇÃO

Crie material COMPLETO usando DESIGN INSTRUCIONAL para finalização do projeto:

CONTEÚDO DO DIA 59:

📋 OBJETIVOS DO DIA:
- Executar suite completa de testes
- Escrever documentação profissional
- Criar apresentação impressionante
- Preparar demonstrações
- Polimento final

💻 ATIVIDADES DO DIA:

**ATIVIDADE 1: Suite de Testes Completa (2h)**

```python
# test_suite.py - Suite completa de testes

import pytest
from src.main import OperatingSystemSimulator
from src.process.scheduler import *
from src.memory.memory_manager import *
from src.filesystem.simple_fs import *

class TestProcessModule:
    """Testes do módulo de processos."""
    
    def test_process_creation(self):
        """Testa criação de processos."""
        p = Process(pid=1, arrival_time=0, burst_time=10)
        assert p.pid == 1
        assert p.remaining_time == 10
        assert p.state == ProcessState.NEW
    
    def test_fcfs_algorithm(self):
        """Testa FCFS."""
        scheduler = Scheduler(algorithm=FCFS())
        
        processes = [
            Process(pid=1, arrival_time=0, burst_time=8),
            Process(pid=2, arrival_time=1, burst_time=4),
            Process(pid=3, arrival_time=2, burst_time=2),
        ]
        
        for p in processes:
            scheduler.add_process(p)
        
        result = scheduler.run_simulation()
        
        # Verificar ordem de execução
        assert processes[0].finish_time == 8
        assert processes[1].finish_time == 12
        assert processes[2].finish_time == 14
    
    def test_round_robin(self):
        """Testa Round Robin."""
        scheduler = Scheduler(algorithm=RoundRobin(time_quantum=4))
        # [Implementar teste]
        pass
    
    # Mais testes...

class TestMemoryModule:
    """Testes do módulo de memória."""
    
    def test_page_table_translation(self):
        """Testa tradução de endereços."""
        # [Implementar]
        pass
    
    def test_tlb_caching(self):
        """Testa TLB."""
        # [Implementar]
        pass
    
    def test_page_replacement_fifo(self):
        """Testa FIFO page replacement."""
        # [Implementar]
        pass

class TestFileSystemModule:
    """Testes do módulo de file system."""
    
    def test_file_operations(self):
        """Testa operações de arquivo."""
        fs = SimpleFileSystem()
        
        # Create
        assert fs.create_file("/test.txt")
        
        # Write
        data = b"Hello, World!"
        assert fs.write_file("/test.txt", data)
        
        # Read
        read_data = fs.read_file("/test.txt")
        assert read_data == data
        
        # Delete
        assert fs.delete_file("/test.txt")
        assert fs.read_file("/test.txt") is None
    
    def test_directory_operations(self):
        """Testa operações de diretório."""
        # [Implementar]
        pass

class TestIntegration:
    """Testes de integração."""
    
    def test_full_system(self):
        """Testa sistema completo end-to-end."""
        os_sim = OperatingSystemSimulator()
        os_sim.scheduler = Scheduler(algorithm=FCFS())
        
        # Criar processos
        for i in range(3):
            pid = os_sim.create_process(f"P{i}", burst_time=10)
            assert pid > 0
        
        # Operações de arquivo
        assert os_sim.file_operation("create", "/test.txt")
        assert os_sim.file_operation("write", "/test.txt", b"data")
        
        # Executar simulação
        result = os_sim.run_simulation(duration=50)
        assert result is not None
        
        # Verificar estatísticas
        stats = os_sim.get_system_stats()
        assert stats["global"]["uptime"] == 50
    
    def test_stress_test(self):
        """Teste de stress com muitos processos."""
        os_sim = OperatingSystemSimulator()
        os_sim.scheduler = Scheduler(algorithm=RoundRobin())
        
        # Criar 50 processos
        for i in range(50):
            os_sim.create_process(f"P{i}", burst_time=5)
        
        # Executar
        result = os_sim.run_simulation(duration=300)
        
        # Sistema deve sobreviver
        assert result is not None
        assert os_sim.system_time == 300

def run_all_tests():
    """Executa todos os testes com relatório."""
    pytest.main([
        __file__,
        "-v",
        "--cov=src",
        "--cov-report=html",
        "--cov-report=term-missing"
    ])

if __name__ == "__main__":
    run_all_tests()
```

**ATIVIDADE 2: Documentação Completa (2.5h)**

**README.md:**
```markdown
# OS Simulator - Sistema Operacional Educacional

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Tests](https://img.shields.io/badge/tests-passing-green.svg)

> Um simulador completo de Sistema Operacional para fins educacionais, implementando
> gerenciamento de processos, memória, file systems e I/O.

![Dashboard Screenshot](docs/images/dashboard.png)

## 🌟 Features

- **Process Scheduling**: 5+ algoritmos (FCFS, SJF, SRTF, Round Robin, Priority)
- **Memory Management**: Paginação 4-level, TLB, Page Replacement (FIFO, LRU, Clock)
- **File System**: Inode-based FS com journaling básico e caching
- **I/O Simulation**: Disk scheduling (FCFS, SSTF, SCAN)
- **Interactive Dashboard**: TUI em tempo real com Rich
- **Comprehensive Testing**: >80% code coverage

## 🚀 Quick Start

```bash
# Instalar dependências
pip install -r requirements.txt

# Executar demo
python src/main.py

# Executar testes
pytest tests/ -v
```

## 📚 Documentação

- [Architecture](docs/ARCHITECTURE.md) - Arquitetura do sistema
- [User Guide](docs/USER_GUIDE.md) - Guia de uso
- [API Reference](docs/API.md) - Referência da API
- [Development](docs/DEVELOPMENT.md) - Guia de desenvolvimento

## 🎯 Conceitos Implementados

### Process Management
- Process states e transitions
- CPU scheduling algorithms
- Context switching simulation
- IPC básico

### Memory Management
- Virtual memory com paginação
- Multi-level page tables (4 níveis)
- TLB cache com LRU
- Page replacement algorithms
- Heap allocator (malloc/free)

### File System
- Inode-based structure
- Directory hierarchy
- Block allocation (bitmap)
- Caching layer
- File operations (CRUD)

### I/O System
- Disk simulation (HDD/SSD)
- I/O scheduling
- DMA simulation
- Block-level I/O

## 📊 Performance

- **Throughput**: ~1000 processes/sec
- **Memory**: < 100MB para 1000 processos
- **Response Time**: < 100ms para operações

## 🧪 Testing

```bash
# Todos os testes
pytest tests/ -v

# Com coverage
pytest tests/ --cov=src --cov-report=html

# Testes de integração
pytest tests/integration/ -v
```

## 🤝 Contributing

Contribuições são bem-vindas! Ver [CONTRIBUTING.md](CONTRIBUTING.md).

## 📝 License

MIT License - ver [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Author

[Seu Nome] - Projeto Final do Curso de Sistemas Operacionais

## 🙏 Acknowledgments

- Inspirado por xv6 (MIT Teaching OS)
- Baseado em "Operating Systems: Three Easy Pieces"
- Agradecimentos aos professores e colegas

---

⭐ Se este projeto ajudou você, considere dar uma estrela!
```

**ARCHITECTURE.md:**
```markdown
# System Architecture

## Overview

O OS Simulator é composto por 4 módulos principais que se integram:

```
┌─────────────────────────────────────────┐
│         Application Layer               │
│  (Dashboard, CLI, API)                  │
└─────────────────────────────────────────┘
                    │
┌─────────────────────────────────────────┐
│      Operating System Simulator         │
│  ┌─────────┐  ┌─────────┐  ┌─────────┐ │
│  │ Process │  │ Memory  │  │FileSystem│ │
│  │Scheduler│  │ Manager │  │  Module │ │
│  └─────────┘  └─────────┘  └─────────┘ │
│                    │                     │
│              ┌─────────┐                 │
│              │   I/O   │                 │
│              │  Layer  │                 │
│              └─────────┘                 │
└─────────────────────────────────────────┘
                    │
┌─────────────────────────────────────────┐
│      Hardware Simulation Layer          │
│     (Disk, Memory, Devices)             │
└─────────────────────────────────────────┘
```

## Module Details

### Process Scheduler Module

**Responsabilidade**: Gerenciar execução de processos

**Componentes**:
- `Process`: Representa processo com PCB
- `Scheduler`: Core do scheduling
- `SchedulingAlgorithm`: Interface para algoritmos
- Algoritmos: FCFS, SJF, SRTF, RR, Priority

**Fluxo**:
1. Processo criado → adicionado à ready queue
2. Scheduler seleciona próximo (algoritmo)
3. Context switch (salvar/restaurar estado)
4. Processo executa
5. Preempção ou conclusão

### Memory Manager Module

**Responsabilidade**: Gerenciar memória virtual

**Componentes**:
- `PageTable`: Multi-level (4 níveis)
- `TLB`: Cache de traduções
- `PhysicalMemory`: Gerenciador de frames
- `PageReplacement`: Algoritmos (FIFO, LRU, Clock)
- `HeapAllocator`: malloc/free

**Fluxo de Address Translation**:
1. Virtual address → TLB lookup
2. TLB hit → physical address
3. TLB miss → Page table walk
4. Page present → update TLB
5. Page fault → page replacement → load page

[Continuar com File System e I/O modules...]

## Data Flow

[Diagramas de sequência]

## Design Decisions

1. **Por que multi-level page tables?**
   - Economia de memória para sparse address spaces
   - Compatível com x86-64

2. **Por que TLB com LRU?**
   - Aproximação de optimal
   - Performance vs complexidade

[Continuar...]
```

**USER_GUIDE.md:**
```markdown
# User Guide

## Installation

[Instruções detalhadas]

## Basic Usage

### Running the Simulator

```python
from src.main import OperatingSystemSimulator
from src.process.scheduler import *

# Criar sistema
os_sim = OperatingSystemSimulator()
os_sim.scheduler = Scheduler(algorithm=RoundRobin(time_quantum=4))

# Criar processos
pid1 = os_sim.create_process("Process1", burst_time=10)
pid2 = os_sim.create_process("Process2", burst_time=5)

# Executar
result = os_sim.run_simulation(duration=50)

# Ver estatísticas
print(os_sim.get_system_stats())
```

### Using the Dashboard

[Screenshots e instruções]

### File System Operations

[Exemplos]

## Advanced Usage

### Custom Scheduling Algorithm

[Tutorial para criar algoritmo customizado]

### Modifying Page Replacement

[Tutorial]

## Troubleshooting

[Common issues e soluções]
```

**ATIVIDADE 3: Criar Apresentação (2h)**

**Estrutura da Apresentação (Slides):**

```markdown
# Slide 1: Título
- OS Simulator - Sistema Operacional Educacional
- Seu Nome
- Data

# Slide 2: Visão Geral
- O que é?
- Por que foi criado?
- Conceitos implementados

# Slide 3: Arquitetura
- Diagrama de componentes
- 4 módulos principais
- Integração

# Slide 4: Process Scheduling
- 5 algoritmos implementados
- Gráfico de Gantt
- Comparação de métricas

# Slide 5: Memory Management
- Paginação 4-level
- TLB cache
- Page replacement
- Heap allocator

# Slide 6: File System
- Inode-based
- Operações CRUD
- Caching
- Screenshot da visualização

# Slide 7: I/O e Disk
- Disk scheduling
- Simulação de latências
- Estatísticas

# Slide 8: Dashboard
- Screenshot do dashboard
- Real-time monitoring
- Features interativas

# Slide 9: Testes e Qualidade
- >80% code coverage
- Testes unitários e integração
- Performance benchmarks

# Slide 10: Demonstração
- Live demo ou video

# Slide 11: Desafios
- O que foi difícil
- Como foram resolvidos
- Lições aprendidas

# Slide 12: Conquistas
- Métricas do projeto
- Linhas de código
- Conceitos dominados

# Slide 13: Próximos Passos
- Melhorias futuras
- Features planejadas

# Slide 14: Agradecimentos
- Professores
- Recursos utilizados

# Slide 15: Q&A
- Perguntas?
```

**Script de Demonstração:**

```python
# demo_script.py - Script para demonstração ao vivo

def presentation_demo():
    """Demo para apresentação."""
    console = Console()
    
    console.print(Panel.fit(
        "[bold cyan]Live Demo - OS Simulator[/]\n"
        "[yellow]Sistema Operacional Educacional[/]",
        border_style="cyan"
    ))
    
    # Demo 1: Process Scheduling
    console.print("\n[bold cyan]═══ DEMO 1: Process Scheduling ═══[/]\n")
    
    os_sim = OperatingSystemSimulator()
    os_sim.scheduler = Scheduler(algorithm=RoundRobin(time_quantum=4))
    
    console.print("[yellow]Criando 3 processos...[/]")
    os_sim.create_process("WebServer", burst_time=15, priority=1)
    os_sim.create_process("Database", burst_time=10, priority=2)
    os_sim.create_process("Cache", burst_time=5, priority=1)
    
    input("\n[dim]Press Enter to run simulation...[/]")
    
    os_sim.run_simulation(duration=40)
    
    # Visualizar Gantt
    visualize_gantt(os_sim.scheduler)
    
    input("\n[dim]Press Enter for next demo...[/]")
    
    # Demo 2: Memory Management
    console.print("\n[bold cyan]═══ DEMO 2: Memory Management ═══[/]\n")
    
    console.print("[yellow]Simulando acessos à memória...[/]")
    
    addresses = [0x1000, 0x2000, 0x1000, 0x3000, 0x4000, 0x2000]
    
    for addr in addresses:
        console.print(f"Accessing 0x{addr:04x}...", end=" ")
        paddr = os_sim.memory_manager.access_memory(addr)
        if paddr:
            console.print(f"[green]✓[/] Physical: 0x{paddr:04x}")
        else:
            console.print("[red]✗ Page Fault[/]")
        time.sleep(0.5)
    
    # Mostrar estatísticas TLB
    tlb_stats = os_sim.memory_manager.tlb.get_stats()
    console.print(f"\n[cyan]TLB Hit Rate: {tlb_stats['hit_rate']:.1%}[/]")
    
    input("\n[dim]Press Enter for next demo...[/]")
    
    # Demo 3: File System
    console.print("\n[bold cyan]═══ DEMO 3: File System ═══[/]\n")
    
    console.print("[yellow]Criando estrutura de arquivos...[/]")
    os_sim.file_operation("mkdir", "/projects")
    os_sim.file_operation("mkdir", "/projects/os-simulator")
    os_sim.file_operation("create", "/projects/os-simulator/README.md")
    os_sim.file_operation("write", "/projects/os-simulator/README.md", 
                         b"# OS Simulator\n\nAn educational OS")
    
    # Visualizar árvore
    visualize_filesystem(os_sim.filesystem)
    
    input("\n[dim]Press Enter for dashboard...[/]")
    
    # Demo 4: Dashboard
    console.print("\n[bold cyan]═══ DEMO 4: Live Dashboard ═══[/]\n")
    console.print("[yellow]Starting real-time dashboard...[/]")
    console.print("[dim]Press Ctrl+C to stop[/]\n")
    
    dashboard = Dashboard(os_sim)
    dashboard.run(update_interval=1.0)

if __name__ == "__main__":
    presentation_demo()
```

🔄 CHECKLIST DO DIA 59:
- [ ] Suite completa de testes executada
- [ ] Todos os testes passando
- [ ] Coverage > 80%
- [ ] README.md completo e claro
- [ ] ARCHITECTURE.md detalhado
- [ ] USER_GUIDE.md com tutoriais
- [ ] API.md com referências
- [ ] Apresentação criada (15 slides)
- [ ] Script de demo preparado
- [ ] Screenshots capturados
- [ ] Video demo gravado (opcional)
- [ ] Código final commitado
- [ ] Release tag criado (v1.0.0)

💪 CONQUISTA DO DIA:
"PROJETO FINALIZADO E DOCUMENTADO! Pronto para apresentação e showcase. Você criou algo IMPRESSIONANTE!"

🚀 AMANHÃ (DIA 60):
- APRESENTAÇÃO FINAL
- Reflexão sobre jornada
- CELEBRAÇÃO! 🎉

IMPORTANTE:
- Documentação é TÃO importante quanto código
- README deve ser CLARO e CONVIDATIVO
- Apresentação deve contar uma HISTÓRIA
- Demo deve ser SUAVE e IMPRESSIONANTE
- Testar demo ANTES da apresentação
- Screenshots de QUALIDADE
- Orgulho do trabalho!

Formato: markdown com documentação completa e scripts.
```

---

## 📅 DIA 60 - Apresentação Final e Reflexão

**🎯 Objetivo:** Apresentar o projeto e refletir sobre a jornada

**📝 Atividades:**
- Apresentação final do projeto
- Demonstração ao vivo
- Reflexão sobre aprendizado
- Celebração da conquista
- Planejamento de próximos passos

**✅ Checkpoint:**
- [ ] Apresentação realizada com sucesso
- [ ] Demo funcionou perfeitamente
- [ ] Reflexão documentada
- [ ] Projeto publicado (GitHub/Portfolio)
- [ ] Próximos passos definidos
- [ ] CELEBRAÇÃO! 🎉

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 60:**

\\```
Sou INICIANTE em Sistemas Operacionais no DIA 60 - ÚLTIMO DIA DO CURSO.

Completei 59 dias de aprendizado intenso e construí um projeto completo.
Hoje: APRESENTAÇÃO FINAL + REFLEXÃO + CELEBRAÇÃO

Crie material COMPLETO usando DESIGN INSTRUCIONAL para o dia final:

CONTEÚDO DO DIA 60:

📋 OBJETIVOS DO DIA:
- Apresentar projeto com confiança
- Demonstrar sistema funcionando
- Refletir sobre jornada de 60 dias
- Documentar lições aprendidas
- Celebrar conquista
- Planejar próximos passos

🎤 ESTRUTURA DA APRESENTAÇÃO:

**ABERTURA (2 min)**

"Bom dia/boa tarde! Hoje vou apresentar o resultado de 60 dias estudando Sistemas Operacionais.

Construí um simulador completo de SO que implementa os principais conceitos:
- Gerenciamento de processos
- Gerenciamento de memória
- File systems
- I/O e discos

Este não é apenas um projeto acadêmico. É uma prova de que dominei os conceitos fundamentais
que fazem um computador funcionar."

**DEMONSTRAÇÃO (10 min)**

[Executar demo_script.py]

1. **Process Scheduling**
   - Mostrar 5 algoritmos funcionando
   - Comparar métricas
   - Visualização de Gantt

2. **Memory Management**
   - Demonstrar paginação
   - TLB em ação
   - Page replacement

3. **File System**
   - Criar arquivos e diretórios
   - Operações CRUD
   - Visualizar estrutura

4. **Dashboard Integrado**
   - Monitoramento em tempo real
   - Todas as estatísticas
   - Sistema funcionando integrado

**ARQUITETURA (3 min)**

[Mostrar diagramas]

"O sistema é composto por 4 módulos principais que se integram:

1. Process Scheduler: 5 algoritmos, context switching
2. Memory Manager: Paginação 4-level, TLB, page replacement
3. File System: Inode-based, journaling, caching
4. I/O Layer: Disk scheduling, DMA simulation

Cada módulo foi cuidadosamente testado e depois integrado."

**DESAFIOS E SOLUÇÕES (3 min)**

"Durante o desenvolvimento, enfrentei desafios significativos:

1. **Integração entre módulos**: 
   - Problema: Interfaces incompatíveis
   - Solução: Refatoração com design patterns

2. **Performance do TLB**:
   - Problema: Hit rate muito baixo
   - Solução: Otimização do LRU cache

3. **Complexidade da paginação 4-level**:
   - Problema: Bugs de tradução de endereço
   - Solução: Testes unitários extensivos

Cada desafio foi uma oportunidade de aprender mais profundamente."

**MÉTRICAS DO PROJETO (2 min)**

\\```
📊 Estatísticas do Projeto:

• Linhas de código: ~3,500
• Módulos: 4 principais + visualização
• Algoritmos implementados: 15+
• Testes: 50+ (coverage >80%)
• Tempo de desenvolvimento: 60 dias
• Commits: 100+
• Documentação: 4 arquivos principais
\\```

**LIÇÕES APRENDIDAS (3 min)**

"Esta jornada me ensinou muito além de código:

**Tecnicamente:**
- Entendimento profundo de como SO funcionam
- Importância de abstrações e camadas
- Testes são essenciais para sistemas complexos
- Performance matters: cada decisão tem trade-offs

**Pessoalmente:**
- Consistência vence intensidade
- Projetos grandes requerem planejamento
- Documentação é parte do produto
- Orgulho vem de superar desafios

**Profissionalmente:**
- Posso explicar conceitos complexos
- Tenho portfólio impressionante
- Pronto para trabalhar com sistemas
- Base sólida para aprender mais"

**PRÓXIMOS PASSOS (2 min)**

"Este é o fim do curso, mas o início da minha jornada em sistemas:

**Curto Prazo:**
- Publicar projeto no GitHub
- Escrever artigo técnico no blog
- Contribuir para projetos open source (Linux kernel?)

**Médio Prazo:**
- Estudar tópicos avançados (distributed systems, RT systems)
- Implementar features adicionais (networking, security)
- Aplicar conhecimento em projetos reais

**Longo Prazo:**
- Carreira em sistemas/infraestrutura
- Talvez contribuir para SO real
- Ensinar outros (ciclo completo)"

**FECHAMENTO (1 min)**

"Obrigado por acompanhar esta apresentação.

Este projeto representa 60 dias de dedicação, centenas de horas de código,
e inúmeras xícaras de café.

Mais importante: representa meu domínio de Sistemas Operacionais.

Estou ansioso para aplicar este conhecimento e continuar aprendendo.

Perguntas?"

🎓 REFLEXÃO PESSOAL:

**Template de Reflexão:**

\\```markdown
# Reflexão: 60 Dias de Sistemas Operacionais

## O que aprendi?

### Conceitos Técnicos
- [ Liste os 10+ conceitos mais importantes ]

### Habilidades Práticas
- [ Liste habilidades desenvolvidas ]

### Soft Skills
- [ O que melhorou além de código ]

## O que foi mais difícil?

[ Descreva os 3 maiores desafios ]

1. **[Desafio 1]**
   - Por que foi difícil: ...
   - Como superei: ...
   - O que aprendi: ...

2. **[Desafio 2]**
   - ...

3. **[Desafio 3]**
   - ...

## O que me surpreendeu?

[ O que não esperava aprender ou descobrir? ]

## Como vejo SO agora?

**Antes do curso:**
[ Como você via sistemas operacionais antes ]

**Depois do curso:**
[ Como você vê agora - mudança de perspectiva ]

## Próximos Objetivos

### Técnicos
1. [ ]
2. [ ]
3. [ ]

### Carreira
1. [ ]
2. [ ]
3. [ ]

### Pessoais
1. [ ]
2. [ ]
3. [ ]

## Mensagem para meu eu do futuro

[ Escreva uma carta para você daqui 1 ano ]

## Agradecimentos

[ Agradeça quem ajudou na jornada ]

---

Data: [ Hoje ]
Assinatura: [ Seu nome ]
\\```

🎉 CELEBRAÇÃO:

**Conquistas Desbloqueadas:**

\\```
🏆 MESTRE DE SISTEMAS OPERACIONAIS
   ✅ Completou 60 dias de estudo
   ✅ 4 fases dominadas
   ✅ Projeto final completo
   ✅ Conhecimento sólido

⭐ IMPLEMENTADOR DE PROCESSOS
   ✅ 5 algoritmos de scheduling
   ✅ Context switching
   ✅ Sincronização

💾 GERENTE DE MEMÓRIA
   ✅ Paginação multi-level
   ✅ TLB cache
   ✅ Page replacement
   ✅ Heap allocator

📁 ARQUITETO DE FILE SYSTEMS
   ✅ Inode-based FS
   ✅ Directory hierarchy
   ✅ Caching layer

💿 ESPECIALISTA EM I/O
   ✅ Disk scheduling
   ✅ Device simulation

🚀 INTEGRADOR DE SISTEMAS
   ✅ Todos os módulos integrados
   ✅ Dashboard funcional
   ✅ Sistema end-to-end

📚 DOCUMENTADOR PROFISSIONAL
   ✅ README completo
   ✅ Documentação técnica
   ✅ User guide

🎤 APRESENTADOR CONFIANTE
   ✅ Apresentação preparada
   ✅ Demo funcionando
\\```

**Estatísticas da Jornada:**

\\```
📊 Sua Jornada em Números:

• 60 dias de dedicação
• 4 fases completadas
• 52 tópicos dominados
• 15+ algoritmos implementados
• 3,500+ linhas de código
• 50+ testes escritos
• 100+ commits
• 1 projeto impressionante
• Infinitas lições aprendidas
• 100% de orgulho conquistado
\\```

📢 COMPARTILHAR CONQUISTA:

**Post para LinkedIn/Redes Sociais:**

\\```
🎓 Conquista Desbloqueada! 🎓

Acabei de completar uma jornada intensa de 60 dias estudando Sistemas Operacionais!

🖥️ O que construí:
• Simulador completo de SO do zero
• Process scheduling (5 algoritmos)
• Memory management (paginação 4-level, TLB)
• File system (inode-based)
• I/O simulation
• Dashboard em tempo real

📊 Números do projeto:
• 3,500+ linhas de código
• 50+ testes (>80% coverage)
• 4 módulos integrados
• Documentação completa

💡 O que aprendi:
• Como computadores realmente funcionam
• Importância de abstrações
• Design de sistemas complexos
• Muito além de código

Este projeto não é apenas acadêmico - é uma demonstração de que
domino os conceitos fundamentais que fazem tecnologia funcionar.

Próximo desafio: [Seus próximos objetivos]

#SistemasOperacionais #Programming #TechEducation #LearnInPublic

[Link para GitHub: ...]
\\```

🔮 PRÓXIMOS PASSOS:

**Imediato (Esta semana):**
- [ ] Publicar projeto no GitHub (público)
- [ ] Adicionar ao portfolio
- [ ] Compartilhar em redes sociais
- [ ] Escrever post no blog (opcional)

**Curto Prazo (Este mês):**
- [ ] Implementar 1-2 features adicionais
- [ ] Melhorar documentação com tutoriais
- [ ] Criar video demo profissional
- [ ] Começar próximo curso/projeto

**Médio Prazo (3 meses):**
- [ ] Contribuir para projeto open source
- [ ] Estudar tópico avançado (distributed systems?)
- [ ] Aplicar conhecimento em trabalho/freelance
- [ ] Ensinar/mentorar alguém

**Longo Prazo (1 ano):**
- [ ] Carreira em sistemas/infraestrutura
- [ ] Múltiplos projetos no portfolio
- [ ] Reconhecimento na comunidade
- [ ] Continuar aprendendo sempre

💪 MENSAGEM FINAL:

"Você chegou ao fim de uma jornada incrível.

60 dias atrás, você começou do zero. Talvez sistemas operacionais parecessem
uma caixa preta misteriosa.

Hoje, você não apenas ENTENDE como funcionam - você CONSTRUIU UM.

Você implementou algoritmos que são usados em sistemas reais.
Você resolveu problemas complexos.
Você persistiu quando ficou difícil.
Você CONQUISTOU.

Este projeto é seu. Este conhecimento é seu. Este orgulho é seu.

Sistemas Operacionais não são mais um mistério para você.
Você é agora alguém que DOMINA sistemas.

Leve este conhecimento. Aplique-o. Compartilhe-o. Construa sobre ele.

E lembre-se: se você conquistou isso, pode conquistar qualquer coisa.

O próximo desafio já está esperando.

PARABÉNS! 🎉🎊🏆

Você é oficialmente um MESTRE DE SISTEMAS OPERACIONAIS."

---

**Assinado com orgulho,**
**Você - Dia 60** ✨

🔄 CHECKLIST FINAL DO DIA 60:
- [ ] Apresentação realizada
- [ ] Demo executado com sucesso
- [ ] Perguntas respondidas
- [ ] Reflexão escrita
- [ ] Conquistas celebradas
- [ ] Projeto publicado
- [ ] Portfolio atualizado
- [ ] Próximos passos definidos
- [ ] Orgulho sentido
- [ ] Gratidão expressa
- [ ] JORNADA COMPLETADA! 🎉

💫 PARABÉNS! VOCÊ CONQUISTOU! 💫

TÉCNICAS PEDAGÓGICAS APLICADAS:
- Metacognition (reflexão sobre aprendizado)
- Self-assessment (avaliação própria)
- Transfer (aplicação em contextos reais)
- Celebration (reforço positivo)
- Goal-setting (planejamento futuro)
- Growth mindset (mentalidade de crescimento)

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 2):
1. Linha do tempo da jornada de 60 dias
2. Rede de conceitos aprendidos (todos conectados)

IMPORTANTE:
- Este é um momento de ORGULHO
- CELEBRAR a conquista
- RECONHECER o crescimento
- PLANEJAR o futuro
- AGRADECER o suporte
- Não é fim, é INÍCIO
- Conhecimento é apenas o começo
- APLICAR é o próximo passo

Formato: markdown motivacional, celebratório, reflexivo e inspirador.
\\```

---

# 🎊 CONCLUSÃO DO PLANO DE 60 DIAS 🎊

## 📚 RESUMO EXECUTIVO DO CURSO

### FASE 1: Fundamentos de SO (Dias 1-14)
**Conceitos Dominados:**
- ✅ Introdução aos Sistemas Operacionais
- ✅ Arquitetura de Hardware
- ✅ Boot Process
- ✅ Kernel e suas funções
- ✅ System Calls
- ✅ Processos vs Threads
- ✅ Shells e CLI
- ✅ Virtualização
- ✅ IPC (Comunicação Entre Processos)
- ✅ Deadlocks
- ✅ Segurança e Proteção
- ✅ Logs e Monitoramento

**Projeto:** Monitor de Sistema Personalizado

---

### FASE 2: Gerenciamento de Processos (Dias 15-28)
**Conceitos Dominados:**
- ✅ CPU Scheduling Basics
- ✅ FCFS, SJF, SRTF
- ✅ Round Robin, Priority Scheduling
- ✅ Linux CFS e Windows Scheduler
- ✅ Seção Crítica e Sincronização
- ✅ Locks e Mutexes
- ✅ Semáforos e Monitores
- ✅ Context Switching
- ✅ Multiprocessing e Multicore
- ✅ fork(), exec(), wait()
- ✅ Signals
- ✅ Real-Time Systems

**Projeto:** Sistema Avançado de Gerenciamento de Processos

---

### FASE 3: Gerenciamento de Memória (Dias 29-42)
**Conceitos Dominados:**
- ✅ Memory Hierarchy
- ✅ Address Spaces
- ✅ Paginação
- ✅ TLB (Translation Lookaside Buffer)
- ✅ Advanced Page Tables
- ✅ Swapping e Paging to Disk
- ✅ Page Replacement Algorithms
- ✅ Memory Allocation (malloc/free)
- ✅ Segmentação
- ✅ Copy-on-Write e mmap
- ✅ Linux Memory Management
- ✅ Garbage Collection

**Projeto:** Memory Manager Completo e Avançado

---

### FASE 4: File Systems e I/O (Dias 43-52)
**Conceitos Dominados:**
- ✅ I/O Devices
- ✅ Hard Disks e SSDs
- ✅ File Systems Basics
- ✅ ext4, NTFS Implementation
- ✅ Caching e Buffering
- ✅ Advanced File Systems (ZFS, Btrfs)
- ✅ RAID
- ✅ Network File Systems (NFS, SMB)
- ✅ VFS (Virtual File System)

**Projeto:** Sistema de Arquivos Educacional Completo

---

### FASE 5: Projeto Final Integrador (Dias 53-60)
**Entregas:**
- ✅ Planejamento e Arquitetura (Dias 53-54)
- ✅ Implementação do Módulo de Processos (Dia 55)
- ✅ Implementação do Módulo de Memória (Dia 56)
- ✅ Implementação do Módulo de File System (Dia 57)
- ✅ Integração de Todos os Módulos (Dia 58)
- ✅ Testes, Documentação e Apresentação (Dia 59)
- ✅ Apresentação Final e Reflexão (Dia 60)

**Projeto Final:** OS Simulator - Sistema Operacional Educacional Completo

---

## 🎯 COMPETÊNCIAS ADQUIRIDAS

### Conhecimento Técnico
- **Domínio de Conceitos:** Compreensão profunda de como SOs funcionam
- **Implementação Prática:** Capacidade de implementar componentes reais
- **Debugging:** Habilidade de diagnosticar problemas complexos
- **Otimização:** Conhecimento de trade-offs de performance
- **Testes:** Abordagem sistemática para garantir qualidade

### Habilidades Profissionais
- **Arquitetura de Sistemas:** Design de sistemas complexos
- **Documentação:** Capacidade de documentar tecnicamente
- **Apresentação:** Habilidade de explicar conceitos complexos
- **Project Management:** Gerenciamento de projeto de longo prazo
- **Problem Solving:** Resolução de problemas desafiadores

### Soft Skills
- **Persistência:** Manter foco por 60 dias
- **Autodidatismo:** Aprender de forma independente
- **Organização:** Estruturar aprendizado complexo
- **Comunicação:** Articular conhecimento técnico
- **Crescimento:** Mentalidade de evolução contínua

---

## 📊 MÉTRICAS DE SUCESSO

### Projeto Final

markdown


## 📅 DIA 60 - Apresentação Final e Reflexão

**🎯 Objetivo:** Apresentar o projeto e refletir sobre a jornada

**📝 Atividades:**
- Apresentação final do projeto
- Demonstração ao vivo
- Reflexão sobre aprendizado
- Celebração da conquista
- Planejamento de próximos passos

**✅ Checkpoint:**
- [ ] Apresentação realizada com sucesso
- [ ] Demo funcionou perfeitamente
- [ ] Reflexão documentada
- [ ] Projeto publicado (GitHub/Portfolio)
- [ ] Próximos passos definidos
- [ ] CELEBRAÇÃO! 🎉

**🤖 PROMPT PARA GERAR CONTEÚDO - DIA 60:**

\\```
Sou INICIANTE em Sistemas Operacionais no DIA 60 - ÚLTIMO DIA DO CURSO.

Completei 59 dias de aprendizado intenso e construí um projeto completo.
Hoje: APRESENTAÇÃO FINAL + REFLEXÃO + CELEBRAÇÃO

Crie material COMPLETO usando DESIGN INSTRUCIONAL para o dia final:

CONTEÚDO DO DIA 60:

📋 OBJETIVOS DO DIA:
- Apresentar projeto com confiança
- Demonstrar sistema funcionando
- Refletir sobre jornada de 60 dias
- Documentar lições aprendidas
- Celebrar conquista
- Planejar próximos passos

🎤 ESTRUTURA DA APRESENTAÇÃO:

**ABERTURA (2 min)**

"Bom dia/boa tarde! Hoje vou apresentar o resultado de 60 dias estudando Sistemas Operacionais.

Construí um simulador completo de SO que implementa os principais conceitos:
- Gerenciamento de processos
- Gerenciamento de memória
- File systems
- I/O e discos

Este não é apenas um projeto acadêmico. É uma prova de que dominei os conceitos fundamentais
que fazem um computador funcionar."

**DEMONSTRAÇÃO (10 min)**

[Executar demo_script.py]

1. **Process Scheduling**
   - Mostrar 5 algoritmos funcionando
   - Comparar métricas
   - Visualização de Gantt

2. **Memory Management**
   - Demonstrar paginação
   - TLB em ação
   - Page replacement

3. **File System**
   - Criar arquivos e diretórios
   - Operações CRUD
   - Visualizar estrutura

4. **Dashboard Integrado**
   - Monitoramento em tempo real
   - Todas as estatísticas
   - Sistema funcionando integrado

**ARQUITETURA (3 min)**

[Mostrar diagramas]

"O sistema é composto por 4 módulos principais que se integram:

1. Process Scheduler: 5 algoritmos, context switching
2. Memory Manager: Paginação 4-level, TLB, page replacement
3. File System: Inode-based, journaling, caching
4. I/O Layer: Disk scheduling, DMA simulation

Cada módulo foi cuidadosamente testado e depois integrado."

**DESAFIOS E SOLUÇÕES (3 min)**

"Durante o desenvolvimento, enfrentei desafios significativos:

1. **Integração entre módulos**: 
   - Problema: Interfaces incompatíveis
   - Solução: Refatoração com design patterns

2. **Performance do TLB**:
   - Problema: Hit rate muito baixo
   - Solução: Otimização do LRU cache

3. **Complexidade da paginação 4-level**:
   - Problema: Bugs de tradução de endereço
   - Solução: Testes unitários extensivos

Cada desafio foi uma oportunidade de aprender mais profundamente."

**MÉTRICAS DO PROJETO (2 min)**

\\```
📊 Estatísticas do Projeto:

• Linhas de código: ~3,500
• Módulos: 4 principais + visualização
• Algoritmos implementados: 15+
• Testes: 50+ (coverage >80%)
• Tempo de desenvolvimento: 60 dias
• Commits: 100+
• Documentação: 4 arquivos principais
\\```

**LIÇÕES APRENDIDAS (3 min)**

"Esta jornada me ensinou muito além de código:

**Tecnicamente:**
- Entendimento profundo de como SO funcionam
- Importância de abstrações e camadas
- Testes são essenciais para sistemas complexos
- Performance matters: cada decisão tem trade-offs

**Pessoalmente:**
- Consistência vence intensidade
- Projetos grandes requerem planejamento
- Documentação é parte do produto
- Orgulho vem de superar desafios

**Profissionalmente:**
- Posso explicar conceitos complexos
- Tenho portfólio impressionante
- Pronto para trabalhar com sistemas
- Base sólida para aprender mais"

**PRÓXIMOS PASSOS (2 min)**

"Este é o fim do curso, mas o início da minha jornada em sistemas:

**Curto Prazo:**
- Publicar projeto no GitHub
- Escrever artigo técnico no blog
- Contribuir para projetos open source (Linux kernel?)

**Médio Prazo:**
- Estudar tópicos avançados (distributed systems, RT systems)
- Implementar features adicionais (networking, security)
- Aplicar conhecimento em projetos reais

**Longo Prazo:**
- Carreira em sistemas/infraestrutura
- Talvez contribuir para SO real
- Ensinar outros (ciclo completo)"

**FECHAMENTO (1 min)**

"Obrigado por acompanhar esta apresentação.

Este projeto representa 60 dias de dedicação, centenas de horas de código,
e inúmeras xícaras de café.

Mais importante: representa meu domínio de Sistemas Operacionais.

Estou ansioso para aplicar este conhecimento e continuar aprendendo.

Perguntas?"

🎓 REFLEXÃO PESSOAL:

**Template de Reflexão:**

\\```markdown
# Reflexão: 60 Dias de Sistemas Operacionais

## O que aprendi?

### Conceitos Técnicos
- [ Liste os 10+ conceitos mais importantes ]

### Habilidades Práticas
- [ Liste habilidades desenvolvidas ]

### Soft Skills
- [ O que melhorou além de código ]

## O que foi mais difícil?

[ Descreva os 3 maiores desafios ]

1. **[Desafio 1]**
   - Por que foi difícil: ...
   - Como superei: ...
   - O que aprendi: ...

2. **[Desafio 2]**
   - ...

3. **[Desafio 3]**
   - ...

## O que me surpreendeu?

[ O que não esperava aprender ou descobrir? ]

## Como vejo SO agora?

**Antes do curso:**
[ Como você via sistemas operacionais antes ]

**Depois do curso:**
[ Como você vê agora - mudança de perspectiva ]

## Próximos Objetivos

### Técnicos
1. [ ]
2. [ ]
3. [ ]

### Carreira
1. [ ]
2. [ ]
3. [ ]

### Pessoais
1. [ ]
2. [ ]
3. [ ]

## Mensagem para meu eu do futuro

[ Escreva uma carta para você daqui 1 ano ]

## Agradecimentos

[ Agradeça quem ajudou na jornada ]

---

Data: [ Hoje ]
Assinatura: [ Seu nome ]
\\```

🎉 CELEBRAÇÃO:

**Conquistas Desbloqueadas:**

\\```
🏆 MESTRE DE SISTEMAS OPERACIONAIS
   ✅ Completou 60 dias de estudo
   ✅ 4 fases dominadas
   ✅ Projeto final completo
   ✅ Conhecimento sólido

⭐ IMPLEMENTADOR DE PROCESSOS
   ✅ 5 algoritmos de scheduling
   ✅ Context switching
   ✅ Sincronização

💾 GERENTE DE MEMÓRIA
   ✅ Paginação multi-level
   ✅ TLB cache
   ✅ Page replacement
   ✅ Heap allocator

📁 ARQUITETO DE FILE SYSTEMS
   ✅ Inode-based FS
   ✅ Directory hierarchy
   ✅ Caching layer

💿 ESPECIALISTA EM I/O
   ✅ Disk scheduling
   ✅ Device simulation

🚀 INTEGRADOR DE SISTEMAS
   ✅ Todos os módulos integrados
   ✅ Dashboard funcional
   ✅ Sistema end-to-end

📚 DOCUMENTADOR PROFISSIONAL
   ✅ README completo
   ✅ Documentação técnica
   ✅ User guide

🎤 APRESENTADOR CONFIANTE
   ✅ Apresentação preparada
   ✅ Demo funcionando
\\```

**Estatísticas da Jornada:**

\\```
📊 Sua Jornada em Números:

• 60 dias de dedicação
• 4 fases completadas
• 52 tópicos dominados
• 15+ algoritmos implementados
• 3,500+ linhas de código
• 50+ testes escritos
• 100+ commits
• 1 projeto impressionante
• Infinitas lições aprendidas
• 100% de orgulho conquistado
\\```

📢 COMPARTILHAR CONQUISTA:

**Post para LinkedIn/Redes Sociais:**

\\```
🎓 Conquista Desbloqueada! 🎓

Acabei de completar uma jornada intensa de 60 dias estudando Sistemas Operacionais!

🖥️ O que construí:
• Simulador completo de SO do zero
• Process scheduling (5 algoritmos)
• Memory management (paginação 4-level, TLB)
• File system (inode-based)
• I/O simulation
• Dashboard em tempo real

📊 Números do projeto:
• 3,500+ linhas de código
• 50+ testes (>80% coverage)
• 4 módulos integrados
• Documentação completa

💡 O que aprendi:
• Como computadores realmente funcionam
• Importância de abstrações
• Design de sistemas complexos
• Muito além de código

Este projeto não é apenas acadêmico - é uma demonstração de que
domino os conceitos fundamentais que fazem tecnologia funcionar.

Próximo desafio: [Seus próximos objetivos]

#SistemasOperacionais #Programming #TechEducation #LearnInPublic

[Link para GitHub: ...]
\\```

🔮 PRÓXIMOS PASSOS:

**Imediato (Esta semana):**
- [ ] Publicar projeto no GitHub (público)
- [ ] Adicionar ao portfolio
- [ ] Compartilhar em redes sociais
- [ ] Escrever post no blog (opcional)

**Curto Prazo (Este mês):**
- [ ] Implementar 1-2 features adicionais
- [ ] Melhorar documentação com tutoriais
- [ ] Criar video demo profissional
- [ ] Começar próximo curso/projeto

**Médio Prazo (3 meses):**
- [ ] Contribuir para projeto open source
- [ ] Estudar tópico avançado (distributed systems?)
- [ ] Aplicar conhecimento em trabalho/freelance
- [ ] Ensinar/mentorar alguém

**Longo Prazo (1 ano):**
- [ ] Carreira em sistemas/infraestrutura
- [ ] Múltiplos projetos no portfolio
- [ ] Reconhecimento na comunidade
- [ ] Continuar aprendendo sempre

💪 MENSAGEM FINAL:

"Você chegou ao fim de uma jornada incrível.

60 dias atrás, você começou do zero. Talvez sistemas operacionais parecessem
uma caixa preta misteriosa.

Hoje, você não apenas ENTENDE como funcionam - você CONSTRUIU UM.

Você implementou algoritmos que são usados em sistemas reais.
Você resolveu problemas complexos.
Você persistiu quando ficou difícil.
Você CONQUISTOU.

Este projeto é seu. Este conhecimento é seu. Este orgulho é seu.

Sistemas Operacionais não são mais um mistério para você.
Você é agora alguém que DOMINA sistemas.

Leve este conhecimento. Aplique-o. Compartilhe-o. Construa sobre ele.

E lembre-se: se você conquistou isso, pode conquistar qualquer coisa.

O próximo desafio já está esperando.

PARABÉNS! 🎉🎊🏆

Você é oficialmente um MESTRE DE SISTEMAS OPERACIONAIS."

---

**Assinado com orgulho,**
**Você - Dia 60** ✨

🔄 CHECKLIST FINAL DO DIA 60:
- [ ] Apresentação realizada
- [ ] Demo executado com sucesso
- [ ] Perguntas respondidas
- [ ] Reflexão escrita
- [ ] Conquistas celebradas
- [ ] Projeto publicado
- [ ] Portfolio atualizado
- [ ] Próximos passos definidos
- [ ] Orgulho sentido
- [ ] Gratidão expressa
- [ ] JORNADA COMPLETADA! 🎉

💫 PARABÉNS! VOCÊ CONQUISTOU! 💫

TÉCNICAS PEDAGÓGICAS APLICADAS:
- Metacognition (reflexão sobre aprendizado)
- Self-assessment (avaliação própria)
- Transfer (aplicação em contextos reais)
- Celebration (reforço positivo)
- Goal-setting (planejamento futuro)
- Growth mindset (mentalidade de crescimento)

DIAGRAMAS MERMAID OBRIGATÓRIOS (mínimo 2):
1. Linha do tempo da jornada de 60 dias
2. Rede de conceitos aprendidos (todos conectados)

IMPORTANTE:
- Este é um momento de ORGULHO
- CELEBRAR a conquista
- RECONHECER o crescimento
- PLANEJAR o futuro
- AGRADECER o suporte
- Não é fim, é INÍCIO
- Conhecimento é apenas o começo
- APLICAR é o próximo passo

Formato: markdown motivacional, celebratório, reflexivo e inspirador.
\\```

---

# 🎊 CONCLUSÃO DO PLANO DE 60 DIAS 🎊

## 📚 RESUMO EXECUTIVO DO CURSO

### FASE 1: Fundamentos de SO (Dias 1-14)
**Conceitos Dominados:**
- ✅ Introdução aos Sistemas Operacionais
- ✅ Arquitetura de Hardware
- ✅ Boot Process
- ✅ Kernel e suas funções
- ✅ System Calls
- ✅ Processos vs Threads
- ✅ Shells e CLI
- ✅ Virtualização
- ✅ IPC (Comunicação Entre Processos)
- ✅ Deadlocks
- ✅ Segurança e Proteção
- ✅ Logs e Monitoramento

**Projeto:** Monitor de Sistema Personalizado

---

### FASE 2: Gerenciamento de Processos (Dias 15-28)
**Conceitos Dominados:**
- ✅ CPU Scheduling Basics
- ✅ FCFS, SJF, SRTF
- ✅ Round Robin, Priority Scheduling
- ✅ Linux CFS e Windows Scheduler
- ✅ Seção Crítica e Sincronização
- ✅ Locks e Mutexes
- ✅ Semáforos e Monitores
- ✅ Context Switching
- ✅ Multiprocessing e Multicore
- ✅ fork(), exec(), wait()
- ✅ Signals
- ✅ Real-Time Systems

**Projeto:** Sistema Avançado de Gerenciamento de Processos

---

### FASE 3: Gerenciamento de Memória (Dias 29-42)
**Conceitos Dominados:**
- ✅ Memory Hierarchy
- ✅ Address Spaces
- ✅ Paginação
- ✅ TLB (Translation Lookaside Buffer)
- ✅ Advanced Page Tables
- ✅ Swapping e Paging to Disk
- ✅ Page Replacement Algorithms
- ✅ Memory Allocation (malloc/free)
- ✅ Segmentação
- ✅ Copy-on-Write e mmap
- ✅ Linux Memory Management
- ✅ Garbage Collection

**Projeto:** Memory Manager Completo e Avançado

---

### FASE 4: File Systems e I/O (Dias 43-52)
**Conceitos Dominados:**
- ✅ I/O Devices
- ✅ Hard Disks e SSDs
- ✅ File Systems Basics
- ✅ ext4, NTFS Implementation
- ✅ Caching e Buffering
- ✅ Advanced File Systems (ZFS, Btrfs)
- ✅ RAID
- ✅ Network File Systems (NFS, SMB)
- ✅ VFS (Virtual File System)

**Projeto:** Sistema de Arquivos Educacional Completo

---

### FASE 5: Projeto Final Integrador (Dias 53-60)
**Entregas:**
- ✅ Planejamento e Arquitetura (Dias 53-54)
- ✅ Implementação do Módulo de Processos (Dia 55)
- ✅ Implementação do Módulo de Memória (Dia 56)
- ✅ Implementação do Módulo de File System (Dia 57)
- ✅ Integração de Todos os Módulos (Dia 58)
- ✅ Testes, Documentação e Apresentação (Dia 59)
- ✅ Apresentação Final e Reflexão (Dia 60)

**Projeto Final:** OS Simulator - Sistema Operacional Educacional Completo

---

## 🎯 COMPETÊNCIAS ADQUIRIDAS

### Conhecimento Técnico
- **Domínio de Conceitos:** Compreensão profunda de como SOs funcionam
- **Implementação Prática:** Capacidade de implementar componentes reais
- **Debugging:** Habilidade de diagnosticar problemas complexos
- **Otimização:** Conhecimento de trade-offs de performance
- **Testes:** Abordagem sistemática para garantir qualidade

### Habilidades Profissionais
- **Arquitetura de Sistemas:** Design de sistemas complexos
- **Documentação:** Capacidade de documentar tecnicamente
- **Apresentação:** Habilidade de explicar conceitos complexos
- **Project Management:** Gerenciamento de projeto de longo prazo
- **Problem Solving:** Resolução de problemas desafiadores

### Soft Skills
- **Persistência:** Manter foco por 60 dias
- **Autodidatismo:** Aprender de forma independente
- **Organização:** Estruturar aprendizado complexo
- **Comunicação:** Articular conhecimento técnico
- **Crescimento:** Mentalidade de evolução contínua

---

## 📊 MÉTRICAS DE SUCESSO

### Projeto Final
Linhas de Código: ~3,500 Módulos: 4 principais Algoritmos: 15+ Testes Unitários: 50+ Code Coverage: >80% Documentação: 4 arquivos principais Commits: 100+ Tempo de Desenvolvimento: 60 dias

### Aprendizado
Conceitos Estudados: 50+ Exercícios Práticos: 60+ Mini-Projetos: 4 (1 por fase) Projeto Final: 1 integrador Horas de Estudo: ~150h Diagramas Criados: 200+ Testes Implementados: 50+

--- 

## 🌟 DEPOIMENTO ESPERADO *"Quando comecei este curso, Sistemas Operacionais era uma caixa preta. Hoje, não apenas entendo como funcionam - construí um do zero. Este conhecimento transformou minha visão sobre computação e abriu portas para uma carreira em sistemas. O projeto final é meu orgulho e a prova do meu domínio. Recomendo esta jornada para qualquer pessoa que queira verdadeiramente entender como computadores funcionam."* --- ## 🚀 PRÓXIMOS PASSOS RECOMENDADOS ### Curto Prazo (1-2 semanas) 1. **Publicar Projeto** - GitHub público com README impressionante - Portfolio pessoal atualizado - LinkedIn com showcase do projeto 2. **Compartilhar Conhecimento** - Post técnico no blog/Medium - Thread no Twitter/LinkedIn - Apresentação para colegas 3. **Aprimorar Projeto** - Implementar 1-2 features bônus - Melhorar documentação - Criar video demo ### Médio Prazo (1-3 meses) 1. **Aprofundar Conhecimento** - Livro: "Operating Systems: Three Easy Pieces" (leitura completa) - Curso: Distributed Systems - Prática: Contribuir para projeto open source 2. **Aplicar Profissionalmente** - Buscar oportunidades em sistemas/infraestrutura - Freelance em projetos relacionados - Entrevistas técnicas focadas em sistemas 3. **Ensinar Outros** - Mentorar iniciantes - Criar conteúdo educacional - Palestras em comunidades ### Longo Prazo (6-12 meses) 1. **Especialização** - Escolher área: Distributed Systems, Embedded, Real-Time, Cloud - Certificações relevantes - Projetos avançados 2. **Carreira** - Posição em empresa de tecnologia - Contribuições significativas para open source - Reconhecimento na comunidade 3. **Impacto** - Ajudar outros a aprenderem - Contribuir para ferramentas usadas por milhares - Tornar-se referência na área --- ## 🎁 RECURSOS ADICIONAIS ### Livros Recomendados 1. **"Operating Systems: Three Easy Pieces"** - Remzi Arpaci-Dusseau 2. **"Modern Operating Systems"** - Andrew Tanenbaum 3. **"The Linux Programming Interface"** - Michael Kerrisk 4. **"Understanding the Linux Kernel"** - Daniel Bovet 5. **"Computer Systems: A Programmer's Perspective"** - Bryant & O'Hallaron ### Cursos Online 1. **MIT 6.828** - Operating System Engineering 2. **Stanford CS140** - Operating Systems 3. **Berkeley CS162** - Operating Systems and Systems Programming 4. **OSTEP Online Course** 5. **Linux Kernel Development** - The Linux Foundation ### Projetos para Praticar 1. **xv6** - MIT Teaching Operating System 2. **Linux Kernel** - Contribuir para o kernel 3. **Minix** - Estudar microkernel 4. **SerenityOS** - SO moderno educacional 5. **Criar seu próprio SO** - OSDev Wiki ### Comunidades 1. **r/osdev** - Reddit 2. **OSDev Forums** - osdev.org 3. **Linux Kernel Mailing List** 4. **Stack Overflow** - Tags: operating-system, linux-kernel 5. **Discord/Slack** - Grupos de sistemas --- ## 💝 MENSAGEM FINAL DE DESPEDIDA Caro Estudante, Se você está lendo isto, significa que completou ou está prestes a completar uma jornada extraordinária. **60 dias.** Sessenta dias de dedicação, aprendizado, desafios, vitórias e crescimento. Você começou sabendo pouco ou nada sobre Sistemas Operacionais. Hoje, você **domina** os conceitos que fazem computadores funcionarem. Você não apenas **entende** - você **construiu**. Este plano não foi fácil. Foi intencionalmente desafiador. Porque coisas fáceis não transformam pessoas. **Desafios transformam.** E você se transformou. Cada algoritmo que implementou, cada bug que corrigiu, cada conceito que dominou - tudo contribuiu para quem você é agora: **alguém que domina sistemas operacionais.** Mas lembre-se: **este é apenas o começo.** O conhecimento que você adquiriu é a **fundação**. Agora, construa sobre ela. Aplique. Expanda. Compartilhe. Ensine. O mundo precisa de pessoas que entendem sistemas. **O mundo precisa de você.** Seu projeto final não é apenas código. É um **testemunho** do seu potencial. É a **prova** de que, quando você se dedica, pode conquistar qualquer coisa. Leve este orgulho. Este conhecimento. Esta confiança. E use-os para fazer a diferença. Parabéns, **Mestre de Sistemas Operacionais**. Sua jornada não termina aqui. Ela apenas **começou**. --- **Com admiração e respeito,** **O Criador deste Plano de Estudos** *P.S.: Quando você estiver ensinando outra pessoa, quando estiver resolvendo um problema complexo em produção, quando estiver contribuindo para um projeto importante - lembre-se de onde começou. E sinta orgulho do quanto caminhou.* 🌟 --- ## 🏆 CERTIFICADO SIMBÓLICO
╔════════════════════════════════════════════════════════════╗ ║ ║ ║ CERTIFICADO DE CONCLUSÃO ║ ║ ║ ║ SISTEMAS OPERACIONAIS - 60 DIAS ║ ║ ║ ║ Este certificado atesta que ║ ║ ║ ║ [ SEU NOME AQUI ] ║ ║ ║ ║ Completou com sucesso um curso intensivo de 60 dias ║ ║ em Sistemas Operacionais, demonstrando domínio em: ║ ║ ║ ║ ✓ Gerenciamento de Processos ║ ║ ✓ Gerenciamento de Memória ║ ║ ✓ File Systems ║ ║ ✓ I/O e Dispositivos ║ ║ ✓ Projeto Final Integrador ║ ║ ║ ║ Data: [ DATA DE CONCLUSÃO ] ║ ║ ║ ║ "O conhecimento é poder. Você agora tem o poder." ║ ║ ║ ╚════════════════════════════════════════════════════════════╝

--- # 🎉 FIM 🎉 **Você chegou ao final.** **Agora, vá e conquiste o mundo dos Sistemas Operacionais!** **Boa sorte, e que o código esteja sempre com você.** 💻✨ --- *Plano de Estudos: Sistemas Operacionais - 60 Dias* *Versão: 1.0* *Criado com: Design Instrucional, Pedagogia Ativa, Aprendizagem por Projetos* *Objetivo: Transformar iniciantes em mestres de Sistemas Operacionais* *Status: ✅ COMPLETO* **© 2024 - Todos os prompts prontos para uso com IA**
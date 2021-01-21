# Introduction

## EXERCISES

1. Consider a simple Web browser that takes as input a textual string in html format and displays the specified graphics on the screen. Is the display process one of compilation or interpretation ?

        Eu esperaria um interpretador traduziria a sequencias
        de tags em uma árvore de elementos gráficos e renderizaria.
        Por questões de segurança não teria suporte a javascript.

2. In designing a compiler, you will face many tradeoffs. What are the five qualities that you, as a user, consider most important in a compiler that you purchase? Does that list change when you are the compiler writer? What does your list tell you about a compiler that you would implement ?

        - Compilação rápida 
        - Mensagens de erros intuitivas
        - Target Program Otimizado
        - Extremamente Confiável (muitos testes)
        - Excelente Documentação
        Sim, não implementaria a otimização e documentado,
        mas nada excelente.
        Meu compilador poderia gerar um programa não
        suficientemente performático e provávelmente alguém
        me mandaria um e-mail querendo tirar dúvidas, além
        dele não ter proteção contra crackers.

3. Compilers are used in many different circumstances. What differences might you expect in compilers designed for the following applications ?

   1. A just-in-time compiler used to translate user interface code

            Esperaria Que ele tenha camadas de segurança
            extremamente competentes, que impeça a execução
            arbitrária de código na máquina dos meus usuários
            e alta performance.

   2. A compiler that targets the embedded processor used in a cellular telephone

            Esperaria um compilador que tenha com prioridade gerar programas
            com poucos mega bytes e rápidos quanto possível e que seu
            processo de compilação pudesse ser rápido para desenvolvimento.

   3. A compiler used in an introductory programming course at a high school

            Um compilador com mensagens de erros amigáveis de preferência que
            também seja capaz de falar, alunos de graduação de engenharia
            já tem dificuldade em ler as menagens, provavelmente os de ensino
            médio terão ainda dificuldade. OBS: A feature Voz da google
            poderá ser desabilitada passando uma flag. 

   4. A compiler used to build wind-tunnel simulations that run on a massively parallel processor (where all processors are identical)

            Compilador que gera um programa optimizado para múltiplos
            processadores e que tenha um interpretador simples para testes
            rápidos uma véz que quando maior a otimização maior é o tempo
            de compilação aumentando o tempo de criação das simulações.  

   5. A compiler that targets numerically intensive programs to a large number of diverse machines

            Um compilador extremamente confiável, capaz também de emular
            todos os dispositivos suportados com a finalidade de testar
            o programa gerado em diferentes máquinas.

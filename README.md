🧠 1. Estruturas Condicionais
✅ Verificação de Idade

O programa solicita a idade do usuário e, com base no valor informado, determina:

Idade inválida (menor que 0)

Entrada não permitida (até 17 anos)

Entrada liberada (18 anos ou mais)

🧪 Exemplos de Entrada/Saída
Entrada	Saída
-3	Idade inválida.
16	Entrada não permitida.
25	Entrada liberada.

PSEUDOCÓDIGO:
ESCREVA "Digite a sua idade"
    LEIA idade

    SE idade < 0 ENTÃO
        ESCREVA "Idade inválida."
    
    SENÃO SE idade <= 17 ENTÃO
        ESCREVA "Entrada não permitida."
    
    SENÃO
        ESCREVA "Entrada liberada."


🔁 2. Estruturas de Repetição 💎 Números Pares com For e While
O arquivo apresenta duas maneiras diferentes de exibir todos os números pares de 1 a 100:

Usando um loop for

Usando um loop while

📝 Exemplo de Saída 2 4 6 ... 100

PSEUDOCÓDIGO (FOR):

    PARA n DE 1 ATÉ 100 FAÇA
        
        SE n MOD 2 = 0 ENTÃO
            ESCREVA n
        FIMSE

    FIMPARA

PSEUDOCÓDIGO (WHILE):


    n ← 1

    ENQUANTO n ≤ 100 FAÇA

        SE n MOD 2 = 0 ENTÃO
            ESCREVA n
        FIMSE

        n ← n + 1

    FIMENQUANTO


📋 3. Listas
🧑‍🎓 Cadastro e Listagem de Alunos

O usuário insere nomes de alunos livremente.
Os nomes são armazenados em uma lista e, quando o usuário pressiona Enter sem digitar nada, o programa encerra e exibe todos os nomes cadastrados.

🧪 Exemplos de Entrada/Saída

Entrada:

Digite o nome do aluno: Pedro
Digite o nome do aluno: Ana
Digite o nome do aluno:


Saída:

Lista de alunos:
Pedro
Ana


Se nenhum nome for digitado:

Nenhum aluno foi registrado.

PSEUDOCÓDIGO:

    criar lista nomes_alunos vazia

    ENQUANTO verdadeiro FAÇA

        escrever "Digite o nome do aluno (deixe em branco para sair):"
        ler nome

        SE nome está vazio OU contém apenas espaços ENTÃO
            interromper loop
        SENÃO
            adicionar nome à lista nomes_alunos
        FIMSE

    FIMENQUANTO

    escrever "Lista de alunos:"

    SE lista nomes_alunos NÃO estiver vazia ENTÃO

        PARA cada aluno EM nomes_alunos FAÇA
            escrever aluno
        FIMPARA

    SENÃO

        escrever "Nenhum aluno foi registrado."

    FIMSE


🧾 4. Dicionários
🛒 Cadastro de Produtos (nome e preço)

O usuário cadastra produtos informando nome e preço.
Os itens são armazenados em uma lista de dicionários.
Ao deixar o nome em branco, o programa finaliza o cadastro e exibe todos os produtos.

🧪 Exemplos de Entrada/Saída

Entrada:

Nome do produto: Arroz
Preço de Arroz: 23.50

Nome do produto: Feijão
Preço de Feijão: 7.80

Nome do produto:


Saída:

Produto: Arroz | Preço: 23.5
Produto: Feijão | Preço: 7.8


Se nada for cadastrado:

Nenhum produto cadastrado.

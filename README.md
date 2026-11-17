# StellarisOS
Trabalho final da matéria optativa Programação para IOT
Neste trabalho o aluno deverá implementar um sistema que abrange os seguintes conceitos:
- Estruturas (struct);
- Ponteiros;
- Alocação dinâmica de memória;
- Manipulação de arquivos;
- Modularização de código (Funções);

## Objetivo
Desenvolver um sistema que permita cadastrar, consultar, alterar, excluir e armazenar informações permanentemente (em arquivos) utilizando a linguagem C.
Tema: A critério do aluno

## Contextualização
StellarisOS é um sistema que busca simplicidade, eficiência e confiabilidade em ambientes extremos e com poucos recursos disponíveis, está sendo desenvolvido para gerenciar aspectos individuais de uma colônia espacial em exoplanetas habitáveis, a ideia central é manter registros de forma confiável e acessível ao operador. Controlando aspectos como: relatórios de falha em equipamentos, acompanhamento dos níveis de consumo de recursos, controle da capacidade de produção, acompanhamento da população (nome, idade, tipo sanguíneo, ocupação/cargo, sexo, alergias, doenças conhecidas, status de saúde, entre outros).

## Requisitos
1. O sistema deverá conter pelo menos 2 structs; 
<br>  1.1 Pessoa - guarda os dados pessoais dos habitantes da colônia.
<br>  1.2 Maquinário - possui dados sobre as máquinas como: tipo, local, criticidade, status atual, datas de manutenção (última e próxima).
<br>  ~~1.3 PessoaRegistro e MaquinarioRegistro - guarda a struct antes de executar uma alteração nos dados e depois de alterar (cada registro terá um arquivo diferente).~~
3. Passagem de estruturas por referência para funções;
4. Alocação dinâmica de memória com malloc, calloc ou realloc;
5. Armazenamento e recuperação de dados em arquivos;

## Funcionalidades esperadas do sistema
- Cadastrar registros;
- Listar todos os registros;
- Consultar um registro específico;
- Alterar informações de um registro;
- Excluir um registro;
- Salvar os dados em arquivo;
- Recuperar os dados ao iniciar o programa.

A entrega deve ser feita via formulário que será disponibilizado na página da disciplina.

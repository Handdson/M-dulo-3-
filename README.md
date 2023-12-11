Trabalho Projeto individual Módulo 3 Handdson Wanglas


#1. Quais são as entidades necessárias?;
Tecnologia, Empresa, Colaboradores.

#2. Quais são os principais campos e seus respectivos tipos?;
id_tecnologia,id_empresa,id_colaboradores. int

#3. Como essas entidades estão relacionadas?;
Muitas pra muitas(n:n).



#4. Simule 2 registros para cada entidade.
insert into empresa(nome_emp,endereco_emp,telefone_emp,data)
values
('Fullhouse','Tokyo','95956210',2023-12-24), 
('Canadá','Vancouver','25103652',2023-12-24);

insert into  colaboradores(nome_cl,cpf_cl,endereco_cl, data)
Values
('Julia','987.152.456-74','Rua guilherme peixoto',2023-12-08),
('Arthur','563.892.756-00','Rua tenente ramos xv',2023-12-08);

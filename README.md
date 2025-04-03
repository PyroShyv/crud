### Como rodar o projeto 

Executar o MySQL pelo XAMPP

Ultilizar o VS Code para editar os códigos e visualizar as pastas

Criar bando de dados "crud"
...
CREATE DATABASE crud;
....
Criar tabela alunos;
...
CREATE TABLE crud.alunos (
    id INT NOT NULL AUTO_INCREMENT,
    nome VARCHAR(225) NOT NULL,
    email VARCHAR(50) NOT NULL,
    telefone VARCHAR(50) NOT NULL,
    data_nascimento DATE NOT NULL,
    PRIMARY KEY (id)
) ENGINE=InnoDB;

INSERT INTO alunos (nome, email, telefone, data_nascimento) VALUES 
('Luna Estrela', 'lunaestrela@gmail.com', '9876-5432', '2008-12-15'),
('Tico Teco', 'ticoteco@gmail.com', '2345-6789', '2010-01-30'),
('Mia Fada', 'miafada@gmail.com', '3456-7890', '1999-05-05'),
('Zeca Picolé', 'zecapicole@gmail.com', '4567-8901', '2003-10-12'),
('Duda Maravilha', 'dudamaravilha@gmail.com', '5678-9012', '1997-12-20'),
('Beto Brincalhão', 'betobrincalhao@gmail.com', '6789-0123', '1988-02-28'),
('Nina Sonhos', 'ninasonhos@gmail.com', '7890-1234', '2005-01-01'),
('Léo Aventura', 'leoaventura@gmail.com', '8901-2345', '2015-05-15'),
('Vivi Colorida', 'vivicolorida@gmail.com', '9012-3456', '1998-03-18');

...
Criar uma pasta na raiz do projeto chamada "fronted"
...
criar uma pasta na raiz do  projeto chamada "node"
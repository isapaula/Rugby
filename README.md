<h3>Arquivo config</h3>
<p>O arquivo config.php tem a rota do projeto, é importante verificá-lo e caso necessário alterá - lo.</p>
<p> Exemplo: 
se o projeto está em um localhost / nome da pasta que está a pasta do projeto/nome da pasta do projeto.
A variável $_SERVER['HTTP_HOST'] que foi utilizada pega somente o localhost.</p> 
<h3>Banco de dados</h3>
<p>pode utilizar o comando a baixo</p>
<p>ou o arquivo SQL que esta na pasta do projeto</p>
<p>O arquivo model na pasta App tem a conexao com o banco.</p>
<p>
            CREATE TABLE torcedores (
            idTorcedores int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT ,
            nome varchar(200) NOT NULL,
            documento varchar(30) NOT NULL,
            cep varchar(30) NOT NULL,
            endereco varchar(100) NOT NULL,
            bairro varchar(100) NOT NULL,
            cidade varchar(100) NOT NULL,
            uf char(2) NOT NULL,
            telefone varchar(20) DEFAULT NULL,
            email varchar(100) DEFAULT NULL,
            ativo varchar(5) DEFAULT NULL
            ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
</p>

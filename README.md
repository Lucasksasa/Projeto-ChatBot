# Projeto de Chat Bot

## Integrantes do Grupo
| Nome              |
| ----------------- |
| Guilherme Silva   |
| Yara Rosa         |
| Lucas Ferrari     |
| Yasmin Alves      |
| Izabela Gomes     |

## Descrição do Projeto
Criamos um chat bot de WhatsApp para fazer marcação de consultas, através do banco de dados do login, para localizar qual é o paciente, em qual clínica vamos marcar, e após marcar aparecer o dia e a hora que o paciente está marcado.

O sistema é dividido em duas partes:
1. **Auxiliar ou Profissional da Saúde**: Responsável pelas marcações e gestão das agendas.
2. **Profissional da Saúde**: Pode fazer a evolução do prontuário do que foi realizado na consulta/exame.

## Objetivo
O objetivo do sistema é facilitar o dia-a-dia de uma clínica na questão de marcação/gestão de agendas e evolução de prontuário, sendo um sistema completo, evitando a dependência de outros aplicativos e sistemas, filas e desgastes desnecessários, tanto por parte do cliente quanto para o profissional da saúde em questão.

Estrutura do Projeto
dp_connection.php Esqueceu_senha.html forgot_password.php index.html Login.html login.php README.md register.php Script.sql style/ desktop.ini index.html style/ desktop.ini index.html style.css style.css

Principais Classes e Interfaces
dp_connection.php: Conexão com o banco de dados.
login.php: Lógica de autenticação de usuários.
register.php: Registro de novos usuários.
forgot_password.php: Recuperação de senha.
Uso
Para usar o projeto, siga as instruções abaixo:

Clone o repositório para o seu ambiente local.
Configure o banco de dados utilizando o script Script.sql.
Configure a conexão com o banco de dados no arquivo dp_connection.php.
Abra o arquivo index.html no seu navegador para acessar a interface principal.
Utilize as páginas de login (Login.html) e registro (register.php) para gerenciar usuários.
Exemplo de Código
// Exemplo de conexão com o banco de dados
include 'dp_connection.php';

$conn = OpenCon();

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";

CloseCon($conn);


<h3>Criação de Login</h3>
<p>Foi criado com as linguagens HTML, CSS. Para a conexão de dados da página, usamos MySQL para a criação do script e php.</p>

Faça Login:
![image](https://github.com/user-attachments/assets/a2950d73-6ea4-4627-a598-449b9943945e)

Criar Conta:
![image](https://github.com/user-attachments/assets/4fbc03d0-ebf9-45a9-9a69-bcd8d74d7576)

esqueci senha:
![image](https://github.com/user-attachments/assets/751b5d4b-a4a2-4cae-a8b3-2c5f5f4ddee9)

<h3>CHAT BOT</h3>
- Criado Javascript e com a ligação com os banco de dados

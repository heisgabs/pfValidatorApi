🛠️ CPF Validator API
API em C# para validar números de CPF.

🚀 Funcionalidades
✅ Validação de CPF (estrutural e com dígitos verificadores).
⚙️ Tecnologias Utilizadas
C#
.NET Core
Azure (deploy)
💻 Como Executar Localmente
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Acesse o diretório do projeto:

bash
Copiar
Editar
cd nome-do-repositorio
Execute o projeto:

bash
Copiar
Editar
dotnet run
API disponível em http://localhost:5000.

🌐 Deploy na Azure
A API está hospedada no Azure. Para usar em produção, acesse: Link do Serviço Azure.

📝 Como Usar
Envie um POST para /api/valida-cpf com o corpo:

json
Copiar
Editar
{
    "cpf": "12345678909"
}
Exemplo de resposta:

json
Copiar
Editar
{
    "valido": true
}
📄 Licença
Este projeto é licenciado sob a MIT License.

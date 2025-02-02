# validadorCPF
Esta é uma API desenvolvida em C# que valida CPFs informados. 
O objetivo é fornecer um serviço simples e eficiente para validar números de CPF, retornando o status de validade.

Funcionalidades
Validação de CPF: A API recebe um CPF e verifica se ele é válido ou não, levando em consideração a estrutura e os dígitos verificadores.

Tecnologias Utilizadas
C#
.NET Core
Azure (para o deploy)

Como Executar Localmente
Clone este repositório para o seu ambiente local:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/nome-do-repositorio.git
Navegue até o diretório do projeto:

bash
Copiar
Editar
cd nome-do-repositorio
Execute o projeto usando o .NET CLI:

bash
Copiar
Editar
dotnet run
A API estará disponível em http://localhost:5000 ou outra porta configurada.

Deploy na Azure
Esta API foi implantada no Azure para garantir alta disponibilidade e escalabilidade. Caso deseje utilizar a versão em produção, acesse o link do serviço hospedado na Azure (insira o URL aqui).

Como Usar
Faça uma requisição POST para o endpoint /api/valida-cpf com o seguinte corpo JSON:

json
Copiar
Editar
{
    "cpf": "12345678909"
}
A resposta será um JSON indicando se o CPF é válido:

json
Copiar
Editar
{
    "valido": true
}
Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

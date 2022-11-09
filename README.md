# Convenção da documentação de API - Ideia Original

Essa documentação destina-se aos desenvolvedores que necessitam fazer manutenção das nossas APIs ou trazer novas funcionalidades para a aplicação.

Para fornece excelencia na utilização de nossas APIS, desenvolvemos a seguinte convenção.

Os nomes utilizados nas APIs devem ser em português brasileiro.
A nomenclatura de variaveis utilizada é o camelCase.

Segue um breve exemplo do padrão utilizado:

| Nome  | Exemplo | 
|---|---|
| Nome da aplicação | IO - Prestação de Serviçços API  |
| URI do serviço | https://ideiaoriginal.net/v1/prestador/codigoPrestador/542/registroServicosPrestados | 
| Nome do variavel | tipoServico |
| Nome do Metodo | criarCategoria |
| Nome da API | cliente |

**A URI de serviço foi atualizada para suportar o versionamento das APIs.**

Para gestão das APIs, é proposto os seguintes tópicos:

* Aplicar políticas de segurança de APIs;
* Organizar o catálogo de APIs;
* Reutilizar APIs e fazer com que estas tenham aderência com as estratégias de negócio;
* Controlar o versionamento das APIs;
* Rastrear os dados de roteamento para o back-end;
* Acompanhar o ciclo de vida de cada API;
* Definir os padrões de interfaces de APIs;
* Reunir estatísticas sobre portal do desenvolvedor e uso de API Gateway.
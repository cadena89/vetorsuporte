# VetorSuporte

Programa de acesso remoto da **Vetor Sistemas**, usado pelo nosso suporte técnico.

## Download

Baixe sempre pela página da versão mais recente:
**https://github.com/cadena89/vetorsuporte/releases/latest**

| Arquivo | Para quem |
| --- | --- |
| `VetorSuporte-*-install.exe` | Cliente: instala o VetorSuporte no computador que vai receber atendimento |
| `VetorSuporte-*-portatil.exe` | Cliente: roda sem instalar, para um atendimento rápido |
| `VetorTecnico-*-install.exe` / `-portatil.exe` | Técnicos da Vetor |
| `DefinirNomeTecnico.bat` | Técnicos: define o nome que o cliente vê durante o acesso |

Só aceite um acesso se você pediu atendimento à Vetor Sistemas. Na dúvida, ligue para **(41) 3094-5480**.

## Atualização automática

As versões instaladas consultam esta página uma vez por dia. O arquivo `versao.assinado` é assinado com a chave da Vetor, e o programa só instala uma atualização quando a assinatura e o SHA-256 do instalador conferem.

## Licença

O VetorSuporte é baseado no [RustDesk](https://github.com/rustdesk/rustdesk), distribuído sob a licença AGPL-3.0. O código-fonte com as alterações da Vetor está disponível mediante solicitação à Vetor Sistemas.

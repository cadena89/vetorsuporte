# Suporte Vetor Sistemas

Programa de acesso remoto da **Vetor Sistemas**, usado pelo nosso suporte técnico.

## Download

Baixe sempre pela página da versão mais recente:
**https://github.com/cadena89/vetorsuporte/releases/latest**

| Arquivo | Para quem |
| --- | --- |
| `SuporteVetorSistemas-*-install.exe` | Cliente: instala o Suporte Vetor Sistemas no computador que vai receber atendimento |
| `SuporteVetorSistemas-*-portatil.exe` | Cliente: roda sem instalar, para um atendimento rápido |
| `SuporteVetorSistemas-*-arm64.apk` / `-armv7.apk` | Cliente no celular Android (arm64 para a maioria dos aparelhos atuais) |
| `TecnicoVetorSistemas-*-install.exe` / `-portatil.exe` | Técnicos da Vetor |
| `DefinirNomeTecnico.bat` | Técnicos: define o nome que o cliente vê durante o acesso |
| `ConfigurarFTP.bat` | Técnicos: liga e testa o envio das gravações para o servidor da Vetor |

Só aceite um acesso se você pediu atendimento à Vetor Sistemas. Na dúvida, ligue para **(41) 3094-5480**.

Até a versão 1.5.1 (2), o programa se chamava VetorSuporte (e VetorTecnico). Quem tem essa versão deve desinstalá-la e instalar a nova.

## Atualização automática

As versões instaladas no Windows consultam esta página uma vez por dia. O arquivo `versao.assinado` é assinado com a chave da Vetor, e o programa só instala uma atualização quando a assinatura e o SHA-256 do instalador conferem.

## Licença

O Suporte Vetor Sistemas é baseado no [RustDesk](https://github.com/rustdesk/rustdesk), distribuído sob a licença AGPL-3.0. O código-fonte com as alterações da Vetor está disponível mediante solicitação à Vetor Sistemas.

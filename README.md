# Transcreve Audio :studio_microphone: :black_nib:

A idéia é utilizar o Gemini para transcrever áudios, principalmente os do whatsapp, futuramente quero incluir isso em um chatbot automatizado (seja no próprio whatsapp ou no telegram) onde o usuário envia o áudio e ele é devolvido transcrito.

O Arquivo .waptt.opus é o arquivo gerado pelo whatsapp ao salvar um áudio recebido, o arquivo no projeto foi enviado via whatsapp e salvo para ser utilizado como exemplo.

A API é capaz de transcrever basicamente qualquer formato de áudio (.mp3, .m4a, wav etc.). Durante meus testes notei que em caso de áudios muito longos ou arquivos muito grandes via colab vamos receber um erro de timeout

Outra anomalia notada durante os testes foi que o modelo acaba aluciando com áudios muito curtos, em alguns áudios de teste de 5 segundos ou menos ele acaba por criar todo um plot que não tem nada a ver com o áudio em si.
## Como Usar

*  Insira sua API key nos secrets do google colab
*  Rode a instalação de dependências
*  Rode o códio principal (os comentários detalhados estarão diretamente nele usando o formato #)
*  Logo abaixo do código principal sera exibido um botão para o upload do áudio
*  Escolha o áudio teste presente no projeto
*  Se tudo der certo (e a IA não alucinar :smile:) a transcrição aparecerá logo abaixo

## Autor

- Luis Henrique: [GIT](https://github.com/lhsluis) / [X-Twitter](http://twitter.com/lhs_luis)

## Licenças

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

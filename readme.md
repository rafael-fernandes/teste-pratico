# Teste prático da WeCare!

Olá, você precisará desenvolver uma funcionalidade de reconhecimento entre pares.

A funcionalidade funciona da seguinte forma:

1. Você pesquisa alguém para reconhecer.
2. Seleciona qual o valor da empresa a pessoa está se destacando.
3. Escreva uma mensagem.
4. Pronto! Reconhecimento feito, pessoas mais felizes!

Além disso, devemos acompanhar os reconhecimentos realizados pela página Estatísticas.

## Instruções

[Clique aqui](https://xd.adobe.com/view/b27bb5ae-fcce-423e-be40-c67d73ae7479-e728/) para acessar o protótipo da funcionalidade.

- A fonte utilizada é a [Poppins](https://fonts.google.com/specimen/Poppins). Os pesos e tamanhos usados estão no protótipo, além de todas as cores.

- O pacote de avatares das pessoas e logo da WeCare estão nessa pasta.

- A biblioteca de ícones utiliza é a Font Awesome.

- Utilize o Ruby on Rails para a implementação do backend da aplicação.

- Você pode utilizar qualquer framework CSS e JS que desejar.

- Não é preciso implementar o sistema de login e cadastro, apenas crie vários usuários no sistema sem necessidade de interface para esse cadastro.

- Cada parte do formulário para reconhecer deve aparecer somente quando o anterior tiver sido concluído (exemplo: os valores só devem aparecer depois de selecionar a pessoa).

- Na página de estatísticas ([protótipo](https://xd.adobe.com/view/b27bb5ae-fcce-423e-be40-c67d73ae7479-e728/screen/32962e62-0cf9-4826-a46a-de40f1d68c38/)), liste apenas os reconhecimentos feitos, sem necessidade de paginação ou de mostrar as mensagens dos reconhecimentos.

- A exportação dos reconhecimentos deve ser realizada de forma assíncrona, após clicar em "Download em CSV", um relatório é criado para download, após o processamento assíncrono. (dica: utilize ActiveJob)

## Prazo e entrega

O prazo para entrega do teste é de 1 semana. Me mande o link do repositório do Github com o seu projeto para o email rafael@sejawecare.com.br

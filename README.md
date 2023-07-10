# code-review-pull-request

Este repositório será utilizado para testes de criação de Pull Request durante sua implementação.
A equipe poderá utilizá-lo para testar Pull Requests e tirar dúvidas.

## Criação de Pull Request

Após realizar o push do código para a branch de desenvolvimento, **NÃO** realize mais o merge! Crie um Pull Request.

O Code Review será realizado através do Pull Request.

O merge será feito pelo revisor através do Pull Request, após aprovação do desenvolvimento realizado.

Para criar um Pull Request, siga os passos abaixo (considerando que o dev já realizar o push do código para sua branch): 

1. Entre no repositório pelo navegador.
2. Verifique se abaixo do nome do repositório, existe a seguinte mensagem:

![Alt text](.readme_images/image.png)

3. Clique no botão "Compare & pull request".
4. Se não houver a mensagem, clique em **Pull requests** no cabeçalho da página e clique no botão **New pull request**
5. Ajuste a branch de destino para a branch na qual irá receber o código. No exemplo abaixo, o código da branch **ajuste_teste** irá para a branch **main**.
    - Verifique se a mensagem **Able to merge** está ao lado com a cor verde. Caso não esteja, significa que seu código possui conflitos, impossibilitando prosseguir. Resolva o conflito, e crie o Pull Request novamente.

![Alt text](.readme_images/image-1.png)

6. Altere o nome do pull request para o seguinte padrão: **[PROJETO] TIPO DE DESENVOLVIMENTO: Spec/Card**, por exemplo **[ECOMMERCE] FEATURE: CARD001 - Ajuste de Readme**
7. Se houver, insira o arquivo de Spec na descrição, arrastando para a caixa de descrição ou clicando no texto abaixo da caixa.
8. Ao lado direito, clique em **Reviewers** e insira o time **projetofocvserp/reviewers**.
9. Ainda no meu lateral, clique em **Labels** e insira a label do projeto e do tipo de desenvolvimento, se é feature ou fix.
10. Clique no botão **Create pull request** e aguarde a finalização.
11. Após o code review, caso o revisor aprovar, o dev irá fazer o merge clicando em **Merge pull request**

TESTE
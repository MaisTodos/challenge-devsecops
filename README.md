# DevSecOps Challenge Junior

## Prerequisitos
Neste desafio você precisará de uma conta na AWS. Crie uma se você ainda não tiver. Este teste deve ser feito com o Nível Gratuito dos serviços da AWS e será necessário fornecer os acessos devidos aos avaliadores na sua conta, escolha a forma que preferir para dar estes acessos.

## Tarefa
O time de Segurança percebeu que estava sofrendo recorrentemente um ataque DOS  nos seus servidores. O time ainda está implementando soluções que impediriam esse tipo de ataque e até lá precisam monitorar os seus servidores para verificar se algum ataque foi bem sucedido e o servidor caiu. Para resolver esse problema, foi pedido que você crie um *AWS Lambda* que deve **verificar** se os servidores estão de pé e caso algum não esteja, fazer um print com o texto **ALERTA DE ATAQUE**.

## Requisitos
- Criar duas instâncias EC2 com configurações de Nível Gratuito na AWS. Estas instâncias serão utilizadas somente para verificar o funcionamento da *AWS Lambda*.
- Criar uma AWS Lambda usando o runtime de Python que vai verificar as duas instâncias de uma em uma hora.
- Configurar os acessos necessários para que esses serviços se comuniquem.
- Conceder acesso de leitura aos recursos criados para conferência dos avaliadores. Neste é preciso ver tudo que você criou e poder simular uma falha no servidor. (Nos enviar um usuário e senha por email)

## Perguntas
### Terei que pagar pelas taxas da AWS?
Não. Nesse desafio é necessário que você use apenas recursos gratuitos que não gerem nenhuma cobrança. Lembre-se de excluir seus recursos assim que o processo de revisão estiver concluído para não ser cobrado pela AWS.
### No que vocês vão me avaliar?
Desenvolvimento em Python, compreensão das tecnologias usadas e principalmente segurança. Lembre de aplicar os conceitos de boas práticas do IAM (Gestão de Acessos) na hora de conceder os acessos para os serviços envolvidos e para os avaliadores.
### Terei a chance de explicar minhas escolhas?
Sinta-se à vontade para comentar seu processo. Discutiremos as escolhas que você fez na entrevista.
### Por que utilizar uma AWS Lambda para isso se não é o melhor método para gerir EC2?
Queremos avaliar a habilidade de escrever código em Python e interagir com a biblioteca do boto3 para manipular recursos da AWS.

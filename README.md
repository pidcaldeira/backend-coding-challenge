# Coding Challenge Backend #

Bem vindo! Se você está aqui é porque gostamos do seu perfil e queremos conhecer um pouco mais sobre suas habilidades como desenvolvedor.

## Submissão

Utilize **Git** para versionamento do seu projeto. Faça um FORK e submeta um PULL REQUEST para este repositório com a sua solução.

Atenção: Não criar um repositório público com o conteúdo do desafio ou solução.

## Critérios de avaliação

* Compreensão dos requistos
* Fornecer documentação explicando como rodar e testar localmente
* Engenharia de Software
* Cobertura de Testes
* Versionamento
* Arquitetura do Código
* Separação de Responsabilidades
* Manutenabilidade
* Modelagem de dados (Estruturas de dados utilizadas, banco de dados, etc)

## Diferenciais

* Utilizar Docker e docker-compose.
* API utilizando JSON API (REST).
* Disponibilizar um README com possíveis evoluções na sua solução. Tendo em vista o prazo proposto. 

## Considerações finais

* Sinta-se livre para entrar em contato conosco sempre que necessário!


# Desafio

Fornecer ao investidor um serviço para obter dados sobre fundos de investimentos. 

Como base de informações será utilizados o **Informe diário**, que é o demostrativo que contém informações sobre um Fundo de Investimento. O registro é diário, e contém as seguintes informações:

* Valor total da carteira do fundo
* Patrimônio líquido
* Valor da cota
* Captações realizadas no dia
* Resgates pagos no dia
* Número de cotistas

No diretório **informes** estão os informes diários organizados em arquivos mensais referente aos **Fundos de Investimentos no mês de Julho/2019**.

**Dados obtidos através do portal CVM Dados Abertos:**
http://dados.cvm.gov.br/dataset/fi-doc-inf_diario

## Tarefa

### Sugestão de Fundo de Investimentos

Disponibilizar os 10 fundos com maior captação liquida no mês de Julho.

** A captação liquida é obtida através da dirença entre **Captação** e **Resgate**.
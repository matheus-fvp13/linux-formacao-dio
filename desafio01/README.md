# Infraestrutura como código: Script de criação de estrutura de usuários, diretórios e permissões 

## Diretórios, Grupos e usuários
- **Diretórios** -> /publico, /admin, /ven, /sec
- **Grupos** -> GRP_ADM, GRP_VEN, GRP_SEC
- **Usuários** -> carlos, maria, joao, debora, sebastiana, roberto, josefina, amanda, rogerio

### Distribuição de usuários por grupo
| GRUPOS | USUARIOS |
| ------ | -------- |
| GPR_ADM | carlos, maria, joao |
| GPR_VEN | debora, sebastiana, roberto |
| GPR_SEC | josefina, amanda, rogerio |

## Definições para criação do script
- Excluir diretórios, arquivos, grupos e usuários criados anteriormente;
- Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;
- O dono de todos os diretórios criados será o usuário root;
- Todos os usuários terão permissão total dentro do diretório publico;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem;



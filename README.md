![Tux2](https://user-images.githubusercontent.com/65175946/218834784-5f281006-a456-43b1-9dd8-2d171b3e10e9.png)
# Linux - Projeto IAC
Repositório para os arquivos do primeiro projeto do Bootcamp de Linux da DIO.

>Foi utilizado o **Ubuntu Server** para o desenvolvimento e execução do script.

**O QUE O SCRIPT FAZ?**

Executa uma sequência de configurações iniciais pré-estabelecidas pelo Administrador para usuários específicos em um novo ambiente Linux.

**COMO O SCRIPT FUNCIONA?**

Veja abaixo as etapas de execução.

1. O script inicia criando 4 diretórios específicos:
- Público;
- ADM;
- VEN;
- SEC;

2. Cria 3 grupos de usuários:
- GRP_ADM;
- GRP_VEN;
- GRP_SEC;

3. Cria 9 usuários e os insere em grupos específicos:
- Carlos (GRP_ADM);
- Maria (GRP_ADM);
- João (GRP_ADM);
- Débora (GRP_VEN);
- Sebastiana (GRP_VEN);
- Roberto (GRP_VEN);
- Josefina (GRP_SEC);
- Amanda (GRP_SEC);
- Rogério (GRP_SEC);

4. Especifica as permissões dos diretórios:
- O dono de todos os diretórios criados será o usuário root;
- Todos os usuários terão permissão total dentro do diretório público;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertençam;

5. Finaliza.

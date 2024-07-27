# Projeto de Criação de Estrutura de Diretórios e Usuários

Este projeto foi desenvolvido como parte do curso de Linux Fundamentals, com o objetivo de automatizar a criação de diretórios, grupos de usuários, usuários e definir as permissões apropriadas para cada um deles usando um script em Bash.

## Descrição do Script

O script realiza as seguintes tarefas:

1. **Criação de Diretórios:**
   - `/publico`
   - `/adm`
   - `/ven`
   - `/sec`

2. **Criação de Grupos de Usuários:**
   - `GRP_ADM`
   - `GRP_VEN`
   - `GRP_SEC`

3. **Criação de Usuários e Associação aos Grupos:**
   - Usuários do grupo `GRP_ADM`:
     - `carlos`
     - `maria`
     - `joao`
   - Usuários do grupo `GRP_VEN`:
     - `debora`
     - `sebastiana`
     - `roberto`
   - Usuários do grupo `GRP_SEC`:
     - `josefina`
     - `amanda`
     - `rogerio`

4. **Especificação de Permissões dos Diretórios:**
   - Diretório `/adm`: Acesso total para `GRP_ADM`
   - Diretório `/ven`: Acesso total para `GRP_VEN`
   - Diretório `/sec`: Acesso total para `GRP_SEC`
   - Diretório `/publico`: Acesso total para todos os usuários

## Uso do Script

Para executar o script, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/GustavGregory/linux-projeto1-iac

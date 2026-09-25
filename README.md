# Sistema Escolar em Java

Projeto de terminal para cadastrar alunos e administradores, registrar notas e consultar informações escolares.

## Requisitos

- Java Development Kit (JDK) instalado.
- Terminal aberto na pasta do projeto.

## Como executar

Compile o programa:

```powershell
javac SchoolSystem.java
```

Depois execute:

```powershell
java SchoolSystem
```

## Funcionalidades

1. Cadastrar aluno.
2. Listar usuários — disponível apenas para administrador autenticado.
3. Editar dados de usuário — disponível apenas para administrador autenticado.
4. Cadastrar administrador.
5. Adicionar notas por matéria — disponível apenas para administrador autenticado.
6. Mostrar notas.
7. Encerrar o sistema.
8. Entrar como administrador.
9. Entrar como aluno.

## Como funcionam os acessos

O sistema possui dois tipos de usuário:

- `ALUNO`: depois de entrar com e-mail e senha, pode consultar somente as próprias notas.
- `ADMINISTRADOR`: depois de entrar com e-mail e senha, pode listar usuários, editar dados, adicionar notas e consultar as notas de qualquer aluno.

Para testar, cadastre um aluno ou administrador pelas opções 1 e 4. Em seguida, use a opção 8 ou 9 e informe o mesmo e-mail e senha do cadastro.

## Estrutura do projeto

- `SchoolSystem.java`: código-fonte do sistema.
- `SchoolSystem.class` e `Usuario.class`: arquivos criados automaticamente após a compilação. Não devem ser editados.

## Observação

Os dados ficam apenas na memória enquanto o programa está aberto. Ao encerrar, os cadastros e as notas são apagados.

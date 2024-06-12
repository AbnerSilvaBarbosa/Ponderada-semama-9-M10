## Passo a passo da ponderada

Para deixar tudo de uma forma unificada passo a passo de como utilizar o terraform para subir uma EC2 na sua AWS Academy 💪

### 1ª Instalar a CLI do terraform e da AWS

Primeiro você deve seguir o tutorial de instalação das duas CLI's, segue os links abaixo:

[Como instalar a CLI do terraform](config.md/#instalar-a-cli-do-terraform)

[Como instalar a CLI da AWS](config.md/#instalar-a-cli-da-aws)

### 2ª Configurar as credências da AWS na CLI

Você vai precisar ter as credências da sua AWS academy, segue o tutotial a baixo

[Video de como pegar as credências](./assets/tutorial_crede.mp4)

Após isso você pode seguir o tutorial de inserir na CLI da AWS as credências aqui:

[Colocando credências pela CLI da AWS](config.md/#configurar-as-credencias-da-sua-conta-da-aws)

### 3ª Entrar na pasta da Infra do projeto e executar os comandos do terraform

```bash
# entrar na pasta com o codigo do terraform
cd infra
```

Após isso você deve executar os comandos do terraform abaixo:

```bash
terraform init
```

```bash
terraform fmt
```

```bash
terraform validate
```

```bash
terraform apply
```

```bash
terraform plan
```

a explicação de cada comando está no link abaixo

[terraform comandos](./terraform.md)

### 4ª Sucesso !!!

Caso queira ver s edeu tudo certo pode acessar os logs nesse [link](./logs.md) para validar se os seus retornos também foram esses.
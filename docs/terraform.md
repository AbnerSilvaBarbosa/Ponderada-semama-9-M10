## Comandos do terraform 💻

Aqui você vai visualizar os comandos basicos que foi utilizado nessa ponderada, e suas explicações.

Assim podendo ser revisado futuramente, caso você esqueça de como utilizar o terraform no terminal

### Executando código do Terraform

**Após realizar todas as configurações acima, você deve acessar a pasta infra do projeto e logo em seguida executar os seguintes comandos no terminal:**



<p><span style="color: purple;">terraform init</span>: Este comando é usado para inicializar um diretório de trabalho do Terraform. Ele é geralmente executado no início de um novo projeto ou quando o diretório do projeto é atualizado com novos plugins ou módulos. Durante a inicialização, o Terraform baixa os plugins necessários para a configuração do provedor (por exemplo, AWS, Azure, Google Cloud, etc.) e estabelece uma conexão com o backend de armazenamento de estado, se aplicável.</p>

```bash
terraform init
```



<br>

<p><span style="color: purple;">terraform fmt</span>: Este comando é usado para formatar o código do Terraform de acordo com as convenções de estilo recomendadas pelo Terraform. Ele ajusta a indentação, espaçamento e formatação geral do código para torná-lo mais legível e consistente. Executar terraform fmt ajuda a manter um estilo de código uniforme em um projeto e facilita a colaboração entre membros da equipe.</p>

```bash
terraform fmt
```

<br>


<p><span style="color: purple;">terraform validate</span>: Este comando é usado para validar a sintaxe e a semântica do código do Terraform. Ele verifica se o código está correto em termos de estrutura e configuração. Durante a validação, o Terraform analisa os arquivos de configuração e identifica quaisquer erros ou avisos, como referências a recursos inexistentes ou configurações inválidas.</p>

```bash
terraform validate
```

<br>

<p><span style="color: purple;">terraform plan</span>: Este comando é usado para criar um plano de execução do Terraform. Ele examina o código do Terraform e determina quais mudanças serão feitas na infraestrutura quando o comando terraform apply for executado. O plano mostra uma visão geral das adições, atualizações e remoções de recursos que ocorrerão, permitindo que você revise e confirme as mudanças antes que sejam aplicadas.</p>

```bash
terraform plan
```

<br>


<p><span style="color: purple;">terraform apply</span>: Este comando é usado para aplicar as mudanças planejadas à infraestrutura. Quando executado, o Terraform verifica o plano de execução gerado pelo comando terraform plan e solicita confirmação para aplicar as mudanças. Depois de confirmado, o Terraform faz as alterações na infraestrutura de acordo com o plano e atualiza o estado do projeto para refletir as mudanças realizadas.</p>

```bash
terraform apply
```
<br>

Após essa mini aulinha dos comandos que eu executei, vou mostrar os logs e as evidências desse processo como um todo

[Evidências da ponderada](logs.md)

# DeslocamentoApi

É um uma api desenvolvida durante a matéria de back-end C# no Biopark Connect


## Rodando os testes

Para iniciar dotnet-ef

```bash
  dotnet tool install --global dotnet-ef
```
Para criar uma migration
```bash
  dotnet ef migrations add NewMigration --project .\Deslocamento.Data --startup-project .\Deslocamento.WebAPI --context ApplicationDbContext
```
Para executar a migration
```bash
  dotnet ef database update --project .\Deslocamento.Data --startup-project .\Deslocamento.WebAPI --context ApplicationDbContext
```

# dotnet

## User secrets

1. Add UserSecretsId to project

   - `dotnet user-secrets init` (in project directory)

2. put secrets into file `init.json`

3. Add user secrets

   - `cat ./input.json | dotnet user-secrets set` (in project directory)

- Or just go to `${HOME}\.microsoft\usersecrets\$user_secrets_id\secret.json`

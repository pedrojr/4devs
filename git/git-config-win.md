
### config user name
```
git config --global user.name "user"
```

### config email
```
git config --global user.email user@email.com
```

### gerar chave ssh
```
ssh-keygen -t rsa -b 4096 -C "user@email.com"
```

### copia chave para o clipboard
```
clip < %USERPROFILE%\.ssh\id_rsa.pub
```

### adicionar no github a chave ssh
```
Em "Settings" >> "SSH and GPG keys", clicar em "New SSH key"
```

**xxxx**
```

```

**Diferença entre branches**
```
git diff develop
```


**Checar diferença dos repositórios**
```
git status
```

**Listar novidades no repositório sem aplicar localmente**
```
git log --all --oneline --decorate --graph --remotes
```

**Baixar do repositório remoto sem integrar**  

origin: *Seu repositório pessoal (onde fez o fork).*  
upstream: *Repositório original de onde fez o fork.*  
–all: *Busca atualizações de todos os remotos configurados (origin, upstream, etc.).*
```
git fetch origin
git fetch upstream
git fetch --all
```

**er as novidades que chegaram após a sincronização**
```
git log -p -1
```

**Commits recentes na branch master**
```

```

**Comando seguro para apenas baixar atualizações:**
```
git pull origin master
```

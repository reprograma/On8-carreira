## CV Reprograma
### Instruções de preenchimento

1. Faça o *fork* deste repositório
2. Clone o repositório do seu *fork* para a sua máquina.

```
git clone <url_do_repositório>
```

3. Crie uma nova *branch* com o seu nome, por exemplo "fulana-maria"

```
git checkout -b fulana-maria
```

4. Adicione o repositório da Reprograma como *upstream*.

```
git remote add upstream https://github.com/reprograma/On8-carreira
```

5. Verifique se os links remotos estão corretos:
```
git remote -v

********
origin  https://github.com/fulanamaria/On8-carreira.git (fetch)
origin  https://github.com/fulanamaria/On8-carreira.git (push)
upstream  https://github.com/reprograma/On8-carreira.git (fetch)
upstream  https://github.com/reprograma/On8-carreira.git (push)
********
```

6. Na pasta students_json, faça uma cópia do arquivo `nome_sobrenome.json` para o seu nome. Exemplo: `fulana_maria.json`. Mude o conteúdo do arquivo para o seu caso.

7. Faça o *commit* da sua alteração e *push* pra sua *branch*, no seu repositório.
```
git add .
git commit -m "Adicionar Fulana Maria CV"
git push origin fulana-maria
```

8. Abra um *pull request* da sua branch, para a master do repositório da Reprograma.

Tudo pronto!

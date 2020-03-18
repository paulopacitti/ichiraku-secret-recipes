# Secret Recipes of Ichiraku :ramen: :leaves:

![Ichiraku Lamen Restaurant](https://vignette.wikia.nocookie.net/narutoprofile/images/9/9b/Ichiraku_Ramen.png)

- All the secret recipes of Ichiraku's restaurant stored in a Git repository.
- All the recipes must be a **Markdown** file.

## Chefs

## Git Workflow
- Enviando seus commits para o repositório remoto:
  - vá para a branch master:
  `$ git checkout master`
  - verifique se existem novas mudanças:
  `$ git pull`
  - se sim:
    - volte para a branch da sua tarefa:
    `$ git checkout nome-da-branch`
    - dê um rebase:
    `$ git rebase master`
    - resolva os conflitos, **se houverem**, e dê:
    `$ git add`
    `$git rebase --continue`
    - volte para a branch master:
    `$ git checkout master`
    - mescle a sua branch com a master: `$ git merge nome-da-branch`
  - se não:
      - mescle a sua branch com a master:
      `$ git merge nome-da-branch`
  - mande para o repositório
    - `$ git push`

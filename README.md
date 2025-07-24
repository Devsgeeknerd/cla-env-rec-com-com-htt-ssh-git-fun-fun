<!-- Título -->
# Enviando e Recebendo Commits

***Conteúdo da Aula:***

* Comandos utilizado:
  * git push -u origin master;
  * git pull origin master.

## :memo: Explicação do Processo

### O que este conteúdo faz?

Ensina como enviar (empurrar) e receber (puxar) alterações em um repositório Git.

### Vocabulário Básico:

* `git push` &#8594; Enviar mudanças para o repositório remoto.
* `git pull` &#8594; Baixar mudanças do repositório remoto.
* `origin` &#8594; Nome padrão do repositório original.
* `master/main` &#8594; Nome da branch principal do projeto.

### Explicação Passo a Passo

#### 1. `git push -u origin master`

* Como se fosse: Enviar uma carta para casa (repositório remoto).
* `-u` significa configurar o "caminho de volta" automaticamente.
* `origin` é o endereço do repositório.
* `master` é a versão principal do projeto.

#### 2. `git pull origin master`

* Como se fosse: Receber correspondências de casa.
* Baixa todas as novas alterações feitas por outros colaboradores.
* Atualiza seu repositório local com a versão mais recente.

### Cuidado!

* Sempre faça `pull` antes de `push` para evitar conflitos.
* Verifique se você tem permissão para enviar alterações.
* Certifique-se de estar na branch correta.

### Analogia Divertida

Imagine o Git como um grupo de amigos trocando figurinhas:

* `push` = Dar suas figurinhas novas.
* `pull` = Receber figurinhas dos amigos.

### Exercício Prático

Tente:

1. Fazer uma alteração no código.
2. Salvar.
3. Fazer `git pull` para atualizar.
4. Fazer `git push` para enviar suas mudanças.

> [!IMPORTANT]\
> **Boas práticas**:
>
> * **Verificação antes do Push**:
>   * Sempre realizar `git status`.
>   * Confirmar arquivos que serão enviados.
>   * Validar commits.
>
> * **Segurança no Pull**:
>   * Commitar alterações locais antes.
>   * Verificar possíveis conflitos.
>   * Usar `git fetch` para inspeção prévia.

---

> [!WARNING]\
> **Recomendações**:
>
> * Substituir `master` por `main` (nomenclatura moderna).
> * Usar `git push origin HEAD` para enviar branch atual.
> * Configurar `git config --global push.default current`.

---

> [!NOTE]\
> **Observações**:
>
> * Nunca force push em branches compartilhadas.
> * Sempre comunique equipe antes de grandes alterações.
> * Use pull requests para revisão de código.

---

## :clipboard: Próximos Passos

* Aprender branches.
* Entender merge e rebase.
* Configurar workflows no GitHub/GitLab.
* Estudar estratégias de versionamento.

## :bookmark: Tags

`#git` `#versionamento` `#devops` `#workflow` `#boas-praticas`

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-env-rec-com-com-htt-ssh-git-fun-fun&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-env-rec-com-com-htt-ssh-git-fun-fun?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-env-rec-com-com-htt-ssh-git-fun-fun?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-env-rec-com-com-htt-ssh-git-fun-fun?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-env-rec-com-com-htt-ssh-git-fun-fun?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-env-rec-com-com-htt-ssh-git-fun-fun?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")

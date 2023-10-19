# Plano de Contribuição

Para contribuir com o projeto basta clonar o repositório do projeto e seguir as políticas listadas abaixo.

### Repositórios
- [Doc](https://github.com/fga-eps-mds/2023.2-UnB-TV-DOC)
    
## 1. Issue

Deve obedecer o template para uma nova funcionalidade, ou o template de bug e deve ter o máximo de indicadores do que se trata:

### Nome da feature ou bug

#### Descrição
Pequena e objetiva descrição sobre a issue.

#### Tarefas
Seção para tarefas (tasks) para issues mais complexas ou sub-tarefas.

- [ ] Adição de outro documento.
- [ ] Implementação do Cadastro.
- [ ] Redefinir senha.
- [ ] Alguma outra tarefa.

#### Contexto adicional
Alguma informação necessária para melhor compreensão.

1. Após criar a issue, deve ser adicionado a pontuação da tarefa caso exista
2. Deve ser adicionado as labels pertinentes para a issue

---

## 2. Branch

1. Toda nova branch deve ser feita a partir da develop
2. Ao resolver a issue proposta, a nova branch deve ser merjada e comparada em relação a develop
3. Caso o PR seja aprovado pela equipe, a nova branch será deletada e seu conteúdo integrado a develop
4. Na develop será testada a integração entre as funcionalidades recentemente adicionadas
5. Quando a equipe atestar a estabilidade da develop seu conteúdo é integrado a master

O nome da branch deve ser associado ao número da issue, e depois o nome da tarefa. Cada branch deve ter uma tarefa associada.

```
9-Nome-da-tarefa
```

---

## 3. Commit

Os commits devem ser atômicos (uma contribuição pequena para resolver um problema específico). A mensagem do commit deve conter o que foi feito de maneira sucinta e direta, além disso ela precisa estar em português, começar com um verbo e com a primeira letra maiúscula.

Exemplo de contribuição feita por um autor:
```
$ git commit -m "Adiciona estrutura inicial do documento de identidade visual"
```

Caso o commit tenha sido feito em cooperação com alguém, deve ser feita a co-autoria:

```
$ git commit -m "Cria model do usuário
>
>
Co-authored-by: name <name@example.com>
Co-authored-by: another-name <another-name@example.com>"
```

---

## 4. Pull request

Devem obedecer o template de pull request:

- Nome do Pull Request

O nome do pull request deve ser constituído por número da issue relacionada e seu nome.

```
#X nome da issue
```

- Conteúdo do Pull Request

O conteúdo do pull request deve ser constituído de uma lista contendo as principais modificações feitas.

```
1. Descrição
2. Issue Relacionada
3. Como Isso Foi Testado?
4. Capturas de Tela (se apropriado):
5. Tipos de Mudanças
```

- Critério de aceitação

Ex:

- [x] Testes criados.
- [x] Testes passando.
- [x] Build passando.

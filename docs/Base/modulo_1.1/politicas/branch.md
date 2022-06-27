# Políticas de Branch

## 1. Introdução

Esse documento tem como objetivo padronizar a nomenclatura e uso de branchs no repositório.

## 1. Padronização das Branches

### 1.1 Prefixos:

- ```main```
- ```documentation```
- ```hotfix```
- ```develop```
- ```feature```

### 1.2 Formato:
```
<prefixo>/assunto
```

Não esquecer de dividir as palavras(sempre minúsculas) do assunto com "-".
Exemplo: 

```
feature/novo-menu
```

### 1.3 Branches:

Esse repositório trabalhará com quatro tipos de branchs: main, hotfix, develop e feature.

- **Branch main:** É a branch que contém código em nível de produção, ou seja, o código mais maduro existente na aplicação. Todo o código novo produzido eventualmente é juntado com a branch main, em algum momento do desenvolvimento;
- **Branch develop:** É a branch que contém código em nível preparatório para o próximo deploy. Ou seja, quando features são terminadas, elas são juntadas com a branch develop, testadas (em conjunto, no caso de mais de uma feature), e somente depois as atualizações da branch develop passam pela fase de homologação e, se aprovadas, são juntadas com a branch main para produção. Sempre que uma correção for feita (hotfix) essa branch deverá ser atualizada;
- **Branches documentation:** Branches na qual são desenvolvidos os documentos do projeto. São ciradas começando com o prefixo **documentation/** Exemplo: ```documentation#49/template-documento```
- **Branches feature:** São branches no qual são desenvolvidos recursos novos para o projeto em questão. Essas branches tem por convenção nome começando com feature/issue-description (exemplo: feature/#54) e são criadas a partir da branch develop (pois um recurso pode depender diretamente de outro recurso em algumas situações), e, ao final, são juntadas com a branch develop.Exemplo: ```feature/implementacao-botao-principal```
- **Branchs hotfix:** Branches no qual são realizadas correções de bugs São criadas começando com o prefixo **hotfix/**. Exemplo: ```hotfix/correcao-politicas```


### 1.4 Princípios:

- Por ser um projeto voltado totalmente para um público brasileiro e por toda equipe ter mais afinidade com o português, foi decidido que todas as braches serão em pt-BR.


## 2. Referências

DULCETTI, Bruno. Padrões e nomenclaturas no Git. *BrunoDulcetti*. Disponível em: <https://www.brunodulcetti.com/padroes-e-nomenclaturas-no-git/>. Acesso em: 26 de jun. de 2022.

Políticas de Branches. Disponível em: <https://fga-eps-mds.github.io/2018.2-ComexStat/docs/politicaBranches>. Acesso em: 26 de jun. de 2022.

HADLER, Mikael. Utilizando o fluxo Git Flow. *Medium*. Disponível em: <https://medium.com/trainingcenter/utilizando-o-fluxo-git-flow-e63d5e0d5e04>. Acesso em: 26 de jun. de 2022.

## 3. Histórico de Versionamento


| Data       | Versão |  Descrição                     | Autor(es)                                               | Revisor |
| :--------: | :----: | :----------------------------: | :-----------------------------------------------------: | :-----: |
| 26/06/2022 |  1.0   | Criação da política de branchs | [Lameque Fernandes](https://github.com/LamequeFernandes)| Davi Marinho     |

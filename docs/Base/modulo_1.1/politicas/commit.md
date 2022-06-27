# Políticas de Commit

Padronização dos commits no projeto. 

## 1. Introdução

Esse documento tem como objetivo padronizar a nomenclatura e uso de commits no repositório.

## 2. Semântica do Commit

### 2.1 Princípios:

#### 2.1.1 Commits atômicos

Sempre dividir em pequenos commits, para melhor manutenção e rastreamento.

#### 2.1.2 Commits em português

Por se tratar de um projeto realizado por brasileiros, foi decidido que todos os commits serão em pt-BR.

### 2.2 Formato:
```
<tipo>: assunto
```

#### 2.2.1 Tipos:

- ```docs```: referente a documentação
- ```feat```: nova funcionalidade
- ```test```: relacionado a testes 
- ```fix```: correções
- ```refact```: relacionado a refatoração de código

#### 2.2.2 Assunto:

- Deve possuir até 50 caracteres
- Deve haver apenas letras minúsculas

*Exemplo de commit:*
```
git commit -m "docs: adicionado politicas de commit"
```

## 2. Referências

DARTORA, João. Tudo o que você precisa saber sobre commits semânticos. *Ilegra*. Disponível em: <https://ilegra.com/blog/tudo-o-que-voce-precisa-saber-sobre-commits-semanticos/>. Acesso em: 26 de jun. de 2022.

Políticas de Commit. Disponível em: <https://fga-eps-mds.github.io/2020.1-Grupo6/policies/commits/>. Acesso em: 26 de jun. de 2022.


## 3. Histórico de Versionamento

| Data       | Versão |  Descrição                     | Autor(es)                                               | Revisor |
| :--------: | :----: | :----------------------------: | :-----------------------------------------------------: | :-----: |
| 26/06/2022 |  1.0   | Criação da política de commits | [Lameque Fernandes](https://github.com/LamequeFernandes)| Davi Marinho     |

# Projeto Among Us
Este é um projeto que simula uma interface do jogo online Among Us.

## Tecnologias utilizadas
- **HTML** : estrutura do site
- __CSS__ : estilização do site
- *_JS_* : funções do site
- __IMG__ : background 



### Melhorias Possiveis
1. [x] Subir para GitHubPages
2. [x] Alterar os Alerts
3. [x] Deixar responsivo

### disponibilizado em
[GitHubPage](https://github.com/karilarissa/among_us)

[Vídeo para desenvolvimento do jogo](https://www.youtube.com/watch?v=C3WZrP0zlUk)


### Prints da tela

| ID | Frame da Tela | 
|----|---------------|
|  1 | imagem de fundo  |
| 2  | ![tela ilustrativa](background.jpg) |

#### Função Principal
```js:
function generateOrder() {
    for (let i = 0; i < 5; i++) {
        let index = Math.floor(Math.random() * (showNum.length - 0)) + 0;
        order.push(index);
    }
}
```

#### comando git
para iniciar o projeto
```bash:
git init
```
```bash:
git add
```
```bash:
git status
```

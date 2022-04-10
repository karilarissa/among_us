# Jogo da Velha
Simulador do clássico jogo da velha.

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

[Vídeo para desenvolvimento do jogo](https://www.youtube.com/watch?v=M258B1b_pMs)


### Prints da tela

| ID | Frame da Tela | 
|----|--------------- |
|  1 | interface |
| 2  | ![tela ilustrativa](https://user-images.githubusercontent.com/100212761/162634700-ea1d1b7a-5b92-462f-991b-b78221e17a88.png)) |

#### Função Principal
```js:
function escolherQuadrado(id) {
    if (vencedor !== null) {
        return;
    }

    var quadrado = document.getElementById(id);
    if (quadrado.innerHTML !== '-') {
        return;
    }

    quadrado.innerHTML = jogador;
    quadrado.style.color = '#000';

    if (jogador === 'X') {
        jogador = 'O';
    } else {
        jogador = 'X';
    }

    mudarJogador(jogador);
    checaVencedor();
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

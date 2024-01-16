# Snake_DJPM - Android
## Trabalho realizado por:
- João Sousa - 25613
- Miguel Sousa - 25977
- Tomás Carvalho - 25963
## Índice

- 
- Descrição
- Layout
- Features
- Instalação
- Controles
- Firebase

### Descrição

Snake_djpm é um jogo inspirado no jogo "Snake" original, desenvolvido em kotlin, neste jogo o objetivo é conseguir apanhar o maior número de comida possível, cada pedaço de comida obtido corresponde a um ponto.

![menu](https://github.com/JPMini84/Snake_djpm/assets/118979969/3df2b31f-4abe-41fe-9852-62872357c0ef)
![jogo](https://github.com/JPMini84/Snake_djpm/assets/118979969/842375c2-5d9a-4e4a-96e3-0ba3e6058ff6)
![Score](https://github.com/JPMini84/Snake_djpm/assets/118979969/c56fe61a-732b-41bd-abf4-b56f618267ed)

### Layout

Quando se abre o jogo é disponibilizado ao jogador a opção de começar, depois que começar podera jogar, depois quando o jogador perder podera visualizar o seu score e o highscore.

### Features
- Controlos: Simples de aprender, bastando apenas pressionar a seta que a aponta para a direção que deseja ir e o botão de pause que lhe permite pausar o jogo.
- Highscore: Permeti lhe saber qual é o maior highscore alguma vez feito.

### Controles
Clique nos botões na tela para movimentar a cobra.

## Firebase
### Graddle
``` kt
implementation(platform("com.google.firebase:firebase-bom:32.7.0"))
implementation("com.google.firebase:firebase-analytics")
implementation("com.google.firebase:firebase-auth")
implementation("com.google.firebase:firebase-database-ktx:+")
implementation ("com.google.firebase:firebase-firestore-ktx:+")
implementation ("com.google.firebase:firebase-firestore:+")
```
### Packages
``` kt
import com.google.firebase.Firebase
import com.google.firebase.auth.FirebaseAuth
import com.google.firebase.auth.auth
import java.util.*
import kotlin.math.pow
import kotlin.math.sqrt
import com.google.firebase.firestore.FirebaseFirestore
```
### Instalação
1. Clone o repositorio:
  [https://github.com/GR3ENP1G08/Snake_djpm](https://github.com/MiguelVS2004/Snake-Android)
2. Abra-o projeto no Android Studio e abra-o utilizando um telemóvel ou o emulador.
3. Aproveite o jogo.

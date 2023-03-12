![Screen do projeto](https://aplicativoscriativos.com/imagens_projetos/lottie.gif)

## Lottie Splash screen
Lottie é um formato de arquivo de animação de código aberto que é pequeno, de alta qualidade, programável,
interativo e pode ser manipulado em tempo de execução. Os 500 principais aplicativos da App

## Uso
Para usar a implementação deste projeto, verifique o projeto.

1. adicione a dependençia da biblioteca ao seu build.gradle

dependencies {
                implementation "com.airbnb.android:lottie:5.2.0"
            }

2. Inclua em seu xml layout LottieAnimationView

    <com.airbnb.lottie.LottieAnimationView
        android:id="@+id/animacao"
        android:layout_width="300dp"
        android:layout_height="300dp"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="60dp"
        app:lottie_fileName="burguer.json"
        app:lottie_autoPlay="true"
        app:lottie_loop="true"/>
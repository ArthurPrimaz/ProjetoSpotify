# Spotify Clone

Protótipo de app Android em Java que imita o visual do Spotify, com tema escuro e o verde característico. Projeto acadêmico da disciplina de Desenvolvimento Mobile, sem vínculo com o Spotify.

## Telas

**Login**
- Campos de e-mail e senha
- Botão **Entrar**, que abre o player
- Botão **Cadastrar**, que abre a tela de cadastro

**Cadastro**
- Campos de nome, e-mail e senha
- Botão **Salvar Cadastro**, que exibe a mensagem "Cadastro realizado!" e volta para o login

**Player**
- Capa, nome da música e botão **Play/Pause**
- Reprodução de um arquivo de áudio local com `MediaPlayer`

## Tecnologias
- Java 11
- Android SDK (minSdk 24)
- AndroidX AppCompat, Material Components e ConstraintLayout
- Navegação entre telas com `Intent`
- Reprodução de áudio com `MediaPlayer`

## Como rodar
1. Clone o repositório
2. Abra a pasta `SpotifyClone` no Android Studio
3. Aguarde a sincronização do Gradle
4. Execute em um emulador ou celular com Android 7.0 ou superior

## Limitações atuais
- O login não valida e-mail nem senha
- O cadastro não salva os dados
- O player toca apenas uma música fixa, sem lista de faixas, barra de progresso nem troca de música

## Próximos passos
- Validar login e salvar cadastros (por exemplo, com SQLite)
- Adicionar lista de músicas e controles de avançar e voltar

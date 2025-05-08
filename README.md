# android_crypto_monitor-main
📱 Android CryptoMonitor
CryptoMonitor é um aplicativo Android desenvolvido em Kotlin com o objetivo de exibir, de forma simples e eficiente, a cotação atual do Bitcoin em reais (BRL). Ele realiza a consulta de dados por meio da API pública do Mercado Bitcoin, permitindo que o usuário veja a variação do preço da criptomoeda com apenas um clique.

🧾 Sobre o Projeto
Este projeto foi criado com fins educacionais e demonstra o uso de requisições HTTP em aplicativos Android utilizando Retrofit, juntamente com a conversão de dados JSON via Gson. Também serve como exemplo de como utilizar o View Binding para manipular componentes da interface de forma segura e moderna.

Ao abrir o aplicativo, o usuário encontra um botão "Atualizar". Ao pressioná-lo, o app faz uma requisição à API, obtém o preço mais recente do Bitcoin e exibe o valor juntamente com a data e hora da última atualização.

O projeto é ideal para quem está aprendendo desenvolvimento Android moderno com Kotlin e deseja ver na prática como consumir APIs REST, trabalhar com JSON, e estruturar um app simples com foco na responsividade da interface.

🖼️ Capturas de Tela
Exemplos fictícios de tela (adapte se você tiver screenshots):

Tela Inicial	Após Atualizar

⚙️ Funcionalidades
Busca em tempo real da cotação do Bitcoin (BTC).

Exibição da data e hora da última consulta.

Atualização manual ao toque de um botão.

Layout simples, limpo e funcional.

🛠️ Tecnologias Utilizadas
Kotlin – linguagem principal de desenvolvimento.

Retrofit – biblioteca para requisições HTTP.

Gson – para converter JSON em objetos Kotlin.

View Binding – acesso seguro a componentes de layout.

🚀 Como Executar o Projeto
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/Leonardo-Mazzuca/android-cryptomonitor.git
Abra o projeto no Android Studio.

Conecte um dispositivo Android ou use um emulador.

Clique em Run para compilar e executar o aplicativo.

📄 Licença
Este projeto está licenciado sob a Licença MIT.

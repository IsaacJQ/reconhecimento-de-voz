Botão "Falar número": Adicionei um novo botão que inicia o reconhecimento de voz.

Função startRecognition: Essa função utiliza a Web Speech API para escutar a fala do usuário. Quando um número é reconhecido, ele é colocado no campo de texto e o jogo é testado automaticamente.

Reconhecimento de voz: A função de reconhecimento é configurada para ouvir em português (pt-BR) e processar o resultado, chamando a função testejogo() após a fala.

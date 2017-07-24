# firebase_exemplo_de_uso

Um simples exemplo de uso do Firebase


## Criar um conta gratuita no Firebase

Para criar uma nova conta acesse [Site do Firebase](https://firebase.google.com/)


## Configuração em sua aplicação

O firebase lhe fornecerá alguns dados para configurar e inicializar a conecexão com o Firebase.

    // Initialize Firebase
    var config = {
        apiKey: "SuaAPIKey",
        authDomain: "seu-banco-no-firebase.firebaseapp.com",
        databaseURL: "https://seu-banco-no-firebase.firebaseio.com",
        projectId: "seu-banco-no-firebase",
        storageBucket: "",
        messagingSenderId: "SeuSenderId"
    };
    firebase.initializeApp(config);
    

Depois de configurado, é só usar a imaginação.

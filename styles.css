document.addEventListener('DOMContentLoaded', () => {
    const terminalContainer = document.getElementById('terminal-container');
    const term = new Terminal();
    term.open(terminalContainer);
    term.write('Bienvenido al juego!\r\n');
    
    let gameStarted = false;

    term.onData(data => {
        if (!gameStarted) {
            term.write('\r\nIniciando el juego...\r\n');
            gameStarted = true;
        } else {
            term.write(data); // Reflejar lo que el usuario escribe
            // Lógica del juego aquí
            // Por ejemplo, puedes analizar el comando del usuario y actualizar el estado del juego
        }
    });
});

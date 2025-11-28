class Heroi {
    constructor(nome, idade, tipo) {
        this.nome = nome;
        this.idade = idade;
        this.tipo = tipo;
    }

    atacar() {
        let ataque;

        // Define o ataque de acordo com o tipo
        if (this.tipo === "ninja") {
            ataque = "shuriken";
        }

        // Exibe a mensagem final
        console.log("O ninja atacou usando shuriken");

    }
}

// Criando o herói 
const heroi = new Heroi("Yoshimitsu", 100, "ninja");

// Chamando o método atacar
heroi.atacar();

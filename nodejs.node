class Guerreiro {
    constructor(heroiNome, heroiIdade, classe) {
        this.nome = heroiNome;
        this.idade = heroiIdade;
        this.tipo = classe;
    }

    atacar() {
        let tipoDeAtaque;

        // Definindo a descrição do ataque com base no tipo do herói
        switch (this.tipo.toLowerCase()) {
            case 'mago':
                tipoDeAtaque = 'magia';
                break;
            case 'guerreiro':
                tipoDeAtaque = 'espada';
                break;
            case 'monge':
                tipoDeAtaque = 'artes marciais';
                break;
            case 'ninja':
                tipoDeAtaque = 'shuriken';
                break;
            default:
                tipoDeAtaque = 'ataque desconhecido';
                break;
        }

        // Exibindo a mensagem do ataque
        console.log(`O ${this.tipo} atacou usando ${tipoDeAtaque}.`);
    }
}

// Função principal para executar o código
function executar() {
    // Criando instâncias de heróis
    const heroico1 = new Guerreiro('Gandalf', 100, 'mago');
    const heroico2 = new Guerreiro('Aragorn', 87, 'guerreiro');
    const heroico3 = new Guerreiro('Shifu', 45, 'monge');
    const heroico4 = new Guerreiro('Naruto', 25, 'ninja');

    // Atacando
    heroico1.atacar(); // Saída: O mago atacou usando magia.
    heroico2.atacar(); // Saída: O guerreiro atacou usando espada.
    heroico3.atacar(); // Saída: O monge atacou usando artes marciais.
    heroico4.atacar(); // Saída: O ninja atacou usando shuriken.
}

// Executa o programa
executar();

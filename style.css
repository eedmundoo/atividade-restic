function toggleMenu() {
    const menu = document.getElementById('menu');
    menu.classList.toggle('show');
}

function calcularIMC() {
    const peso = parseFloat(document.getElementById('peso').value);
    const altura = parseFloat(document.getElementById('altura').value);
    const imc = (peso / (altura * altura)).toFixed(2);

    let classificacao;
    if (imc < 18.5) {
        classificacao = "Baixo peso";
    } else if (imc < 24.9) {
        classificacao = "Peso normal";
    } else if (imc < 29.9) {
        classificacao = "Sobrepeso";
    } else {
        classificacao = "Obesidade";
    }

    document.getElementById('resultado').innerHTML = `Seu IMC é ${imc} (${classificacao})`;
}

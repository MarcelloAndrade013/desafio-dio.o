function calcular(n1, n2, operador) {
    switch (operador) {
        case '+':
            return n1 + n2;
        case '-':
            return n1 - n2;
        case '*':
            return n1 * n2;
        case '/':
            return n2 !== 0 ? n1 / n2 : "Erro: Divisão por 0";
        default:
            return "Operador inválido";
    }
}

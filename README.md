# atividade-ternarias
public class ExerciciosTernaria {
    public static void main(String[] args) {
        
        // 1. Par ou Ímpar
        int numero = 5;
        String resultado1 = (numero % 2 == 0) ? "Par" : "Ímpar";
        System.out.println("1. " + resultado1);

        // 2. Maior de idade ou Menor de idade
        int idade = 18;
        String resultado2 = (idade >= 18) ? "Maior de idade" : "Menor de idade";
        System.out.println("2. " + resultado2);

        // 3. Positivo, Negativo ou Zero
        String resultado3 = (numero > 0) ? "Positivo" : (numero < 0) ? "Negativo" : "Zero";
        System.out.println("3. " + resultado3);

        // 4. Múltiplo de 5
        String resultado4 = (numero % 5 == 0) ? "Múltiplo de 5" : "Não é múltiplo de 5";
        System.out.println("4. " + resultado4);

        // 5. Ano Bissexto
        int ano = 2024;
        String resultado5 = ((ano % 4 == 0 && ano % 100 != 0) || (ano % 400 == 0)) ? "Bissexto" : "Não é Bissexto";
        System.out.println("5. " + resultado5);

        // 6. Pode Dirigir
        boolean temCarteiraDeMotorista = true;
        String resultado6 = (idade >= 18 && temCarteiraDeMotorista) ? "Pode Dirigir" : "Não pode Dirigir";
        System.out.println("6. " + resultado6);

        // 7. Positivo e Par
        String resultado7 = (numero > 0 && numero % 2 == 0) ? "Sim" : "Não";
        System.out.println("7. " + resultado7);

        // 8. Aprovado ou Reprovado
        double nota = 7.5;
        String resultado8 = (nota >= 7) ? "Aprovado" : "Reprovado";
        System.out.println("8. " + resultado8);

        // 9. Maior ou Menor ou Igual
        int numero1 = 10, numero2 = 5;
        String resultado9 = (numero1 > numero2) ? "Maior" : "Menor ou Igual";
        System.out.println("9. " + resultado9);

        // 10. Alto ou Baixo
        String resultado10 = (numero > 100) ? "Alto" : "Baixo";
        System.out.println("10. " + resultado10);

        // 11. Vogal ou Consoante
        char letra = 'a';
        String resultado11 = (letra == 'a' || letra == 'e' || letra == 'i' || letra == 'o' || letra == 'u') ? "Vogal" : "Consoante";
        System.out.println("11. " + resultado11);

        // 12. Par e Positivo, Par e Negativo, Ímpar e Positivo, ou Ímpar e Negativo
        String resultado12 = (numero % 2 == 0 && numero > 0) ? "Par e Positivo" :
                             (numero % 2 == 0 && numero < 0) ? "Par e Negativo" :
                             (numero % 2 != 0 && numero > 0) ? "Ímpar e Positivo" : "Ímpar e Negativo";
        System.out.println("12. " + resultado12);

        // 13. Maior dos dois números
        String resultado13 = (numero1 > numero2) ? "Maior" : (numero1 < numero2) ? "Menor" : "Igual";
        System.out.println("13. " + resultado13);

        // 14. Dentro ou Fora do Intervalo
        String resultado14 = (numero >= 10 && numero <= 50) ? "Dentro do intervalo" : "Fora do intervalo";
        System.out.println("14. " + resultado14);

        // 15. FizzBuzz
        String resultado15 = (numero % 3 == 0 && numero % 5 == 0) ? "FizzBuzz" : String.valueOf(numero);
        System.out.println("15. " + resultado15);

        // 16. Conversão de Booleano
        boolean valor = true;
        String resultado16 = (valor) ? "Sim" : "Não";
        System.out.println("16. " + resultado16);

        // 17. Qualificado para Desconto
        boolean isEstudante = false;
        String resultado17 = (idade > 60 || isEstudante) ? "Qualificado para Desconto" : "Não Qualificado para Desconto";
        System.out.println("17. " + resultado17);

        // 18. Tipo de Triângulo
        int lado1 = 3, lado2 = 3, lado3 = 3;
        String resultado18 = (lado1 == lado2 && lado2 == lado3) ? "Equilátero" :
                             (lado1 == lado2 || lado2 == lado3 || lado1 == lado3) ? "Isósceles" : "Escaleno";
        System.out.println("18. " + resultado18);

        // 19. Divisível por 2 ou 3
        String resultado19 = (numero % 2 == 0 || numero % 3 == 0) ? "Divisível" : "Não divisível";
        System.out.println("19. " + resultado19);

        // 20. Recuperação, Aprovado ou Reprovado
        String resultado20 = (nota >= 7) ? "Aprovado" : (nota >= 5 && nota < 7) ? "Recuperação" : "Reprovado";
        System.out.println("20. " + resultado20);

        // 21. Par ou Ímpar, Positivo ou Negativo
        String resultado21 = (numero % 2 == 0) ? (numero > 0 ? "Par e Positivo" : "Par e Negativo") :
                             (numero > 0 ? "Ímpar e Positivo" : "Ímpar e Negativo");
        System.out.println("21. " + resultado21);

        // 22. Frete grátis
        double precoProduto = 120;
        String resultado22 = (precoProduto >= 100) ? "Frete grátis" : "Frete pago";
        System.out.println("22. " + resultado22);

        // 23. Senha válida
        String senha = "12345678";
        String resultado23 = (senha.length() >= 8) ? "Senha válida" : "Senha inválida";
        System.out.println("23. " + resultado23);

        // 24. Número Perfeito
        int somaDivisores = 6;
        String resultado24 = (somaDivisores == numero) ? "Perfeito" : "Não perfeito";
        System.out.println("24. " + resultado24);

        // 25. Dia útil ou Final de semana
        int diaSemana = 6; // 1 = Segunda-feira, 7 = Domingo
        String resultado25 = (diaSemana >= 2 && diaSemana <= 6) ? "Dia útil" : "Final de semana";
        System.out.println("25. " + resultado25);

        // 26. Pode votar
        String resultado26 = (idade >= 16) ? "Pode votar" : "Não pode votar";
        System.out.println("26. " + resultado26);

        // 27. Positivo ou Zero
        String resultado27 = (numero >= 0) ? "Positivo ou Zero" : "Negativo";
        System.out.println("27. " + resultado27);

        // 28. Dentro ou Fora do Intervalo de 20 a 30
        String resultado28 = (numero >= 20 && numero <= 30) ? "Dentro do intervalo" : "Fora do intervalo";
        System.out.println("28. " + resultado28);

        // 29. Adulto, Idoso ou Jovem
        String resultado29 = (idade >= 18 && idade <= 60) ? "Adulto" : (idade > 60) ? "Idoso" : "Jovem";
        System.out.println("29. " + resultado29);

        // 30. Aprovado ou Reprovado com base na média
        double nota1 = 5.0, nota2 = 7.0;
        double media = (nota1 + nota2) / 2;
        String resultado30 = (media >= 6) ? "Aprovado" : "Reprovado";
        System.out.println("30. " + resultado30);
    }
}

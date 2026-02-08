# Projeto1[ExerciciosAlura.java](https://github.com/user-attachments/files/25170654/ExerciciosAlura.java)
import java.util.Scanner;

public class Exercicios {
    public static void main(String[] args) {
        double nota1 = 8.5;
        double nota2 = 6.5;
        double media = (nota1 + nota2) / 2;
        System.out.println("media" + media);

    }
}

class Exercicios2 {
    public static void main(String[] args) {
        double numeroFuturo = 52.5;
        int valorRecorrente = (int) numeroFuturo;
        System.out.println("Futuro Casting " + valorRecorrente);
    }
}

class Exercicio3 {
    public static void main(String[] args) {  //Declare uma variável do tipo char (letra) e uma variável do tipo String (palavra). Atribua valores a essas variáveis e concatene-as em uma mensagem.

        char genero = 'M';
        String name = "Kerrison";

        String mensagem = "Nome e " + name;
        String mensagem2 = "Genero " + genero;
        System.out.println(mensagem);
        System.out.println(mensagem2);
    }
}

class Exercicios4 {
    public static void main(String[] args) {
        //preço produto 2300R$
        double preçoProduto = 2300.13;
        int quantidade = 16;
        double total = preçoProduto * quantidade;
        String mensagem = "O valor total da compra e " + total;
        System.out.println(mensagem);
    }
}

class Exericicios5 {
    public static void main(String[] args) {
        double valorEmDolar = 5;
        double taxaDaConversao = 4;
        double valorEmReal = valorEmDolar * taxaDaConversao;

        System.out.println("O valor em real e " + valorEmReal);

    }
}

class Exercicios6 {
    public static void main(String[] args) {
        double preçoOriginal = 150;

        double percentualDesconto = 10.0;
        double valorDesconto = (percentualDesconto / 100.0) * preçoOriginal; //valor do desconto e 15
        double novoPreço = preçoOriginal - valorDesconto; // o calculo aqui vai ser 150 -15 = 135

        System.out.println("Preço original : R$" + preçoOriginal);
        System.out.println("Desconto de R$" + percentualDesconto);
        System.out.println("Novo preço com desconto : R$" + novoPreço);
    }
}

class exerciciosPrimitivos {
    public static void main(String[] args) {
        double altura = 19.5;
        int alturaint = (int) altura;
        System.out.println("o valor inteiro do produto e : " + alturaint);
    }
}

class mediaNOta {
    public static void main(String[] args) {
        double nota1 = 7.5;
        double nota2 = 8.0;
        double nota3 = 9.0;

        double media = (nota1 + nota2 + nota3) / 3;
        System.out.println("A media das notas e " + media);

    }


}

class ConversaoDeTemperatura {
    public static void main(String[] args) {

        int celsius = 20;
        double Fahrenheit = (celsius * 9 / 5) + 32;
        System.out.println("A temperatura em Fahrenheit e " + Fahrenheit);
    }
}

class ExerciciosDificil {
    public static void main(String[] args) {
        String titulo = "Navio negreiro";
        String autor = "Kerrison";
        int paginas = 169;
        double preçoDOLivro = 210.99;
        char categoria = 'F';

        String categoriaDescricao;

        if (categoria == 'F') {
            categoriaDescricao = "Ficçao";
        } else if (categoria == 'N') {
            categoriaDescricao = "Não-ficçao";
        } else if (categoria == 't') {
            categoriaDescricao = "Tecnologia";
        } else if (categoria == 'H') {

            categoriaDescricao = "Historia";
        }
        System.out.println(" Livro cadastrado " + titulo + " do autor " + autor + " quantidade de paginas " + paginas + " quantidade maxima de paginas " + paginas + " Valor do livro " + preçoDOLivro);

    }
}

class exercicio121 { //Você trabalha em um e-commerce e precisa classificar os produtos em diferentes categorias com base no preço.
    public static void main(String[] args) {


        double preço = 150;

        if (preço <= 50) {
            System.out.println("Categoria do produto : Economico ");
        } else if (preço <= 50 && preço <= 200) {
            System.out.println("Categoria do produto : Intermediario");
        } else if (preço < 200) {
            System.out.println("Categoria do produto : Premium");
        } else {
            System.out.println("Invalido");
        }
        System.out.println(preço);
    }
}

class PArouImpar {
    public static void main(String[] args) {

        int numeração = 8;

        if (numeração % 2 == 0) {
            System.out.println("numero par");
        } else {
            System.out.println("impar");
        }
        System.out.println(numeração);
    }
}

class dolar {
    public static void main(String[] args) {
        double valorReais = 451.50;
        double valorCambio = 5.25;
        double valorDoolar = valorReais / valorCambio;
        System.out.println("O valor em dollares e " + valorDoolar);

    }
}

class exercicio7 {
    public static void main(String[] args) {
        String livro = "Pequeno principe";
        String Autor = "kerrison";
        int paginas = 555;
        double valor = 169.90;
        char categoria = 'f';

        String categoriaDescrição;
        if (categoria == 'f') {
            System.out.println("Ficção");
        } else if (categoria == 'N') {
            System.out.println("Não-Ficção");
        } else if (categoria == 'T') {
            System.out.println("Tecnologia");
        } else if (categoria == 'H') {
            System.out.println("Historia");
        } else {
            System.out.println("invalido");
        }
        System.out.println(" Livro cadastrado " + livro + " Autor do livro " + livro + " quantidade de paginas " + paginas + " valor do livro " + livro);
    }

}

class produtosgg {
    public static void main(String[] args) {
        double preço = 211.0;

        if (preço <= 50) {
            System.out.println("Produto economico");
        } else if (preço > 50 && preço <= 200) {
            System.out.println("Produto intermediario ");
        } else {
            System.out.println("Produto premium");
        }
        System.out.println(preço);
    }
}

class imparoupar {
    public static void main(String[] args) {

        int numero = 7;


        if (numero % 2 == 0) {
            System.out.println("Par");
        } else {
            System.out.println("Impar");
        }
    }
}

class conersao {
    public static void main(String[] args) {
        double valorReais = 451.50;
        double convesaoDoDollar = 5.25;

        double calcularDoolar = (valorReais / convesaoDoDollar);

        System.out.println("O valor em dolar e " + calcularDoolar);

    }
}

class indenticarOErro {
    public static void main(String[] args) {
        int idade = 17;
        String mensagem;

        if (idade >= 18) {
            mensagem = "voce de maior ";
        } else {
            mensagem = "voce e menor";
        }
        System.out.println(mensagem);
    }

}

class viagem {
    public static void main(String[] args) {
        double consumoMedio = 12.5;
        double capacidadeTanque = 50;
        double combustivelAtual = 20;
        double distanciaViagem = 200;

        double autonomiaMaxima = consumoMedio * capacidadeTanque;
        double autonmiaAtual = combustivelAtual * combustivelAtual;
        System.out.println("Autonomia maxima do veiculo : %.1f km%n :" + autonomiaMaxima);
        System.out.println("Autonomia atual : %.1 km%n : " + autonmiaAtual);

        if (autonmiaAtual >= distanciaViagem) {
            System.out.println("Viagem incompleta, porem combustivel alto ");
        } else {
            System.out.println("Viagem completa, porem combustivel baixo");
        }

    }
}


class viagem2 {
    public static void main(String[] args) {
        double capidadeTanque = 12.5; //carro faz 12,5km a cada litro
        double maximoCOmbustivel = 50;
        double disponivelLitros = 20;
        double distanciaVIagem = 200; //distancia da viagem

        double quantosKmpercorrido = distanciaVIagem * capidadeTanque;
        double quantidadeDeGasolinaAtual = maximoCOmbustivel * disponivelLitros;
        System.out.println(" Quantos km percorrido: %.1 km/n " + quantosKmpercorrido);
        System.out.println(" Quantidade de gasolina atual " + quantidadeDeGasolinaAtual);

        if (quantosKmpercorrido >= distanciaVIagem) {
            System.out.println(" Viagem completa ");
        } else {
            System.out.println(" Viagem incompleta ");
        }
    }
}

class ifEelse { //se vai executar um bloco de codigo sim ou nao. if = se  else = se não  and = verdadeiro / verdadeoro
    public static void main(String[] args) { //or = falso / falso 

    }
}

class ImparPar3 {
    public static void main(String[] args) {  // melhor jeito que eu sei fazer
        Scanner sc = new Scanner(System.in);

        System.out.println("escolha seu numero 0 a 10");
        int numero = sc.nextInt();


        if (numero % 2 == 0) {
            System.out.println("Numero par " + numero);
        } else {
            System.out.println("Impar " + numero);
        }
    }
}

class NotaEaprovação {
    public static void main(String[] args) {
        double notaDoAluno = 4;

        if (notaDoAluno >= 9) {
            System.out.println("Parabéns! Excelente desempenho 🎉 Média: " + notaDoAluno);

        } else if (notaDoAluno >= 7) {
            System.out.println("Parabéns! Você foi aprovado com média " + notaDoAluno);

        } else if (notaDoAluno >= 6) {
            System.out.println("Recuperação, com a média de " + notaDoAluno);

        } else {
            System.out.println("Reprovado, com a média de " + notaDoAluno);
        }
    }
}

class SenhaExercicios {
    public static void main(String[] args) {
        String senha = "123456";
        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite a senha ");
        String tentativaDeSenha = scanner.nextLine();
        scanner.close();


        if (tentativaDeSenha.equals(senha)) {
            System.out.println("Acesso permitivo");
        }else  {
            System.out.println("Acesso Negado");
        }
    }

}



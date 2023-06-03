void main() {
  //Variaveis que armazena numeros inteiros
  int indade = 33;
  print(indade);

  // Variaveis que armazena numeros decimais
  double raio = 10.5;
  print(raio);

  // Variaveis que armazena textos
  String nome = "Victor";
  print(nome);

  //Variavel que armazena verdadeiro ou false
  bool ligado = true;
  print(ligado);

  //Lista Generica
  List numerosGenericos = [10, "Victor", true, 20];
  print(numerosGenericos);
  
  //Lista de numeros Inteiros
  List numerosInteiro = [1, 2, 3, 4];
  print(numerosInteiro);

  //Variavel MAP
  Map<String, String> nomeSobrenome = {"Victor": "Padovam", "Caio": "Silva"};
  print(nomeSobrenome);
  
  //Sem tipo
  var nomeTeste = "Victor";
  print("O nome é $nomeTeste");

  //Operaçoes
   int soma = 1;
   int dois = 2;
   int sum = soma + dois;
   print(sum);

   int subtrai = 1;
   int menos = 2;
   int sumMenos = subtrai - menos;
   print(sumMenos);
}

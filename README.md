Scanner entrada = new Scanner(System.in);


    int tempo, cliente, media;
    

System.out.println("quantos clientes?");
 cliente = entrada.nextInt();

  System.out.println("seu tempo cliente 1");
 tempo = entrada.nextInt();
  System.out.println("seu tempo cliente 2");
 tempo = entrada.nextInt();
  System.out.println("seu tempo cliente 3");
 tempo = entrada.nextInt();
  System.out.println("seu tempo cliente 4");
 tempo = entrada.nextInt();
  System.out.println("seu tempo cliente 5");
 tempo = entrada.nextInt();
 

 while (tempo<0) {
    System.out.println("Isso e impossivel");
 }


for (i = 1; i <=5; i ++) {
    System.out.println("Tempo de espera " + cliente  + i);
} if(cliente>=0) {
System.out.println("Atendimento");
}
(cliente / tempo) = media;

if (media<=10) {
System.out.println("Atendimento agil");
} else if (media<=20) {
    System.out.println("regular");
} else (media>20) {
    System.out.println("troca esses funcionarios"); 
}

# Kalkulator
Kalkulator "+ i -"



        import java.util.Scanner;

        public class Test {
        public static void main(String args[]) {
        
                   //System.out.println() - Wyświetla nam żądaną wartość
                   //Prócz tekstu mozesz dodac zmienną (po nawiasie dodaj +zmienna)
        
        System.out.println("Witaj w apliakcji 'Kalkulator 2018'");
        System.out.println("\n");
        System.out.println("Aby rozpocząc podaj pierwszą liczbe...");

        int a;
        int b;
               
                   //Scanner oznacza zapisywanie do wybranej zmiennej (np. "a") to co 
                   //Napiszemy gdy program o to poprosi po uruchomieniu go.
        
        Scanner wejscie = new Scanner(System.in);
        a = wejscie.nextInt();

        System.out.println("  ");

        System.out.println("Twoja pierwsza liczba to :  " + a);
        System.out.println("Podaj liczbę drugą...");

        wejscie = new Scanner(System.in);
        b = wejscie.nextInt();

        System.out.println("  ");

        
                   //int c - czyli zmienna "c" równa się sumie po dodaniu wartości "a" i "b"
        
        int c = a+b;

        System.out.println("Podane liczby to:  ");
        System.out.println("  ");
        System.out.println("Pierwsza:  "+a);
        System.out.println("Druga:  "+b);
        System.out.println("  ");
        System.out.println("Wynik dodawania to:  " +c);

        System.out.println("------------------------------------------------------");



                   //        @Kacper @Gawlik
                   //        Do wglądu dla każego, tzw. "Podstawy, podstaw"! =)

            }
        }

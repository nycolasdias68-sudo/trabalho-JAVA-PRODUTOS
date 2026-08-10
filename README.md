/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package javaapplication11;

import java.util.Scanner;

/**
 *
 * @author Aluno
 */
public class JavaApplication11 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        System.out.println("Digite o primeiro numero");
        Scanner teclado = new Scanner (System.in);
        int n1 = teclado.nextInt();
        System.out.println("Digite o Segunda valor maior ");
        int n2 = teclado.nextInt();
        int nl = 0;
        int ale = (int) (Math.random()*(nl - n2 + 1)+ n2);
        System.out.println("O valor aleatorio"+ ale);
        
        // TODO code application logic here
    }
    
}

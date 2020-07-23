# matrix_multiphication
//Умножение двух матриц заданного размера. Элементы матриц заданы в коде

package org.apache.poi.hssf.usermodel;

import java.sql.SQLOutput;

public class Main {

    public static void main(String[] args) {
        int ni = 3;
        int nj = 5;
        int arr1[][] = new int[][]{
                {5, 8, 3, 1, 6},
                {9, 0, 6, 3, 1},
                {4, 8, 1, 3, 4}};

        int arr2[][] = new int[][]{
                {6, 4, 8, 2, 1},
                {1, 1, 2, 3, 6},
                {9, 0, 4, 3, 1}};



        for (int i = 0; i < ni; i++) {
            System.out.println();
            for (int j = 0; j < nj; j++) {
                System.out.print(arr1[i][j] + " " );
            }
        }
        System.out.println();
        System.out.println("------------------------");


        for (int i=0; i<ni; i++){
            System.out.println();
            for(int j=0; j<nj; j++){
                System.out.print(arr2[i][j]+ " " );
            }
        }

        System.out.println();
        System.out.println("------------------------");
        System.out.println("Новая перемноженная матрица");

        for (int i=0; i<ni; i++) {
            System.out.println();
            for(int j=0; j<nj; j++) {
                System.out.print(arr1[i][j] * arr2[i][j] + " ");
            }
        }

    }
}

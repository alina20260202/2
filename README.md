Стрсница 87 Номер 6

House: id, Номер квартиры, Площадь, Этаж, Количество комнат, Улица, Тип здания, Срок эксплуатации.


# задача 1

package by.baltkrievs;

import java.io.BufferedReader;
import java.io.IOException;
import java.util.Arrays;
import java.util.Objects;

public class Main {

public static void main(String[] args) throws IOException, InterruptedException {

// read line from console
BufferedReader Utils;
Utils = null;
String rString = Utils.readLine();
// try parse string to integer array and return it
int[] intArray = new int[0];
Utils.mark(Integer.parseInt(rString));
// instance of Group A
TaskAtaskA = new TaskA();

taskA.findLongestAndShortestElement(intArray);


taskA.showNumbersLessThanAverage(intArray);

taskA.showFirstDifferentNumber(intArray);

taskA.showPalindrome(intArray);


TaskBtaskB = new TaskB();

        int[] interval = {-1, 4};
        int valueToCheck = 3;
booleanisBelongs = taskB.isBelongsToInterval(valueToCheck, interval);
        if (isBelongs){
System.out.println("Value " + valueToCheck +
" belongs to interval " + Arrays.toString(interval));
}else{
System.out.println("Value " + valueToCheck +
" doesn't belong to interval " + Arrays.toString(interval));
}


taskB.showMatrix(26);

        double a = (double)Integer.valueOf(args[0]);
        double b = (double)Integer.valueOf(args[1]);
        double c = (double)Integer.valueOf(args[2]);
taskB.solveQuadraticEquation(a, b, c);

taskB.printMonth(12);

TaskCtaskC = new TaskC();
Object Matrix;
Matrix = null;
        double[][] matrix = getDoubles(Matrix);
Objects.equals(Matrix, matrix);
System.out.println(" 1");

taskC.getSumOfELementsInPositiveRange();
System.out.println("65");

        double[][] tMatrix = taskC.transposeMatrix();
Matrix.equals(tMatrix);
System.out.println("67");

Matrix.equals(taskC.turnMatrix());
System.out.println("15");


Object o = taskC.turnMatrix(matrix);
taskC.turnMatrix(matrix);
System.out.println("46");

Matrix.equals(taskC.deleteMaxRowsCols());
}

private static double[][] getDoubles(Object matrix) {
double[][] doubles = new double[0][];
        return doubles;
}


}

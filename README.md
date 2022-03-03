Learn Java

public class ControlStock {

    int costumerid;
    String nameproduct;
    double stockavailable;
    double valuestock;

    public int costumerid() {
    	return costumerid;
    }


    public String nameproduct() {
    	return nameproduct;
    }

    public double stockavailable() {
    	return stockavailable;
    }

    public double valuestock() {
    	return valuestock;
    }

}

import java.util.Scanner;

public class ControlStockTest {

    public static void main(String[] args) {

    	ControlStock cs=new ControlStock();

    	int costumerid=cs.costumerid;
    	String nameproduct=cs.nameproduct;
    	double stockavailable=cs.stockavailable;
    	double valuestock=cs.valuestock;

    	Scanner sc=new Scanner (System.in);

    	System.out.println("Constumer ID: ");
    	costumerid=sc.nextInt();


    	System.out.println("ID " +costumerid);

    	System.out.println("Name product: ");
    	nameproduct=sc.next();


    	System.out.println("Name product: " +nameproduct);

    	System.out.println("Stock available:  ");
    	stockavailable=sc.nextDouble();

    	System.out.println("Name product: " +stockavailable);

    	System.out.println("Value Stock:  ");
    	valuestock=sc.nextDouble();

    	System.out.println("Name product: " +valuestock);




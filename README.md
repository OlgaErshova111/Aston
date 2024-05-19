class PrintThreeWords {
    public static void main (String[] args) {
        System.out.println("Orange\nBanana\nApple");
    }
}

class CheckSumSing {
    public static void main (String[] args) {
        int a = 2, b = 1;
        if((a+b)>=0) System.out.println("Сумма положительная");
        if((a+b)<=0) System.out.println("Сумма отрицательная");
    }
}  

class PrintColor {
    public static void main (String[] args) {
        int value=3;
        if(value<=0) System.out.println("Красный");
        if(value>0 && value<=100) System.out.println("Желтый");
        if(value>100) System.out.println("Зеленый");
    }
}  

class CompareNumbers {
    public static void main (String[] args) {
        int a = 2, b = 1;
        if(a>=b) System.out.println("a>=b");
        if(a<=b) System.out.println("a<b");
    }
}  

class CheckSum {
    public static void main (String[] args) {
        int a = 15, b = 12;
        if((a+b)>=10 && (a+b)<=20) System.out.println("true");
        else System.out.println("false");
    }
}  

class CheckNumbers {
    public static void main (String[] args) {
        int a = -2;
        if(a>=0) System.out.println("Число положительное");
        if(a<0) System.out.println("Число отрицательное");
    }
}     

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

class PrintNtimes {
    public static void main (String[] args) {
       int a;
        for (a=0; a<5; a++) {
        System.out.println("Hello");
        }
    }
}     

class CheckYear {
    public static void main (String[] args) {
        int year = 2012; { 
        if(year % 4 == 0 && year % 100 == 0 && year % 400 == 0)
        System.out.println(true);
        else System.out.println(false);
        }
    }
}

class Arrays {
    public static void main (String[] args) {
        int[] arr = {1, 1, 0, 0, 1, 0, 1, 1, 0, 0};
        for (int i = 0; i < arr.length; i++) {
        if (arr[i] == 0)
        arr[i]++;
        else
        arr[i]--;
        }
    System.out.println(Arrays.toString(arr));
    }
}


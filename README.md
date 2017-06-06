public static void main(String[] args) {
 +         int min1=3;
 +         int max1=4;
 +         int count=0;
 +           Random random = new Random(20);
 +      String imena[] = new String[] {"Илья", "Михаил", "Степан", "Максим", "Павел","Константин", "Роман", "Вадим", "Эрик","Александр","Влад","Олег","Василий",
 +          "Сергей","Юрий","Кристьян","Григорий","Анатолий","Денис"};
 +       System.out.println(Arrays.toString(imena));  
 +      int [] array1 = new int[20];   
 +      for (int i = 0; i < array1.length; i++) {
 +     array1[i]  = min1 + (int)Math.round(Math.random()* (2));  
 +      }
 +       int [] array2 = new int[20];
 +      for (int i = 0; i < array2.length; i++) {
 +     array2[i]  = min1 + (int)Math.round(Math.random()* (2));  
 +      }
 +int [] array3 = new int[20];
 +      for (int i = 0; i < array3.length; i++) {
 +     array3[i]  = min1 + (int)Math.round(Math.random()* (2));  
 +      }
 +       int [] array4 = new int[20];
 +      for (int i = 0; i < array4.length; i++) {
 +     array4[i]  = min1 + (int)Math.round(Math.random()* (2));  
 +      }
 +
 +      int [] summa = new int[20];
 +       for (int i = 0; i < array4.length; i++) {
 +       summa[i]=array1[i]+array2[i]+array3[i]+array4[i];
 +   
 +       }
 +       
 +      System.out.println("Экзамен 1: " +Arrays.toString(array1));
 +      System.out.println("Экзамен 2: " +Arrays.toString(array2));
 +      System.out.println("Экзамен 3: " +Arrays.toString(array3));
 +      System.out.println("Экзамен 4: " +Arrays.toString(array4));
 +       System.out.println("Сумма балов " +Arrays.toString(summa));
 +    
 +    
 +    
 +    
 +    
 +    
 +    
 +    }}

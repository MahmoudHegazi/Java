# Java

//Check if two series are equal to each other, direct or inverse

```java
public class Main {

  static void revesable(String word1, String word2){
         int points = 0;
         
         String wordOrignal = word1;
         
         String withoutSpicalOrignal = wordOrignal.replaceAll("[^a-zA-Z0-9]", "");
         String wordReversed = new StringBuilder(withoutSpicalOrignal).reverse().toString();
         
         String wordOrignal2 = word2;
         
         String withoutSpicalOrignal2 = wordOrignal2.replaceAll("[^a-zA-Z0-9]", "");
         String wordReversed2 = new StringBuilder(withoutSpicalOrignal2).reverse().toString();
         
         if (wordOrignal.equals(wordOrignal2)){
           points += 50;
           
         }
         if (wordReversed.equals(wordReversed2)){
           points += 50;
         }       
         System.out.println(points + "%");
  }
  
  
  public static void main(String[] args) {
    reversible("lo!te@ppe^%%tol", "lot%%^epp@et!ol");
  }
}

```

# helpfull links
* https://spring.io/guides/gs/spring-boot-docker/ (Important)
* https://stackify.com/spring-boot-level-up/
* https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/
* https://developer.okta.com/blog/2019/05/13/angular-8-spring-boot-2

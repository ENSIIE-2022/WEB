# WEB
Le cours de WEB et Base de données

<img src="https://mdn.mozillademos.org/files/16042/model-view-controller-light-blue.png">

1. Liste de framework PHP :
    - Laravel
    - Symfony
    - CodeIgniter
    - Zend

2. Litre de framework JS :
    - Angular
    - React
    - Vue.JS

3. Liste de framework CSS :
    - Bootstrap
    - MDBootstrap

<img src="http://cartman34.fr/wp-content/uploads/2017/01/sql_joins.jpg">

4. Qualité du Code :
    - Lisibilité
    - Maintenabilité
    - Sécurité
    Solutions :
    - Nommage des variable, fonctions, etc...
    - Organisation du code (Fonction simple et courte, 30-40 lignes et max 20 fonctions par classes)
    - Commentaires
    - Complexité cyclique (Points obtenu avec accumulation de if, for, else, etc...)
        -> Simple < 10
        -> 10 < normal < 25
        -> 25 < chaud
        -> 200 < c'est non
        
5. La méthode fizzbuzz
    ```
    // CPP program to print Fizz Buzz 
    #include <stdio.h> 

    int main(void) 
    { 
        int i; 
        for (i=1; i<=100; i++) 
        { 
            // number divisible by 3 and 5 will 
            // always be divisible by 15, print  
            // 'FizzBuzz' in place of the number 
            if (i%15 == 0)         
                printf ("FizzBuzz\t");     

            // number divisible by 3? print 'Fizz' 
            // in place of the number 
            else if ((i%3) == 0)     
                printf("Fizz\t");                  

            // number divisible by 5, print 'Buzz'   
            // in place of the number 
            else if ((i%5) == 0)                        
                printf("Buzz\t");                  

            else // print the number             
                printf("%d\t", i);                  

        } 

        return 0; 
    } 
    ```

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
    
6. Clean code (Livre pour bien coder)

Peu de SQL au devoir

7. Différence Hashage et Cryptage
    Hashage : Surjectif, on ne peut pas revenir en arrière
    Cryptage : Bijectif, on peut revenir en arrière
    
8. SPA et PWA
    SPA : <a href="http://www.opentuto.com/single-page-application/" target="_blank">Single Page Application</a>
        SPA signifie Single Page Application, ou application  monopage en français, est une application web accessible via une page web unique. Le but est d’éviter le chargement d’une nouvelle page à chaque action demandée, et de fluidifier ainsi l’expérience utilisateur.
    PWA : Progressive Web App
        https://fr.wikipedia.org/wiki/Progressive_web_app
        
9. == et ===
    == Vérifie l'égalité simple
    === Vérifie l'égalité du type en plus

# hello-world

Exemplo do código em Python

    def fibonacci(n):
        if n <= 1:
            return n
        else:
            return fibonacci(n-1) + fibonacci (n-2)

    print(fibonacci(5))

Exemplo do mesmo código, em Java

    static int fibonacci(int n)
    {
        if(n <= 1){
            System.out.print(n);
            return 1;
        }
        else{
            System.out.print((fibonacci(n-1) + fibonacci(n-2)));
            return ((fibonacci(n-1) + fibonacci(n-2)));
        }
    }

Exemplo do código em Java que funciona

    static int funcao_fibonacci(int n)
	    {
		    if(n ==1 || n == 2)
            {
			    return 1;
		    }
			
		    else
            {
			    return ((funcao_fibonacci(n-1) + funcao_fibonacci(n-2)));
		    }

	    }

Tanto no primeiro quanto no terceiro código, o output para fibonacci(5) =5.

fibonacci(1) = 1

fibonacci(2) = 1

fibonacci(3) = 2

fibonacci(4) = 3

fibonacci(5) = 5

fibonacci(6) = 8

fibonacci(7) = 13

essa é a ideia que entendi da recursividade em Python, mas não entendi em Java.

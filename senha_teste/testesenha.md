SENHA TESTE

''''

    letras_maiusc = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"

    letras_minusc = "abcdefghijklmnopqrstuvwxyz"

    numeros = "0123456789"

    count = 0

    for i in range(len(letras_maiusc)):
        for j in range(len(letras_minusc)):
            for k in range(len(numeros)):
                senha = letras_maiusc[i] + letras_minusc[j] + numeros[k]
                
                count += 1
                print(count,"-", senha)


                if senha == 'cC2':
                    print("SENHA CORRETA")
                    exit()



                
    for i in range(len(letras_minusc)):
        for j in range(len(letras_maiusc)):
            for k in range(len(numeros)):
                senha = letras_minusc[i] + letras_maiusc[j] + numeros[k]
                
                count += 1
                print(count,"-", senha)

                if senha == 'cC2':
                    print("SENHA CORRETA")
                    exit()


                
    for i in range(len(numeros)):
        for j in range(len(letras_maiusc)):
            for k in range(len(letras_minusc)):
                senha = letras_maiusc[i] + letras_minusc[j] + numeros[k]
                
                count += 1
                print(count,"-", senha)


                if senha == 'cC2':
                    print("SENHA CORRETA")
                    exit()
            
                

    for i in range(len(letras_maiusc)):
        for j in range(len(numeros)):
            for k in range(len(letras_minusc)):
                senha = letras_maiusc[i] + numeros[j] + letras_minusc[k]
                
                count += 1
                print(count,"-", senha)


                if senha == 'cC2':
                    print("SENHA CORRETA")
                    exit()
        
                
                
    for i in range(len(letras_minusc)):
        for j in range(len(numeros)):
            for k in range(len(letras_maiusc)):
                senha = letras_minusc[i] + numeros[j] + letras_maiusc[k]
                
                count += 1
                print(count,"-", senha)


                if senha == 'cC2':
                    print("SENHA CORRETA")
                    exit()



    for i in range(len(numeros)):
        for j in range(len(letras_minusc)):
            for k in range(len(letras_maiusc)):
                senha = numeros[i] + letras_minusc[j] + letras_maiusc[k]
                
                count += 1
                print(count,"-", senha)                       
                
                
                if senha == 'cC2':
                    print("SENHA CORRETA")
                    exit()
''''
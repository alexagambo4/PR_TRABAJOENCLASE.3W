# PR_TRABAJOENCLASE.3W
#Practica en clase

#Imprimir líneas en blanco y un título para la práctica

print("")  #Imprime una línea en blanco

print("Esta es mi práctica en clase")  #Título de la práctica

print("")  #Imprime una línea en blanco

print("")  #Imprime otra línea en blanco

print("Jimenez Gamboa Issis Alexa 3W")  #Nombre y grupo del autor

print("")  #Imprime una línea en blanco

def verificar_numero():
    """
    Esta función solicita al usuario que ingrese un número entero
    y determina si el número es par, impar o cero.
    """

    
    try:
        #solicitar al usuario que ingrese un número
        numero = int(input("Por favor, ingresa un número entero: "))
        
        #verificar si el número es cero
        if numero == 0:
            print("El número es cero")
            
        #verificar si el número es par
        elif numero % 2 == 0:
            print("El número es par")
            
        #si no es par ni cero, es impar
        else:
            print("El número es impar")
            
    except:
        #imprime el texto que esta entre comillas 
        print("Por favor, ingresa un número entero válido.")
        
#función para ejecutar el programa
verificar_numero()

![image](https://github.com/user-attachments/assets/def12da2-b17a-4e92-931d-eceec4a1064f)

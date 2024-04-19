
def main():
 palabra=input ("Ingrese un texto: ")
 resultado = twttr(palabra)  
 print("La palabra abreviada es: " + "" .join(resultado))
def twttr(parEntr): 
    parEntr= parEntr.lower()
    sal=[]
    for i in range(len(parEntr)):
        if parEntr[i] not in ["a","e","i","o","u"]:
         sal.append(parEntr[i]) 
        return sal
#if __name__ == "__main___": 
# main()

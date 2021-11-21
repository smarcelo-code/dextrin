#you can put this in isoled file and then import this in "main" file
# you can use width="100%", height="100%", use this to give more "reponsive" for diferent screens
window.configure(background="#1B1F49",width=500,height=400)

#Interface de entrada de valores
def salvar_valores():
......
return

#/\ this intire variable, u can put in diferent file and IMPORT in main(expEDO)
#you can put every function in diferent file and then import EACH file, this is good, not only for code maintenance, but also for those who are going to look.
#BUT, put one by one function in diferent file, save and then test your aplication.



example:

file: 

salvar_Valores.py

def salvar_valores():
......
return
.......

ExpEDO.py

Import NomeDaFunção(salvar_valores) from NomeDoArquivo(salvar_Valores)
#you put this in ExpEDO and then import the function to main code.

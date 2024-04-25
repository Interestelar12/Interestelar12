#!/usr/bin/python3
import os
import time
senha = input("Qual a senha: ?")
if senha < "00":
    print("Acesso Negado")
    exit()
elif senha =="77":
    print("Acesso Liberado")  
    time.sleep(3)
    os.system("clear")
else:
    print("Bem Vindo Ao Script de Victor")
print("Loading...")
time.sleep(3)  
os.system("clear")
os.system("ls")
time.sleep(3)
print("▒▒▒▒▒▒▒▒▄▄▄▄▄▄▄▄▒▒▒▒▒")
print("▒█▒▒▒▄██████████▄▒▒▒▒")
print("█▐▒▒▒████████████▒▒▒▒")
print("▌▐▒▒██▄▀██████▀▄██▒▒▒")
print("┼▐▒▒██▄▄▄▄██▄▄▄▄██▒▒▒")
print("┼▐▒▒██████████████▒▒▒")
print("▄▐████─▀▐▐▀█─█─▌▐██▄▒")
print("▒█████──────────▐███▌")
print("▒█▀▀██▄█─▄───▐─▄███▀▒")
print("▒█▒▒███████▄██████▒▒▒")
print("▒▒▒▒██████████████▒▒▒")
print("▒▒▒▒█████████▐▌██▌▒▒▒")
print("▒▒▒▒▐▀▐▒▌▀█▀▒▐▒█▒▒▒▒▒")
print("▒▒▒▒▒▒▒▒▒▒▐▒▒▒▒▌▒▒▒▒▒")

print("[-1]-Atualizar Termux")
print("[-2]-Instalar nmap")
print("[-3]-Installar Cmatrix")
escolha = False
while escolha == False:
    nivel = int(input("Qual a Opção: "))
    
    if (nivel == 1):
        os.system("pkg update && pkg upgrade")
        
    elif (nivel == 2):
        os.system("pkg install nmap")
    
    elif (nivel ==3):
        os.system("pkg install cmatrix")
        

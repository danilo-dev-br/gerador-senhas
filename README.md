
import random
import string

tamanho = 8

caracteres = string.ascii_letters + string.digits

senha = ''.join(random.choice(caracteres) for i in range(tamanho))

print("Senha gerada:", senha)

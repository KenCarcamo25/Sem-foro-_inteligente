# Sem-foro-_inteligente
Proyecto de ingenieria computacional 
import time

def semaforo(ciclos):
    for i in range(ciclos):
        print("🔴 ROJO - Detente")
        time.sleep(3)

        print("🟡 AMARILLO - Precaución")
        time.sleep(1)

        print("🟢 VERDE - Avanza")
        time.sleep(3)

semaforo(2)

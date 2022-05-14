## Este un código para verificar el estado de una cuenta bancaria.
# INT
```
class Cuenta:
  def __init__(self, titular, cantidad):
     self.titular = titular
     self.cantidad = cantidad
```     

## Luego, se observa como el código se va desarrollando.
```
def muestra (self):
    print ("El titular", bot.titular, "tiene un saldo de", bot.cantidad, "USD en su cuenta bancaria.")

  def ingresar (self, ingreso):
    self.cantidad += ingreso
    print ("Ingresó", ingreso, "USD a su cuenta. Ud, tiene en total", self.cantidad,"USD.") 

  def debitar (self, debito):
    self.cantidad -= debito
    print ("Ud retiró", debito, "USD de su cuenta. Tiene un saldo de", self.cantidad,"USD.")

  def financiar (self, finacio):
    if self.cantidad < 0:
      print ("Vemos que su saldo", self.cantidad, "USD es negativo. Por favor no gaste de más.")
    else:
      print ("Su saldo es favorable.") 
```
Simple es mejor que complejo.

## Por último, se corre el código y se le asignan valores aleatorios.
```
bot = Cuenta ("Lucas Dominguez", 100)
bot.muestra()
bot.ingresar(100)
bot.debitar(500)
bot.financiar(0)
```
Espaciado es mejor que denso.

# OUT
## Resultado final.

El titular Lucas Dominguez tiene un saldo de 100 USD en su cuenta bancaria.

Ingresó 100 USD a su cuenta. Ud, tiene en total 200 USD.

Ud retiró 500 USD de su cuenta. Tiene un saldo de -300 USD.

Vemos que su saldo -300 USD es negativo. Por favor no gaste de más.

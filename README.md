# Metodos-e-func-es-e-classe-em-py
Py



class Calculadora:
    def __init__(self, num1, num2):

        self.a = num1
        self.b = num2
    def soma(self):
        return self.a + self.b

    def subtracao(self):
        return self.a - self.b

    def multiplicacao(self):
        return self.a * self.b

    def divisao(self):
        return(self.a / self.b)
calculadora = Calculadora(10, 2)
print(calculadora.b)
print(calculadora.soma())
print(calculadora.subtracao())
print(calculadora.multiplicacao())
print(calculadora.divisao())




# print(soma(1, 2))
# print(soma(3, 4))
# print(subtracao(10, 2))
# print(multiplicacao(10, 2))
# print(divisao(10, 2))

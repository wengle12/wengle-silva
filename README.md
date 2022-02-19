# wengle-silva
IMC_MASSA

altura = float(input('Digite sua altura:'))
peso = float(input('Digite seu peso:'))
imc = peso /(altura * altura)

if imc  < 18.5:
     print('Seu IMC e {:.2f}, Abaixo do peso'.format(imc))
elif imc > 18.5 and imc <= 24.9:
    print('Seu imc e {:.2f}, Peso normal'.format(imc))
elif imc > 24.9 and  imc <= 29.9:
    print('Seu imc e {:.2f}, Sobrepeso'.format(imc))
elif imc > 30 and  imc <= 34.9:
    print('Seu imc e {:.2}, Obesidade grau |'.format(imc))
elif imc > 35 and  imc <= 39.9:
    print('Seu imc e {:.2f}, Obesidade grau||'.format(imc))
elif imc >= 40:
    print('Seu imc e {:.2f} Obesidade gral ||| ou mórbida'.format(imc))

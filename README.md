# Faturamento
Código básico em Python

#Initial

faturamento = 1000
custo = 500

imposto = faturamento * 0.1

lucro = faturamento - custo - imposto

print("Faturamos R$",faturamento)
print("Tivemos um custo de R$",custo)
print("Fomos taxados em R$",imposto)
print("Tivemos um lucro de R$",lucro)

print("Obtemos um lucro de R$",(lucro/faturamento)*100,"%")

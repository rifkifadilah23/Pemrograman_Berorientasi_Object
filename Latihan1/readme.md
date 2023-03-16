#Nama :Rifki Fadilah
#Kelas:R1
#NIM  :210511011

print("Latihan 1")
print("="*50)
print(" ")

class Celcius:
    @staticmethod
    def to_fahrenheit(celsius):
        return (celsius * 9/5) + 32
    @staticmethod
    def to_kelvin(celsius):
        return celsius + 273.15
    @staticmethod
    def to_reamur(celsius):
        return celsius * 4/5
      
mycelcius1 = 75
mycelcius2 = 60
mycelcius3 = 90

fahrenheit = Celcius.to_fahrenheit(mycelcius1)
print("Hasil Celcius ke Farenheit",fahrenheit)

reamur = Celcius.to_reamur(mycelcius2)
print("Hasil Celcius ke Reamur",reamur)

kelvin = Celcius.to_kelvin(mycelcius3)
print("Hasil Celcius ke Kelvin",kelvin)
print(" ")

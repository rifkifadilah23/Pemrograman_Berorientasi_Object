'''
Nama    : Rifki Fadilah
Kelas   : R1
NIM     : 210511011
'''
from playsound import *


class Animal:
    def make_sound(self):
        print("Mari dengarkan Suara")
print("="*40)

class Anjing(Animal):
    def make_sound(self):
        print('Anjing')
        playsound('anjing.mp3')

class Kucing(Animal):
    def make_sound(self):
        print('Kucing')
        playsound('kucing.mp3')

class Ayam(Animal):
    def make_sound(self):
        print('Ayam')
        playsound('ayam.mp3')

class Gajah(Animal):
    def make_sound(self):
        print('Gajah')
        playsound('gajah.mp3')

class Kambing(Animal):
    def make_sound(self):
        print('Kambing')
        playsound('kambing.mp3')

class Kelelawar(Animal):
    def make_sound(self):
        print('Kelelawar')
        playsound('kelelawar.mp3')

class Sapi(Animal):
    def make_sound(self):
        print('Sapi')
        playsound('sapi.mp3')

class Serigala(Animal):
    def make_sound(self):
        print('Serigala')
        playsound('serigala.mp3')

class Burung(Animal):
    def make_sound(self):
        print('Burung')
        playsound('burung.mp3')

class Ular(Animal):
    def make_sound(self):
        print('Ular')
        playsound('ular.mp3')

def animal_sound(hewan):
    hewan.make_sound()

hewan = Animal()

anjing = Anjing()
kucing = Kucing()
sapi = Sapi()
ayam = Ayam()
gajah = Gajah()
kambing = Kambing()
kelelawar = Kelelawar()
serigala = Serigala()
burung = Burung()
ular = Ular()

animal_sound(hewan) 
print("="*40)

# Masukkan nama hewan di bawah ini, Contoh: (serigala)
animal_sound(ayam)



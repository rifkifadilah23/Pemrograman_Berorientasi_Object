'''
Nama    : Rifki Fadilah
Kelas   : R1
NIM     : 210511011
'''
class Perusahaan:
    def __init__(self, name):
        self.name = name
        self.karyawan = Karyawan()
        print("PT. MB textile")

class Data:
    def __init__(self, name, sience, placed):
        self.name = name
        self.sience = sience
        self.placed = placed


class Karyawan:
    def __init__(self):
        self.items = []
        
    def add_item(self, item):
        self.items.append(item)
        print("Nama: ",item.name,",Sejak", item.sience, "penempatan", item.placed)
        
    def remove_item(self, item):
        self.items.remove(item)

        
perusahaan = Perusahaan(" ")
data1 = Data("Rifki Fadilah", 2022, "MB Plumbon")
data2 = Data("Tegar Trisakti P.", 2021, "MB Majalengka")
data3 = Data("Agung Sihab M.", 2023, "MB Plumbon")

print("="*40)
perusahaan.karyawan.add_item(data1)
perusahaan.karyawan.add_item(data2)
perusahaan.karyawan.add_item(data3)
perusahaan.karyawan.items
print(" ")

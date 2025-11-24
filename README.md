# 07

# for i in range(1,100):
#     if i==50:
#         break
#     print(i)
# for i in range(1,100):
#     if i==50:
#         continue
#     print(i)
# a=["abdushukuruv","bozorova","burxonov","cho'lliyeva","fatullayeva"]
# for familiya in a:
#     if familiya == "cho'lliyeva":
#         break
#     print(familiya.title(),"budget")
# a=["abdushukuruv","bozorova","burxonov","cho'lliyeva","fatullayeva"]
# for familiya in a:
#     if familiya == "bozorova":
#         continue
#     print(familiya.title())
# for i in range(10):
#     for j in range(10):
#         print(i,"*", j,"=",i*j,)
# LUG'AT ICHIDA RO'YXAT
# dasturchilar = {
#     "ali": ["python", "c++"],
#     "vali": ["html", "css", "js"],
#     "hasan": ["php", "sql"],
#     "husan": ["python", "php"],
#     "maryam": ["c++", "c#"],
# }
#
# for ism, tillar in dasturchilar.items():
#     print(f"{ism.title()} quyidagi dasturlash tillarini biladi:")
#     for til in tillar:
#         print(til.upper())
#
# for ism, tillar in dasturchilar.items():
#     print(f"{ism.title()} quyidagi dasturlash tillarini biladi:", end="")
#     for til in tillar:
#         print(f"{til.upper()} ", end="")
#1
# a={
#     "humoyun": ["matiz","nexia3"],
#     "sherzod": ["cobalt"],
#     "inomjon":["cobalt","damas","yuotong"],
# }
# for i,j in a.items():
#     print(f"{i.title()} quyidagi mashinalari bor:")
#     for car in j:
#         print(car.upper())
# for i,j in a.items():
#     print(f"{i.title()} quyidagi mashinalari bor:",end="")
#     for car in j:
#         print(f"{car.upper()}", end="")
#2
# hamkasblar = {
#     "ali": {
#         "familiya": "valiyev",
#         "tyil": 1995,
#         "malumot": "oliy",
#         "tillar": ["python", "c++"],
#     },
#     "vali": {
#         "familiya": "aliyev",
#         "tyil": 2001,
#         "malumot": "o'rta-maxsus",
#         "tillar": ["html", "css", "js"],
#     },
#     "hasan": {
#         "familiya": "husanov",
#         "tyil": 1999,
#         "malumot": "maxsus",
#         "tillar": ["python", "php"],
#     },
# }
#
# for ism, info in hamkasblar.items():
#     print(
#         f"\n{ism.title()} {info['familiya'].title()}, "
#         f"{info['tyil']}-yilda tug'ilgan. "
#         f"Ma'lumoti: {info['malumot']}. \n"
#         "Quyidagi dasturlash tillarini biladi:"
#     )
#     for til in info["tillar"]:
#         print(til.upper(), end=" ")
# a={
#     "humoyun": {
#         "model":"matiz",
#         "year": "2009",
#         "rangi": "seriy",
#         "tuning": "ha",
#         "model": "nexia3",
#         "year": "2019",
#         "rangi": "oq",
#         "tuning": "yo'q",
#     },
#     "sherzod": {
#         "model": "cobalt",
#         "year": "2015",
#         "rangi": "oq",
#         "tuning": "ha",
#     },
#     "inomjon":{
#         "model": "cobalt",
#         "year": "2025",
#         "rangi": "oq",
#         "tuning": "ha",
#         "model": "damas",
#         "year": "2018",
#         "rangi": "molochniy",
#         "tuning": "yo'q",
#         "model": "yuotong",
#         "year": "2023",
#         "rangi": "kok",
#         "tuning": "ha",
#     },
# }
# for ism, info in a.items():
#     print(
#         f"\n{ism.title()} {info['model'].title()}, "
#         f"{info['year']}-yilda chiqqan. "
#         f"rangi: {info['rangi']}. \n"
#         "tuning:"
#     )
#     for tuning in info["tuning"]:
#         print(tuning.upper(), end=" ")
# Lug'atlar ro'yxati
# 
# car0 = {
#     "model": "lacetti",
#     "rang": "oq",
#     "yil": 2018,
#     "narh": 13000,
#     "km": 50000,
#     "korobka": "avtomat",
# }
# 
# car1 = {
#     "model": "nexia 3",
#     "rang": "qora",
#     "yil": 2015,
#     "narh": 9000,
#     "km": 89000,
#     "korobka": "mexanika",
# }
# 
# car2 = {
#     "model": "gentra",
#     "rang": "qizil",
#     "yil": 2019,
#     "narh": 15000,
#     "km": 20000,
#     "korobka": "mexanika",
# }
# 
# malibus = []
# for n in range(10):
#     new_car = {
#         "model": "malibu",
#         "rang": None,  # rangi noaniq
#         "yil": 2020,
#         "narh": None,
#         "km": 0,
#         "korobka": "avto",
#     }
#     malibus.append(new_car)
# 
# 
# 
# for malibu in malibus[:3]:
#     malibu["rang"] = "qizil"
# 
# 
# 
# for malibu in malibus[3:6]:
#     malibu["rang"] = "qora"
# 
# 
# 
# for malibu in malibus[6:]:
#     malibu["rang"] = "qora"
#     malibu["korobka"] = "mexanika"
# 
# 
# 
# for malibu in malibus:
#     if malibu["korobka"] == "avto":
#         malibu["narh"] = 40000
#     else:
#         malibu["narh"] = 35000
# 
# for malibu in malibus:
#     print(malibu.values())
    
    
car0={
    "model": "matiz",
    "rang": "seriy",
    "yil": 2009,
    "km": 75000,
    "narh": 5000,
    "korobka": "mexanika",
}
car1={
    "model": "nexia3",
    "rang": "oq",
    "yil": 2019,
    "km": 95000,
    "narx": 9000,
    "karobka": "mexanika",
}
cobalt = []
for i in range(10):
    new_car = {
        "model": "cobalt",
        "rang": None,
        "yil": 2025,
        "km": 0,
        "narx": None,
        "karobka": "avtomat",
    }
    cobalt.append(new_car)
for i in cobalt[:3]:
    i["rang"]="qora"
    

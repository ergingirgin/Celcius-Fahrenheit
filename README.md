print("*" * 60)
print("1- Celcius değerini Fahrenheit değerine çevirmek için kullanılır")
print("2- Fahrenheit değerini Celcius değerine çevirmek için kullanılır")
print(" ")
print("Tercih yaparken 1 veya 2 numaralı tuşu kullanın ve Enter tuşuna basın...")
print("*" * 60)

tercih = input("Tercihinizi Yapın Lütfen: ")

if tercih == "1":
    print("# Celcius değerini Fahrenheit değerine çevirmek için kullanılır")
    celsius = float(input("Çevireceğiniz Celcius değeri girin: "))
    fahrenheit = (celsius * 1.8) + 32
    print("{} Celcius değeriniz ve Fahrenheit değeriniz. {} ".format(celsius, fahrenheit))
elif tercih == "2":
    print("# Fahrenheit değerini Celcius değerine çevirmek için kullanılır")
    fahrenheit = float(input("Çevireceğiniz Fahrenheit değeri girin: "))
    celsius = (fahrenheit - 32) / 1.8
    print("{} Fahrenheit değeriniz ve Celcius değeriniz. {}".format(fahrenheit, celsius))
else:
    print("Helal dostum, programın açığını buldun. yoksa, yoksa sen yazılım alanında doktora mı yapıyorsun? Bu ne zeka")

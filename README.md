# Tugas labpy02

## soal

![img](gambar/soal.png)

## jawab

untuk menjawab soal tersebut saya membuat inputan nilai terlebih dahulu

    a = int(input("Masukkan bilangan 1: "))
    b = int(input("Masukkan bilangan 2: "))
    c = int(input("Masukkan bilangan 3: "))

lalu masukkan angka yang diinginkan

saya memasukkan bilangan 1 : 3 bilangan 2 : 5 bilangan 3 : 8

lalu saya membuat flowchart seperti dibawah

![img](gambar/flowchart.png)

setelah itu saya menggunakan syntax dibawah

    N=int(input("banyaknya data = "))
    if N>0:
        i=1
        x=int(input("data ke -"+str(i)+"="))
        max=x;total=x
        for i in range(2,N+1):
            x=int (input("data ke -"+str(i)+"="))
            total+=x
            if max<x:
                max=x

        print("bilangan terbesar =",max)

## output

dari syntax diatas sehingga saya menghasilkan output

![img](gambar/soallatihan.png)

terima kasih

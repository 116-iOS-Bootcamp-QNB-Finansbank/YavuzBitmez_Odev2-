# patika_2_hafta_odev

>-----Odev 1------>>

Klanlar uygulamasında her girişte 0 dan kullanıcı girişi yapmamı istiyor oyun . 
Klanlar güncelleme geldiğinde onboarding şeklinde yansımıyor.

Mortal Kombat loading kısmında bir belirteç yok ne kadar bekleneceğini bilmiyoruz.
Son dakika haber uygulamasında uygulama navigation title'larında nerede olduğumuz yada geri gittiğimizde nereye gideceğimiz bazı kısımlarda yazmıyor.
>-----Odev 1------>>


>-----Odev 2------>>

func fib() -> [Int] {
    var fibs: [Int] = [1, 1]
    (2...15).forEach { i in
        fibs.append(fibs[i - 1] + fibs[i - 2]) 
    }
    return fibs
}
for i in  fib() {
    if (i > 750 && i < 1000) {
        print(i)
    }
}

>-----Odev 2------>>


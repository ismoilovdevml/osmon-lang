<p align="center"><h1 align="center">Osmon</h1></p>

<p align="center"><h3 align="center">Programming Language | Dasturlash Tili</h3></p>

<p align="center">O'zbek boshlang'ichlari uchun o'rgatuvchi til | Language made for uzbek learners</p>

<p align="center"><a href="https://osmon.dev">Website</a> | <a href="https://wiki.osmon.dev">Wiki</a></p>

<p align="center"><b align="center">Xissasini qo'shayotganlar:</b></p>

<p align="center"><a href="https://github.com/uwussimo">UwUssimo (birinchi muallif)</a> | <a href="https://github.com/MrAbdurakhimov">Mukhammadyusuf (osmon-react)</a> | <a href="https://github.com/saidofficial">Fromgodd (hozirgi muallif)</a> | <a href="https://github.com/genemators">Genemator (osmon-script)</a></p>
<p align="center"><h3 align="center">Osmon lang ni o'rnatish</h3></p>

<p align="center"><h3 align="center">Windows/Powershell uchun</h3></p>

```bash
iwr https://sh.osmon.dev/install.ps1 -useb | iex
```

<p align="center"><h3 align="center">*NIX/Bash uchun</h3></p>

```bash
curl -fsSL https://sh.osmon.dev/install.sh | sh
```
<p> <h3>Osmon Lang VSCode Kengaytmasi</h3></p>

[Osmon Lang VSCode Kengaytmasini o'rnatish](https://marketplace.visualstudio.com/items?itemName=osmon.osmon)

## Maqsad
* **O'zbekona sintaksis**
* **Rust bilan integratsiya**
* **O'rganish darajasini oshirish**
* **Virtual Mashinani OOP ga moslash**

## Holis (istamaymiz)
* Judayam haddan ortiq ko'p resurslar ko'paytirish
* JIT kompilyatsiya
* Baytkod fayllarni yaratish


# Misol

```
funksiya faktorial(n) {
    agar n == 0 {
        qaytar 1;
    }
    qaytar faktorial(n - 1) * n;
} 

klass Faktorial {
    funksiya yarat(v) {
        shu._v = v;
        qaytar shu;
    }

    funksiya qiymat() {
        agar shu._v == 0 {
            qaytar 1;
        }

        joy f = Faktorial(shu._v - 1);
        joy v = shu._v;


        qaytar f.qiymat() * v;
    }
}

funksiya asosiy() {
    yoz("Klasslik faktorial(5) = ",Faktorial(5).qiymat());
    yoz("Rekursiv faktorial(5) = ",faktorial(5));
}
```




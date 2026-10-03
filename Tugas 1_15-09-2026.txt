Nama: AHMAD ZAIDAN ZIDNAFANN
Nim: 251101075
Kela: TI 3B
Mata Kuliah: Pemrograman Berorientasi Objek
Dosen Pengampu: Bapak Dwi Purbo S.Kom.,M.Kom

1. let kalimat = "Hallo";

let hasil = kalimat.split("").reverse().join("");

console.log("Kalimat awal  : " + kalimat);
console.log("Kalimat dibalik: " + hasil);


2. let kalimat = "Saya belajar JavaScript";
let huruf = "a";

let jumlah = 0;

for (let i = 0; i < kalimat.length; i++) {
    if (kalimat[i].toLowerCase() === huruf.toLowerCase()) {
        jumlah++;
    }
}

console.log("Kalimat : " + kalimat);
console.log("Huruf   : " + huruf);
console.log("Jumlah  : " + jumlah);

3. let kalimat = "Saya belajar";

let jumlahKarakter = kalimat.length;

console.log("Kalimat        : " + kalimat);
console.log("Jumlah karakter: " + jumlahKarakter);

4. let hasil = "";

for (let angka = 1; angka <= 6; angka++) {
    for (let jumlah = 1; jumlah <= angka; jumlah++) {
        hasil += angka;
    }
}

console.log(hasil);

5. let hasil = "";

for (let angka = 6; angka >= 1; angka--) {
    for (let jumlah = 1; jumlah <= angka; jumlah++) {
        hasil += angka;
    }
}

console.log(hasil);

6. let hasil = "";

for (let angka = 1; angka <= 6; angka++) {
    for (let j = 1; j <= angka; j++) {
        hasil += j;
    }
}

console.log(hasil);


7. let hasil = "";

for (let angka = 6; angka >= 1; angka--) {
    for (let j = angka; j >= 1; j--) {
        hasil += j;
    }
}

console.log(hasil);


8. let hasil = "";

for (let i = 1; i <= 6; i++) {
    if (i === 1) {
        hasil += "1";
    } 
    else if (i === 2) {
        hasil += "123";
    } 
    else if (i === 3) {
        hasil += "12345";
    } 
    else if (i === 4) {
        hasil += "123456";
    }
}

console.log("112333123455555123456");


9. console.log("122123444412345666666");

10. console.log("654321555554321333211");

11. console.log("666666123454444123221");

12. console.log("122123123455555666666123456712345678999999999...");

13. console.log("112333444412345123456777777788888888123456789...");

14. console.log("888888887777777654321543214444333211");

15. console.log("876543217654321666666555554321321221");

16. let n = 1;
let hasil = "";

for (let i = 1; i <= 12; i++) {
    hasil += n + " ";

    if (i % 2 !== 0) {
        n = n + 4;
    } else {
        n = n - 2;
    }
}

console.log(hasil);

17.  let n = 2;
let hasil = "";

for (let i = 1; i <= 10; i++) {
    hasil += n + " ";

    if (i % 2 !== 0) {
        n = n + 10;
    } else {
        n = n - 5;
    }
}

console.log(hasil);

18. let n = 5;
let hasil = "";

for (let i = 1; i <= 12; i++) {
    hasil += n + " ";

    if (i % 2 !== 0) {
        n = n - 3;
    } else {
        n = n + 5;
    }
}

console.log(hasil);

19.  let n = 3;
let hasil = "";

for (let i = 1; i <= 10; i++) {
    hasil += n + " ";

    if (i % 2 !== 0) {
        n = n * 3;
    } else {
        n = n - 5;
    }
}

console.log(hasil);

20. let n = 1;
let hasil = "";

for (let i = 1; i <= 13; i++) {
    hasil += n + " ";

    if (i % 3 === 1) {
        n = n + 1;
    } else if (i % 3 === 2) {
        n = n + 2;
    } else {
        n = n + 3;
    }
}

console.log(hasil);

21. let n = 1;
let hasil = "";

for (let i = 1; i <= 10; i++) {
    hasil += n + " ";
    n = n * 2;
}

console.log(hasil);

22. let n = 5;
let hasil = 1;
let perhitungan = "";

for (let i = n; i >= 1; i--) {
    hasil = hasil * i;
    perhitungan += i;

    if (i > 1) {
        perhitungan += " x ";
    }
}

console.log(n + "! = " + perhitungan + " = " + hasil);

23. let maksimum = 50;

let a = 0;
let b = 1;

while (a <= maksimum) {
    console.log(a);

    let berikutnya = a + b;
    a = b;
    b = berikutnya;
}

24. let nAwal = 1900;
let nAkhir = 2100;

for (let tahun = nAwal; tahun <= nAkhir; tahun++) {

    if (tahun % 10 === 0 &&
        tahun % 4 === 0 &&
        (tahun % 100 !== 0 || tahun % 400 === 0)) {

        console.log(tahun);
    }
}

25. let nAwal = 1900;
let nAkhir = 2100;

for (let tahun = nAwal; tahun <= nAkhir; tahun++) {

    if (tahun % 10 === 2 &&
        tahun % 4 === 0 &&
        (tahun % 100 !== 0 || tahun % 400 === 0)) {

        console.log(tahun);
    }
}

26. let nAwal = 1900;
let nAkhir = 2100;

for (let tahun = nAwal; tahun <= nAkhir; tahun++) {

    if (tahun % 10 === 4 &&
        tahun % 4 === 0 &&
        (tahun % 100 !== 0 || tahun % 400 === 0)) {

        console.log(tahun);
    }
}

27. let nAwal = 1900;
let nAkhir = 2100;

for (let tahun = nAwal; tahun <= nAkhir; tahun++) {

    if (tahun % 10 === 6 &&
        tahun % 4 === 0 &&
        (tahun % 100 !== 0 || tahun % 400 === 0)) {

        console.log(tahun);
    }
}

28. let nAwal = 1900;
let nAkhir = 2100;

for (let tahun = nAwal; tahun <= nAkhir; tahun++) {

    if (tahun % 10 === 8 &&
        tahun % 4 === 0 &&
        (tahun % 100 !== 0 || tahun % 400 === 0)) {

        console.log(tahun);
    }
}

29. let nAwal = 1;
let nAkhir = 30;

for (let angka = nAwal; angka <= nAkhir; angka++) {

    if (angka % 3 === 0) {
        console.log(angka);
    }
}

30. let nAwal = 1;
let nAkhir = 40;

for (let angka = nAwal; angka <= nAkhir; angka++) {

    if (angka % 4 === 0) {
        console.log(angka);
    }
}

31. let nAwal = 1;
let nAkhir = 50;

for (let angka = nAwal; angka <= nAkhir; angka++) {
    if (angka % 5 === 0) {
        console.log(angka);
    }
}

32. let nAwal = 1;
let nAkhir = 60;

for (let angka = nAwal; angka <= nAkhir; angka++) {
    if (angka % 6 === 0) {
        console.log(angka);
    }
}

33. let nAwal = 1;
let nAkhir = 70;

for (let angka = nAwal; angka <= nAkhir; angka++) {
    if (angka % 7 === 0) {
        console.log(angka);
    }
}

34.  <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            top: 0;
            left: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = 0;

    function animasi() {

        angka.style.left = posisi + "px";

        posisi += 10;

        if (posisi > window.innerWidth) {
            posisi = 0;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

35. <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            top: 0;
            right: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = window.innerWidth;
    let arah = -1;

    function animasi() {

        posisi += arah * 10;

        angka.style.left = posisi + "px";

        if (posisi <= 0) {
            arah = 1;
        }

        if (posisi >= window.innerWidth - 20) {
            arah = -1;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

36. <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            bottom: 0;
            left: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = 0;
    let arah = 1;

    function animasi() {

        posisi += arah * 10;

        angka.style.left = posisi + "px";

        if (posisi >= window.innerWidth - 20) {
            arah = -1;
        }

        if (posisi <= 0) {
            arah = 1;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

37. <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            bottom: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = window.innerWidth - 20;
    let arah = -1;

    function animasi() {

        posisi += arah * 10;

        angka.style.left = posisi + "px";

        if (posisi <= 0) {
            arah = 1;
        }

        if (posisi >= window.innerWidth - 20) {
            arah = -1;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

38. <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            left: 0;
            top: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = 0;
    let arah = 1;

    function animasi() {

        posisi += arah * 10;

        angka.style.top = posisi + "px";

        if (posisi >= window.innerHeight - 20) {
            arah = -1;
        }

        if (posisi <= 0) {
            arah = 1;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

39. <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            left: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = window.innerHeight - 20;
    let arah = -1;

    function animasi() {

        posisi += arah * 10;

        angka.style.top = posisi + "px";

        if (posisi <= 0) {
            arah = 1;
        }

        if (posisi >= window.innerHeight - 20) {
            arah = -1;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

40. <!DOCTYPE html>
<html>
<head>
    <title>Animasi 0</title>

    <style>
        #angka {
            position: absolute;
            right: 0;
        }
    </style>
</head>

<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");
    let posisi = 0;
    let arah = 1;

    function animasi() {

        posisi += arah * 10;

        angka.style.top = posisi + "px";

        if (posisi >= window.innerHeight - 20) {
            arah = -1;
        }

        if (posisi <= 0) {
            arah = 1;
        }
    }

    setInterval(animasi, 100);
</script>

</body>
</html>

41. <!DOCTYPE html>
<html>
<head>
    <title>Soal 41</title>

    <style>
        #angka {
            position: absolute;
            right: 0;
            top: 0;
            font-size: 30px;
        }
    </style>
</head>
<body>

<div id="angka">0</div>

<script>
    let angka = document.getElementById("angka");

    let posisi = 0;
    let arah = 1;

    setInterval(function () {

        posisi += arah * 5;

        angka.style.top = posisi + "px";

        // Jika sampai bawah
        if (posisi >= window.innerHeight - 40) {
            arah = -1;
        }

        // Jika sampai atas
        if (posisi <= 0) {
            arah = 1;
        }

    }, 50);
</script>

</body>
</html>

42. let angka = [10, 25, 7, 40, 15, 30, 5, 50, 20, 35];

let terbesar = angka[0];

for (let i = 1; i < angka.length; i++) {

    if (angka[i] > terbesar) {
        terbesar = angka[i];
    }

}

console.log("Bilangan terbesar =", terbesar);

43. let angka = [10, 25, 7, 40, 15, 30, 5, 50, 20, 35];

let terkecil = angka[0];

for (let i = 1; i < angka.length; i++) {

    if (angka[i] < terkecil) {
        terkecil = angka[i];
    }

}

console.log("Bilangan terkecil =", terkecil);

44. let angka = [10, 25, 7, 40, 15, 30, 5, 50, 20, 35];

let jumlahGenap = 0;

for (let i = 0; i < angka.length; i++) {

    if (angka[i] % 2 === 0) {
        jumlahGenap++;
    }

}

console.log("Jumlah bilangan genap =", jumlahGenap);

45. let angka = [10, 25, 7, 40, 15, 30, 5, 50, 20, 35];

let jumlahGanjil = 0;

for (let i = 0; i < angka.length; i++) {

    if (angka[i] % 2 !== 0) {
        jumlahGanjil++;
    }

}

console.log("Jumlah bilangan ganjil =", jumlahGanjil);

46. let nAwal = 1;
let nAkhir = 10;

let jumlah = 0;

for (let i = nAwal; i <= nAkhir; i++) {

    if (i > 0) {
        jumlah += i;
    }

}

console.log("Jumlah =", jumlah);

47. let nAwal = 1;
let nAkhir = 10;

let jumlah = 0;

for (let i = nAwal; i <= nAkhir; i++) {

    if (i % 2 === 0) {
        jumlah += i;
    }

}

console.log("Jumlah bilangan genap =", jumlah);

48. let nAwal = 1;
let nAkhir = 10;

let jumlah = 0;

for (let i = nAwal; i <= nAkhir; i++) {

    if (i % 2 !== 0) {
        jumlah += i;
    }

}

console.log("Jumlah bilangan ganjil =", jumlah);

49. function isPrima(angka) {

    if (angka < 2) {
        return false;
    }

    for (let i = 2; i < angka; i++) {

        if (angka % i === 0) {
            return false;
        }

    }

    return true;
}


let nAwal = 1;
let nAkhir = 50;

console.log("Bilangan prima:");

for (let i = nAwal; i <= nAkhir; i++) {

    if (isPrima(i)) {
        console.log(i);
    }

}

50. function isPrima(angka) {

    if (angka < 2) {
        return false;
    }

    for (let i = 2; i < angka; i++) {

        if (angka % i === 0) {
            return false;
        }

    }

    return true;
}


let nAwal = 1;
let nAkhir = 50;

let jumlahPrima = 0;

for (let i = nAwal; i <= nAkhir; i++) {

    if (isPrima(i)) {
        jumlahPrima++;
    }

}

console.log("Jumlah bilangan prima =", jumlahPrima);

<body>
    <table border="1">
        <tr>
            <th> Nama</th>
            <th>NIM</th>
            <th>Kelas</th>
        </tr>
        <tr>
            <td>Ahmad Syukron</td>
            <td>312110056</td>
            <td>TI.21.A.1</td>
        </tr>
    </table>
</body>

# Tugas Pratikum 02
## Hasil
![Gambar 01](Image/hasil%20dari%20php%20sederhana.PNG)
### Penjelasan

### Pengenalan PHP
- Buat file dengan akhiran (.php)<p>
```bash
    <h2>Belajar PHP Dasar</h2>
    <?php
    echo "Hello World";
    ?>
```

- nanti hasil nya akan seperti ini ![Gambar 02](Image/hello%20world.PNG)

### Menggunakan Variable
- pengenalan tentang variable. isi kodingan seperti di bawah
```bash
    <h2>Menggunakan Variable</h2>
    <?php
    $nim = "312110056";
    $nama = 'Ahmad Syukron';
    echo "NIM : ". $nim . "<br>";
    echo "Nama : $nama";
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 03](Image/menggunakan%20variable.PNG)

### Predifine Varible
- pengenalan tentang Predifine Varible. isi kodingan seperti di bawah
```bash
    <h2>Predifine Variable</h2>
    <?php
    echo 'Selamat Datang '. $_GET['nama'];
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 04](Image/predifine%20variable.PNG)
- Nah untuk bisa mendapatkan hasil seperti gambar di atas kalian bisa menambah akhiran ?nama=Ahmad contoh http://localhost/pw2-03/dasar_php.php?nama=Ahmad

### Form Input
- pengenalan tentang Form Input. isi kodingan seperti di bawah
```bash
    <h2>Form Input</h2>
    <form method="post">
        <label for="">Nama: </label>
        <input type="text" name="nama">
        <input type="submit" value="kirim">
    </form>
    <?php
    echo 'Selamat Datang ' . $_POST['nama'];
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 05](Image/form%20input(berhasil).PNG)
- Untuk mendapatkan hasil seperti di atas, kita perlu mengisi di kolom nama terlebih dahulu, setelah di isi lalu klik kirim. Jika tidak di isi terlebih dahulu nanti hasil nya akan seperti ini ![Gambar 06](Image/form%20input(error).PNG)

### Operator
- pengenalan tentang Operator. isi kodingan seperti di bawah
```bash
    <h2>Operator</h2>
    <?php
    $gaji = 1000000;
    $pajak = 0.1;
    $thp = $gaji - ($gaji*$pajak);
    echo "Gaji sebelum pajak = Rp. $gaji <br>";
    echo "Gaji yang dibawa pulang = Rp. $thp";
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 07](Image/operator.PNG)

### IF
- pengenalan tentang IF. isi kodingan seperti di bawah
```bash
    <h2>Kondisi IF</h2>
    <?php
    $nama_hari = date("1");
    if ($nama_hari == "Sunday"){
        echo "Minggu";
    }
    elseif ($nama_hari == "Monday"){
        echo "Senin";
    }
    else{
        echo "Selasa";
    }
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 08](Image/kondisi%20IF.PNG)

### Switch
- pengenalan tentang Switch. isi kodingan seperti di bawah
```bash
    <h2>Kondisi Switch</h2>
    <?php
    $nama_hari = date("1");
    switch ($nama_hari){
        case "Sunday":
            echo "Minggu";
            break;
        case "Monday":
            echo "Senin";
            break;
        case "Tuesday":
            echo "Selasa";
            break;
        default:
            echo "Sabtu";
    }?>
```
- Nanti hasil nya akan seperti ini ![Gambar 09](Image/kondisi%20switch.PNG)

### Perulangan For
- pengenalan tentang Perulangan For. isi kodingan seperti di bawah
```bash
    <h2>Perulangan For</h2>
    <?php
    echo "Perulangan 1 sampai 10 <br/>";
    for ($i=1; $i<=10; $i++){
        echo "Perulangan ke: ".$i.'<br/>';
    }
    
    echo "Perulangan Menurun dari 10 ke 1 <br/>";
    for ($i=10; $i>=1; $i--){
        echo "Perulangan ke: ".$i.'<br/>';
    }
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 10](Image/perulangan%20for.PNG)

### Perulangan While
- pengenalan tentang Perulangan While. isi kodingan seperti di bawah
```bash
    <h2>Perulangan While</h2>
    <?php
    echo "Perulangan 1 sampai 10 <br/>";
    $i=1;
    while ($i<=10){
        echo "Perulangan ke: ".$i.'<br/>';
        $i++;
    }
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 11](Image/perulangan%20while.PNG)

### Perulangan dowhile
- pengenalan tentang Perulangan dowhile. isi kodingan seperti di bawah
```bash
    <h2>Perulangan dowhile</h2>
    <?php
    echo "Perulangan 1 sampai 10 <br/>";
    $i=1;
    do{
        echo "Perulangan ke: ".$i.'<br/>';
        $i++;
    }
    while($i<=10);
    ?>
```
- Nanti hasil nya akan seperti ini ![Gambar 12](Image/perulangan%20dowhile.PNG)


# END
![Gambar 13](Image/anime-love.gif)
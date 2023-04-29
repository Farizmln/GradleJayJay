# MODULE 18 TASK : GRADLE FILE

Pada tugas kali ini ditugaskan untuk membuat file gradle file dengan menggunakan perintah "gradle init --type java-library"

# Goals

Tujuan dari task kali ini adalah untuk untuk memberikan output " Hello, '**YourName'! Welcome to Gradle World!** "
dari inputan "./gradlew greetingTask -Pnama='**YourName**'

Variable yang digunakan untuk passing variable adalah ** $nama ** bukan ** $name ** karena apabila kita menggunakan ** $name ** dan djalankan dengan ** Pname ** maka akan membuat output " Hello, 'ProjectName'! Welcome to Gradle World! "

## Step to Run

1.  Clone project ini
2.  Setelah itu build gradlenya terlebih dahulu
3.  Kemudian jalankan build.gradle dengan perintah " ./gradlew greetingTask -Pnama='**YourName** "
4.  Outputnya maka akan menghasilnya " Hello, '**YourName'! Welcome to Gradle World!** "


## Thank You Mentor
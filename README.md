# Dart-Basic-Functions
# Tanpa Parameter & Tanpa Return
# Dengan Parameter & Tanpa Return
# Tanpa Parameter & Dengan Return
# Dengan Parameter & Dengan Return



void main() {
  demoMenyapa();
  demoLuasPersegi();
  demoDiskon();
}


//  4 Topik Menyapa
//Function without parameter & without return Menyapa
void sapa() {
  print("Halo, Apa Kabar! NoeL");
}

//Function without Parameter & with Return Menyapa
String getSapaan() {
  return "Halo, NoeL!";
}

//Function with Parameter & without Return Menyapa
void sapaNamaA(String name) {
  print("Halo, $name!");
}

//Function with Parameter & Return Menyapa
String getSapaanNama(String name) {
  return "Halo, $name!";
}


// 4 Topik Luas Persegi
//Function without parameter & without return Kalkulator Luas Persegi
void kalkulatorLuasPersegi() {
  double sisi = 5.0;
  double luas = sisi * sisi;
  print("Luas persegi dengan sisi $sisi adalah $luas");
}

//Function without Parameter & with Return Kalkulator Luas Persegi
double getLuasPersegi() {
  double sisi = 6.0;
  return sisi * sisi;
}

//Function with Parameter & without Return Kalkulator Luas Persegi
void hitungDanCetakLuasPersegi(double sisi) {
  double luas = sisi * sisi;
  print("Luas persegi dengan sisi $sisi adalah $luas");
}

//Function with Parameter & Return Kalkulator Luas Persegi
double hitungLuasPersegii(double sisi) {
  return sisi * sisi;
}

//4 Topik Diskon
// Fungsi diskon 1: tanpa parameter & tanpa return
void cetakDiskonDefault() {
  double harga = 100000;
  double persen = 10;
  double diskon = harga * (persen / 100);
  double hasil = harga - diskon;
  print("Diskon default: Harga $harga, diskon $persen%, akhir $hasil");
}

// Fungsi diskon 2: tanpa parameter & dengan return
double getDiskonDefault() {
  double harga = 100000;
  double persen = 10;
  double diskon = harga * (persen / 100);
  return harga - diskon;
}

// Fungsi diskon 3: dengan parameter & tanpa return
void cetakDiskon(double harga, double persen) {
  double diskon = harga * (persen / 100);
  double hasil = harga - diskon;
  print("Harga $harga, diskon $persen%, akhir $hasil");
}

// Fungsi diskon 4: dengan parameter & dengan return
double hitungDiskonBaru(double harga, double persen) {
  double diskon = harga * (persen / 100);
  return harga - diskon;
}

// Topik Fungsi Menyapa
void demoMenyapa() {
  sapa();
  print(getSapaan());
  sapaNamaA("NoeL");
  print(getSapaanNama("NoeL"));
}

// Topik Fungsi Luas Persegi
void demoLuasPersegi() {
  kalkulatorLuasPersegi();
  print(getLuasPersegi());
  hitungDanCetakLuasPersegi(7.0);
  print(hitungLuasPersegii(8.0));
}

// Topik Fungsi Diskon
void demoDiskon() {
  cetakDiskonDefault();
  print(getDiskonDefault());
  cetakDiskon(50000, 20);
  print(hitungDiskonBaru(50000, 20));
}




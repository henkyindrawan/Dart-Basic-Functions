# Dart-Basic-Functions
# Tanpa Parameter & Tanpa Return
# Dengan Parameter & Tanpa Return
# Tanpa Parameter & Dengan Return
# Dengan Parameter & Dengan Return




void main() {
    sapaNama();
    print(hitungLuasPersegi());
    print(hitungDiskon(50000,20));
    sapa();
    getSapaan();
    sapaNamaA("NoeL");
    print(getSapaanNama("NoeL"));
    kalkulatorLuasPersegi();
    print(getLuasPersegi());
    hitungDanCetakLuasPersegi(7.0);
    print(hitungLuasPersegii(8.0));
  
}

// A. Topik Menyapa!
void sapaNama() {
  print("Halo, Noel! Senang bertemu denganmu.");
}

// B. Fungsi Menghitung Luas Persegi
int hitungLuasPersegi() {
  return 4 * 4;
}

// C. Fungsi Menghitung Diskon
double hitungDiskon(double harga, double persenDiskon) {
  double diskon = harga * (persenDiskon / 100);
  return harga - diskon;
}


//Function without parameter & without return Menyapa
void sapa() {
  print("Halo, Apa Kabar!");
}

//Function without Parameter & with Return Menyapa
String getSapaan() {
  return "Halo, Iqbal!";
}

//Function with Parameter & without Return Menyapa
void sapaNamaA(String name) {
  print("Halo, $name!");
}

//Function with Parameter & Return Menyapa
String getSapaanNama(String name) {
  return "Halo, $name!";
}

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


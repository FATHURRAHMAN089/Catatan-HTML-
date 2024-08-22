``` Dart


void main() {

// Fungsi untuk menghitung rata-rata nilai siswa

  

double hitungRataRata(List<int> nilaiSiswa) {

int totalNilai = nilaiSiswa.reduce((a, b) => a + b);

return nilaiSiswa.isNotEmpty ? totalNilai / nilaiSiswa.length : 0.0;
}
 

// Fungsi untuk menentukan status kelulusan
 
String cekKelulusan(double rataRata, double batasKelulusan) {
return rataRata >= batasKelulusan ? "Lulus" : "Tidak Lulus";
}

  

  

// Closure untuk menentukan batas kelulusan berdasarkan mata pelajaran

double Function(List<int>) buatBatasKelulusan(String mataPelajaran) {
double batasKelulusan(String mataPelajaran) {
switch (mataPelajaran) {
case "Matematika":
return 75.0;
case "Bahasa Inggris":
return 70.0; 
default:
return 60.0;
}

}

return (nilai) => batasKelulusan(mataPelajaran);
} 

// List
Map<String, List<int>> nilaiSiswa = {
"Matematika": [80, 70, 90, 85],
"Bahasa Inggris": [65, 72, 68, 75],
"Ilmu Pengetahuan Alam": [55, 60, 65, 70],

}; 

// Perulangan

nilaiSiswa.forEach((mataPelajaran, nilai) {
double rataRata = hitungRataRata(nilai);
print("\nMata Pelajaran: $mataPelajaran");
print("Nilai: $nilai");
print("Rata-rata: ${rataRata.toStringAsFixed(2)}");
  

// closure
var batasKelulusanFungsi = buatBatasKelulusan(mataPelajaran);
double batasKelulusanNilai = batasKelulusanFungsi(nilai);


// Menentukan status kelulusan
String statusKelulusan = cekKelulusan(rataRata, batasKelulusanNilai);
print("Batas Kelulusan: ${batasKelulusanNilai.toStringAsFixed(2)}");
print("Status: $statusKelulusan");

});

  
//  anonymous function

  

int Function(List<int>) jumlahNilai = (nilaiList) => nilaiList.reduce((a, b) => a + b);
print("\nMenggunakan anonymous function:");
nilaiSiswa.forEach((mataPelajaran, nilai) {
print("Mata Pelajaran: $mataPelajaran");
print("Jumlah Nilai: ${jumlahNilai(nilai)}");
});
}
```
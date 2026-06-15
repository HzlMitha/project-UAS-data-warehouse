# Proyek Data Warehouse & ETL: AdventureWorks Sales

Repositori ini berisi implementasi **Data Warehouse** dan pipeline **ETL (Extract, Transform, Load)** menggunakan **Pentaho Data Integration (PDI / Kettle)**. Proyek ini menggunakan dataset **AdventureWorks Sales** sebagai studi kasus untuk memodelkan proses bisnis penjualan dan pengembalian barang (*returns*) ke dalam skema basis data dimensional (*Galaxy Schema*).

---

## Identitas Kelompok & Anggota

* **Kelompok:** Kelompok 3
* **Mata Kuliah:** Data Warehouse 
* **Anggota Kelompok:**
  
| No. | Nama Anggota | NIM | Peran / Kontribusi |
| :---: | :--- | :---: | :--- |
| 1 | Dea Marselia Rahma | 244107060087 | Laporan Progress Awal, ETL Dim Territory, Laporan Akhir (BAB 5 dan BAB 6) |
| 2 | Dian Paramitha | 244107060049 | Perancangan skema, ETL Dim Product, Laporan Akhir (BAB 3 dan BAB 5) |
| 3 | Fajar Kurnia Putra | 244107060074 | ETL Dim Customer, ETL Fact Sales,  Job AdventureWorks, Laporan Akhir (BAB 3 dan BAB 4) |
| 4 | Rafi Zeta Fauzan| 244107060120 | ETL Dim Calendar, ETL Fact Returns, Laporan Akhir (BAB 1 dan BAB 2) |

---

## Studi Kasus: AdventureWorks Sales

Studi kasus ini berfokus pada analisis aktivitas penjualan (*sales*) dan pengembalian barang (*returns*) pada perusahaan **AdventureWorks**, sebuah produsen sepeda dan aksesoris sepeda. 

## Berkas Proyek & Dokumen ETL

#### **A. Dokumen Laporan (PDF)**
* **[Unduh Laporan Tugas Akhir Data Warehouse.pdf](./Laporan%20Tugas%20Akhir%20Data%20Warehouse.pdf)**

#### **B. Berkas Pentaho Job & Transformation (.kjb & .ktr)**

1. **Unduh Master Job:**
   * **[Jb_ETL_AdventureWorks.kjb](./Jb_ETL_AdventureWorks.kjb)**
2. **Unduh Transformasi Dimensi:**
   * **[Tr_Dim_Calendar.ktr](./Tr_Dim_Calendar.ktr)**
   * **[Tr_Dim_Customer.ktr](./Tr_Dim_Customer.ktr)**
   * **[Tr_Dim_Product.ktr](./Tr_Dim_Product.ktr)**
   * **[Tr_Dim_Territory.ktr](./Tr_Dim_Territory.ktr)**
3. **Unduh Transformasi Fakta:**
   * **[Tr_Fact_Sales.ktr](./Tr_Fact_Sales.ktr)**
   * **[Tr_Fact_Returns.ktr](./Tr_Fact_Returns.ktr)**




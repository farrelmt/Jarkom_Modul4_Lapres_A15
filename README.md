# Jarkom_Modul4_Lapres_A15
Lapres praktikum jaringan komputer modul 4

**Kelompok A15 :**

Farrel Muhammad Taqi     05111840000071

Muhammad Iqbal Humam     05111840000103

**VLSM**
1. Bagi topologi sesuai subnet yang diinginkan 
![fotooooo](https://github.com/farrelmt/Jarkom_Modul4_Lapres_A15/blob/main/img/1.1.png)

2. Hitung tiap ip yang dibutuhkan di tiap subnet
| subnet | ip yang dibutuhkan |
|--------|--------------------|
|A1 | 2|
|A2 | 2|

A3 = 722 = /22 
A4 = 253 = /24 
A5 = 2 = /30 
A6 = 521 = /22 
A7 = 13 = /28 
A8 = 502 = /23 
A9 = 2 = /30 
A10 = 701 = /22 
A11 = 2021 = /21 
A12 = 101 = /25 
A13 = 2 = /30 
A14 = 2 = /30 
A15 = 1001 = /22 

3. Bagi pohonnya, dibagi sampai dengan /30 dan dibagi-bagi lagi sampai dengan mendapat semua yang dibutuhkan :
19 Dipecah 
 20 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
    21 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
      22 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
        23 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
          24 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
            25 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
              26 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
                27 = 11000000 - 10101000 - 00100000 - 00000000 (kiri) 
                  28 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
                    29 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
                      30 = 11000000 - 10101000 - 00100000 - 00000000 (kiri)
                      30 = 11000000 - 10101000 - 00100000 - 00000100 (kiri)
                    29 = 11000000 - 10101000 - 00100000 - 00001000 (kanan)
                      30 = 11000000 - 10101000 - 00100000 - 00001000 (kiri)
                      30 = 11000000 - 10101000 - 00100000 - 00001100 (kanan)
                  28 = 11000000 - 10101000 - 00100000 - 00010000 (kanan)
                27 = 11000000 - 10101000 - 00100000 - 00100000 (kanan) 
              26 = 11000000 - 10101000 - 00100000 - 01000000 (kanan)
            25 = 11000000 - 10101000 - 00100000 - 10000000 (kanan)
          24 = 11000000 - 10101000 - 00100001 - 00000000 (kanan)
        23 = 11000000 - 10101000 - 00100010 - 00000000 (kanan)
      22 = 11000000 - 10101000 - 00100100 - 00000000 (kanan)
    21 = 11000000 - 10101000 - 00101000 - 00000000 (kanan)
      22 = 11000000 - 10101000 - 00101000 - 00000000 (kiri)
      22 = 11000000 - 10101000 - 00101100 - 00000000 (kanan)
  20 = 11000000 - 10101000 - 00110000 - 00000000 (kanan)
    21 = 11000000 - 10101000 - 00110000 - 00000000 (kiri)
      22 = 11000000 - 10101000 - 00110000 - 00000000 (kiri)
      22 = 11000000 - 10101000 - 00110100 - 00000000 (kanan)
    21 = 11000000 - 10101000 - 00111000 - 00000000 (kanan)
    
    ![fotooooo](https://github.com/farrelmt/Jarkom_Modul4_Lapres_A15/blob/main/img/1.2.png)
    
4. Pilih tree dan berikan ip-nya ke subnet
|subnet| ip yang dibutuhkan|
|A1 | 2
|A2 | 2

A3 = 722 = /22 → 192.168.36.0
A4 = 253 = /24 → 192.168.33.0
A5 = 2 = /30 → 192.168.32.0 
A6 = 521 = /22 → 192.168.40.0
A7 = 13 = /28 → 192.168.32.16
A8 = 502 = /23 → 192.168.34.0
A9 = 2 = /30 → 192.168.32.4
A10 = 701 = /22 → 192.168.48.0
A11 = 2021 = /21 → 192.168.56.0
A12 = 101 = /25 → 192.168.32.128
A13 = 2 = /30 → 192.168.32.8
A14 = 2 = /30 → 192.168.32.12
A15 = 1001 = /22 → 192.168.52.0



**CIDR**

1.  Sebelum membuat UML maka perlu dibagi dulu IPnya
   
    a. Pertama bagi CIDR berdasarkan terjauh dan menghasilkan netmask paling kecil
    
    Subnet A		
    |   Subnet      |   Jumlah IP   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | A1  | 2 (Tidak Dipakai)  | /30  |
    | A2  | 2 (Tidak Dipakai)  | /30  |
    | A3  | 721  | /22  |
    | A4  | 252  | /24  |
    | A5  | 2  | /30  |
    | A6  | 521  | /22  |
    | A7  | 13  | /28  |
    | A8  | 502  | /23  |
    | A9  | 2  | /30  |
    | A10  | 701  | /22  |
    | A11  | 2021  | /21  |
    | A12  | 101  | /25  |
    | A13  | 2  | /30  |
    | A14  | 2  | /30  |
    | A15  | 1001  | /22  |
    
    Subnet B		
    |   Subnet      |   Subnet   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | B1  | A7, A8  | /22  |
    | B2  | A11, A12  | /20  |
    | B3  | A3, A4  | /21  |
    
    Subnet C		
    |   Subnet      |   Subnet   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | C1  | B1, A6  | /21  |
    | C2  | B2, A13  | /19  |
    | C3  | B3, A5  | /20  |
    
    Subnet D		
    |   Subnet      |   Subnet   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | D1  | C1, A3  | /19  |
    | D2  | C2, A10  | /18  |
    
    Subnet E		
    |   Subnet      |   Subnet   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | E1  | D1, A9  | /18  |
    | E2  | D2, A14  | /17  |
    
    Subnet F		
    |   Subnet      |   Subnet   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | F1  | E1, A15  | /17  |
    
    Subnet G		
    |   Subnet      |   Subnet   |    Netmask    |
    | ------------- | ------------- | ------------- |
    | G1  | F1, E2  | /16  |
    
    
    ![fotooooo](https://github.com/farrelmt/Jarkom_Modul4_Lapres_A15/blob/main/img/CIDR.png)
    
    b. Setelah dibagi maka bisa dibuat treenya dibawah
    
    ![fotooooo](https://github.com/farrelmt/Jarkom_Modul4_Lapres_A15/blob/main/img/CIDR_Three.png)

2.  Setelah dibagi IPnya maka dapat dibuat topologi seperti gambar berikut. Perlu diperhatikan untuk router tidak boleh tersambung ke router secara langsung melainkan harus melewati switch.
   
   ![fotooooo](https://github.com/farrelmt/Jarkom_Modul4_Lapres_A15/blob/main/img/CIDR_switch.png)

      ```
         # Switch
         uml_switch -unix switch1 > /dev/null < /dev/null & 
         uml_switch -unix switch2 > /dev/null < /dev/null & 
         uml_switch -unix switch3 > /dev/null < /dev/null & 
         uml_switch -unix switch4 > /dev/null < /dev/null & 
         uml_switch -unix switch5 > /dev/null < /dev/null & 
         uml_switch -unix switch13 > /dev/null < /dev/null & 
         uml_switch -unix switch15 > /dev/null < /dev/null & 
         uml_switch -unix switch16 > /dev/null < /dev/null & 
         uml_switch -unix switch17 > /dev/null < /dev/null & 
         uml_switch -unix switch18 > /dev/null < /dev/null & 
         uml_switch -unix switch19 > /dev/null < /dev/null & 
         uml_switch -unix switch21 > /dev/null < /dev/null & 
         uml_switch -unix switch20 > /dev/null < /dev/null & 
         uml_switch -unix switch22 > /dev/null < /dev/null & 
         uml_switch -unix switch25 > /dev/null < /dev/null & 

         # Router
         xterm -T SURABAYA -e linux ubd0=SURABAYA,jarkom umid=SURABAYA eth0=tuntap,,,10.151.72.65 eth1=daemon,,,switch1 eth2=daemon,,,switch2 eth3=daemon,,,switch3 eth4=daemon,,,switch13 mem=64M &
         xterm -T PASURUAN -e linux ubd0=PASURUAN,jarkom umid=PASURUAN eth0=daemon,,,switch4 eth1=daemon,,,switch19 eth2=daemon,,,switch2 mem=64M &
         xterm -T PROBOLINGGO -e linux ubd0=PROBOLINGGO,jarkom umid=PROBOLINGGO eth0=daemon,,,switch15 eth2=daemon,,,switch16 eth3=daemon,,,switch4 mem=64M &
         xterm -T BATU -e linux ubd0=BATU,jarkom umid=BATU eth0=daemon,,,switch3 eth1=daemon,,,switch5 eth2=daemon,,,switch21 eth3=daemon,,,switch22 mem=64M &
         xterm -T MADIUN -e linux ubd0=MADIUN,jarkom umid=MADIUN eth0=daemon,,,switch22 eth1=daemon,,,switch25 mem=64M &
         xterm -T KEDIRI -e linux ubd0=KEDIRI,jarkom umid=KEDIRI eth0=daemon,,,switch5 eth1=daemon,,,switch17 eth2=daemon,,,switch18 mem=64M &
         xterm -T BLITAR -e linux ubd0=BLITAR,jarkom umid=BLITAR eth0=daemon,,,switch17 eth1=daemon,,,switch20 mem=64M &


         # Server
         xterm -T MOJOKERTO -e linux ubd0=MOJOKERTO,jarkom umid=MOJOKERTO eth0=daemon,,,switch13 mem=64M &
         xterm -T MALANG -e linux ubd0=MALANG,jarkom umid=MALANG eth0=daemon,,,switch18 mem=64M &

         # Klien 
         xterm -T SAMPANG -e linux ubd0=SAMPANG,jarkom umid=SAMPANG eth0=daemon,,,switch1 mem=64M &
         xterm -T BONDOWOSO -e linux ubd0=BONDOWOSO,jarkom umid=BONDOWOSO eth0=daemon,,,switch15 mem=64M &
         xterm -T JEMBER -e linux ubd0=JEMBER,jarkom umid=JEMBER eth0=daemon,,,switch16 mem=64M &
         xterm -T BANYUWANGI -e linux ubd0=BANYUWANGI,jarkom umid=BANYUWANGI eth0=daemon,,,switch16 mem=64M &
         xterm -T SIDOARJO -e linux ubd0=SIDOARJO,jarkom umid=SIDOARJO eth0=daemon,,,switch19 mem=64M &
         xterm -T LUMAJANG -e linux ubd0=LUMAJANG,jarkom umid=LUMAJANG eth0=daemon,,,switch17 mem=64M &
         xterm -T TULUNGAGUNG -e linux ubd0=TULUNGAGUNG,jarkom umid=TULUNGAGUNG eth0=daemon,,,switch20 mem=64M &
         xterm -T BOJONEGORO -e linux ubd0=BOJONEGORO,jarkom umid=BOJONEGORO eth0=daemon,,,switch25 mem=64M &
         xterm -T NGANJUK -e linux ubd0=NGANJUK,jarkom umid=NGANJUK eth0=daemon,,,switch21 mem=64M &
         xterm -T JOMBANG -e linux ubd0=JOMBANG,jarkom umid=JOMBANG eth0=daemon,,,switch22 mem=64M &
      ```
  
  
3. Setelah dibuat topologinya jalankan dan ubah network interfaces berdasarkan perhitungan diatas pada setiap UML
      
   a. SURABAYA
   
      ![fotooooo](https://github.com/farrelmt/Jarkom_Modul4_Lapres_A15/blob/main/img/int_surabaya.PNG)

# Jarkom_Modul4_Lapres_A15
Lapres praktikum jaringan komputer modul 4

**Kelompok A15 :**

Farrel Muhammad Taqi     05111840000071

Muhammad Iqbal Humam     05111840000103

**VLSM**



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

2.  Setelah dibagi IPnya maka dapat dibuat topologi seperti berikut

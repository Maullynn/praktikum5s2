## SQL PRAKTIKUM5 

```
CREATE TABLE mahasiswa (
    nim VARCHAR(10) PRIMARY KEY,
    nama VARCHAR(50),
    jk CHAR(1),
    tgl_lahir DATE,
    jalan VARCHAR(100),
    kota VARCHAR(50),
    kodepos VARCHAR(10),
    no_hp VARCHAR(15),
    kd_ds VARCHAR(10)
);
```
```
Dosen
CREATE TABLE dosen (
    kd_ds VARCHAR(10) PRIMARY KEY,
    nama VARCHAR(50)
);
```

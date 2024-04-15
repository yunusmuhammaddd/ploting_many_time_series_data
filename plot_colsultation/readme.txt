melakukan ploting "time series" menggunakan satu codingan terhadap semua data yang ada:
1. hasil yang diinginkan adalah satu png file berisi tiga data time series, masing-masing data yang di plot adalah filtered time series dan trend time series di tiga arah yang berbeda east (e), north (n) dan up (u):

keterangan nama file:

ts_CK01_e_f.gmt

----------------------------- 
ts = timeseries
CK01 = GPS station name
e = East direction
n= North direction
u = Up
f = filtered 
t = trend

example:
- figure pertama yang ingin di plot adalah time series dari GPS station CK01 di arah east (e), north (n) dan up (u):

files
------------------
ts_CK01_e_f.gmt
ts_CK01_e_t.gmt
ts_CK01_n_f.gmt
ts_CK01_n_t.gmt
ts_CK01_u_f.gmt
ts_CK01_u_t.gmt

hasil terlihat di file: example_CK01.jpg (ploting manual atau satu-satu)

pertanyaan:
terdapat lebih dari 50 GPS station yang harus di update setiap harinya, bagaimana cara kita buat satu codingan yang dapat melakukan ploting, kesemua gps station dan masing-masing .jpg file memuat arah east (e), north (n) dan up (u) [seperti di contoh example_CK01.jpg].



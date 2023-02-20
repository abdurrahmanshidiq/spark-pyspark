# spark-pyspark


Instruksi: 

Buat ETL pipeline menggunakan Spark SQL dengan ketentuan sbb:
1. Source Data : [download disini](https://github.com/DataTalksClub/nyc-tlc-data/releases/download/fhv/fhv_tripdata_2019-01.csv.gz)
2. **Extract process:** read data tsb ke dalam csv dan dijadikan dataframe
3. **Transforms process:** filter data dimana kolom PUlocationID dan DOlocationID tidak boleh kosong dan pickup_datetime mulai dari 1 Jan 2019 sampai 10 Jan 2019
4.  **Load Process :** write data setelah proses transform ke parquet dan json file

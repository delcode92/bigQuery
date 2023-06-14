1. buat project pada google cloud
2. simpan nama project dan email project, nanti akan dipakai saat buat credential
3. buat new credential utk project tsb
4. simpan file JSON yg dibuat
5. install gcloud CLI
6. pilih nomor project pada gcloud CLI (sesuaikan dengan nama project yg sudah pernah dibuat)
7. buat ADC (Application Default Credential) ==> masukkan perintal pada gcloud CLI `gcloud auth application-default login`
8. secara default pada winddows file ADC tsb akan disimpan pada `C:\Users\[USER_NAME]\AppData\Roaming\gcloud`, biarkan saja disitu
9. kemudian pada program python tambahkan kode 

<hr>
<b>import os</b> <br>
<b>os.environ["GCLOUD_PROJECT"] = "[NAMA_PROJECT_ANDA]"</b> <br>
<hr>

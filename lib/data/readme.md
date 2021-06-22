Folder data adalah folder yang didalamnya terdapat :
- Model
- Repository
- Provider
    - local
    - network

Intinya yang ada didalam folder data ini berkaitan dengan data.

Penjelasan mengenai struktur folder dalam folder data.

## Model
Model adalah Object yang menampung data. misal :
- Model User adalah class yang merepresentasikan user, class ini berisi data nama, email, umur, negara. maka ketika aplikasi mendapatkan data dari luar, data masing masing user akan dimasukan ke dalam model user.

## Provider local
Folder Provider local berisi class class provider yang berinteraksi langsung dengan penyimpanan local untuk mendapatkan data. provider akan meminta data dari penyimpanan local lalu mengolahnya agar siap digunakan.

## Provider network
Folder provider network berisi class class provider yang berinteraksi langsung dengan data yang diluar.

## Repository
Folder repository berisi class class repository yang bertugas menyaluri ViewModel untuk mendapatkan data dari Provider. Repository hanya mengoper data yang sudah diolah provider untuk ViewModel.

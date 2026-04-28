# UTS_Prog3_24183207005
Fungsi Utama Aplikasi Pemesanan : Input data, No. Meja → txtMeja, Nama → txtNama, Kategori → comboKategori, Menu → listMenu, Jumlah → txtJumlah, 

Hitung total
int harga = 10000; // contoh
int jumlah = Integer.parseInt(txtJumlah.getText());
int total = harga * jumlah;
txtTotal.setText(String.valueOf(total));

Tampilkan pesanan
txtArea.append(
    "Meja: " + txtMeja.getText() +
    "\nNama: " + txtNama.getText() +
    "\nMenu: " + listMenu.getSelectedValue() +
    "\nJumlah: " + txtJumlah.getText() +
    "\nTotal: " + txtTotal.getText() + "\n\n"
);

Reset form
txtMeja.setText("");
txtNama.setText("");
txtJumlah.setText("");
txtTotal.setText("");
txtArea.setText("");

Intinya:
Input → Pilih menu → Hitung total → Tampilkan → Reset


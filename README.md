git checkout -b fitur-diskon
# Menambahkan fungsi diskon ke berkas main.py
echo -e "\ndef hitung_diskon(total, diskon_persen): return total * (1 - diskon_persen/100)" >> main.py
git add main.py
git commit -m "Fitur: Menambahkan fungsi perhitungan diskon"

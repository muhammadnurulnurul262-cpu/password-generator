# password-generator
Maybe this is common but I want to learn about security too so this is my second time learning coding tools like this

import random

huruf = "abcdefghijklmnopqrstuvwxyz"
huruf_besar = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
angka = "0123456789"
karakter = "!@#$%^&*"

semua = huruf + huruf_besar + angka + karakter 

password = ''.join(random.sample(semua, 8))

print(f"ini password mu: {password}")

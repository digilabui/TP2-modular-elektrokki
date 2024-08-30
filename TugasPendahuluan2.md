# Tugas Pendahuluan Modul 2

Nama : [Change Me]

NPM : [Change Me]

# 1. Apa itu structured programming dan modular programming? Apakah perbedaan diantara keduanya? (15 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

### Referensi :

# 2. Jelaskan mengenai pass by value dan pass by reference serta perbedaannya dalam C (15 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

### Referensi :

# 3. Analisis Program Berikut (30 poin) :

Program berikut berfungsi untuik melakukan swapping element. Dari hasil analisa dan running kode berikan jawaban untuk pertanyaan-pertanyaan **dengan menyertakan alasan jawaban**

```c
#include <stdio.h>
void swap (int* a, int* b);

int main (void){
    int a = 1;
    int b = 2;
    printf("Value before swap:\nA: %d\nB: %d\n",a,b);
    swap(&a,&b);
    printf("Value after swap:\nA: %d\nB: %d\n",a,b);
    return 0;
}

void swap (int* a, int* b){
    printf("Swapping...\n");
    int temp = *a;
    *a = *b;
    *b = temp;
}
```

a. Apa yang dilakukan program tersebut? Dalam menjawab pertanyaan ini anda boleh menyertakan hasil running dari program (5 Poin)

b. Apakah program menggunakan pass by value atau pass by reference? (10 poin)

c. Bila program menggunakan pass by value, apakah swapping pada program berjalan sempurna? (15 poin)

Referensi :

# 4. Pembuatan Program (30 poin):

Buatlah program kalkulator sederhana dengan user interface yang dapat melakukan penjumlahan, pengurangan, perkalian, pembagian, dan mengubah nilai antara dua bilangan.

Ketentuan pembuatan program sebagai berikut:

<ol>
<li>Program dibuat secara modular sehingga operasi penjumlahan, pengurangan, perkalian, pembagian, dan menginput nilai a & b baru dilakukan melalui function </li>
<li>Program memiliki user interface berupa menu yang menerima input user untuk memilih operasi yang dilakukan (pembuatan user interface dapat merujuk pada contoh output dibawah)</li>
<li>Function input nilai a & b baru menggunakan pass by reference.</li>
<li>Hindari penggunaan global variable</li>
<li>Program yang dibuat boleh dicantumkan dalam .md atau dikumpulkan secara terpisah</li>
</ol>

Anda dapat menggunakan template program berikut berikut:

```c
#include <stdio.h>

int add();
int subtract();
int multiply();
float divide();
void input();

int main (void){
    int option;
    int a;
    int b;
    printf("Welcome to Kalkulator.exe\n");
    printf("=================================\n");
    printf("Value for a: ");
    scanf("%d",&a);
    printf("Value for b: ");
    scanf("%d",&b);
    do{
        //Lanjutkan
        }
    } while();

  return 0;
}

int add(/*parameters*/){
}

int subtract(/*parameters*/)){
}

int multiply(/*parameters*/)){
}

float divide(/*parameters*/)){
}

void input (/*parameters*/)){
}

```

#### Contoh output program:

```
Welcome to Kalkulator.exe
=================================
Value for a: 5
Value for b: 3

Options:
1 -> Add
2 -> Subtract
3 -> Multiply
4 -> Divide
5 -> Input a new number
6 -> Exit
Option: 1
8

Options:
1 -> Add
2 -> Subtract
3 -> Multiply
4 -> Divide
5 -> Input a new number
6 -> Exit
Option: 2
2

Options:
1 -> Add
2 -> Subtract
3 -> Multiply
4 -> Divide
5 -> Input a new number
6 -> Exit
Option: 4
1.666667

Options:
1 -> Add
1 -> Add
2 -> Subtract
3 -> Multiply
4 -> Divide
5 -> Input a new number
6 -> Exit
Option: 5
New Value for a: 1
New Value for b: 4
Values updated

Options:
1 -> Add
2 -> Subtract
3 -> Multiply
4 -> Divide
5 -> Input a new number
6 -> Exit
Option: 2
-3


```

# 5. Membuat Header (10 poin)

Pindahkan function-function dari program yang telah dibuat kedalam file header (.h) yang terpisah. Pada file main, import header tersebut sehingga dapat digunakan kembali.

Anda dapat merujuk kepada contoh berikut: https://www.geeksforgeeks.org/write-header-file-c/

<b>**Pengumpulan file dilakukan secara terpisah sehingga terdapat 3 file yang wajib dikumpulkan :**

<ol>
<li>File .md dari TP</li>
<li>Program main.c</li>
<li>Function headers.h</li>
</ol

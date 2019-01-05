# mengubah-nilai-ke-huruf

    #include<stdio.h>
    #include<conio.h>

    int tukar (int nilai);

    int main (void)
    {
    int nilai;
    printf("Masukan Nilai Antara 1 sampai 4 : ");
    scanf("%d",&nilai);
    tukar (nilai);
    getch ();
    }

    int tukar (int nilai)
    {
    switch (nilai)
    {
                case 4:
                                printf("Nilai Huruf : A"); break;
                case 3:
                                printf("Nilai Huruf : B"); break;
                case 2:
                                printf("Nilai Huruf : C"); break;
                case 1:
                                printf("Nilai Huruf : D"); break;
                default :
                                printf("Kesalah dalam memasukan Angka");
    }
    return (nilai);
    }
    © 2019 GitHub, Inc.
    
    
  hasil
  ![img](https://github.com/septianaana/mengubah-nilai-ke-huruf/blob/master/mengubah%20nilai%20ABCD.png?raw=true)

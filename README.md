# Perulangan


              #include<stdio.h>
              #include<conio.h>

              int ulang (int n);

              int main (void)
              {printf(" \t|=======================================================|\n");
              printf(" \t|======== PROGRAM MENGULANG KALIMAT SEBANYAK N =========|\n") ;
              printf(" \t|=================== ALIF MUSTAFANAH ===================|\n") ;
              printf(" \t|=======================================================|\n");
              printf(" \t\n");
              int n;

              printf("Masukan Nilai (n) : ");
              scanf("%d",&n);
              ulang (n);
              getch ();
              }

              int ulang (int n)
              {
              int i;
              for(i=1;i<=n;i++)
              printf("Algoritma dan Pemrograman\n");
              return (i);
              }



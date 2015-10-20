#include <stdio.h>
#include <string.h>
#include <math.h>


void hitung_3gelang() {

	int G1=0, G2=0, G3=0;
	int N=0;
	char WARNA[20];

	for (N=1; N<=3; N++) {

		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		if ( strcmp(WARNA, "hitam") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
			 }
		}else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				}
        }else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
			 }
        }else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;}
		}else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;}
		}else if ( strcmp(WARNA, "abu abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;}
		}else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 9; break;
				case 2: G2 = 9; break;
				case 3: G3 = 9; break;}

		}

	}

	N = (G1*10 + G2) * pow(10,G3);

	printf("\nNilai resistor R = %d ohm toleransi: 20 persen", N );

}


void hitung_4gelang() {

	int G1=0, G2=0, G3=0, G4=0;
	int N=0;
	char WARNA[20];
	char PERSEN = '%';


	for (N=1; N<=4; N++) {

		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		if ( strcmp(WARNA, "hitam") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
				case 4: G4 = 0; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
				case 4: G4 = 0; break;
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
				case 4: G4 = 2; break;
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 0; break;
			 }
		} else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				case 4: G4 = 0; break;
			 }
		} else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
				case 4: G4 = 0.5; break;
			 }
		} else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G4 = 0.25; break;
			 }
		} else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;
				case 4: G4 = 0.1; break;
			 }
		} else if ( strcmp(WARNA, "abu abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;
				case 4: G4 = 0.05; break;
			 }
        } else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 4: G4 = 5; break;
			 }
		}
		  else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 4: G4 = 10; break;
			 }
		}
		  else if ( strcmp(WARNA, "tak berwarna") == 0 ) {
			 switch (N) {
				case 4: G4 = 20; break;
			 }
		}
	}
	N = (G1*10 + G2) * pow(10,G3);

	printf("\nNilai resistor R = %d ohm", N );
	printf("\nNilai Toleransi = %d %c", G4, PERSEN );


}

void hitung_5gelang() {

	int G1=0, G2=0, G3=0, G4=0, G5=0 ;
	int N=0;
	char WARNA[20];
	char PERSEN = '%';


	for (N=1; N<=5; N++) {
		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		if ( strcmp(WARNA, "hitam") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
				case 4: G4 = 0; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
				case 4: G4 = 1; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
				case 4: G4 = 2; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 3; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				case 4: G4 = 4; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
				case 4: G5 = 5; break;
				case 5: G4 = 0.5; break;
			 }
		} else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G5 = 6; break;
				case 5: G4 = 0.25; break;
			 }
		} else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 7; break;
				case 2: G2 = 7; break;
				case 3: G3 = 7; break;
				case 4: G5 = 7; break;
				case 5: G4 = 0.1; break;
			 }
		} else if ( strcmp(WARNA, "abu abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 8; break;
				case 2: G2 = 8; break;
				case 3: G3 = 8; break;
				case 4: G5 = 8; break;
				case 5: G4 = 0.05; break;
			 }
        } else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 9; break;
				case 2: G2 = 9; break;
				case 3: G3 = 9; break;
				case 4: G4 = 9; break;
				case 5: G5 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 5: G4 = 5; break;
			 }
		}
		  else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 5: G4 = 10; break;
			 }
		}
		  else if ( strcmp(WARNA, "tak berwarna") == 0 ) {
			 switch (N) {
				case 5: G4 = 20; break;
			 }
		}

	}

	N = (G1*100 + G2*10 + G3) * pow(10,G4);

	printf("\nNilai resistor R = %d ohm", N );
	printf("\nNilai Toleransi = %d %c", G5, PERSEN );


}

void hitung_6gelang() {

	int G1=0, G2=0, G3=0, G4=0, G5=0, G6=0 ;
	int N=0;
	char WARNA[20];
	char PERSEN = '%';

	for (N=1; N<=6; N++) {
		printf("Masukan warna GELANG ke %d: ", N);
		scanf("%s", WARNA);

		if ( strcmp(WARNA, "hitam") == 0 ) {
			 switch (N) {
				case 1: G1 = 0; break;
				case 2: G2 = 0; break;
				case 3: G3 = 0; break;
				case 4: G4 = 0; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "coklat") == 0 ) {
			 switch (N) {
				case 1: G1 = 1; break;
				case 2: G2 = 1; break;
				case 3: G3 = 1; break;
				case 4: G4 = 1; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "merah") == 0 ) {
			 switch (N) {
				case 1: G1 = 2; break;
				case 2: G2 = 2; break;
				case 3: G3 = 2; break;
				case 4: G4 = 2; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "orange") == 0 ) {
			 switch (N) {
				case 1: G1 = 3; break;
				case 2: G2 = 3; break;
				case 3: G3 = 3; break;
				case 4: G4 = 3; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "kuning") == 0 ) {
			 switch (N) {
				case 1: G1 = 4; break;
				case 2: G2 = 4; break;
				case 3: G3 = 4; break;
				case 4: G4 = 4; break;
				case 5: G5 = 0; break;
			 }
		} else if ( strcmp(WARNA, "hijau") == 0 ) {
			 switch (N) {
				case 1: G1 = 5; break;
				case 2: G2 = 5; break;
				case 3: G3 = 5; break;
				case 4: G5 = 5; break;
				case 5: G4 = 0.5; break;
			 }
		} else if ( strcmp(WARNA, "biru") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G5 = 6; break;
				case 5: G4 = 0.25; break;
			 }
		} else if ( strcmp(WARNA, "ungu") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G5 = 6; break;
				case 5: G4 = 0.1; break;
			 }
		} else if ( strcmp(WARNA, "abu abu") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G5 = 6; break;
				case 5: G4 = 0.05; break;
			 }
        } else if ( strcmp(WARNA, "putih") == 0 ) {
			 switch (N) {
				case 1: G1 = 6; break;
				case 2: G2 = 6; break;
				case 3: G3 = 6; break;
				case 4: G4 = 6; break;
				case 5: G5 = 0; break;
			 }
		}  else if ( strcmp(WARNA, "emas") == 0 ) {
			 switch (N) {
				case 5: G4 = 5; break;
			 }
		}
		  else if ( strcmp(WARNA, "perak") == 0 ) {
			 switch (N) {
				case 5: G4 = 10; break;
			 }
		}
		  else if ( strcmp(WARNA, "tak berwarna") == 0 ) {
			 switch (N) {
				case 5: G4 = 20; break;
			 }
		}

	}

	N = (G1*100 + G2*10 + G3) * pow(10,G4);

	printf("\nNilai resistor R = %d ohm", N );
	printf("\nNilai Toleransi = %d %c", G5, PERSEN);
	printf("\nNilai gelang ke-6 diabaikan.....!!!");


}



int main() {

	int GELANG = 0;

	while ( (GELANG<3) || (GELANG>6) ) {
		printf("Masukan jumlah gelang : ");
		scanf("%d", &GELANG );

		if ( (GELANG<3) || (GELANG>6) ) {
			printf("\n---------------------------");
			printf("\nNilai GELANG antara 3 s/d 6");
		    printf("\n---------------------------\n");
		}

		if (GELANG == 3) {
			hitung_3gelang();
		} else if (GELANG == 4) {
			hitung_4gelang();
		} else if (GELANG == 5) {
		    hitung_5gelang();
		} else if (GELANG == 6) {
            hitung_6gelang();
		}

	}


	return 0;
}

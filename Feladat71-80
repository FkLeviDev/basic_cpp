#include <iostream>
using namespace std;

int main() {
    // 72. Dinamikus Mátrix Létrehozása
    int sor = 3, oszlop = 3;
    
    // A gerinc (pointerek pointere)
    int** matrix = new int*[sor]; 
    
    // A bordák (sorok)
    for(int i=0; i<sor; i++) {
        matrix[i] = new int[oszlop];
    }

    // 73. Feltöltés és 76. Szorzótábla
    for(int i=0; i<sor; i++) {
        for(int j=0; j<oszlop; j++) {
            matrix[i][j] = (i+1) * (j+1);
        }
    }

    // 74. Kiíratás
    cout << "Matrix:" << endl;
    for(int i=0; i<sor; i++) {
        for(int j=0; j<oszlop; j++) {
            cout << matrix[i][j] << " ";
        }
        cout << endl;
    }

    // 77. Egységmátrix (Átlóban 1)
    if(sor == oszlop) {
        for(int i=0; i<sor; i++) matrix[i][i] = 1; // Csak ahol sor==oszlop
    }

    // 75. Törlés (FORDÍTOTT SORREND!)
    for(int i=0; i<sor; i++) {
        delete[] matrix[i]; // Sorok törlése
    }
    delete[] matrix; // Gerinc törlése

    return 0;
}

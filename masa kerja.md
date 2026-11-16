#include <iostream>
using namespace std;

int main() {
    int usia, mk, up;

    // Input data
    cout << "Masukkan usia: ";
    cin >> usia;

    cout << "Masukkan masa kerja: ";
    cin >> mk;

    // Percabangan berdasarkan usia
    if (usia > 65) {
        cout << "Anda sudah pensiun" << endl;
    } 
    else {
        // Percabangan berdasarkan masa kerja
        if (mk > 35) {
            up = 200000;
        } 
        else {
            up = 300000;
        }

        // Output
        cout << "Masa Kerja : " << mk << endl;
        cout << "Uang Pensiun (UP) : Rp" << up << endl;
        cout << "Usia : " << usia << endl;
    }

    return 0;
}

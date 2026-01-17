'''
#include <iostream>
using namespace std;

int main() {
    string name;
    int artistType;

    cout << "===================================" << endl;
    cout << "     Spotify Favorite Artist    " << endl;
    cout << "===================================" << endl;

    cout << "Enter your name: ";
    cin >> name;

    cout << "\nSelect your favorite artist type:" << endl;
    cout << "1. Pop Artist" << endl;
    cout << "2. K-Pop Artist" << endl;
    cout << "3. Western Artist" << endl;
    cout << "4. Chinese Artist" << endl;
    cout << "Choose (1-4): ";
    cin >> artistType;

    cout << "\nHello " << name << "!" << endl;

    if (artistType == 1) {
        cout << "Spotify suggests: Pop Hits Playlist" << endl;
    }
    else if (artistType == 2) {
        cout << "Spotify suggests: K-Pop Top Chart Playlist" << endl;
    }
    else if (artistType == 3) {
        cout << "Spotify suggests: Western Top Songs Playlist" << endl;
    }
    else if (artistType == 4) {
        cout << "Spotify suggests: Chinese Pop Playlist" << endl;
    }
    else {
        cout << "Invalid choice. Please restart the program." << endl;
    }

    cout << "\nThank you for using Spotify!" << endl;

    return 0;
}


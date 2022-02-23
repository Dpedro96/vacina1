# vacina1
#include<iostream>
#include<iomanip>

using namespace std;

typedef struct{
    int dia;
    int mes;
    int ano;
} Data;
typedef struct{
    cpf;
    nome;
    Data 1dose=00;
    Data 2dose=00;
    Data 3dose=00;
} Dados;
void preenche(Dados *dados){
    cout << "Digite seu CPF" << endl;
    cin >> dados->cpf;
    cout << "Digite seu Nome" << endl;
    cin >> dados->nome;
    cout << "Data da primeira dose" << ednl;
    cin >> dados->dose1.dia;
    cin >> dados->dose1.mes;
    cin >> dados->dose1.ano;
}
void segundadose(Dados *segunda){
    cout << "Data da segunda dose" << endl;
    cin >> segunda->dose2.dia;
    cin >> segunda->dose2.mes;
    cin >> segunda->dose2.ano;
}
void reforso(Dados *terceira){
    cout < "Data da dose de reforço" << endl;
    cin >> terceira->dose3.dia;
    cin >> terceira->dose3.mes;
    cin >> terceira->dose3.ano;
}
    void imprime(Dados *vaciana){
        cout << vacina.cpf << " " << vacina.nome << " " << vacina.dose1.dia <<"/" << vacina.dose.mes << "/" << vacina.dose1.ano;
        cout << "  " << vacina.dose2.dia << "/" << vacina.dose2.mes << "/" << vacina.dose2.ano;
        cout << "  " << vacina.dose3.dia << "/" << vacina.dose3.mes << "/" << vacina.dose3.ano;
    }
int main(){
    int i;
    preenche();
    
}

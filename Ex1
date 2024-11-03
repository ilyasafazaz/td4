#include <iostream>
using namespace std;
class NbrComplex
{
private:
	float partieReel;
	float partieImaginaire;
public:
	float setReel();
	float setImag();
	float getReel();
	float getImag();
	void getNbrComplet();
	static void addition(NbrComplex value1, NbrComplex value2);
	static void egalite(NbrComplex value1, NbrComplex value2);
	static void soustraction(NbrComplex value1, NbrComplex value2);
	//static void multiplication(NbrComplex value1, NbrComplex value2);
	//static void division(NbrComplex value1, NbrComplex value2);
	//NbrComplex();
	//~NbrComplex();
};
float NbrComplex::setReel()
{
    cout << "Saisir la partie reel: ";
    cin >> partieReel;
    return partieReel;
}

float NbrComplex::setImag()
{
    cout << "Saisir la partie imaginaire: ";
    cin >> partieImaginaire;
    return partieImaginaire;
}

float NbrComplex::getReel()
{
    return partieReel;
}

float NbrComplex::getImag()
{
    return partieImaginaire;
}

void NbrComplex::getNbrComplet()
{
    cout << getReel() << "+" << getImag() << "i"<<endl;
}

void NbrComplex::addition(NbrComplex value1,NbrComplex value2)
{
    float resultReel;
    float resultImag;
    resultReel =value1.getReel() + value2.getReel();
    resultImag = value1.getImag() + value2.getImag();
    cout <<"la somme de deux nombres complexe est : "<< resultReel <<"+"<< resultImag <<"i"<<endl;
}

void NbrComplex::egalite(NbrComplex value1, NbrComplex value2)
{
    if ((value1.getReel() == value2.getReel()) && (value1.getImag() == value2.getImag()))
        cout << "Les deux nombres complexes sont egaux!"<<endl;
    else
        cout << "Les deux nombres complexes ne sont pas egaux!" << endl;
}

void NbrComplex::soustraction(NbrComplex value1, NbrComplex value2)
{
    float resultReel;
    float resultImag;
    resultReel = value1.getReel() - value2.getReel();
    resultImag = value1.getImag() - value2.getImag();
    cout << "la soustraction de deux nombres complexe est : " << resultReel << "+" << resultImag << "i"<<endl;
}
int main(){
    NbrComplex value1;
    value1.setReel();
    value1.setImag();
    value1.getNbrComplet();
    NbrComplex value2;
    value2.setReel();
    value2.setImag();
    value2.getNbrComplet();
    NbrComplex::egalite(value1, value2);
    NbrComplex::addition(value1, value2);
    NbrComplex::soustraction(value1, value2);
    return 0;
}

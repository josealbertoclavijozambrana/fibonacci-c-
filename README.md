

/*@author jose clavijo*/

using namespace std;

int main()
{
    int ingresar ,  valor1 , valor2 ,serie;
    serie=0;
    valor1 =0;
    valor2=1;
    bool bandera =true;


cin>> ingresar;
cout<<valor1<<"," << valor2 << ",";
for(int contador=0; contador <= ingresar; contador++){

    if(bandera== true){
             valor1 = valor1+valor2;
    cout << valor1<<"," ;
        bandera = false;
    }
    else{

            valor2= valor1 + valor2 ;
              cout << valor2 << "," ;
        bandera = true;

    }





}
    }





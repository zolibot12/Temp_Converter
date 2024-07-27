written in c++

join my discord server: https://discord.gg/58Y7X2Cq

#include <iostream>
#include <cmath>
#include <cstdlib>

int main(){
double temp;
char unit;

   std::cout << "*****Temparature Converter***** " << '\n';
      std::cout << "F is for feranhite " << '\n';
      std::cout << "C is for celsius " << '\n';
         std::cout << "What unit would you like to convert to: "; 
            std::cin >> unit;

            if(unit == 'F' || unit == 'f'){
                   std::cout << "Enter the temparature in Celsius: " << '\n';
                   std::cin >> temp;

                   temp = (1.8 * temp) + 32.0;
                      std::cout << "Temparature is: " << temp << "F" << '\n';
                    }
        else if(unit == 'C' || unit == 'f'){
                   std::cout << "Enter the temparature in Ferenhite: " << '\n';
                   std::cin >> temp;

                   temp = (temp - 32) / 1.8;
                      std::cout << "Temparature is: " << temp << "Cel" << '\n';
        }
        else{
                   std::cout << "Please only enter F or C ";
        }
                
    return 0;
}

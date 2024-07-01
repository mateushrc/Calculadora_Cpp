#include <iostream>
#include <cstdlib>

void Menu();
void Soma();
void Subtrair();
void Multiplicar();
void Dividir();

void Soma()
{
    system("cls");
    float n1;
    float n2;

    std::cout << "\nDigite o primeiro numero: ";
    std::cin >> n1;
    std::cout << "\nDigite o segundo numero: ";
    std::cin >> n2;

    float res = n1 + n2;

    std::cout << "\nResultado: " << res << "\n";
    system("pause");
    Menu();
}

void Subtrair()
{
    system("cls");
    float n1;
    float n2;

    std::cout << "\nDigite o primeiro numero: ";
    std::cin >> n1;
    std::cout << "\nDigite o segundo numero: ";
    std::cin >> n2;

    float res = n1 - n2;

    std::cout << "\nResultado: " << res << "\n";
    system("pause");
    Menu();
}

void Multiplicar()
{
    system("cls");
    float n1;
    float n2;

    std::cout << "\nDigite o primeiro numero: ";
    std::cin >> n1;
    std::cout << "\nDigite o segundo numero: ";
    std::cin >> n2;

    float res = n1 * n2;

    std::cout << "\nResultado: " << res << "\n";
    system("pause");
    Menu();
}

void Dividir()
{
    system("cls");
    float n1;
    float n2;

    std::cout << "\nDigite o primeiro numero: ";
    std::cin >> n1;
    std::cout << "\nDigite o segundo numero: ";
    std::cin >> n2;

    float res = n1 / n2;

    std::cout << "\nResultado: " << res << "\n";
    system("pause");
    Menu();
}

void Menu()
{
    system("cls");
    int res;

    std::cout << "Ola, Seja Bem-Vindo a Calculadora\n";
    std::cout << "O que voce deseja fazer?\n";
    std::cout << "1 - Somar\n";
    std::cout << "2 - Subtrair\n";
    std::cout << "3 - Multiplicar\n";
    std::cout << "4 - Dividir\n";
    std::cout << "-1 - Sair\n";
    std::cout << "Digite um numero: ";
    std::cin >> res;

    switch (res)
    {
    case 1:  Soma(); break;
    case 2:  Subtrair(); break;
    case 3:  Multiplicar(); break;
    case 4:  Dividir(); break;
    case -1: exit(0); break;
    default:
        std::cout << "Opcao invalida. Tente novamente.\n";
    }
}

int main()
{
    Menu();
    return 0;
}

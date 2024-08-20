Sistema Simples de Recepção

#include <stdio.h>

int main() {
    int numVisitantes;

    // Solicita ao recepcionista o número de visitantes
    printf("Digite o número de visitantes que entraram na empresa hoje: ");
    scanf("%d", &numVisitantes);

    // Exibe uma mensagem de confirmação
    printf("Número de visitantes registrado: %d\n", numVisitantes);
    printf("Obrigado por registrar o número de visitantes.\n");

    return 0;
}


Aplicativo de gestão financeira pessoal

#include <stdio.h>

int main() {
    float receita, despesa, saldo;

    // Solicita ao usuário a receita
    printf("Digite o valor da receita: ");
    scanf("%f", &receita);

    // Solicita ao usuário a despesa
    printf("Digite o valor da despesa: ");
    scanf("%f", &despesa);

    // Calcula o saldo
    saldo = receita - despesa;

    // Exibe o saldo atualizado
    printf("Saldo atualizado: %.2f\n", saldo);

    return 0;
}

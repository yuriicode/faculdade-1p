Código Comissão por Venda:

    #include <stdio.h>
    #include <stdlib.h>

    int main() {

      float valorVenda, comissaoVenda, valorTotal;

      printf("Qual foi o valor da venda? \n");
      printf("Digite: ");
      scanf("%f", &valorVenda);
      system("cls");

      if (valorVenda < 300.00) {
        comissaoVenda = (5 * valorVenda/100);
        valorTotal = valorVenda - comissaoVenda;
        printf("Valor da sua venda: %0.2f", valorVenda);
        printf("\nComissão de venda (5): %0.2f", comissaoVenda);
        printf("\nValor da venda - comissão: %0.2f", valorTotal);

      } else if (valorVenda < 500.00) {
        comissaoVenda = (10 * valorVenda/100);
        valorTotal = valorVenda - comissaoVenda;
        printf("Valor da sua venda: %0.2f", valorVenda);
        printf("\nComissão de venda (10): %0.2f", comissaoVenda);
        printf("\nValor da venda - comissão: %0.2f", valorTotal);
      } else if (valorVenda < 1000.00) {
        comissaoVenda = (15 * valorVenda/100);
        valorTotal = valorVenda - comissaoVenda;
        printf("Valor da sua venda: %0.2f", valorVenda);
        printf("\nComissão de venda (15): %0.2f", comissaoVenda);
        printf("\nValor da venda - comissão: %0.2f", valorTotal);
      } else {
        comissaoVenda = (20 * valorVenda/100);
        valorTotal = valorVenda - comissaoVenda;
        printf("Valor da sua venda: %0.2f", valorVenda);
        printf("\nComissão de venda (20): %0.2f", comissaoVenda);
        printf("\nValor da venda - comissão: %0.2f", valorTotal);
      }

    }

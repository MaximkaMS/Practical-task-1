# Practical-task-1
#include <stdio.h>

int main() {
    int t1, t2, t3;
    double total_time;

    // Введення значень часу для кожного гостя
    printf("Введіть три значення: ");
    scanf("%d %d %d", &t1, &t2, &t3);

    // Обчислення сумарного часу
    total_time = 1.0 / (1.0/t1 + 1.0/t2 + 1.0/t3);

    // Виведення результату
    printf("Час, необхідний для з'їдання пирога: %.2f годин\n", total_time);

    return 0;
}

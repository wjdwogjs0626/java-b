void main() {
    Scanner keyboard = new Scanner(System.In);
    int base;
    int rectagular_area;
    double radius;
    double circle_area;

    System.out.print("정사각형의 한변의 길이 입력해(예 5) : ");
    base = keyboard.nextInt();

    rectagular_area = base * base;
    redius = base / 2.0;
    circle_area = PI * radius *  radius;
    area = rectsgular_area - circle_area;

    System.out.printf("한변의 길이가 %,d Cm인 정사각형의 면적 = %,d \u33A0\n");
    System.out.printf("이 정사각형 내부 원의 면적 : %,2f \u33A0\n",circle_area);
    System.out.printf("구하려는 면적 : %,.2f\u33a0\n",area);
}

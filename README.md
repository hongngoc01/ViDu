#include <iostream>
using namespace std;

void main()
{
	int x = 0, y = 0;

	// Đọc giá trị của x và y từ bàn phím
	cout << "Please input x: "<<endl;
	cin >> x;
	
	cout << "Please input y: "<<endl;
	cin >> y;

	// Xuất ra kết quả tính toán tương ứng

	cout << "\tx + y = " << x + y << endl;
	cout << "\tx - y = " << x - y << endl;
	cout << "\tx * y = " << x * y << endl;
	cout << "\tx / y = " << x / y << endl;
	
}

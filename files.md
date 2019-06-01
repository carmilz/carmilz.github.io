---
title: Files
subtitle: 파일 리스트
layout: "page"
icon: fa-file
order: 3
---
* 숫자맞추기 - [프로그램](https://github.com/carmilz/TestOnly/releases/download/v1.0/bin.exe)

소스 코드

```cpp
#include <fstream>
#include <iostream>
using namespace std;

int main()
{
	ifstream fin("number.txt");
	if (!fin) {
		cout << "오류: 파일을 읽을 수 없습니다." << endl;
		return 1;
	}

	int win = 0;
	int num;
	int inum;
	fin >> num;

	cout << "숫자 맞추기 게임 by CarMilZ" << endl;
	cout << "제가 미리 정한 숫자를 맞추시면 됩니다." << endl;
	cout << "범위는 0~1000까지입니다." << endl;

	while (!win) {
		cin >> inum;
		if (num != inum) {
			if (num > inum) {
				cout << "Up!" << endl;
			}
			else {
				cout << "Down!" << endl;
			}
		}
		else {
			cout << "정답!" << endl;
			win = 1;
		}
	}

	return 0;
}
```
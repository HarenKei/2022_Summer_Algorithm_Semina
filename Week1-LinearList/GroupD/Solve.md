Daelim ICC 2022 Summer Algorithm Semina - Group B
==============================
## Week 1 - Linear List


### ✍️ 1. BOJ 8958 - OX 퀴즈
#### 정승민 / HarenKei / 풀이 코드 / C++
```cpp
#include <bits/stdc++.h>

using namespace std;

int main(){
    ios::sync_with_stdio(false); 
    cin.tie(NULL);
    cout.tie(NULL);

    int testCase;
    cin >> testCase;

    for(int i = 0; i < testCase; i++){ // testCase 크기만큼 반복
        string oxquiz;
        cin >> oxquiz;
        int cntO = 0;
        int cntResult = 0;

        for(int j = 0; j < oxquiz.length(); j++){ // 입력받은 OX 문자열 길이만큼 반복하며 값을 계산
            if(oxquiz[j] == 'O'){
                cntO ++; //문자열의 j번째가 'O'면 개수 세기
                cntResult += cntO; //'O'의 개수를 총합에 더함
                
            } else{
                cntO = 0; //X가 나오면 'O' 카운트를 초기화.
            }
        }
        cout << cntResult << endl;
    }
    return 0;
}
```

#### 이준성 / git / 풀이코드 / 언어
```
```

#### 김태은 / hugesilver / 풀이코드 / 언어
```
```

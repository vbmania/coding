coding
======

1. integer가 몇 바이트인가?
4byte (32bit) : 시스템에 따라 다르나 일반적으로 32bit


2. short integer의 최하/최상 값은 얼마인가?
65536 (16bit)


3. unsigned integer는 얼마 정도까지 표현 가능한가?
4294967296 (42억 9천만)


4. quick sort의 time complexity는 어떻게 되나?

http://ko.wikipedia.org/wiki/퀵_정렬

5. 100만개의 integer 자료를 가지는 integer array가 있는데, 이중 최상위 1000개의 값만 뽑고 싶다.
    그런데 그 값이 1부터 10만까지의 값으로 bound되어 있다.
    array를 많이 써도 되니, 가장 빠르게 구할 수 있는 방법은 뭐냐?
    - 그냥 array 10만까지 만들고, 단순 count -> O(n)
6. 100만개에서 최상위 1000개만 뽑으려면?
7. program coding 반드시 판서를 시켜보세요. (자바든 C든 C++이든)
   만약 C coding을 할 줄 아는 사람이면,
  char* strcat(char *dst, char *src) 이 함수를 써 놓고, 기능을 코딩하라고 (날 코드로) 하세요.
  
char* strcat(char *dst, char *src)
{
    while (*dst) dst++ ;
    while (*dst++ = *src++) ;
}
   제가 지금까지 strcat, strcpy, 그리고, linked list를 이용해서 stack을 구현해봐라..
   이런것을 날코딩 시켜봤는데요, 이거 제대로 작성하는 사람 50%도 안됩니다.
   꼭 코딩을 시켜보세요.
  
8. java에서 static int main (..)으로 시작하는데, 그거 왜 static을 붙이나?
  
품질팀은 아래와 같은 질문 특히 maximum likelihood estimation이 뭐냐?를 반드시 물어보세요.
1. maximum likelihood estimation하고, bayesian learning하고 차이가 뭐냐?
2. svm 들어봤냐? 들어봤다고 답하면, 거기서 support vector가 무슨 뜻이냐?
3. bias와 variance가 뭐냐?
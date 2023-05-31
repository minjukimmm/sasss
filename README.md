sass 요즘엔 사용 안함, SCSS를 사용한다. (샤스싸쓰쌰쓰)
![image](https://github.com/minjukimmm/sasss/assets/129017089/e4366bf7-5c74-40f7-a939-e39eceedce7c)

scss 컴파일
![image](https://github.com/minjukimmm/sasss/assets/129017089/927ade49-a42f-4470-b665-7597c848569b)


css 위치변경
![image](https://github.com/minjukimmm/sasss/assets/129017089/f5013ccd-52d3-44ef-a73c-a99f61b0197d)


savePath :null 이면 scss파일과 같은 위치에 style.css가 생긴다
![image](https://github.com/minjukimmm/sasss/assets/129017089/233cd635-1929-4b57-a6fe-540c42c59eb1)


~은 style.scss를 의미, /는 style.scss가 있는 폴더
![image](https://github.com/minjukimmm/sasss/assets/129017089/e9a1e3a4-943e-4744-b3f1-35d64b75314e)

scss 파일이 있는 폴더의 상위폴더에 생성
![image](https://github.com/minjukimmm/sasss/assets/129017089/dfe94ca5-ee01-4155-b603-33fda5e6dfc6)

주석처리방법-----------
// 주석처리방법은 css로 컴파일되지않는다
/**/ 주석처리방법은 css로 컴파일 되어 나타난다
![image](https://github.com/minjukimmm/sasss/assets/129017089/b18139ae-8c57-49d1-a61a-6f7eaf710c05)

변수 만들기 --> $로 시작(영문,숫자, - , _ )만 사용할 수 있음, 숫자로 시작 불가능
![image](https://github.com/minjukimmm/sasss/assets/129017089/7fe10da0-566d-4711-a67b-f328b82a647a)

![image](https://github.com/minjukimmm/sasss/assets/129017089/d815e756-491a-4788-82eb-cd8e85a6c650)

Partials(파샬)
-- 관련된것끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리 분산시켜서 모듈화시키는 기능

Partials(파샬)의 파일명은 _ 로 시작하며
불러들일때는 @import '파일명', 이 때 파일명에 _ 는 포함시키지 않고 확장명도 포함시키지 않는다.
SCSS는 _ 로 시작하는 파일은 컴파일하지 않는다.

![image](https://github.com/minjukimmm/sasss/assets/129017089/9c0c51a6-f9d2-486c-8fa5-19f5ca93780f)


# @import -> 변수가 중복될때는 아래의 것이 적용된다. 

[![image](https://github.com/minjukimmm/sasss/assets/129017089/1894cb4e-8c19-476f-bc98-a0ea2b25096f)](https://user-images.githubusercontent.com/60366769/242167285-611e8060-de4c-410f-8fb8-fbe56eb20e26.png)


# @use -> 변수 이름이 같을 때 에러 발생, @use를 사용할때는 앞에 파일명을 추가해서 파일명.변수명
![image](https://github.com/minjukimmm/sasss/assets/129017089/fbdfaa80-e3d9-4d0c-86b3-24430e34a8a5)


# as 뒤에 별명을 붙여서 사용할수 있다.
![image](https://github.com/minjukimmm/sasss/assets/129017089/c1e311f0-eaa2-45f4-a295-19151a715e44)



# @forward 는 파샬을 묶어줌 style.scss에서는 _index.scss를 호출하여 사용함
![image](https://github.com/minjukimmm/sasss/assets/129017089/702ee09c-3ec2-4105-9357-7606f62831bb)

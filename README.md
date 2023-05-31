sass 요즘엔 사용 안함, SCSS를 사용한다. (샤스싸쓰쌰쓰)
image

scss 컴파일
image

css 위치변경
image

savePath :null 이면 scss파일과 같은 위치에 style.css가 생긴다
image

~은 style.scss를 의미, /는 style.scss가 있는 폴더
image

scss 파일이 있는 폴더의 상위폴더에 생성
image

주석처리방법-----------
// 주석처리방법은 css로 컴파일되지않는다
/**/ 주석처리방법은 css로 컴파일 되어 나타난다
image

변수 만들기 --> $로 시작(영문,숫자, - , _ )만 사용할 수 있음, 숫자로 시작 불가능
image

image

Partials(파샬)
-- 관련된것끼리 묶어서 분리 / 소스에 반복되는 부분들을 분리 분산시켜서 모듈화시키는 기능

Partials(파샬)의 파일명은 _ 로 시작하며
불러들일때는 @import '파일명', 이 때 파일명에 _ 는 포함시키지 않고 확장명도 포함시키지 않는다.
SCSS는 _ 로 시작하는 파일은 컴파일하지 않는다.

image

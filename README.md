# sass 사용거의 안함 scss를 사용한다  scss--->사스라고 읽음


![image](https://github.com/heoyounggyu/sass/assets/129017041/e440b883-36b5-4db5-8915-0b523f09231f)


#scss 컴파일

![image](https://github.com/heoyounggyu/sass/assets/129017041/85ec4a89-1037-4c2b-8034-aed9364e138c)



#css위치변경

![image](https://github.com/heoyounggyu/sass/assets/129017041/2c275047-c37a-41bf-bffb-4577c2c6001a)

#sace path:null이면 scss파일과 같은 위치에 style.css가생긴다

![image](https://github.com/heoyounggyu/sass/assets/129017041/6ee1269e-6c7e-4dc8-b3d6-240c0ee165e4)


#~은 style.scss를 의미, / style.scss 가 있는 폴더

![image](https://github.com/heoyounggyu/sass/assets/129017041/798e7384-6df0-40a0-9de1-184b40a8083a)


# scss파일이 있는 폴더의 상위요소에 생성

![image](https://github.com/heoyounggyu/sass/assets/129017041/bc4addc8-f90b-4548-b802-36f5c154af8b)

#주석 처리 방법

//주석처리방법은  css로 컴파일 되지 않는다

/**/주석처리 방법은 css로 컴파일되어 나타남

![image](https://github.com/heoyounggyu/sass/assets/129017041/4eb950af-d331-4fcf-8f07-6784c3ff592f)

#변수 만들기 --->  $로 시작함,(영문, 숫자, -,_)만 사용할수 있음. 숫자로 시작할수 없음

![image](https://github.com/heoyounggyu/sass/assets/129017041/cd45391b-0610-42ae-a98f-7194a74307c4)


#partlals(파샹)
  관련된것끼지 묶어서 분리 소스에 반복되는 부분들을 분리 분산시켜서 모듈화 시키는기능
  partlals의 파일명은 _로 시작하며
  
  불러들할때는 @import '파일명' 이때 파일명에 _는 포함시키지 않고 확장명도 포함시키지 않는다
  
  scss는 _로 시작하는 파일은 컴파일하지 않는다
  
  ![image](https://github.com/heoyounggyu/sass/assets/129017041/64dd61c1-a103-466b-af98-f9f4991e02e8)

#@import --> 변수가 중복될때는 아래의 것이 적용된다 

![image](https://github.com/heoyounggyu/sass/assets/129017041/66a302e2-3be3-47f8-b5b5-c60c8eba7464)


# @use  --> 변수이름이 같을때 에러발생. @use를 사용할때는 앞에 파일명에 추가해서 파일명, 변수명

![image](https://github.com/heoyounggyu/sass/assets/129017041/4b541fb5-fa3d-43f2-a526-ff7d7a5740f5)



  
  
  






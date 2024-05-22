# 이차원, 삼차원 운동



- [[#3.1 벡터]]
- [[#3.2 속도 벡터, 가속도 벡터]]
- [[#3.3 상대 운동]]
- 

## 3.1 벡터
  크기와 방향을 함께 가지는 물리량을 **벡터**(vector)라고한다. 벡터는 크기만 가진 **스칼라**(scalar)와는 다르다.
### 위치와 변위
  원점에서 어떤 점까지 그린 화살표를 그 점의 **위치 벡터**(position vector) $\vec{r}$ 로 표시한다. $\Delta \vec{r}$를 위치변화를 나타내는 **변위 벡터**(displacement vector)라고 부른다.
  **벡터 더하기**(vector addtion)는 다음과 같은 규칙을 성립한다.
  $$\vec{A} + \vec{B} = \vec{B} + \vec{A}$$
![[Essential_University_Physicis.pdf#page=53&rect=122,509,255,575|Richard Wolfson - Essential University Physics_ Volume 1 (4th Edition) (2019, Pearson) - libgen.li, p.35]]

 $$(\vec{A} + \vec{B}) + \vec{C} = \vec{A} + (\vec{B} + \vec{C})$$
![[Essential_University_Physicis.pdf#page=53&rect=266,503,424,574|Richard Wolfson - Essential University Physics_ Volume 1 (4th Edition) (2019, Pearson) - libgen.li, p.35]]


  
### 곱하기
  ![[Essential_University_Physicis.pdf#page=53&rect=463,549,605,617|Richard Wolfson - Essential University Physics_ Volume 1 (4th Edition) (2019, Pearson) - libgen.li, p.35]]
  벡터 $\vec{B}$가 벡터 $\vec{A}$보다 2배 크면 $\vec{B} = 2\vec{A}$로 표기한다. 스칼라와 벡터의 곱은 벡터의 크기만 바꾼다. 위 그림에$\vec{r_1} = \vec{r_2}+(-1)\Delta\vec{r}$ 또는 $\vec{r_1} = \vec{r_2} - \Delta\vec{r}$임을 알 수 있다.
### 벡터 성분
![[Essential_University_Physicis.pdf#page=53&rect=478,131,600,205|Essential_University_Physicis, p.35]]
  **좌표계**는 공간에서 위치를 지정하는 틀이다. **데카르트 좌표계**(Cartesian coordinate system),  **직각 좌표계**(rectangular coordinate system)에서는 평면의 한 점을 $(x,y)$로 표기한다. 직각 좌표계에서 $\vec{A}$의 성분은 $A_x$와 $A_y$로 표기한다. 이들 성분 벡터가 아니고 스칼라다. 이를 피타고라스를 정리를 이용하면 다음의 관계식을 얻을 수 있다.

![[24-1/physics_1/physics_math_ex_set#^0c3e0f]]
  또한 다음과 같이 표기할 수 있다.
![[24-1/physics_1/physics_math_ex_set#^51cede]]

### 단위 벡터
![[Essential_University_Physicis.pdf#page=54&rect=66,643,199,763|Essential_University_Physicis, p.36]]
  ![[Essential_University_Physicis.pdf#page=54&rect=67,496,202,635|Essential_University_Physicis, p.36]]
  **단위 벡터**(unit vector) $\hat i$와 $\hat j$를 사용하면 훨씬 간명하고 편리하게 표현할 수 있다. 단위 벡터의 크기 1이, 단위가 없으면 각각$x$축과 $y$축의 양의 방향을 향한다. 삼차원에서는 $z$축 방향의 단위 벡터 $\hat k$를 추가한다. 이차원 평면에서 $\vec A = A_x\hat i + A_y\hat j$ ,삼차원 공간에서 $\vec A = A_x\hat i + A_y\hat j + A_z\hat k$로 표기한다.

### 단위 벡터 계산
  단위 벡터를 사용하면 벡터 더하기가 더 쉬워진다. 예를 들어 설명하겠다. 벡터$\vec A = A_x\hat i + A_y\hat j$와 벡터 $\vec B = B_x\hat i + B_y\hat j$를 더한다고 가정하면 벡터의 성분만 더하면 된다.
  $$\vec A + \vec B = (A_x\hat i + B_x\hat j) + (A_y\hat i + B_y\hat j) = (A_x + B_x)\hat i + (A_y + B_y)\hat j$$


## 3.2 속도 벡터, 가속도 벡터
  일차원에서 속도를 위치의 시간 변화율로 정의하였다. 고차원에서 위치의 변화인 변위가 벡터인 점을 제외하면 똑같다.
  ![[physics_math_ex_set#^3774fc]]
  순간 속도 벡터는 다음과 같이 정의한다.
  ![[physics_math_ex_set#^cee9d3]]
  식 3.4를 벡터 성분으로 표현하는 방법이 있다.  $\vec r = x\hat i + y\hat j$라고 한다면 다음과 같다.
  $$\vec v = \frac{d\vec r}{dt} = \frac{dx}{dt}\hat i + \frac{dy}{dt}\hat j = v_x\hat i + v_y\hat j$$
  가속도 속도의 시간 변화율이므로, 평균 가속도 벡터
  ![[physics_math_ex_set#^d626f8]]
  이고, 순간 가속도 벡터는 다음과 같다.
  ![[physics_math_ex_set#^0035f4]]
  또한 성분으로 표기하면 다음과 같다.
  $$\vec a = \frac{d\vec v}{dt} = \frac{dv_x}{dt}\hat i + \frac{dv_y}{dt}\hat j = a_x\hat i + a_y\hat j$$  
### 이차원에서 속도 벡터와 가속도 벡터
![[Essential_University_Physicis.pdf#page=55&rect=468,274,584,427|Essential_University_Physicis, p.37]]
  일차원에서 운동하면 가속도가 있을 수도 없을 수도 있지만, 이차원이나 삼차원에서 곡선 운동은 항상 가속 운동이다. 고차원에서 운동하면 방향이 바뀌기 때문이다. 방향이 바뀌면 속도가 바뀌므로 가속도가 있다. 위 그림을 참조하자.
## 3.3 상대 운동
  한 **기준틀**(frame of reference)에 대한 어떤 물체의 상대 속도(비행기르 예를들) 다른 기준틀에 대한 상대 속도 바꿔야 하는 경우가 있다. 일차원인 경우에는 두 벡터를 단순히 더하면 된다. 
  비행기가 대기에 대한 상대 속도 $\vec v\prime$으로 비행하고 있을, 바람의 영향으로 지표면에 대한 대기의 상대 속도가 $\vec V$라면, 지표면에 대한 상대 속도 $\vec v$는 다음과 같다.
  ![[physics_math_ex_set#^1f37f3]]
## 3.4 등가속도 운동
## 3.5 발사체 운동
### 발사체 궤적
### 발사체 수평 도달 거리
## 3.6 등속 원운동
### 가속 원운동

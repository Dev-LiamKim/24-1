
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
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 2.webp]]
$$\vec{A} + \vec{B} = \vec{B} + \vec{A}$$ 
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis.webp]]
$$(\vec{A} + \vec{B}) + \vec{C} = \vec{A} + (\vec{B} + \vec{C})$$

### 곱하기
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 1.webp]]
  벡터 $\vec{B}$가 벡터 $\vec{A}$보다 2배 크면 $\vec{B} = 2\vec{A}$로 표기한다. 스칼라와 벡터의 곱은 벡터의 크기만 바꾼다. 위위 그림에서 $\vec{r_1} = \vec{r_2}+(-1)\Delta\vec{r}$ 또는 $\vec{r_1} = \vec{r_2} - \Delta\vec{r}$임을 알 수 있다.
  

### 벡터 성분
**좌표계**는 공간에서 위치를 지정하는 틀이다. **데카르트 좌표계**(Cartesian coordinate system),  **직각 좌표계**(rectangular coordinate system)에서는 평면의 한 점을 $(x,y)$로 표기한다. 직각 좌표계에서 $\vec{A}$의 성분은 $A_x$와 $A_y$로 표기한다. 이들 성분 벡터가 아니고 스칼라다. 이를 피타고라스를 정리를 이용하면 다음의 관계식을 얻을 수 있다.
![[24-1/physics_1/physics_math_ex_set#^0c3e0f]]
  또한 다음과 같이 표기할 수 있다.
![[24-1/physics_1/physics_math_ex_set#^51cede]]

![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 3.webp]]
	
### 단위 벡터
  **단위 벡터**(unit vector) $\hat i$와 $\hat j$를 사용하면 훨씬 간명하고 편리하게 표현할 수 있다. 단위 벡터의 크기 1이, 단위가 없으면 각각$x$축과 $y$축의 양의 방향을 향한다. 삼차원에서는 $z$축 방향의 단위 벡터 $\hat k$를 추가한다. 이차원 평면에서 $\vec A = A_x\hat i + A_y\hat j$ ,삼차원 공간에서 $\vec A = A_x\hat i + A_y\hat j + A_z\hat k$로 표기한다.

| ![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 4.webp]] | ![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 5.webp]] |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |

### 단위 벡터 계산
단위 벡터를 사용하면 벡터 더하기가 더 쉬워진다. 예를 들어 설명하겠다. 벡터$\vec A = A_x\hat i + A_y\hat j$와 벡터 $\vec B = B_x\hat i + B_y\hat j$를 더한다고 가정하면 벡터의 성분만 더하면 된다.
  $$\vec A + \vec B = \left(A_x\hat i + B_x\hat j\right) + \left(A_y\hat i + B_y\hat j\right) = \left(A_x + B_x\right)\hat i + \left(A_y + B_y\right)\hat j$$


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
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 6.webp|300]]
  일차원에서 운동하면 가속도가 있을 수도 없을 수도 있지만, 이차원이나 삼차원에서 곡선 운동은 항상 가속 운동이다. 고차원에서 운동하면 방향이 바뀌기 때문이다. 방향이 바뀌면 속도가 바뀌므로 가속도가 있다. 위 그림을 참조하자.
## 3.3 상대 운동
  한 **기준틀**(frame of reference)에 대한 어떤 물체의 상대 속도(비행기를 예로들) 다른 기준틀(지표면)에 대한 상대 속도 바꿔야 하는 경우가 있다. 일차원인 경우에는 두 벡터를 단순히 더하면 된다. 
  비행기가 대기에 대한 상대 속도 $\vec v\prime$으로 비행하고 있을, 바람의 영향으로 지표면에 대한 대기의 상대 속도가 $\vec V$라면, 지표면에 대한 상대 속도 $\vec v$는 다음과 같다.
  ![[physics_math_ex_set#^1f37f3]]
## 3.4 등가속도 운동
  가속도가 일정하면 가속도 벡터의 성분들도 일정하다. 더욱이 한 방향의 가속도 성분은 수직한 운동과는 전혀 상관이 없다. 즉 가속도가 일정하면 운동의 성분별로 등가속도 운동을 한다.
![[physics_math_ex_set#^eb97d3]]![[physics_math_ex_set#^9d77f7]]
>$\vec r$ 은 임이의 시간 $t$에서의 물체의 속도이다.
>$\vec r_0$은 $t = 0$에서 초기 위치이다.
>
## 3.5 발사체 운동
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 7.webp|500]]
  공중으로 발사된 **발사체**(projectile)는 중력의 영향 아래에서 움직인다. 발사체 운동을 기술하려면 다음의 두 가지 가정이 필요하다. 1) 중력가속도의 크기나 방향의 변화를 무시한다. 2) 공기 저항을 무시한다.
  발사체 운동을 기술할, $y$축을 수직방향, $x$축을 수평 방향으로 택하면 편리하다. 가속도 성분은 중력 가속도 하나뿐이므로, $a_x = 0, \quad a_y=-g$이다
  ![[physics_math_ex_set#^5a2a08]]![[physics_math_ex_set#^5cf907]]![[physics_math_ex_set#^964005]]![[physics_math_ex_set#^ceb39e]]

  
### 발사체 궤적
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 8.webp|500]]
  많은 경우 발사체 운동보다는 발사체 **궤적**(trajectory)에 관심이 많다. 위 그림에 따르면, 식 3.12와 3.13은 각각 다음과 같다. 
  $$x=v_0\cos\theta_0t \quad \quad and \quad \quad y = v_0\sin\theta_0t-\frac{1}{2}gt^2$$
  $x$성분 식에서 시간 $t$는 
  $$t = \frac{x}{v_0\cos\theta_0}$$
  이 결과를 $y$성분 식에 넣으면
  $$y=v_0\sin\theta_0\left(\frac{x}{v_0\cos\theta_0}\right)-\frac{1}{2}g\left(\frac{x}{v_0\cos\theta_0}\right)^2$$
  또는 다음과 같이 궤적을 얻는다.
![[physics_math_ex_set#^3fbd34]]
### 발사체 수평 도달 거리
**수평 도달 거리**(horizontal range)는 다음과 같이 얻을 수 있다.
식 3.14에 $y=0$을 넣으면 지면에서 발사한 발사체가 다시 지면으로 되돌아오는 거리를 얻을 수 있다. 
$$ 0= x\tan\theta_0-\frac{g}{2v_0^2\cos^2\theta_0}x^2 = x\left(\tan\theta_0 - \frac{gx}{2v_0^2\cos^2\theta_0}\right)$$
에서 출발 지점에 해당하는 $x = 0$과 
$$x=\frac{2v_0^2}{g}\cos^2\theta_0\tan\theta_0=\frac{2v_0^2}{g}\sin\theta_0\cos\theta_0$$
을 얻는다. 그런데 여기서 $sin2\theta_0 = 2\sin\theta_0\cos\theta_0$이므로 다음을 얻는다.
![[physics_math_ex_set#^4a6035]]

  출발 높이와 도달 높이가 다르면 올바른 도달 거리가 아니다.

| ![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 12.webp]]<br><br> | ![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 13.webp]]<br><br> |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |

## 3.6 등속 원운동
![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 14.webp|400]]
  **등속 원운동**은 속력은 일정하지만 속도의 방향이 바뀌므로 가속 운동이다. 위 그림은 반지름이 $r$인 원둘레를 속력 $v$로 움직이는 속도 벡터들이다. 속도 벡터들은 원의 접선방향이므로 운동의 순간 방향을 가리킨다.
  
| ![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 15.webp]] | ![[24-1/physics_1/Essential_University_Physics/Essential_University_Physicis 16.webp]] |
| --- | --- |
  그림 (b)는 변위 벡터 $\Delta \vec r = \vec r_2 - \vec r_1$, 그림 (c) 속도의 차이 $\Delta \vec v = \vec v_2 - \vec v_1$이다. 그림 (a)에서 $\vec v_1$은 $\vec r_1$에, $\vec v_2$은 $\vec r_1$에 수직이므로, 위 a, b, c 그림의 세 각도 $\theta$는 모두 같다. 그림 (b)와 (c)의 삼각형은 닮은꼴므로 다음을 얻는다.
  $$\frac{\Delta v}{v} = \frac{\Delta r}{r}$$
  각도 $\theta$가 충분히 작다면, 위치 벡터 $\vec r_1$에서 $\vec r_2$로 바뀌는 시간 간격 $\Delta t$ 또한 작다. 따라서 벡터 $\Delta \vec r$의 길이는 그림 (b)에서 뒤 위치 벡터의 머리 점을 잇는 원호의 길이와 어림잡아 같다. 즉 $\Delta t$동안 물체가 이동한 길이인 원호의 길이는 $v\Delta t$이므로 $\Delta r \simeq v\Delta t$이다. 이 식은 다음과 같아진다.
$$\frac{\Delta v}{v} \simeq \frac{v\Delta t}{r}$$
  이 식을 재정리하면 다음과 같이 평균 가속도의 크기를 얻는다. 
  $$\bar a = \frac{\Delta v}{\Delta t} \simeq \frac{v^2}{r}$$
  여기서 $\Delta t \to 0$인 극한을 취하면 순간 가속도를 얻을 수 있다. 이 극한에서는 $\theta \to 0$으로 원호와 $\Delta \vec r$가 같고, 어림관계식 $\Delta r \simeq v\Delta t$는 정확한 식이 된다. 따라서
![[physics_math_ex_set#^bdd3a2]]
 >$a$ : 물체가 등속 원운동을 할 때 물체의 가속도 크기.

위 식은 반지름이 $r$인 원둘레를 등속력 $v$로 도는 물체의 순간 가속도 크기이다. 그렇다면 가속도의 방향은 무엇일까? 그림(c)를 보면, $\Delta \vec v$가 두 속도 벡터에 거의 수직이다. 따라서 $\Delta t \to 0$인 극한을 취하면 $\Delta \vec v$는 가속도 $\frac{\Delta \vec v}{\Delta t}$의 방향은 정확히 속도에 수직이다. 즉 가속도 벡터의 방향은 원의 중심을 향한다. 
### 가속 원운동

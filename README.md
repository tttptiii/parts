# Parts
Author: Han Young, <<ttt.pt.iii@gmail.com>>  
Version: 0.0.0  
Date: 2022. 11. 19.  
Copyright: This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt).  
![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

## introduction

*Part*를 주어진 역할을 수행하는 단위라고 하자. 예를 들어,
- 수도꼭지는 수도관으로부터 물을 받아서 외부로 방출하는 역할을 하는 *part*이다.
- 전시실에 놓여있는 돌은 바닥에서 그 형태를 뽐내는 역할을 하는 *part*이다.
- 나란히 세워져있는 도미노 조각 중 하나도 뒤에서 넘어지는 도미노에 의해 쓰러지면서 앞의 도미노를 미는 역할을 하는 *part*이다.

위와 같이, 어떤 현상이 일어나고 있는 시스템, 혹은 어떤 물체가 특정한 역할을 수행하는 것으로 볼 수 있다면 모두 *part*로 해석 가능하다. *Part*는 다음과 같은 특성을 가진다.
- **(Boundary)** *Part*는 특정한 역할을 직접 수행하는 요소들로 이루어진 내부와, 역할을 수행하는 데에 영향을 주는 변수들을 제공해주는 외부로 경계가 나뉜다.
- **(Context)** *Part*의 내부를 이루는 요소들은 용어와 개념, 정보의 형식을 공유한다. 이를 맥락(context)이라 한다.
- **(Input)** *Part*는 외부의 정보를 받을 수도, 받지 않을 수도 있다.
- **(Output)** *Part*는 외부로 정보로 보낼 수도, 보내지 않을 수도 있다.
- **(Structure)** *Part*의 내부에는 여러 *part*가 있을 수 있다. 내부의 *part*들은 서로 정보를 주고받는 관계로 연결되어 있을 수 있다.

전시실에 놓여있는 돌 예시로 돌아가서 위의 특성들이 어떻게 적용되는지 확인해보자.
- **(Boundary)** 전시실 바닥에 놓여있는 돌은 돌 자체가 하나의 *part*로 이루어진 것으로 볼 수 있다. 아무 것도 이 돌에 관여하지 않는 것으로 해석한다면 이 *part*는 외부로부터 정보를 받지 않고, 돌의 형태를 통해 외부에 존재감을 전달하고 있으므로 돌의 위치와 형태 정보를 외부로 내보내고 있다.
- **(Input, Output)** '전시실 조명 아래' 놓여있는 돌을 *part*로 본다면, 해당 *part*는 전시실의 조명을 input으로 받아서 돌의 색과 형태와 같은 시각적인 정보를 output으로 내보내고 있는 것으로 볼 수 있다. 이때, 전시실의 조명의 색을 바꾸면 돌이 외부로 내보내는 정보도 바뀌는 것을 알 수 있다.
- **(Structure)** 전시실에 좌대를 두고 그 위에 돌을 올려놓으면 좌대와 돌을 합쳐서 하나의 *part*로 보고, 그 모습을 뽐내는 역할을 수행한다고 할 수도 있지만, 전시실에 돌이 전시된 상황을 하나의 *part*로 보고, 해당 *part*가 좌대 *part*와 돌 *part*로 이루어져 있는 것으로도 볼 수 있다. 이때, 좌대는 돌을 받치는 역할과 모습을 뽐내는 역할을, 돌은 모습을 뽐내는 역할을 수행한다.
- **(Context)** 위의 돌 예시들은 현실 세계를 이루는 물리 법칙을 맥락으로 공유한다.
# phase_radomize

## I wonder...
음원 파일을 fourier transform했을 때, magnitude와 phase 정보로 정보가 나뉘게 된다.
이 때 magnitude정보를 수정하면 우리 귀에도 그 차이가 느껴진다.
예를 들어, magnitude를 낮추면 우리 귀에는 작은 소리로 들린다.
하지만 phase정보는 청감적으로 어떤 영향을 미칠까?
한 책에서 phase정보는 청감적으로 큰 의미가 없다고 하지만 근거가 제시되지 않았고 얼마나 의미가 없는지도 명확하지 않았다. 
따라서 본 repository에서는 이에 대해 알아본다.

## How to...
만약 phase정보가 청감적으로 정말 아무 영향이 없다면 phase정보를 random하게 바꾸고 다시 음악파일을 들어보면 같을 것이다. 
해당 repository에서는 이 아이디어를 확인한다.

## data
#### violin
사용한 음악 파일은 origin_violinA4.wav로, 오직 A4를 단조롭게 연주하는 바이올린파일이다. 
코드 내에서 바이올린의 배음구조와 음악 파일의 일부를 통해 timbre을 확인할 수 있다. 
코드 내 그래프를 그리는 부분에서 보조선은 라 음을 나타내는 주파수인 440Hz와 그 배음 880Hz(=440*2), 1320Hz(=440*3)를 표시한 것이다. 

## result
결과를 나타낸 음원을 new_violinA4.wav로 첨부하였지만, 직접 코드를 돌려 들어보아도 좋을 것 같다.
해당 repository에는 없지만 violin data 외에도 trumpet, sexophone, piano등의 악기의 음원을 통해 같은 결과를 확인할 수 있었다.
다만 violin외에는 배음 구조가 뚜렷하지 않았다.(data의 품질과 관련있을 것임)

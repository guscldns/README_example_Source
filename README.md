수평선 (구분선, 수평선을 만들려면 - or * or _을 3개를 입력)

---

***

___


*기울기1*
_기울기2_




# 글자크기1
## 글자크기2
### 글자크기3
#### 글자크기4




# 소스코드블록
```c
for i in range(0,5):
   print(i)
```


# 코드블록2

하나

    둘(탭, 스페이스바로 이부분 회색 될 때까지 들여쓰기)

셋



# 링크걸기
[링크를걸겠습니다.](https://www.naver.com/)

# 순서없는목록

+ 목록1
  + 목록 1-1
    + 목록 1-1-1

* 목록1
  * 목록 1-1
    * 목록 1-1-1

- 목록1
  - 목록 1-1
    - 목록 1-1-1





# BlockQuote

> "알파코1기" - 올림
>> "알파코2기" - 올림
>>> "알파코3기" - 올림





# 숫자목록 출력
1. 하나
2. 둘
3. 셋





# 테이블 만들기

프로젝트목록 | 일자 | 사용기술 | 링크
------------|------|-------|-----|
이미지 생성 | 2021 | GAN | [GAN 프로젝트 링크](https://github.com/shiny0510/FewShot_GAN-Unet3D)
객체탐지 | 2022 | YOLO | [링크를걸겠습니다.](https://github.com/shiny0510/pycaret)




# 강조
**이 부분을 집중해주세요!** 감사합니다
__이 부분을 집중해주세요!__ 감사합니다




# 취소선
~~취소선~~






# 이미지 넣기 

<!-- tip) 이미지 크기 조절 -->
<!-- <img src="이미지 링크" width="너비 " height="높이"> -->
ex)
<img src="https://user-images.githubusercontent.com/31477658/85016059-f962aa80-b1a3-11ea-8c91-dacba2666b78.jpeg" width="700" height="370">

![텍스트](이미지 링크 주소) <br>
![CNN-Figure-02](https://user-images.githubusercontent.com/85111065/173890872-1592710c-4711-42a0-803c-6d37ebcd2b3e.png)


<img src="./APOD.jpg" width="300"> <br>

<img src="./APOD.jpg" width="100" height="100">



# 문자열 개행
방법1. 문장 마지막에 스페이스 두 번 이상 입력  
방법2. html <br> 태그를 사용 
방법2. html <br> 태그를 사용 


다음과 같이 체크박스를 표현 할 수 있습니다. 
* [x] 체크박스
* [ ] 빈 체크박스
* [ ] 빈 체크박스




<!-- 참고: https://shields.io/ -->

<!-- <img src="https://img.shields.io/badge/이름-색상코드?style=flat-square&logo=로고명&logoColor=로고색"/> -->

# Badge (뱃지)
기술 스택이나 사용 툴 등을 간결하게 표현하고 싶을 때
인스타, 블로그 등 다양한 바로가기 링크들을 깔끔하게 나타내고 싶을때
로고와 공식컬러를 포함한 예쁜 아이콘 뱃지

<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white"/>


# 뱃지에 링크걸기

<!-- <a href="링크"><img src="위에있는뱃지코드"/></a>  -->

<a href="https://www.naver.com/"><img src="https://img.shields.io/badge/Velog-3DDC84?style=flat-square&logo=Blogger&logoColor=white"/></a>





# 실습 


# Test 모델을 이용한 Test 도출

* Github Url: https://github.com/shiny0510/FewShot_GAN-Unet3D (꼭! 하이퍼링크)

* requirement: pandas, numpy, torch, seaborn, matplotlib

1. 수행 기관: 알파코, 빅데이터기반 딥러닝 부트캠프 (역할: Method 튜닝, 전처리, 팀장, 트러블 슈팅)

2. 데이터: 환자 데이터 10000개, 정상인 데이터 20만개

3. Method:  전처리: 이미지 Normalize + MixUp(Augmentation) + Denosing               
            모델: F-AnoGAN (Medical Image Analysis, 2019.05)
	         optimizer: Adam 
            loss: L1 loss
	<img src="https://user-images.githubusercontent.com/85111065/173891979-c4353c43-345f-4cec-8a4f-d818e00d97f5.png" width="500">

4. 결과: <br>

* Anomaly detection: <br>
	<img src="https://user-images.githubusercontent.com/85111065/173892034-27a00459-f7af-4ed7-877c-45baa59f2a10.png" width="500" >

* Acc: <br>
	<img src="https://user-images.githubusercontent.com/85111065/173892050-d0406ab4-e31b-43c1-bfa7-cd121428e1aa.png" width="500" >

* 프로젝트 수행 중 문제: 정상인 데이터에서도 미세한 Anomaly가 검출되어서, 환자로 분류하는 threshold를
    높혀줌으로써 정확히 분류될 수 있도록 조치하였으며, 데이터가 부족하여 오픈데이터를 다수 활용.

5. 참고: Schlegl, Thomas, et al. "f-AnoGAN: Fast unsupervised anomaly detection with generative 
    adversarial networks." Medical image analysis 54 (2019): 30-44.

---
## readme 꾸미기
<p align="center">
  <img width="140" src="https://user-images.githubusercontent.com/6661165/91657958-61b4fd00-eb00-11ea-9def-dc7ef5367e34.png" />  
  <h2 align="center">GitHub Profile Trophy</h2>
  <p align="center">🏆 Add dynamically generated GitHub Stat Trophies on your readme</p>
</p>
<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy/issues">
    <img src="https://img.shields.io/github/issues/ryo-ma/github-profile-trophy"/> 
  </a>
  <a href="https://github.com/ryo-ma/github-profile-trophy/network/members">
    <img src="https://img.shields.io/github/forks/ryo-ma/github-profile-trophy"/> 
  </a>  
  <a href="https://github.com/ryo-ma/github-profile-trophy/stargazers">
    <img src="https://img.shields.io/github/stars/ryo-ma/github-profile-trophy"/> 
  </a>
    <a href="https://github.com/ryo-ma/github-profile-trophy/LICENSE">
    <img src="https://img.shields.io/github/license/ryo-ma/github-profile-trophy"/> 
  </a>
</p>
<p align="center">
  </a>
    <a href="https://twitter.com/intent/tweet?text=Add%20dynamically%20generated%20GitHub%20Trophy%20on%20your%20readme%0D%0A&url=https%3A%2F%2Fgithub.com%2Fryo-ma%2Fgithub-profile-trophy">
    <img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fryo-ma%2Fgithub-profile-trophy"/> 
  </a>
</p>
<p align="center">
  You can use this service for free. I'm looking for sponsors to help us keep up with this service❤️
</p>
<p align="center">
  <a href="https://github.com/sponsors/ryo-ma">
    <img src="https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=ff69b4"/> 
  </a>
</p>

# Quick Start

Add the following code to your readme. When pasting the code into your profile's readme, change the `?username=` value to your GitHub's username.

```
[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma)](https://github.com/ryo-ma/github-profile-trophy)
```

<p align="center">
  <img alig src="https://github-profile-trophy.vercel.app/?username=ryo-ma&column=7&rank=SSS,SS,S,AAA,AA,A,B,C" />
</p>

## Use theme

Add optional parameter of the theme.

```
[![trophy](https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)
```
<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92327052-d99b9e00-f091-11ea-9a24-c7ec86982370.png">
</p>

**[More detail](#apply-theme)**

# About Rank

Ranks are `SSS` `SS` `S` `AAA` `AA` `A` `B` `C` `UNKNOWN` `SECRET`.

|  Rank  |  Description  |
| ---- | ---- |
|  SSS, SS, S  | You are at a hard to reach rank. You can brag.  |
|  AAA, AA, A  | You will reach this rank if you do your best. Let's aim here first.  |
|  B, C  | You are currently making good progress. Let's aim a bit higher.  |
| UNKNOWN | You have not taken action yet. Let's act first. |
| SECRET | This rank is very rare. The trophy will not be displayed until certain conditions are met. |

## Secret Rank
The acquisition condition is secret, but you can know the condition by reading this code.

<p align="center">
  <img width="110" src="https://user-images.githubusercontent.com/6661165/91643641-28cd4780-ea70-11ea-94a9-a51885252700.png" />
</p>

There are only a few secret trophies. Therefore, if you come up with interesting conditions, I will consider adding a trophy. I am waiting for contributions.

# About Display details

<p align="center">
  <img width="220" src="https://user-images.githubusercontent.com/6661165/91642962-6333e600-ea6a-11ea-83af-e371e996bfa6.png" />
</p>

1. Title name of aggregation target.
2. Current Rank.
3. Title according to rank.
4. Target aggregation result.
5. Next Rank Bar. The road from the current rank to the next rank.


# Optional Request Parameters

* [title](#filter-by-titles)
* [rank](#filter-by-ranks)
* [column](#specify-the-maximum-row--column-size)
* [row](#specify-the-maximum-row--column-size)
* [theme](#apply-theme)
* [margin-w](#margin-width)
* [margin-h](#margin-height)
* [no-bg](#transparent-background)
* [no-frame](#hide-frames)


## Filter by titles

You can filter the display by specifying the titles of trophy.  

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Followers
```

<p align="center">
  <img width="110" src="https://user-images.githubusercontent.com/6661165/92317141-80ebe700-f038-11ea-8501-4015bfbb2cf4.png">
</p>

If you want to specify multiple titles.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&title=Stars,Followers
```

## Filter by ranks

You can filter the display by specifying the ranks.  
`Available values: SECRET SSS SS S AAA AA A B C`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S
```
<p align="center">
  <img width="110" src="https://user-images.githubusercontent.com/6661165/91642657-1cdd8780-ea68-11ea-994b-4568a55cd22a.png" />
</p>

If you want to specify multiple ranks.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=S,AAA
```

You can also exclude ranks.

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&rank=-C,-B
```


## Specify the maximum row & column size

You can specify the maximum row and column size.  
Trophy will be hidden if it exceeds the range of both row and column.

`Available value: number type`  
`Default: column=6 row=3`

Restrict only row
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2
```

Restrict only column
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=2
```

Restrict row & column
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&row=2&column=3
```

<p align="center">
  <img width="330" src="https://user-images.githubusercontent.com/6661165/91659474-c07f7400-eb0a-11ea-84f2-eb6b42547829.png">
</p>

Adaptive column
```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=-1
```

You can set `columns` to `-1` to adapt the width to the number of trophies, the parameter `row` will be ignored.

## Apply theme

Available themes.

|  theme  |
| ---- |
| [flat](#flat) |
| [onedark](#onedark) |
| [gruvbox](#gruvbox) |
| [dracula](#dracula) |
| [monokai](#monokai) |
| [chalk](#chalk) |
| [nord](#nord) |
| [alduin](#alduin) |
| [darkhub](#darkhub) |
| [juicyfresh](#juicyfresh) |
| [buddhism](#buddhism) |
| [oldie](#oldie) |
| [radical](#radical) |
| [onestar](#onestar) |
| [discord](#discord) |
| [algolia](#algolia) |
| [gitdimmed](#gitdimmed) |
| [tokyonight](#tokyonight) |
| [matrix](#matrix) |
| [apprentice](#apprentice) |
| [dark_dimmed](#dark_dimmed) |
| [dark_lover](#dark_lover) |


### flat

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=flat
```
<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92325601-039b9300-f087-11ea-983a-fce8133549ee.png">
</p>

### onedark

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onedark
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92327052-d99b9e00-f091-11ea-9a24-c7ec86982370.png">
</p>

### gruvbox

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=gruvbox
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92315152-e9c56600-f01c-11ea-9536-1bfbb158cfcb.png">
</p>

### dracula

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dracula
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/92490273-c91f2b00-f22b-11ea-9481-b5daae4d7bc3.png">
</p>

### monokai

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=monokai
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/93725426-2c289e80-fbea-11ea-96a4-f6490ccf2126.png">
</p>

### chalk

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=chalk
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/94294003-1de7d300-ff9a-11ea-91d1-60417a4d919b.png">
</p>

### nord

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=nord
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/94346857-7ab2be80-006a-11eb-9082-36d377ae2531.png">
</p>


### alduin

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=alduin
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/99085932-2a88bf00-260c-11eb-9b26-d2f125773831.png">
</p>

### darkhub

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=darkhub
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/102801126-249ab080-43f8-11eb-91c8-f56f94c35777.png">
</p>

### juicyfresh

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=juicyfresh
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/104810094-edbc8c80-5835-11eb-8c20-a76192a00728.png">
</p>

### buddhism

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=buddhism
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/113709167-2412f500-971d-11eb-9ee5-0ab292cf8b4c.png">
</p>

### oldie

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=oldie
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/113709581-a0a5d380-971d-11eb-8583-770dc4091ebf.png">
</p>

### radical

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=radical
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/116633521-adbc8800-a994-11eb-97c4-e45a32721491.png">
</p>

### onestar

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=onestar
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/122048400-2af46d00-ce1c-11eb-94e0-c2c6ddaf6819.png">
</p>

### discord

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=discord
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/122048628-7dce2480-ce1c-11eb-9792-1e600b384c4d.png">
</p>

### algolia

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=algolia
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/131685203-92a31101-2d93-4d18-b24a-d81a8bb012c5.png">
</p>

### gitdimmed

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=gitdimmed
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/131685406-799a864f-2691-4840-bb71-1db9c087a507.png">
</p>

### tokyonight

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=tokyonight
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/6661165/135482087-27764d6f-53b4-4c2a-8473-32431d12660c.png">  
</p>

### matrix

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=matrix
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/141647414-15cfe279-af12-4746-a886-f494c25c096d.png">  
</p>

### apprentice

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=apprentice
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/144701036-285cdd4b-d687-4ddc-95c2-7ccae9e25a1f.png">  
</p>

### dark_dimmed

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dark_dimmed
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/147340893-655b9fa5-138f-4f29-91ec-2a17c93822d1.png">  
</p>

### dark_lover

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&theme=dark_lover
```

<p align="center">
  <img width="660" src="https://user-images.githubusercontent.com/31789752/152659041-de5b23cb-1be8-4e6b-b07b-726127ab8c3a.png">  
</p>

## Margin Width

You can put a margin in the width between trophies.  
`Available value: number type`  
`Default: margin-w=0`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&margin-w=15
```

<p align="center">
  <img width="735" src="https://user-images.githubusercontent.com/6661165/93668661-e0ca9f00-fac8-11ea-9bec-325454f49fb4.png">
</p>

## Margin Height

You can put a margin in the height between trophies.  
`Available value: number type`  
`Default: margin-h=0`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&margin-h=15
```

## Example layout

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&column=3&margin-w=15&margin-h=15
```

<p align="center">
  <img width="360" src="https://user-images.githubusercontent.com/6661165/93668677-ff309a80-fac8-11ea-8ae3-3e3e8adbef39.png">
</p>

## Transparent background

You can turn the background transparent.  
`Available value: boolean type (true or false)`  
`Default: no-bg=false`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&no-bg=true
```

<p align="center">
  <img width=660 src="https://user-images.githubusercontent.com/6661165/104810864-ed72c000-583a-11eb-863b-04acffb705ea.png">
</p>



## Hide frames

You can hide the frames around the trophies.  
`Available value: boolean type (true or false)`  
`Default: no-frame=false`

```
https://github-profile-trophy.vercel.app/?username=ryo-ma&no-frame=true
```

<p align="center">
  <img width=660 src="https://user-images.githubusercontent.com/6661165/104810887-1d21c800-583b-11eb-8f0d-785c1640dc5d.png">
</p>


# Contribution Guide
Check [CONTRIBUTING.md](./CONTRIBUTING.md) for more details.

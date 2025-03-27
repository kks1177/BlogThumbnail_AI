# BlogThumbnail_AI

<!-- 참고 깃허브 : https://github.com/seokahee/RE-V-UP-VER3/blob/chore/search-player/README.md#installation -->
<!-- 
목차 링크 연결해줄 때, 정확한 앵커( ) 이름이 헷갈릴 경우,
깃허브 페이지에서 헤더 옆에 표시되는 🔗링크 아이콘을 클릭해보면 정확한 앵커 주소 확인 가능
-->

<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## Contents-->
<details open>
<summary><h2> Contents </h2></summary>

🚀 [Project Overview](#--Project-Overview--) 🚀
<!-- - 프로젝트 명 & 소개 & 목표 & 개발 기간 -->

<!--🧑‍🤝‍🧑 [Project Team "VUP"](#--Project-Team-VUP--) 🧑‍🤝‍🧑-->
<!-- - Team Members -->

📜 [Project Rules](#--Project-Rules--) 📜
<!-- 
- 개발환경 (버전참고)
- Code Convention & 네이밍 원칙 & 네이밍 방법 & 함수 원칙 & 주석 & 소스코드 구조 & 라이브러리 설치 & 타입스크립트
- 프로젝트 운영 방식 및 Rules 예시
-->

<!--🚩 [Getting Started Guide](#--Getting-Started-Guide--) 🚩-->
<!--
- Installation
- Environment variable
-->

🎨 [Wireframe](#--Wireframe--) 🎨

✨ [Project UI & Feature Overview](#--Project-UI--Feature-Overview--) ✨

🔧 [Troubleshooting](#--Troubleshooting--) 🔧

📂 [File Structure](#--File-Structure--) 📂
<br>
<br>
</details>



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 🚀 Project Overview 🚀-->
<details open>
<summary><h2> 🚀 Project Overview 🚀 </h2></summary>
<hr noshade>

- __프로젝트 명__ : BlogThumbnail_AI

- __프로젝트 소개__ : Tistory 게시글 요약을 기반으로 대표 사진 자동 생성 프로젝트 기획

- __프로젝트 목표__ : 사용자가 티스토리에 작성한 게시글의 내용을 요약하여 한눈에 파악할 수 있는 대표 사진(썸네일)을 자동 생성하는 AI 시스템 구축. 깔끔하고 가독성 높은 디자인을 유지하면서도, 게시글의 핵심 내용을 효과적으로 전달하는 썸네일 제작

- __개발 기간__ : 2025.03.27 ~ 2025.04.01 (약 6일간)

- __프로젝트 블로그__ : [V-UP (Volume Up, 불륨업)](https://www.notion.so/VakVakVerse-16f2aa0964ad45f4b09dee8683b39c23)

- __시연 영상__ : https://www.youtube.com/watch?v=zsFyAOfzZy0
<br>
</details>



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 🧑‍🤝‍🧑 Project Team "VUP" 🧑‍🤝‍🧑-->
<!--
<details>
<summary><h2> 🧑‍🤝‍🧑 Project Team "VUP" 🧑‍🤝‍🧑 </h2></summary>
<hr noshade>

&nbsp;&nbsp;&nbsp;&nbsp;퍼스널 뮤직 검사를 통해 나의 취향에 맞는 음악을 추천받고 음악을 들으며 음악 커뮤니티를 즐길 수 있는 서비스 
<br>
<br>

&nbsp;&nbsp;__[ 팀원 소개 ]__

|                   성예지                   |                 강지수                 |                     남해리                     |                   서가희                   |       전주용       |
| :----------------------------------------: | :------------------------------------: | :--------------------------------------------: | :----------------------------------------: | :----------------: |
|                    ISTP                    |                  ISFP                  |                   ENFJ/ISTJ                    |                    ESTP                    |        ENFJ        |
|                 <p><img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/6282726f-81ff-4c6f-a0a5-7de4d31cc9a6" witdh="300px" height="150px" /></p>         |               <p><img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/6ccd4aec-97af-4c33-bd11-a9e64472313e" witdh="300px" height="150px" /></p>                |                   <p><img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/6f9b5eb2-bbb1-41ff-ab00-e4bb21abd7c1" witdh="300px" height="150px" /></p>                 |              <p><img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/9b00a3e6-1f67-43a1-8502-72730fe3c012" witdh="300px" height="150px" /></p>                  |      <p><img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/4d524727-f55a-4b67-82cc-ad66cb99aac0" witdh="300px" height="150px" /></p>      |
| [@dpwl032](https://github.com/dpwl032) | [@jigico](https://github.com/jigico) | [@r03181231](https://github.com/r03181231) | [@seokahee](https://github.com/kahee430) |      [@iinon00](https://github.com/iinon00)      |
|                    팀장                    |                  팀원                  |                      팀원                      |                    팀원                    |        팀원        |
|                          |                    |                                    |                         |  |

<br>
</details>
-->



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 📜 Project Rules 📜-->
<details>
<summary><h2> 📜 Project Rules 📜 </h2></summary>
<hr noshade>

### 개발 환경 (버전참고)
- __Environment__ : Visual Studio Code, git(2.37.3), github
- __Language__ :  Javascript
- __Framwork__ : Next.js(14.1.4)
- __Library__
  - next-auth(^4.24.7)
  - zustand(^4.5.2) , tanstack/react-query(^5.28.9)
  - eslint(^9.0.0) , prettier(^3.2.5)
  - dompurify(^3.1.0) , lodash(^4.17.21)
  - react-h5-audio-player(^3.9.1)
  - react-quill(^2.0.0)
  - chart.js(^4.4.2)
  - tailwindcss(^3.3.0) , tailwind-scrollbar-hide(^1.1.7) , tailwindcss-animate(^1.0.7) , prettier-plugin-tailwindcss(^0.5.13)
  - sweetalert2(^11.10.8)
- __DB__:  supabase(v2.41.1)
- __Communication__ : figma, slack, notion, zep, canva

### Code Convention
1. interface 보단 type 쓰기
2. types.d.ts 파일 이용하기
3. import 시 import **type** "이름" 으로 type 붙여주고 간격 띄우기

### 네이밍 원칙
- 모호하지 않고 기능을 설명하는 이름 사용
- 검색 가능한 이름 사용
- 동사 - 목적어 순으로 작명
- 넘버링 금지
- 인코딩을 회피하는 네이밍 필수 (접두사, 타입 정보 명시 금지)
- 변수 혹은 함수 이름에 축약어 사용 금지 (btn → button)
- 폴더명은 소문자

### 네이밍 방법
- camelCase  → 변수, 함수 이름
- PascalCase → class / component
- snake_case → 안 씀
- SNAKE_CASE → 상수 표현
- kebab-case → route or path name (e.g. /main-page) / class-name
- 변수나 함수는 위와 같이 귀찮더라도 최대한 풀네임으로 작성!! ex) onChangeHandler

### 함수 원칙
- 새로운 리액트 함수 선언은 rafce 스니펫 사용
- 화살표 함수 사용
- 하나의 함수는 하나의 기능만 하도록 설계
- 인수 최소화
- 사이드 이펙트 발생 방지
- 플래그 인수 금지 (독립적인 메소드로 분리 가능하게 설계)

### 주석
- 의도를 명확히 전달하고자 할 때 주석 사용
- 결과에 대한 경고를 전달하고자 할 때 주석 사용

### 소스코드 구조
- 변수와 함수는 사용하는 곳에 가까이 위치하도록 설계
- 위에서 아래로 읽어내려갈 수 있도록 코드 작성
- 공백은 상하 내용의 관련성을 표기하기 위해 사용

### 라이브러리 설치
- yarn 사용 → npm 사용 금지

### 타입스크립트
- interface 보단 type 쓰기
- types.d.ts 파일 이용하기
- import 시 import **type** “이름” 으로 type 붙여주고 간격 띄우기
- 프리티어 설정 :

```json
{
  "arrowParens": "always",
  "bracketSameLine": false,
  "bracketSpacing": true,
  "embeddedLanguageFormatting": "auto",
  "htmlWhitespaceSensitivity": "css",
  "insertPragma": false,
  "jsxSingleQuote": true,
  "printWidth": 80,
  "proseWrap": "always",
  "quoteProps": "as-needed",
  "requirePragma": false,
  "semi": false,
  "singleAttributePerLine": false,
  "singleQuote": true,
  "tabWidth": 2,
  "trailingComma": "all",
  "useTabs": false,
  "vueIndentScriptAndStyle": false,
  "plugins": ["prettier-plugin-tailwindcss"]
}

```

<br>

### 프로젝트 운영 방식 및 Rules 예시
  ####     __[ 깃허브 규칙 ]__
  - 브랜치 이름 : 기능 이름

  ####     __[ Commit Convention ]__

| 타입     | 설명                                                         |
| -------- | ------------------------------------------------------------ |
| Feat     | 기능 구현                                                    |
| Fix      | 버그 수정                                                    |
| Refactor | 코드 리팩토링                                                |
| chore    | 기능에 영향을 주지 않는 코드 수정                            |
| Style    | 스타일링 관련 코드 추가/수정                                 |
| Minor    | 마이너 한 변경사항 (오타 수정, 탭 사이즈 변경, 변수명 변경 등) |
| test     | 테스트 코드                                                  |
| Dir      | 폴더 구조 수정                                               |

  ####     __[ 커밋 메시지 예시 ]__
&nbsp;&nbsp; __Feat(#12) : 신규 input 태그에 대한 이벤트 함수 추가__

&nbsp;&nbsp; __Note__ : 브랜치 빼고 다 대문자!
<br>
<br>
</details>



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 🚩 Getting Started Guide 🚩-->
<!--
<details>
<summary><h2> 🚩 Getting Started Guide 🚩 </h2></summary>
<hr noshade>

### Installation
```bash
$ git clone https://github.com/RE-V-UP/v-up-ver2.git
$ cd v-up-ver2
$ yarn install or npm install
$ yarn run start or npm run start
```

### Environment variable
- 파일 이름 : .env.local
- 변수 이름1 : NEXT_PUBLIC_SUPABASE_URL
- 변수 이름2 : NEXT_PUBLIC_SUPABASE_ANON_KEY
- 변수 이름3 : NEXTAUTH_SECRET
- 변수 이름4 : NEXTAUTH_URL
- 변수 이름5 : KAKAO_CLIENT_ID
- 변수 이름6 : KAKAO_CLIENT_SECRET
  
- DB는 supabase를 사용하여 관련된 변수 이름을 부여
- Supabase 클라이언트를 초기화하기 위한 도우미 파일 : src/shared/supabase/supabase.ts
<br>
</details>
-->



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 🎨 Wireframe 🎨-->
<details>
<summary><h2> 🎨 Wireframe 🎨 </h2></summary>
<hr noshade>

<br>
</details>



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## ✨ Project UI & Feature Overview ✨-->
<details open>
<summary><h2> ✨ Project UI & Feature Overview ✨ </h2></summary>
<hr noshade>

**[ 입력데이터 ]**

<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/6a6fdbf0-b226-47af-9938-f8fc810965c1" width="400px" height="300px" >
<br>

- 사용자가 작성한 티스토리 게시글의 제목 및 요약
- 핵심 키워드 (필요 시)
- 글의 주제(IT, 개발, 리뷰, 튜토리얼 등)
<br>


**[ AI 자동 생성 기능 ]**

<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/07a008d4-93d8-4d03-80f3-160ebae5b3b4" width="400px" height="300px" >
<br>

- 게시글 요약을 분석하여 적절한 핵심 키워드 추출
- 키워드 기반으로 배경 색상, 글자 색상, 아이콘, 배치 등을 자동 추천
- 대표 사진을 여러 개 생성하여 사용자에게 선택할 수 있도록 제공
<br>


**[ 디자인 가이드라인 ]**

- 깔끔한 디자인 유지
<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/eea993c7-1c66-42ab-a624-76a85a673472" width="400px" height="300px" >
<br>

- 필요 없는 요소 배제
- 한눈에 핵심 내용을 파악할 수 있도록 정리
<br>

- 색상 조합 추천
<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/675a7410-0b71-4eeb-8a7f-d29cdaaeb738" width="400px" height="300px" >
<br>

- 주제별로 적절한 배경 색상과 글씨 색상을 매칭 (예: 보안 이슈 → 파란색, 버그 분석 → 빨간색 등)
<br>

- 아이콘 사용
<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/4adbdc0a-1fa6-4396-891f-c010b3a479b6" width="400px" height="300px" >
<br>

- IT/개발 관련 주제에 맞는 직관적인 아이콘 추가
- 예: 데이터베이스 → DB 아이콘, 보안 → 자물쇠 아이콘, 코드 관련 → 코드 블록 아이콘
<br>


**[ 텍스트 분석 및 키워드 추출 ]**

<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/1328f216-b1a8-451a-8843-59487ecfaab3" width="400px" height="300px" >
<br>

- NLP(자연어 처리)를 이용해 게시글에서 핵심 키워드 자동 추출
- 사용자가 직접 키워드를 입력할 수도 있도록 옵션 제공
<br>


**[ 디자인 템플릿 자동 생성 ]**

<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/4c071d52-f5c1-4fe2-a884-da5bab27dbb6" width="400px" height="300px" >
<br>

- 미리 정의된 템플릿을 활용하여 대표 이미지 생성
- 배경 색상, 글씨 색상, 폰트 스타일, 아이콘 등을 키워드 기반으로 동적으로 조합
<br>


**[ 이미지 생성 및 편집 ]**

<img src="https://github.com/RE-V-UP/v-up-ver2/assets/134026105/75b40b6f-1482-4ebe-a384-aa71988e56ef" width="400px" height="300px" >
<br>

- AI를 활용해 여러 개의 디자인을 자동 생성
- 사용자가 선택 후 미세 조정 가능하도록 설정
<br>
</details>



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 🔧 Troubleshooting 🔧-->
<details>
<summary><h2> 🔧 Troubleshooting 🔧 </h2></summary>
<hr noshade>
  
### onClick 사용으로 인한 실시간 반영이 되지 않는 문제
__`이슈`__
- 체
  
__`해결`__
- 사
<br>


### 역방향 무한스크롤 감지
__`이슈`__
- 역

__`해결`__
- 역
- 유
<br>

### 에디터가 빌드 될 때, document is not defined 오류가 발생하는 문제
__`이슈`__
- 퀼

__`해결`__
- N
<br>

### 플레이 리스트 index 위치 변경 후 유지되지않는 문제
__`이슈`__
- 회

__`해결`__ 
1. 뮤
2. u
3. u
4. z
5. 음
<br>

 - playStore
   
        ```jsx
        type customListMusicStore = {
          customListData: {
            customPlayList: CurrentPlayListType[]
          }
        
          customListMusic: (customPlayList: CurrentPlayListType[]) => void
        }
        
        const customListMusicState = {
          customListData: {
            customPlayList: [],
          },
        }
        
        export const useCustomListMusicStore = create(
          persist<customListMusicStore>(
            (set, _) => ({
              ...customListMusicState,
              customListMusic: (customPlayList: CurrentPlayListType[]) => {
                set({ customListData: { customPlayList } })
              },
            }),
            {
              name: 'customListMusicStore',
            },
          ),
        )
        
        ```
        
- CurrentMusicList.tsx
        
        ```jsx
        const customListMusic = useCustomListMusicStore(
            (state) => state.customListMusic,
          )
          const { customListData } = useCustomListMusicStore()
          const { customPlayList } = customListData
          
           useEffect(() => {
            // 스테이트가 비어있는경우 서버플리 저장
            if (customPlayList.length === 0) {
              // setCustomList(currentPlayList)
              customListMusic(currentPlayList)
              return
            }
        
            // 디비에서 받아오는 데이터와, 스테이트에 저장한 데이터가 일치하지않은것을 반환
            const addValue = currentPlayList.filter((currentItem) => {
              return customPlayList.every((customItem) => {
                return currentItem.musicId !== customItem.musicId
              })
            })
        
            const removeValues = customPlayList.filter((currentItem) => {
              return currentPlayList.every((customItem) => {
                return currentItem.musicId !== customItem.musicId
              })
            })
        
            // console.log('추가', addValue)
            // console.log('삭제', removeValues)
        
            // 디비플리와 스테이트플리가 동일하지않은경우
            if (addValue.length > 0) {
              // 서버플리가 스테이트 플리보다 많으면, 추가된경우
              const addList = [...customPlayList, ...addValue]
              // setCustomList(addList)
              customListMusic(addList)
            }
            if (removeValues.length > 0) {
              console.log('삭제되면 스테이트 값도 지워줘야겠지 또도를 생각해')
              const currentItems = removeValues.map((item) => {
                return item.musicId
              })
        
              // 커스텀 플레이 리스트에서 삭제된 아이템 제거
              const removeList = customPlayList.filter((item) => {
                return !currentItems.includes(item.musicId)
              })
              // setCustomList(removeList)
              customListMusic(removeList)
            }
          }, [currentPlayList, customPlayList])
        ```

<br>
</details>



<!-- --------------------------------------------------------------------------------------------------------------- -->
<!--## 📂 File Structure 📂-->
<details>
<summary><h2> 📂 File Structure 📂 </h2></summary>
<hr noshade>

```📦src
 ┣ 📂app
 ┃ ┣ 📂(auth)
 ┃ ┃ ┣ 📂comment
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂communitycreate
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂mypage
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂new-password
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂personal-music
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂signout
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┗ 📂userpage
 ┃ ┃ ┃ ┗ 📂[id]
 ┃ ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┣ 📂(nonAuth)
 ┃ ┃ ┣ 📂community
 ┃ ┃ ┃ ┣ 📂[id]
 ┃ ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂join
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┣ 📂login
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┃ ┗ 📂search
 ┃ ┃ ┃ ┗ 📜page.tsx
 ┃ ┣ 📂api
 ┃ ┃ ┗ 📂auth
 ┃ ┃ ┃ ┗ 📂[...nextauth]
 ┃ ┃ ┃ ┃ ┗ 📜route.ts
 ┃ ┣ 📜favicon.ico
 ┃ ┣ 📜globals.css
 ┃ ┣ 📜layout.tsx
 ┃ ┣ 📜NextAuthProvider.tsx
 ┃ ┣ 📜not-found.tsx
 ┃ ┣ 📜page.tsx
 ┃ ┣ 📜provider.tsx
 ┃ ┗ 📜UserReSessionProvider.tsx
 ┣ 📂components
 ┃ ┣ 📂comment
 ┃ ┃ ┣ 📜CommentForm.tsx
 ┃ ┃ ┗ 📜CommentsList.tsx
 ┃ ┣ 📂common
 ┃ ┃ ┗ 📜Container.tsx
 ┃ ┣ 📂communityDetail
 ┃ ┃ ┣ 📜CommunityAddMusic.tsx
 ┃ ┃ ┣ 📜CommunityContents.tsx
 ┃ ┃ ┣ 📜CommunityCreate.tsx
 ┃ ┃ ┣ 📜communityCss.ts
 ┃ ┃ ┣ 📜CommunityNoSsrQuillEditor.tsx
 ┃ ┃ ┣ 📜CommunityQuillEditor.tsx
 ┃ ┃ ┣ 📜ContentsHeader.tsx
 ┃ ┃ ┣ 📜detailCss.ts
 ┃ ┃ ┣ 📜DetailEditDelete.tsx
 ┃ ┃ ┣ 📜DetailuserImage.tsx
 ┃ ┃ ┣ 📜LikeButton.tsx
 ┃ ┃ ┣ 📜QuillEditor.tsx
 ┃ ┃ ┗ 📜value.ts
 ┃ ┣ 📂communityList
 ┃ ┃ ┣ 📜CommunityListData.tsx
 ┃ ┃ ┗ 📜CommunityListSort.tsx
 ┃ ┣ 📂findpassword
 ┃ ┃ ┗ 📜FindPassword.tsx
 ┃ ┣ 📂join
 ┃ ┃ ┣ 📜AllowUserInfo.tsx
 ┃ ┃ ┣ 📜Join.tsx
 ┃ ┃ ┗ 📜value.ts
 ┃ ┣ 📂login
 ┃ ┃ ┣ 📜buttonCss.ts
 ┃ ┃ ┣ 📜Login.tsx
 ┃ ┃ ┗ 📜loginCss.ts
 ┃ ┣ 📂logout
 ┃ ┃ ┗ 📜LogOutButton.tsx
 ┃ ┣ 📂main
 ┃ ┃ ┣ 📜GenreMusicItem.tsx
 ┃ ┃ ┣ 📜GenreMusicList.tsx
 ┃ ┃ ┣ 📜MainBanner.tsx
 ┃ ┃ ┣ 📜RandomMusicList.tsx
 ┃ ┃ ┣ 📜RecommendationMusicList.tsx
 ┃ ┃ ┣ 📜SectionTitle.tsx
 ┃ ┃ ┣ 📜SlideButton.tsx
 ┃ ┃ ┗ 📜TopLikedBoard.tsx
 ┃ ┣ 📂mypage
 ┃ ┃ ┣ 📜BoardItem.tsx
 ┃ ┃ ┣ 📜BoardNoData.tsx
 ┃ ┃ ┣ 📜CheckboxItem.tsx
 ┃ ┃ ┣ 📜FollowerList.tsx
 ┃ ┃ ┣ 📜FollowingList.tsx
 ┃ ┃ ┣ 📜LikeBoardList.tsx
 ┃ ┃ ┣ 📜Modal.tsx
 ┃ ┃ ┣ 📜MyInfo.tsx
 ┃ ┃ ┣ 📜MyPlaylist.tsx
 ┃ ┃ ┣ 📜PreviousButton.tsx
 ┃ ┃ ┣ 📜TabMenu.tsx
 ┃ ┃ ┗ 📜WriteList.tsx
 ┃ ┣ 📂personal
 ┃ ┃ ┣ 📜GenderPage.tsx
 ┃ ┃ ┣ 📜MBTIPage.tsx
 ┃ ┃ ┣ 📜PersonalModal.tsx
 ┃ ┃ ┣ 📜PersonalModalDetail.tsx
 ┃ ┃ ┣ 📜PersonalRecommend.tsx
 ┃ ┃ ┣ 📜PersonalSubTest.tsx
 ┃ ┃ ┣ 📜PersonalTestResult.tsx
 ┃ ┃ ┣ 📜ResultChart.tsx
 ┃ ┃ ┗ 📜ResultPage.tsx
 ┃ ┣ 📂player
 ┃ ┃ ┣ 📂playerIcons
 ┃ ┃ ┃ ┣ 📜FaForward.tsx
 ┃ ┃ ┃ ┣ 📜MyLoopIcon.tsx
 ┃ ┃ ┃ ┣ 📜MyLoopOffIcon.tsx
 ┃ ┃ ┃ ┣ 📜MyNextIcon.tsx
 ┃ ┃ ┃ ┣ 📜MyPauseIcon.tsx
 ┃ ┃ ┃ ┣ 📜MyPlayIcon.tsx
 ┃ ┃ ┃ ┣ 📜MyPreviousIcon.tsx
 ┃ ┃ ┃ ┗ 📜ProgressContainer.tsx
 ┃ ┃ ┣ 📜AudioCss.css
 ┃ ┃ ┣ 📜CurrentMusicList.tsx
 ┃ ┃ ┣ 📜MusicPlayer.tsx
 ┃ ┃ ┗ 📜Player.tsx
 ┃ ┣ 📂search
 ┃ ┃ ┣ 📜GenreMusicRecommendations.tsx
 ┃ ┃ ┣ 📜GenreRandomMusic.tsx
 ┃ ┃ ┣ 📜ModalMusicData.tsx
 ┃ ┃ ┣ 📜MusicSearch.tsx
 ┃ ┃ ┣ 📜MusicSearchModal.tsx
 ┃ ┃ ┣ 📜NoSearchResult.tsx
 ┃ ┃ ┣ 📜NoSearchResultItem.tsx
 ┃ ┃ ┣ 📜SearchedCommunityData.tsx
 ┃ ┃ ┣ 📜SearchedMusicData.tsx
 ┃ ┃ ┗ 📜SearchForm.tsx
 ┃ ┣ 📂service
 ┃ ┃ ┣ 📜Service.tsx
 ┃ ┃ ┗ 📜ServiceModal.tsx
 ┃ ┣ 📂socialLogin
 ┃ ┃ ┗ 📜page.tsx
 ┃ ┣ 📂userpage
 ┃ ┃ ┣ 📜LikeBoardList.tsx
 ┃ ┃ ┣ 📜LockContents.tsx
 ┃ ┃ ┣ 📜UserInfo.tsx
 ┃ ┃ ┣ 📜UserPlaylist.tsx
 ┃ ┃ ┗ 📜WriteList.tsx
 ┃ ┣ 📜Footer.tsx
 ┃ ┗ 📜Header.tsx
 ┣ 📂hooks
 ┃ ┗ 📜useInput.ts
 ┣ 📂query
 ┃ ┣ 📂community
 ┃ ┃ ┗ 📜communityQueryKey.ts
 ┃ ┣ 📂communityDetail
 ┃ ┃ ┣ 📜mutation.ts
 ┃ ┃ ┗ 📜queryKey.ts
 ┃ ┣ 📂genreMusic
 ┃ ┃ ┗ 📜queryKeys.ts
 ┃ ┣ 📂musicPlayer
 ┃ ┃ ┗ 📜musicPlayerQueryKeys.ts
 ┃ ┣ 📂personal
 ┃ ┃ ┣ 📜keys.constant.ts
 ┃ ┃ ┣ 📜useMutationPersonal.ts
 ┃ ┃ ┗ 📜useQueryPersonal.ts
 ┃ ┣ 📂search
 ┃ ┃ ┗ 📜searchQueryKeys.ts
 ┃ ┗ 📂user
 ┃ ┃ ┗ 📜userQueryKeys.ts
 ┣ 📂shared
 ┃ ┣ 📂comment
 ┃ ┃ ┗ 📜commentApi.ts
 ┃ ┣ 📂comments
 ┃ ┃ ┗ 📜commentsApi.ts
 ┃ ┣ 📂community
 ┃ ┃ ┗ 📜api.ts
 ┃ ┣ 📂communitydetail
 ┃ ┃ ┗ 📜detailApi.ts
 ┃ ┣ 📂join
 ┃ ┃ ┗ 📜joinApi.ts
 ┃ ┣ 📂login
 ┃ ┃ ┗ 📜loginApi.ts
 ┃ ┣ 📂main
 ┃ ┃ ┗ 📜api.ts
 ┃ ┣ 📂musicPlayer
 ┃ ┃ ┗ 📜api.ts
 ┃ ┣ 📂mypage
 ┃ ┃ ┗ 📜api.ts
 ┃ ┣ 📂personal
 ┃ ┃ ┗ 📜personalApi.ts
 ┃ ┣ 📂search
 ┃ ┃ ┗ 📜api.ts
 ┃ ┣ 📂store
 ┃ ┃ ┣ 📜communityDetailStore.ts
 ┃ ┃ ┣ 📜paginationStore.ts
 ┃ ┃ ┣ 📜personalStore.ts
 ┃ ┃ ┣ 📜playerStore.ts
 ┃ ┃ ┗ 📜searchStore.ts
 ┃ ┣ 📂supabase
 ┃ ┃ ┗ 📜supabase.ts
 ┃ ┣ 📂userpage
 ┃ ┃ ┗ 📜api.ts
 ┃ ┗ 📜store.ts
 ┣ 📂types
 ┃ ┣ 📂comment
 ┃ ┃ ┗ 📜type.ts
 ┃ ┣ 📂comments
 ┃ ┃ ┗ 📜type.ts
 ┃ ┣ 📂community
 ┃ ┃ ┗ 📜type.ts
 ┃ ┣ 📂communityDetail
 ┃ ┃ ┗ 📜detailTypes.ts
 ┃ ┣ 📂loginJoin
 ┃ ┃ ┗ 📜types.ts
 ┃ ┣ 📂main
 ┃ ┃ ┗ 📜types.ts
 ┃ ┣ 📂musicPlayer
 ┃ ┃ ┗ 📜types.ts
 ┃ ┣ 📂mypage
 ┃ ┃ ┗ 📜types.ts
 ┃ ┣ 📂personal
 ┃ ┃ ┗ 📜type.ts
 ┃ ┗ 📜supabase.ts
 ┗ 📂util
 ┃ ┣ 📂main
 ┃ ┃ ┗ 📜util.ts
 ┃ ┣ 📂personal
 ┃ ┃ ┗ 📜util.ts
 ┃ ┣ 📜ButtonPrimary.tsx
 ┃ ┣ 📜ButtonSecondary.tsx
 ┃ ┣ 📜font.ts
 ┃ ┣ 📜InfiniteScrollContainer.tsx
 ┃ ┣ 📜Modal.tsx
 ┃ ┣ 📜Pagination .tsx
 ┃ ┣ 📜useIntersectionObserver.ts
 ┃ ┗ 📜util.ts
```

<br>
</details>


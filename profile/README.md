# 영수증

## 프로젝트 소개
영수증 프로젝트는 메타버스 아카데미 내 융합프로젝트로서 자영업자의 매출/비용 정리를 돕자는 취지로 시작한 프로젝트입니다. 영수증 이미지 입력을 통해서 데이터를 생성/처리하여 장부정리를 간편하게 만드는 것을 주 목표로 하고 있습니다.
## 팀원 소개
|백승진|이유열|김지수|김지현|오태훈|윤상원|한정수|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|서버|서버|서버|AI|AI|기획|기획|
|[ej20001000](https://github.com/ej20001000)|[youyeul1301](https://github.com/youyeul301)|[jisoo9603](https://github.com/jisoo9603)|[jeehyunkim0510](https://github.com/jeehyunkim0510)|[OHTaEH](https://github.com/OHTaEH)|[snagwon](https://github.com/snagwon)|[JS-HAN214](https://github.com/JS-HAN214)|
|<img src="https://avatars.githubusercontent.com/u/53468197?v=4"/>|<img src="https://avatars.githubusercontent.com/u/84696773?v=4"/>|<img src="https://avatars.githubusercontent.com/u/122511847?v=4"/>|<img src="https://avatars.githubusercontent.com/u/56626776?v=4"/>|<img src="https://avatars.githubusercontent.com/u/105119559?v=4"/>|<img src="https://avatars.githubusercontent.com/u/141210119?v=4"/>|<img src="https://avatars.githubusercontent.com/u/139134983?v=4"/>|


## 주요 기술

### Server
|<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F1Kv0P%2FbtrpJQek23V%2FJLIruScfBPvLA7Kw0jCdkk%2Fimg.png" width="80px" height="40px"/>|<img src="https://velog.velcdn.com/images/sa1341/post/561a7a4b-0952-45bf-99ec-242ae58b40ab/jpa.png" width="50px" height="40px" />|<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F99F571395BBB259226" width="90px" height="30px" />|
|:---:|:---:|:---:|

### Client
|<img src="https://tech.osci.kr/wp-content/uploads/2022/05/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA-2022-05-03-%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE-3.57.02.png" width="70px" height="30px" />|
|:---:|

### DataBase
|<img src="https://d1.awsstatic.com/asset-repository/products/amazon-rds/1024px-MySQL.ff87215b43fd7292af172e2a5d9b844217262571.png" width="60px" height="30px"/>|
|:---:|

### AI
|<img src="https://www.python.org/static/img/python-logo@2x.png" width="50%" height="50%"/>|<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fopwfr%2FbtqRAj86uNM%2FMFoeKGk6AK6L8MRwbAfouk%2Fimg.png" width="50%" height="50%"/>|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/Tesseract_OCR_logo_%28Google%29.png/375px-Tesseract_OCR_logo_%28Google%29.png" width="50%" height="50%"/>|<img src="https://scontent-ssn1-1.xx.fbcdn.net/v/t39.2365-6/261808793_1082281822528512_588598751091579214_n.png?_nc_cat=101&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=GCfXkpOypRQAX9Z3dZL&_nc_ht=scontent-ssn1-1.xx&oh=00_AfAdNvXb9TA4IWYOz--6BTYUMXDMVxh0BDBk8ae539NtPw&oe=6513C3ED" width="50%" height="50%"/>|
|:---:|:---:|:---:|:---:|

## 깃 컨벤션
<div class="sc-fXEqDS jlUmJL atom-one"><blockquote>
<blockquote>
<h3 id="1-commit-메시지-구조">1. Commit 메시지 구조</h3>
</blockquote>
<p>기본 적인 커밋 메시지 구조는 <strong><code>제목</code>,<code>본문</code>,<code>꼬리말</code></strong> 세가지 파트로 나누고, 각 파트는 빈줄을 두어 구분한다.</p>
<pre class=" language-javascript"><code class=" language-javascript">type <span class="token punctuation">:</span> subject

body 

footer
</code></pre>
<blockquote>
<h3 id="2-commit-type">2. Commit Type</h3>
<p>타입은 태그와 제목으로 구성되고, 태그는 영어로 쓰되 첫 문자는 대문자로 한다.</p>
</blockquote>
<p><strong><code>태그 : 제목</code>의 형태이며, <code>:</code>뒤에만 space가 있음에 유의한다.</strong></p>
<ul>
<li><code>feat</code> : 새로운 기능 추가</li>
<li><code>fix</code> : 버그 수정</li>
<li><code>docs</code> : 문서 수정</li>
<li><code>style</code> : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우</li>
<li><code>refactor</code> : 코드 리펙토링</li>
<li><code>test</code> : 테스트 코드, 리펙토링 테스트 코드 추가</li>
<li><code>chore</code> : 빌드 업무 수정, 패키지 매니저 수정</li>
</ul>
<blockquote>
<h3 id="3-subject">3. Subject</h3>
<ul>
<li>제목은 최대 50글자가 넘지 않도록 하고 마침표 및 특수기호는 사용하지 않는다. </li>
<li>영문으로 표기하는 경우 동사(원형)를 가장 앞에 두고 첫 글자는 대문자로 표기한다.(과거 시제를 사용하지 않는다.)</li>
<li>제목은 <strong>개조식 구문</strong>으로 작성한다. --&gt; 완전한 서술형 문장이 아니라, 간결하고 요점적인 서술을 의미.</li>
</ul>
</blockquote>
<pre class=" language-javascript"><code class=" language-javascript"><span class="token operator">*</span> Fixed <span class="token operator">--</span><span class="token operator">&gt;</span> Fix
<span class="token operator">*</span> Added <span class="token operator">--</span><span class="token operator">&gt;</span> Add
<span class="token operator">*</span> Modified <span class="token operator">--</span><span class="token operator">&gt;</span> Modify
</code></pre>
<blockquote>
<h3 id="4-body">4. Body</h3>
</blockquote>
<p>본문은 다음의 규칙을 지킨다.</p>
<ul>
<li>본문은 한 줄 당 72자 내로 작성한다.</li>
<li>본문 내용은 양에 구애받지 않고 최대한 상세히 작성한다.</li>
<li>본문 내용은 어떻게 변경했는지 보다 무엇을 변경했는지 또는 왜 변경했는지를 설명한다.</li>
</ul>
<blockquote>
<h3 id="5-footer">5. footer</h3>
</blockquote>
<p>꼬릿말은 다음의 규칙을 지킨다.</p>
<ul>
<li>꼬리말은 <code>optional</code>이고 <code>이슈 트래커 ID</code>를 작성한다.</li>
<li>꼬리말은 <code>"유형: #이슈 번호"</code> 형식으로 사용한다.</li>
<li>여러 개의 이슈 번호를 적을 때는 <code>쉼표(,)</code>로 구분한다.</li>
<li>이슈 트래커 유형은 다음 중 하나를 사용한다.<br>
- <code>Fixes</code>: 이슈 수정중 (아직 해결되지 않은 경우)<br>
- <code>Resolves</code>: 이슈를 해결했을 때 사용<br>
- <code>Ref</code>: 참고할 이슈가 있을 때 사용<br>
- <code>Related to</code>: 해당 커밋에 관련된 이슈번호 (아직 해결되지 않은 경우)<br>
<strong><code>ex) Fixes: #45 Related to: #34, #23</code></strong></li>
</ul>
<blockquote>
<h3 id="6-commit-예시">6. Commit 예시</h3>
</blockquote>
<pre class=" language-null"><code class=" language-null">Feat: "회원 가입 기능 구현"

SMS, 이메일 중복확인 API 개발

Resolves: #123
Ref: #456
Related to: #48, #45</code></pre>
<blockquote>
<h3 id="7-commit-message-emogji">7. Commit Message Emogji</h3>
</blockquote>
<p>아래는 자주 쓰이는 대표적인 몇가지 일부만 정리를 하였다.<br>
자세한 부분에 대해서는 '<a href="https://treasurebear.tistory.com/70">Gitmoji 사용하기</a>' 여기 설명이 잘되어 있는 글이 있어, 이 링크를 참조 부탁한다.</p>
<table><thead><tr><th>Emogi</th><th>Description</th></tr></thead><tbody><tr><td>🎨</td><td>코드의 <strong>형식 / 구조</strong>를 개선 할 때</td></tr><tr><td>📰</td><td><strong>새 파일</strong>을 만들 때</td></tr><tr><td>📝</td><td><strong>사소한 코드 또는 언어</strong>를 변경할 때</td></tr><tr><td>🐎</td><td><strong>성능</strong>을 향상시킬 때</td></tr><tr><td>📚</td><td><strong>문서</strong>를 쓸 때</td></tr><tr><td>🐛</td><td><strong> 버그</strong> reporting할 때, @FIXME 주석 태그 삽입</td></tr><tr><td>🚑</td><td><strong>버그를 고칠 때</strong></td></tr><tr><td>🔥</td><td><strong>코드 또는 파일 제거할 때</strong> , @CHANGED주석 태그와 함께</td></tr><tr><td>🚜</td><td><strong>파일 구조를 변경</strong>할 때 . 🎨과 함께 사용</td></tr><tr><td>🔨</td><td>코드를 <strong>리팩토링</strong> 할 때</td></tr><tr><td>💄</td><td><strong>UI / style 개선시</strong></td></tr><tr><td>♿️</td><td><strong>접근성</strong>을 향상시킬 때</td></tr><tr><td>🚧</td><td><strong>WIP</strong> (진행중인 작업)에 커밋, @REVIEW주석 태그와 함께 사용</td></tr><tr><td>💎</td><td>New <strong>Release</strong></td></tr><tr><td>🔖</td><td>버전 <strong>태그</strong></td></tr><tr><td>✨</td><td><strong>새로운 기능</strong>을 소개 할 때</td></tr><tr><td>⚡️</td><td>도입 할 때 <strong>이전 버전과 호환되지 않는 특징</strong>, @CHANGED주석 태그 사용</td></tr><tr><td>💡</td><td><strong>새로운 아이디어</strong>, @IDEA주석 태그</td></tr><tr><td>🚀</td><td><strong>배포 / 개발 작업</strong> 과 관련된 모든 것</td></tr></tbody></table>

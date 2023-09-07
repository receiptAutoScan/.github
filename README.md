# 깃 컨벤션
<div class="sc-fXEqDS jlUmJL atom-one"><blockquote>
<h2 id="intro">Intro</h2>
</blockquote>
<p>개발자로 시작한지 얼마 안되고 나서, 첫 직장은 설립된지 얼마 안된, 지금도 다니고 있는 모든것을 처음부터 새로 시작하는 스타트업이다.<br>
프론트엔드는 작성자 혼자 뿐이고, 아무것도 모르는 주니어 개발자가 하나부터 열까지 모든 것을 체계를 잡고 스스로 커나가야 하는 환경이다.<br>
그러기에 나중에 후임이 들어왔을때나, 다른 사람과 협업을 할때 어떻게 하면 더 잘할 수 있을까 고민하다 통일성과 체계적인 일처리를 위해 커밋 컨벤션을 정리하기로 했다.<br>
<strong>이 글은 유다시티의 커밋 메시지 스타일 가이드를 참조한 내용이다</strong></p>
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
<blockquote>
<h3 id="마치며">마치며</h3>
</blockquote>
<p><img src="https://velog.velcdn.com/images%2Fshin6403%2Fpost%2Fa51b74dd-d170-4151-9c3d-f08505dae3e5%2F%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-10-11%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%206.25.41.png"></p>
<p>위와 같이 이제까지 커밋을 하면서 단순히 뭘 했는지에 대해서만 간략하게 작성했다.<br>
혼자 헤쳐나가고, 혼자 모든것을 다 도맡아 하다보니 본인만 알아보기 쉽게 나름 규칙을 생각해서 작성했었다.<br>
그러나 이런 사소한 커밋 메시지도 나만 알아보는 것이 아닌, 누군가 보았을때 일관성과 규칙이 있어야 알아보기 쉽다는 것을 알았기에 규칙과 일관성을 재정립하고자 했다. </p>
<p>이렇게 협업하는 사람들 간의 커밋 메시지 스타일을 정해두면 서로 간의 코드 리뷰에 도움이 될 뿐 아니라, 자신의 이전 로그를 살펴보는 것에도 도움이 되는 것을 알아, 유다씨티의 깃 커밋 스타일 가이드를 바탕으로 커밋 컨벤션을 정리해보았다. </p>
<p><a href="https://overcome-the-limits.tistory.com/entry/%ED%98%91%EC%97%85-%ED%98%91%EC%97%85%EC%9D%84-%EC%9C%84%ED%95%9C-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9D%B8-git-%EC%BB%A4%EB%B0%8B%EC%BB%A8%EB%B2%A4%EC%85%98-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0">[협업] 협업을 위한 git 커밋컨벤션 설정하기</a><br>
<a href="https://doublesprogramming.tistory.com/256">Git - 커밋 메시지 컨벤션</a></p></div>

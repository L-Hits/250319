# 마크다운 실습

## 마크다운이란 무엇인가

### 1. 개요

마크다운(Markdown)은 문서를 쉽고 빠르게 작성할 수 있도록 만들어진 경량 마크업 언어입니다.  
텍스트 기반의 문법을 사용하여 간단하게 문서 서식을 지정할 수 있으며, HTML로 변환이 용이합니다.

#### - 언제 생겼나?
마크다운은 2004년 **존 그루버(John Gruber)**와 **아론 스워츠(Aaron Swartz)**가 공동 개발하였습니다.  
이들은 간결한 문법을 통해 사람들이 쉽게 문서를 작성하고, HTML로 변환할 수 있도록 만들었습니다.

#### - 누가 주로 사용하는가?

마크다운은 다양한 분야에서 사용되지만, 특히 다음과 같은 사용자들에게 인기가 많습니다.

- **개발자**
  - 소스 코드와 함께 문서를 작성할 때 유용합니다.
  - 깃허브(GitHub), 깃랩(GitLab) 등에서 `README.md` 파일로 프로젝트 설명을 작성합니다.
  - Jupyter Notebook에서 코드와 함께 설명을 작성할 때 사용됩니다.

- **문서 작업자**
  - 블로거, 작가, 연구자 등이 간편하게 글을 작성할 때 사용합니다.
  - Notion, Obsidian, AFFINE 등의 마크다운 지원 앱을 활용하여 정리합니다.

---

## 2. 간단한 문법

### 2.1. 제목(Header)

제목을 표시할 때는 `#` 기호를 사용합니다.

```markdown
# 제목1 (h1)
## 제목2 (h2)
### 제목3 (h3)
#### 제목4 (h4)
##### 제목5 (h5)
###### 제목6 (h6)
```

#### 예시 출력:
# 제목1 (h1)
## 제목2 (h2)
### 제목3 (h3)
#### 제목4 (h4)
##### 제목5 (h5)
###### 제목6 (h6)

---

### 2.2. 텍스트 스타일

```markdown
**굵은 글씨** 또는 __굵은 글씨__
*기울인 글씨* 또는 _기울인 글씨_
~~취소선~~
```

#### 예시 출력:
- **굵은 글씨**
- *기울인 글씨*
- ~~취소선~~

---

### 2.3. 목록

#### - 순서 없는 목록

```markdown
- 항목 1
- 항목 2
  - 하위 항목 1
  - 하위 항목 2
```
#### 예시 출력:
- 항목 1
- 항목 2
  - 하위 항목 1
  - 하위 항목 2

#### - 순서 있는 목록

```markdown
1. 첫 번째 항목
2. 두 번째 항목
3. 세 번째 항목
```
#### 예시 출력:
1. 첫 번째 항목
2. 두 번째 항목
3. 세 번째 항목

---

### 2.4. 코드 블록

- **인라인 코드**: `코드`
- **여러 줄 코드 블록**:

```markdown
```python
print("Hello, Markdown!")
```
```

#### 예시 출력:
```python
print("Hello, Markdown!")
```

---

### 2.5. 링크

```markdown
[Google](https://www.google.com)
```
#### 예시 출력:
[Google](https://www.google.com)
---

### 2.6. 이미지

```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```
#### 예시 출력:
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" width="100">
---

### 2.7. 인용문

```markdown
> 이것은 인용문입니다.
>> 중첩된 인용문입니다.
```
#### 예시 출력:
> 이것은 인용문입니다.
>> 중첩된 인용문입니다.
---

### 2.8. 테이블

```markdown
| 이름  | 나이 | 직업  |
|------|----|------|
| 이 찬 | 25 | 개발자 |
| 이 설 | 12 | 학생  |
```
#### 예시 출력:
| 이름  | 나이 | 직업  |
|------|----|------|
| 이 찬 | 25 | 개발자 |
| 이 설 | 12 | 학생  |
---

## 3. 참고 사이트

- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Markdown](https://docs.github.com/en/get-started/writing-on-github)

---

## 4. 깃허브에서는 README.md 파일을 왜 사용하는가?

### 4.1. README.md의 역할

깃허브(GitHub)에서 `README.md` 파일은 **프로젝트의 소개 및 사용 방법을 설명하는 문서**입니다.  
프로젝트를 처음 접하는 사람이 이를 보고 쉽게 이해할 수 있도록 도와줍니다.

### 4.2. README.md에 포함될 내용

- **프로젝트 개요**: 프로젝트의 목적과 기능을 설명
- **설치 방법**: 소프트웨어 설치 및 실행 방법 제공
- **사용 방법**: 주요 기능 및 사용 예시 설명
- **기여 방법**: 오픈소스 프로젝트의 경우 기여 가이드 제공
- **라이선스**: 프로젝트의 라이선스 정보 표시

### 4.3. README.md 예시

```markdown
## 프로젝트 개요
이 프로젝트는 **간단한 마크다운 학습을 위한 예제 프로젝트**입니다.  
마크다운 문법을 익히고 깃허브에서 `README.md`를 작성하는 방법을 학습하는 데 초점을 맞추고 있습니다.

## 주요 기능
- 마크다운 기본 문법 학습
- 깃허브 `README.md` 작성법 익히기
- 코드 블록, 테이블, 링크, 이미지 활용법

## 기술 스택
- **언어**: Python, Markdown
- **버전 관리**: Git, GitHub
- **편집기**: Visual Studio Code, Typora

## 설치 및 실행 방법
아래의 명령어를 사용하여 프로젝트를 실행할 수 있습니다.

```bash
# 저장소 클론
git clone https://github.com/username/repository.git

# 프로젝트 디렉토리로 이동
cd repository

# 실행
python main.py
```

## 기여 방법
1. 이 저장소를 `Fork` 합니다.
2. 새로운 브랜치를 생성합니다. (`git checkout -b feature-branch`)
3. 변경 사항을 커밋합니다. (`git commit -m "Add new feature"`)
4. 원격 저장소에 푸시합니다. (`git push origin feature-branch`)
5. Pull Request를 생성합니다.

## 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다. 자유롭게 사용하고 기여할 수 있습니다.

## 문의 및 피드백
- 이메일: dev@example.com
- GitHub 이슈를 통해 버그를 제보하거나 개선점을 제안해주세요.

```

---

## 4.4. 참고 사이트

- [GitHub 공식 문서 - README 작성법](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes)
- [Awesome README Templates](https://github.com/matiassingers/awesome-readme)

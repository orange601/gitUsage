# gitUsage

용어
// 브랜치(branch): 커밋에서 분기하면 브랜치가 됩니다. 말 그대로 한 갈래; 가지를 의미합니다.

// master: 기본 설정된 브랜치에 붙는 이름입니다.

// origin: 기본 설정된 원격 주소에 붙는 별명입니다.

// 태그(Tag): 알아보기 쉽게 하기 위해서 커밋(commit)에 달아 주는 별명입니다.

// HEAD: 현시점에서 작업중인 브랜치를 가리키는 포인터입니다. 작업공간이 현재 위치해 있는 브랜치를 가리킵니다.

git config (최초 1회 실행)
// git commit에 사용될 username
git config --global user.name "your_name"
 
// git commit에 사용될 email
git config --global user.email "your_email@example.com"
 
// 설정한 내용을 확인할 수 있다.
git config --list

// 브랜치 목록 확인
git branch
현재 브랜치에는 "*"가 붙습니다.
- 이것은 브랜치가 master 것이고 현재 브랜치도 master 임을 나타내는 것입니다.

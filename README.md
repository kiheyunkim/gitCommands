# gitCommands

* 히스토리 내에 있는 특정 파일 기록 모두 삭제
	```bash
	git filter-branch -f --index-filter 'git rm --cached --ignore-unmatch ./삭제원하는파일명' --prune-empty -- --all
	```
	삭제를 원하는 파일명을 지정하고 다른 풀더안에 있으면 "./경로/파일명.확장자"로 지정하면 된다.


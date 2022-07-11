## Lint란?

### Lint의 기본
- python code writing guide PEP8 https://peps.python.org/pep-0484/

### Type 관리
1. 파이썬 type hint에 관한 제안사항 https://peps.python.org/pep-0484/
2. 내장모듈 typing https://docs.python.org/3/library/typing.html
3. typing을 강제하도록 도와주는 pydantic https://pydantic-docs.helpmanual.io/

### Linting Tools
1. commit 할 때 자동으로 lint를 체크해주는 pre-commit https://github.com/pre-commit/pre-commit
2. git hooks
- stage    ->     commit      ->      write msg     ->     finalize     ->     complete
-    pre-commit       prepare-commit-msg        commit-msg           post-commit
- https://git-scm.com/book/ko/v2/Git%EB%A7%9E%EC%B6%A4-Git-Hooks

### 언어별 Lint Library(Formatter)
- python: pylint, flake8, black
- JS: eslint, prettier, husky, lint-staged

---

## 

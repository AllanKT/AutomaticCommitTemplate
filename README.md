# Usage

```cmd
C:\> yarn init -y
C:\> yarn add @commitlint/config-conventional @commitlint/cli husky commitizen standard-version -D
C:\> echo module.exports = {extends: ['@commitlint/config-conventional']} > commitlint.config.js
C:\> yarn commitizen init cz-conventional-changelog --yarn --dev --exact
```


* **OBS**: Required .git folder in project

#### yarn log

* Modifica a versão do seu package.json (--first-release ignora esse passo)
* Criar/atualizar o CHANGELOG.md
* Commita o package.json e o CHANGELOG.md
* Gera uma nova tag

#### ChangeLogs

* teste
* teste


# Libs

* [CommitLint](https://github.com/conventional-changelog/commitlint)
* [Husky](https://github.com/typicode/husky)
* [Commitizen](https://github.com/commitizen/cz-cli)

* [Git create project](https://docs.gitlab.com/ee/gitlab-basics/create-project.html)
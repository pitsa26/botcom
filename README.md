# 🤖 OSSDAO Github contrib Bot

OSSDAO.org

## 🛠️ Installation

Clone and fork the repository to make the changes in your local system

```git-bash
git clone https://github.com/fadhiilrachman/ossdao
cd ossdao
```

Now this command creates a directory named node_modules and installs all the required packages in it.

```javascript
npm install
```

## Configuration

Please rename `.env_template` into `.env`, then set your own **Git credentials** bellow:

```shell
GIT_NAME=""         # Your name
GIT_EMAIL=""        # Your email
REPO_URL=""         # Repo URL (eg. https://github.com/fadhiilrachman/ossdao)
BRANCH_NAME="main"  # Github default branch, if you don't have alter branch please don't edit
```

## Run

Finally, run the project to see what the moment package does.

```javascript
node index.js
```

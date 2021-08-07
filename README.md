# LaTex-Template

## Install
'''
$ git clone <github/path>
$ cd Latex-Template
'''

## Usage
'''
$ docker-compose up --build -d
    # 常時起動にする理由
    # 編集中に何度もコンテナを立てるのは非効率と考えた。

$ docker-compose exec latex platex <filename>.tex
$ docker-compose exec latex dvipdfmx <filename>.dvi
'''
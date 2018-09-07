# funnyface-infra
fannyface infrastructure tools

## playbooks 実行方法

    # ansible-playbook を対象のinventoryファイルを -i で指定
    # 対象のサーバには ssh で入るので ~/.ssh/aws.pem に aws の秘密鍵を用意します
    ansible-playbook playbooks/pipenv.yml -i hosts/staging --private-key ~/.ssh/aws.pem

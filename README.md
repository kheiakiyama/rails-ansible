# rails-ansible

これは ansible の playbook です。

この playbook は以下のタスクを含んでいます。

- tasks/iptables.yml （iptables の設定）
- tasks/git.yml （git リポジトリからの pull）
- tasks/ruby.yml （ruby のインストール）
- tasks/mysql.yml （mysql のインストール）
- tasks/bundle.yml （アプリケーションの bundle install）
- tasks/nginx.yml （nginx のインストール）
- tasks/unicorn.yml （unicorn のインストール）
- tasks/database.yml （database の設定。migration）
- tasks/assets.yml （assets precompile）
- tasks/service.yml （service の起動）
 
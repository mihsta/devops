# devops

# git submodules https://git-scm.com/book/ru/v2/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-Git-%D0%9F%D0%BE%D0%B4%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D0%B8
  git clone --recurse-submodules https://github.com/mihsta/devops.git  
  git submodule update --init --recursive 
  git submodule foreach 'git status'
  git submodule update --remote
  
  

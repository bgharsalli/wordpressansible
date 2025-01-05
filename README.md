# wordpressansible
Déploiement WordPress par ansible 
*****Machnie Ansible***
hostnamectl set-hostname vm-ansible
    2  sudo -i
    3  ssh-keygen -t rsa
    4  nana hosts
    5  nano hosts
    6  ssh-keygen -t rsa
    7  sudo apt update
    8  sudo apt install -y ansible
    9  ansible --version
   10  ssh-copy-id -i /home/bilel/.ssh/id_rsa.pub bilel@192.168.8.138
   11  ssh-copy-id -i /home/bilel/.ssh/id_rsa.pub bilel@192.168.8.139
   12  ssh bilel@192.168.8.139
   13  ssh bilel@192.168.8.138
   14  ansible all -i 192.168.8.138, -m ping
   15  ansible all -i 192.168.8.139, -m ping
   16  ls /home/
   17  cd bilel
   18  git clone https://github.com/bgharsalli/wordpressansible.git
   19  sudo git clone https://github.com/bgharsalli/wordpressansible.git
   20  sudo apt update
   21  sudo apt install git
   22  sudo git clone https://github.com/bgharsalli/wordpressansible.git
   23  ls
   24  cd wordpressansible/
   25  ls
   26  nano hosts 
   27  sudo nano hosts 
   28  sudo install.yml
   29  sudo nano install.yml 
   30  cd roles/
   31  ls
   32  cd mysql/
   33  ls
   34  cd defaults
   35  ls
   36  sudo nano main.yml 
   37  cd ..
   38  ls
   39  cd tasks
   40  ls
   41  sudo nano main.yml 
   42  cd ..
   43  ls
   44  cd ..
   45  ls
   46  cd serveur/
   47  ls
   48  cd handlers/
   49  ls
   50  sudo nano main.yml 
   51  cd ..
   52  ls
   53  cd tasks
   54  sudo nano main.yml 
   55  cd ..
   56  ls
   57  cd wp_cli/
   58  ls
   59  cd defaults/
   60  ls
   61  sudo nano main.yml 
   62  cd ..
   63  ls
   64  cd handlers/
   65  sudo nano main.yml 
   66  cd ..
   67  ls
   68  cd tasks
   69  ls
   70  sudo nano main.yml 
   71  cd ..
   72  ls
   73  cd ..
   74  ls
   75  cd templates/
   76  ls
   77  sudo nano wordpress.conf 
   78  cd ..
   79  ls
   80  ansible-playbook -i hosts install.yml --syntax-check
   81  ansible-playbook -i hosts install.yml --check
   82  visudo
   83  sudo -i
   84  ansible-playbook -i hosts install.yml --check --ask-become-pass
   85  sudo ls
   86  sudo nano hosts 
   87  ansible-playbook -i hosts install.yml --check --ask-become-pass
   88  sudo nano hosts 
   89  ansible-playbook -i hosts install.yml --check --ask-become-pass
   90  sudo nano hosts 
   91  ansible-playbook -i hosts install.yml --check --ask-become-pass
   92  sudo nano hosts 
   93  ansible-playbook -i hosts install.yml --check --ask-become-pass
   94  sudo nano hosts 
   95  ansible -i hosts all -m ping
   96  sudo nano hosts 
   97  ansible-playbook -i hosts install.yml --check --ask-become-pass
   98  ssh bilel@192.168.8.138
   99  ssh node-01@192.168.8.138
  100  sudo nano hosts 
  101  ansible-playbook -i hosts install.yml --check --ask-become-pass
  102  sudo nano hosts 
  103  ansible-playbook -i hosts install.yml --check --ask-become-pass
  104  sudo nano hosts 
  105  nano install.yml 
  106  ansible-playbook -i hosts install.yml --check --ask-become-pass --list-hosts
  107  ansible-playbook -i hosts install.yml --check --ask-become-pass
  108  ansible -i hosts wordpress -m ansible.builtin.ping
  109  ansible-playbook -i hosts install.yml --check --ask-become-pass -vvvv
  110  sudo nano hosts 
  111  ansible-playbook -i hosts install.yml --check --ask-become-pass
  112  deactivate
  113  cd ..
  114  deactivate
  115  ansible-playbook -i hosts install.yml --check --ask-become-pass
  116  cd  wordpressansible/
  117  ansible-playbook -i hosts install.yml --check --ask-become-pass
  118  sudo nano ansible.cfg
  119  ll
  120  ~/.ansible.cfg
  121  /etc/ansible/ansible.cfg
  122  cd ..
  123  ll
  124  cd .ansible
  125  ll
  126  cd cp
  127  ll
  128  cd ..
  129  cd  tmp
  130  ll
  131  cd ..
  132  ls
  133  cd ansible.cfg
  134  nano ansible.cfg
  135  rm -rf ~/.ansible/cp/*
  136  ll
  137  cd ..
  138  cd wordpressansible/
  139  ls
  140  sudo nano install.yml 
  141  ansible-playbook -i hosts install.yml --check --ask-become-pass
  142  ls
  143  cd templates/
  144  ls
  145  nano wordpress.conf 
  146  sudo nano wordpress.conf 
  147  cd ..
  148  sudo nano install.yml 
  149  ansible-playbook -i hosts install.yml --check --ask-become-pass
  150  sudo nano install.yml 
  151  ansible-playbook -i hosts install.yml --check --ask-become-pass
  152  sudo nano install.yml 
  153  ansible-playbook -i hosts install.yml --check --ask-become-pass
  154  sudo nano install.yml 
  155  ansible-playbook -i hosts install.yml --check --ask-become-pass
  156  sudo nano install.yml 
  157  ansible-playbook -i hosts install.yml --check --ask-become-pass
  158  systemctl list-units --type=service | grep -i mysql
  159  dpkg -l | grep mysql
  160  sudo apt update
  161  sudo apt install mysql-server
  162  systemctl status mysql
  163  ansible-playbook -i hosts install.yml --check --ask-become-pass
  164  sudo nano install.yml 
  165  ansible-playbook -i hosts install.yml --check --ask-become-pass
  166  sudo nano install.yml 
  167  ansible-playbook -i hosts install.yml --check --ask-become-pass
  168  ansible -m setup localhost | grep ansible_python_version
  169  pip3 install mysqlclient
  170  sudo apt install python3-pip
  171  ansible-playbook -i hosts install.yml --check --ask-become-pass
  172  pip3 show mysqlclient
  173  sudo pip3 install mysqlclient
  174  sudo apt install python3-mysqlclient
  175  sudo apt-get install python3-dev libmysqlclient-dev
  176  sudo apt install python3-pip
  177  pip3 install mysqlclient
  178  sudo apt install pipx
  179  pipx install mysqlclient
  180  sudo apt-get update
  181  sudo apt-get install -y libmysqlclient-dev pkg-config
  182  pipx install mysqlclient
  183  sudo apt install python3-pip
  184  python3 -m venv myenv
  185  source myenv/bin/activate
  186  python3 -m venv myenv
  187  source myenv/bin/activate
  188  pip show mysqlclient
  189  sudo python3 -m venv /home/bilel/wordpressansible/myenv
  190  pip install mysqlclient
  191  # Créer un environnement virtuel sans sudo
  192  python3 -m venv ~/myenv
  193  # Activer l'environnement
  194  source ~/myenv/bin/activate
  195  # Installer mysqlclient
  196  pip install mysqlclient
  197  pip install mysqlclient --break-system-packages
  198  sudo apt install python3-mysqlclient
  199  apt install python3-mysqlclient
  200  ansible-playbook -i hosts install.yml --extra-vars "ansible_python_interpreter=/home/bilel/myenv/bin/python3"
  201  exit
  202  cd wordpressansible/
  203  ansible-playbook -i hosts install.yml --check --ask-become-pass
  204  sudo systemctl status mysql
  205  ansible-playbook -i hosts install.yml --check --ask-become-pass
  206  nano install.yml 
  207  python3 -m site
  208  ansible -m setup localhost | grep ansible_python_version
  209  sudo nano install.yml 
  210  ansible-playbook -i hosts install.yml --check --ask-become-pass
  211  ansible-playbook -i inventory.ini your_playbook.yml -vvv
  212  ansible-playbook -i inventory.ini your_playbook.yml -e ansible_python_interpreter=/usr/bin/python3 -vvv
  213  ansible-playbook -i inventory.ini your_playbook.yml -e ansible_python_interpreter=/usr/bin/python3 -vvv
  214  ~
  215  ansible-playbook -i inventory.ini your_playbook.yml -e ansible_python_interpreter=/usr/bin/python3 -vvv
  216  ls
  217  ansible-playbook -i inventory.ini install.yml -e ansible_python_interpreter=/usr/bin/python3 -vvv
  218  ls -l inventory.ini
  219  chmod 644 inventory.ini
  220  ansible-playbook -i hosts install.yml --check --ask-become-pass
  221  cd ..
  222  ls /home/
  223  cd bilel
  224  ls
  225  git clone https://github.com/mfaical91/ansible-wordpress.git
  226  ls
  227  cd ansible-wordpress/
  228  ansible-playbook -i hosts install.yml --syntax-check
  229  sudo ansible-playbook -i hosts install.yml --syntax-check
  230  ls
  231  sudo ansible-playbook -i hosts install.yaml --syntax-check
  232  sudo ansible-playbook -i hosts install.yaml --check
  233  sudo ansible-playbook -i hosts install.yaml --syntax-check
  234  sudo ansible-playbook -i hosts install.yaml --check
  235  exit
  236  cd wordpressansible/
  237  sudo ansible-playbook -i hosts install.yml --check
  238  ssh bilel@192.168.8.138
  239  ssh bilel@192.168.8.139
  240  sudo ansible-playbook -i hosts install.yml --check
  241  cd ..
  242  ls
  243  rm ansible-wordpress/
  244  cd wordpressansible/
  245  ~/.ssh/authorized_keys
  246  ssh-copy-id bilel@192.168.8.138
  247  ssh-copy-id bilel@192.168.8.139
  248  ssh-copy-id root@192.168.8.138
  249  ssh-copy-id root@192.168.8.139
  250  ssh root@192.168.8.139
  251  ssh bilel@192.168.8.139
  252  sudo ansible-playbook -i hosts install.yml --check
  253  ssh bilel@192.168.8.139
  254  ssh bilel@192.168.8.138
  255  sudo ansible-playbook -i hosts install.yml --check
  256  ~/.ssh/authorized_keys
  257  ssh -i /path/to/private_key bilel@192.168.8.138
  258  ssh -i /path/to/private_key bilel@192.168.8.139
  259  ~/.ssh/authorized_keys
  260  chmod 600 /path/to/private_key
  261  chmod 600 /home/bilel/.ssh/authorized_keys
  262  ~/.ssh/authorized_keys
  263  cd ..
  264  sudo -i
  265  cd wordpressansible/
  266  ~/.ssh/authorized_keys
  267  sudo ansible-playbook -i hosts install.yml --check
  268  ~/.ssh/authorized_keys
  269  sudo systemctl restart sshd
  270  sudo systemctl restart ssh
  271  ll
  272  ssh -v bilel@192.168.8.138
  273  ssh -v bilel@192.168.8.139
  274  ~/.ssh/authorized_keys
  275  sudo ansible-playbook -i hosts install.yml --check
  276  sudo tail -f /var/log/auth.log
  277  ssh -v bilel@192.168.8.138
  278  sudo ansible-playbook -i hosts install.yml --check
  279  ~/.ssh/authorized_keys.
  280  ll
  281  cd ..
  282  ~/.ssh/authorized_keys.
  283  ll
  284  cd .ssh/
  285  ~/.ssh/authorized_keys.
  286  sudo ufw status
  287  sudo ufw reload
  288  sudo systemctl restart ssh
  289  exit
  290  cd wordpressansible/
  291  dpkg -l | grep openssh-server
  292  sudo systemctl restart ssh
  293  sudo apt update
  294  sudo apt install openssh-server
  295  sudo systemctl restart ssh
  296  sudo ufw status
  297  sudo afw allow ftp
  298  sudo ufw enable
  299  sudo ufw allow ssh
  300  sudo ufw allow http
  301  sudo ufw allow ftp
  302  ~/.ssh/authorized_keys.
  303  sudo ansible-playbook -i hosts install.yml --check
  304  sudo systemctl start sshd
  305  sudo systemctl enable sshd
  306  ssh bilel@192.168.8.138
  307  sudo ufw allow mysql
  308  sudo ansible-playbook -i hosts install.yml --check -vvvv
  309  sudo ansible-playbook -i hosts install.yml --check
  310  sudo systemctl status
  311  sudo journalctl -u ssh
  312  sudo ansible-playbook -i hosts install.yml --check
  313  ~/.ssh/authorized_keys.
  314  cd ..
  315  ~/.ssh/authorized_keys.
  316  cd .ssh/
  317  ll
  318  ~/.ssh/authorized_keys.
  319  chmod 600 ~/.ssh/authorized_keys
  320  chmod 700 ~/.ssh
  321  sudo nano ~/.ssh/authorized_keys
  322  cat ~/.ssh/id_rsa.pub
  323  sudo nano ~/.ssh/authorized_keys
  324  chmod 600 ~/.ssh/authorized_keys
  325  chmod 700 ~/.ssh
  326  sudo systemctl restart sshd
  327  sudo systemctl restart ssh
  328  cd ..
  329  cd wordpressansible/
  330  sudo ansible-playbook -i hosts install.yml --check
  331  cd ..
  332  cd .ssh/
  333  ls
  334  ll
  335  cd ..
  336  cd wordpressansible/
  337  ssh bilel@192.168.8.138
  338  sudo tail -f /var/log/auth.log
  339  ssh -i ~/.ssh/id_rsa bilel@192.168.8.137
  340  ssh -i ~/.ssh/id_rsa bilel@192.168.8.138
  341  sudo ansible-playbook -i hosts install.yml --check -f
  342  sudo ansible-playbook -i hosts install.yml --check 
  343  sudo ansible-playbook -i hosts install.yml --check --ssh-common-args='-o StrictHostKeyChecking=no'
  344  nano hosts 
  345  pwd 
  346  exit
  347  ll
  348  cd .ssh/
  349  ll
  350  pwd
  351  cd ..
  352  cd wordpressansible/
  353  sudo ansible-playbook -i hosts install.yml --check --private-key=/home/bilel/.ssh/id_rsa
  354  pip3 install mysqlclient
  355  python
  356  python3
  357  pip3 install mysqlclient
  358  sudo apt install python3-venv
  359  python3 -m venv /chemin/vers/mon/environnement
  360  python3 -m venv /home/bilel/wordpressansible/
  361  python3 -m venv /home/bilel/
  362  source ~/home/bilel/bin/activate
  363  cd ..
  364  ls
  365  cd myenv/
  366  activate-global-python-argcomplete 
  367  pwd
  368  cd ..
  369  cd wordpressansible/
  370  source ~/home/bilel/myenv/bin/activate
  371  source ~/home/bilel/myenv/activate
  372  pip install mysqlclient
  373  source ~/home/bilel/myenv/activate
  374  cd ..
  375  cd myenv/
  376  ls
  377  cd bin
  378  pwd
  379  cd ~
  380  cd wordpressansible/
  381  source ~/home/bilel/myenv/bin/
  382  activate
  383  source ~/bin/activate
  384  pip install mysqlclient
  385  sudo apt install python3-mysqlclient
  386  sudo apt-get install libmysqlclient-dev
  387  pip3 install mysqlclient
  388  python3
  389  sudo ansible-playbook -i hosts install.yml --check --private-key=/home/bilel/.ssh/id_rsa
  390  history 
(bilel) bilel@vm-ansible:~/wordpressansible$ 



********Machine node-01****
bilel@node-01:~$ history
    1  sudo -i
    2  systemctl restart ssh
    3  cd 
    4  ls
    5  ls -l
    6  hostname -i
    7  sudo apt install openssh-server
    8  sudo systemctl status ssh
    9  systemctl restart ssh
   10  hostname -i
   11  sudo apt update
   12  sudo apt install python3 python3-pip
   13  python3 --version
   14  systemctl restart ssh
   15  python3 
   16  cd /usr/bin/python3
   17  ls
   18  cd Téléchargements/
   19  ls
   20  ll
   21  cd ..
   22  ll
   23  which python3
   24  sudo apt install python3 python3-pip
   25  which python3
   26  dpkg -l | grep mysql
   27  sudo apt update
   28  sudo apt install mysql-server
   29  sudo systemctl status mysql
   30  pip3 install PyMySQL
   31  history 
   32  sudo systemctl status mysql
   33  pip3 install mysqlclient
   34  sudo systemctl status mysql
   35  sudo apt install libmysqlclient-dev
   36  pip3 install mysqlclient
   37* 
   38  history 
   39  which python3
   40  hostname - i
   41  hostname -i
   42  cd /etc/ssh/sshd_config
   43  cd /etc/ssh/sshd_config.d/
   44  ls
   45  nano root .conf
   46  sudo -i
   47  ls
   48  nano root .conf
   49  sudo nano root .conf
   50  sudo -i
   51  cd ~
   52  ~/.ssh/authorized_keys
   53  chmod 700 ~/.ssh
   54  chmod 600 ~/.ssh/authorized_keys
   55  sudo systemctl restart ssh
   56  sudo -i
   57  cd /etc/.ssh
   58  ll
   59  cd .ssh/
   60  sudo chown -R bilel:bilel /home/bilel/.ssh
   61  sudo chmod 700 /home/bilel/.ssh
   62  sudo chmod 600 /home/bilel/.ssh/authorized_keys
   63  cd ..
   64  sudo systemctl restart ssh
   65  cd .ssh/
   66  ls 
   67  ll
   68  touch /home/bilel/.ssh/authorized_keys
   69  chmod 600 /home/bilel/.ssh/authorized_keys
   70  ll
   71  cat ~/.ssh/authorized_keys
   72  chmod 700 ~/.ssh
   73  chmod 600 ~/.ssh/authorized_keys
   74  sudo tail -f /var/log/auth.log
   75  cd ..
   76  cd /etc/ssh/sshd_config
   77  cd /etc/ssh/sshd_config.d/
   78  ls
   79  sudo nano root.conf 
   80  sudo nano 60-cloudimg-settings.conf 
   81  cd ..
   82  ls
   83  sudo nano sshd_config
   84* ~/.ssh/authorized
   85  sudo nano sshd_config
   86  sudo systemctl restart ssh
   87  ~/.ssh/authorized_keys.
   88  cd ..
   89  ~/.ssh/authorized_keys.
   90  cd ..
   91  ~/.ssh/authorized_keys.
   92  ll
   93  cd 
   94  ls
   95  ll
   96  cd .ssh/
   97  ~/.ssh/authorized_keys.
   98  ll
   99  ls
  100  cd ..
  101  cd /etc/ssh/sshd_config
  102  cd /etc/ssh/
  103  ls
  104  nano sshd_config
  105  sudo nano sshd_config
  106  sudo systemctl restart ssh
  107  sudo systemctl restart sshd
  108  ~/.ssh/authorized_keys 
  109  cd ~
  110  cd .ssh/
  111  ~/.ssh/authorized_keys 
  112  ls
  113  ls -l ~/.ssh/authorized_keys
  114  cat ~/.ssh/authorized_keys
  115  ls -ld ~/.ssh
  116  chmod 700 ~/.ssh
  117  ls -ld ~/.ssh
  118  sudo tail -f /var/log/auth.log
  119  cd..
  120  cd ..
  121  ssh -i ~/.ssh/id_rsa bilel@192.168.8.137
  122  ls -ld ~/.ssh
  123* 
  124  LogLevel DEBUG
  125  sudo systemctl restart ssh
  126  sudo apt install python3-dev
  127  python
  128  history

  *****Machine node-02*****
  bilel@node-02:/etc/ssh$ history 
    1  sudo -i
    2  exit
    3  hostname -i
    4  sudo -i
    5  hostname -i
    6  sudo apt update
    7  sudo apt install python3 python3-pip
    8  python3 --version
    9  systemctl restart ssh
   10  which python3
   11  sudo apt install python3 python3-pip
   12  which python3
   13  sudo apt update
   14  sudo apt install mysql-server
   15  sudo systemctl status mysql
   16  sudo apt install libmysqlclient-dev
   17  python3 -m site
   18  sudo -i
   19  ~/.ssh/authorized_keys
   20  chmod 700 ~/.ssh
   21  chmod 600 ~/.ssh/authorized_keys
   22  ~/.ssh/authorized_keys
   23  sudo systemctl restart sshd
   24  sudo systemctl restart ssh
   25  su -i
   26  sudo -i
   27  ll
   28  cd .ssh/
   29  sudo chown -R bilel:bilel /home/bilel/.ssh
   30  sudo chmod 700 /home/bilel/.ssh
   31  sudo chmod 600 /home/bilel/.ssh/authorized_keys
   32  exit
   33  sudo systemctl restart ssh
   34  cd .ssh/
   35  ll
   36  cat ~/.ssh/authorized_keys
   37  chmod 700 ~/.ssh
   38  chmod 600 ~/.ssh/authorized_keys
   39  cd ..
   40  ls
   41  ll
   42  cd  /etc/ssh
   43  ls
   44  cd sshd_config
   45  sudo nano  sshd_config
   46  sudo systemctl restart ssh
   47  sudo nano  sshd_config
   48  sudo systemctl restart ssh
   49  chmod 700 ~/.ssh
   50  ls -ld ~/.ssh
   51  ls -l ~/.ssh/authorized_keys
   52  sudo apt install python3-dev
   53  python
   54  hisory
   55  history 



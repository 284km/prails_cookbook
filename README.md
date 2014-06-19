
prails
======

# memo

---

    %vagrant -v
    Vagrant 1.6.2

    %vagrant box add prails https://oss-binaries.phusionpassenger.com/vagrant/boxes/latest/ubuntu-14.04-amd64-vbox.box
    %vagrant box list

---

vagrant init .

    %vim Vagrantfile
    config.vm.box = "ubuntu"

vagrant up

vagrant ssh

vagrant halt

---

vim Gemfile

bundle install

vim Berksfile

bundle exec berks vendor cookbooks

vagrant reload

vagrant provision

---

bundle exec knife solo init rails_book_cookbook

bundle exec berks vendor cookbooks

vagrant reload

vagrant provision


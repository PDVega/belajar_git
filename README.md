# belajar_git
ini repository buat belajar git 

www.atlassian.com/git/tutorials/comparing-workflows
###git command
      git add . 
      git commit - "keterangan perubahan yang dilakukan"
      git push origin master
      git pull --rebase origin master
        pull sendiri artinya tarik
        perintah di atas digunakan untuk menarik semua perubahan yang dilakukan pada branch master dan mendownloadnya
        pada direktori local kita.
        "Rebasing works by transfering each local commit to the updated master branch one at a it time."
      git add <some file yang dibuat>
      git rebase --continue
      git rebase --abort


###creating new branch for new feature
      git checkout -b marys-feature master
      git status
      git add <some file that have been change>
      git commit
      git push


git checkout master
git pull
git pull origin marys-feature
git push


    1  history
    2  grep '\bto\b' texas.txt
    3  grep 'to' texas.txt
    4  ls
    5  sed -r -i.bak 's/(.+\bto\b.+)/~\1/g' texas.txt
    6  ls
    7  nano texas.txt
    8  git status
    9  git add .
   10  git commit -m "Added '~' to relevant lines and created a backup file"
   11  git push
   12  grep '~' texas.txt > index.txt
   13  ls
   14  nano index.txt
   15  git status
   16  git add .
   17  git commit -m "Added index file with only lines beginning with '~'"
   18  git push
   19  grep '[0-9]{4}' index.txt
   20  ls
   21  grep '[0-9]{4}.+' index.txt
   22  ls
   23  grep ' (,)( [0-9]{4})(.+)' index.txt
   24  ls
   25  nano index.txt
   26  sed -r -i.bak 's/(,)( [0-9]{4})(.+)/2\/g' index.txt
   27  sed -r -i.bak 's/(,)( [0-9]{4})(.+)/\2/g' index.txt
   28  ls
   29  nano index.txt
   30  sed -r -i.bak 's/~//g/' index.txt
   31  git status
   32  git add .
   33  git commit -m "Updated dates in index.txt and added backup file"
   34  git push
   35  sed -r -i.bak 's/~//g/' index.txt
   36  sed -r -i.bak 's/~//\g/' index.txt
   37  nano index.txt
   38  sed -r -i.bak 's/^.//g/' index.txt
   39  sed -r -i.bak 's/~//g/' index.txt
   40  sed -r -i.bak 's/~//' index.txt
   41  ls
   42  nano index.txt
   43  git status
   44  git add .
   45  git commit -m "Removed '~' from every line + backup file updated"
   46  git push
   47  sed -r -i.bak 's/(\b to \b)/,/g/' index.txt
   48  sed -r -i.bak 's/(\b to \b)/,/' index.txt
   49  ls
   50  nano index.txt
   51  grep '.+,.+,.+,' index.txt
   52  ls
   53  git pull
   54  ls
   55  nano clean_index.txt
   56  cp clean_index.txt cleaned-correspondence.csv
   57  ls
   58  git status
   59  git add .
   60  git commit -m "Created csv file, modified clean_index.txt"
   61  git push
   62  history
   63  history > exercise1_logs.md

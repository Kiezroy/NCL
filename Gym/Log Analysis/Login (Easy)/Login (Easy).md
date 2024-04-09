![image](https://github.com/Kiezroy/NCL/assets/67439231/40290d55-dbd1-4f92-ba8c-3ef464064242)

Q1: 

    cat login.log | wc -l

6063


Q2:

    cat login.log | cut -f 3 | sort | uniq | wc -l

1879

Q3:

    cat login.log | cut -f 3 | sort | uniq -c |sort -n

ntory

Q4: 124

Q5: 

    cat login.log | cut -f 1 | cut -d " " -f 1 | sort | uniq -c | sort -n

2011-03-23

Q6:

    cat login.log | cut -f 2,3 | sort | uniq | cut -f 2 | sort | uniq -c | sort -n


wlfla0190

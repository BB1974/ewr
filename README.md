# ewr

<h1>This is change made by elvis<h1>
This line is added by developer Agnes
echo -e "\nDeleting files 14 days older\n"

find /var/log -name '*.log' -mtime +14 -exec rm -rf {} \;

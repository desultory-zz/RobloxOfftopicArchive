# RobloxOfftopicArchive
bash script to archive offtopic since it's dying


usage:

archive start_post step threads

explanation:

this script will download every page found containing the text "off topic"

the start is the post number that you want to start at

the step is the number of posts sequentially each thread will search through

the threads is the number of processes that this script will create


running "archive 1 10000 100" will create 100 processes searching through post number 1 to 100*10000 and downloading every page containing the text "Off Topic"

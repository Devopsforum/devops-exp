# devops-exp
Python project learning stage

#running

this project requires Python 3 and the requests package

'python3 find_dev.py'

#to access the requests in the find_dev.py file follow below step

'apt-get isntall python3-pip'
'apt-get install requests'

#Sometimes there might be issue with versions so to overcome this problem use the below step execution.

'pip3 install pipenv'


#Now we need to say the version we are working on and here am using version 3 so am using the below command

'pipenv --three'

#even though if you are facing error with requests module when executing the below step then install the requests module using the command

'pipenv run python find_dev.py'

#if the above command fails because of requests module then we need to execute the below command

'pipenv install requests'

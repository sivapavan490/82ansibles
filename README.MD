what is adhoc cmd in ansible ?

ans:- Running ansible modules in cmd line is adhoc cmd

'''
tasks=module=collection
'''

in ansible groups will be represented as like below


[backend]
54.174.66.52
54.174.66.52
54.174.66.52

in ansible group of groups will be represnted as like below


[expense:childern]
front end 

back end

ansible-playbook -i inventory.ini playbookfilename

Task level variables can only acess in tasks.Task level variables can override play level variables
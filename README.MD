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

Generally in ansible variables also give in files.those file will refer in playbook.
you can see that playbook in this git location :- https://github.com/sivapavan490/82ansibles/blob/7321b650cf69d9daf22a7e59502060514323aa76/variables/var-files.yaml
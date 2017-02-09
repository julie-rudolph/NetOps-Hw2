# NetOps-Hw2
Homework2: Create Summary Reports

# To Run
ansible-playbook -i ./hosts ./hw2.yml

I did upload the sample output files to the repository as well.  This is so that when i go back and look at this, I can easily remind myself what each output task produced.

# Note
I really wanted to be able to create a new dictionary that contained all the information collected from all the devices. But, i couldn't
quite figure out how to do that.  My attempt is commented out in the hw2.yml file.  The idea is that I would've like to have been able to then process all the data with one Jinja2 template versus creating separate files.  I can do this in Python relatively easily, but am not sure if Ansible lends itself to such a thing.

